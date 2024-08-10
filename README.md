# Browser

A web browser is a software application that allows users to access and navigate the World Wide Web.  
The first web browser, WorldWideWeb, later renamed Nexus, was created by Sir Tim Berners-Lee in 1990.  
The browser was released to the public in 1991, and it played a crucial role in the development of the World Wide Web  

### The basic steps of how a web browser works:

- User Input:

  - The process begins when a user enters a Uniform Resource Locator (URL) into the address bar or clicks on a hyperlink.
  - The URL specifies the address of the resource (web page, image, video, etc.) the user wants to access.

- URL Parsing:

  - The browser parses the URL to understand its components, including the protocol (HTTP or HTTPS), domain name, and the specific path to the resource.

- Domain Name System (DNS) Resolution:

  - If the URL contains a domain name (like www.example.com), the browser needs to convert this domain into an IP address. It uses the DNS to perform this translation.

- HTTP/HTTPS Request:

  - The browser initiates an HTTP or HTTPS request to the server identified by the IP address obtained in the DNS resolution.
  - For HTTPS, there is an additional step of establishing a secure TLS/SSL connection between the browser and the server.

- Server Processing:

  - The server receives the request and processes it. If it's a simple web page, the server may return HTML, CSS, and JavaScript files. For more complex applications, the server may execute server-side code before responding.

- HTML Parsing and Rendering:

  - The browser receives the server's response, typically in the form of HTML (Hypertext Markup Language) along with CSS (Cascading Style Sheets) and JavaScript files.
  - The browser parses the HTML to create a Document Object Model (DOM), a structured representation of the web page's content.

- CSS Styling:

  - The browser applies CSS styles to the DOM elements, determining how the content should be presented, including layout, colors, fonts, and other visual aspects.

- JavaScript Execution:

  - The browser executes JavaScript code embedded in the web page. JavaScript enables dynamic behavior, interactivity, and manipulation of the DOM.

- Rendering the Web Page:

  - The browser combines the HTML content, CSS styles, and JavaScript behavior to render the web page on the user's screen.

- Display and Interaction:

  - The rendered web page is displayed to the user. Users can interact with the page by clicking links, submitting forms, or interacting with various elements.

- Resource Loading:

  - During this process, the browser may encounter additional resources such as images, videos, or external scripts referenced in the HTML. It loads these resources asynchronously for a more responsive user experience.

- Caching:

  - The browser may cache certain resources to improve loading times on subsequent visits. Cached resources are stored locally, reducing the need to re-download them from the server.

- User Navigation:

  - Users can navigate to other pages by clicking on links, entering new URLs, or using browser navigation buttons (back, forward, refresh).

- Cookies and Session Management:

  - The browser manages cookies, which are small pieces of data stored on the user's device. Cookies are often used for session management, tracking user preferences, and other purposes.

- Security Features:

  - Modern browsers include security features such as sandboxing, which isolates each tab or window to enhance security. Browsers also warn users about potentially malicious websites and enforce HTTPS connections for secure data transmission.

This simplified overview outlines the key steps involved in how a web browser works, allowing users to interact with and view content on the internet.

## Important metrics

- First contentful paint (FCP): measures the time from when the page starts loading to when any part of the page's content is rendered on the screen.

- Largest contentful paint (LCP): measures the time from when the page starts loading to when the largest text block or image element is rendered on the screen.

- First input delay (FID): measures the time from when a user first interacts with your site (i.e. when they click a link, tap a button, or use a custom, JavaScript-powered control) to the time when the browser is actually able to respond to that interaction.

- Time to Interactive (TTI): measures the time from when the page starts loading to when it's visually rendered, its initial scripts (if any) have loaded, and it's capable of reliably responding to user input quickly.

- Total blocking time (TBT): measures the total amount of time between FCP and TTI where the main thread was blocked for long enough to prevent input responsiveness.

- Cumulative layout shift (CLS): measures the cumulative score of all unexpected layout shifts that occur between when the page starts loading and when its lifecycle state changes to hidden.

## Performance

[Analyze runtime performance](https://developer.chrome.com/docs/devtools/evaluate-performance/)
