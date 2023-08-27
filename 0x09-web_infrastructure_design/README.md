0x09-web_infrastructure_design
0-simple_web_stack
User Accesses the Website:A user wants to access the website hosted at www.foobar.com. They enter the URL in their web browser.
Domain Name: The domain name "foobar.com" is a human-readable address that the user can remember. It maps the actual IP address of the server hosting the website.
DNS Resolution: The user's computer performs a DNS resolution. It contacts a DNS server to resolve "www.foobar.com" to its corresponding IP address (let's say 8.8.8.8).

Infrastructure Components:
Server (8.8.8.8): The physical or virtual machine where all components are hosted. It handles incoming requests and manages communication between the various components.
Web Server (Nginx): It receives incoming HTTP requests from users and forwards them to the application server. Nginx also handles tasks like load balancing and SSL termination.
Application Server:(e.g., running Python, Node.js, )hosts the application codebase. It receives requests from the web server, processes them, and generates dynamic content. It communicates with the database to fetch or store data.
