# Understand Front-End Side

## Proxy

A proxy server acts as an intermediary between an application and another server. The proxy is typically used to forward API requests from the frontend (running on one server) to the backend (running on another server).

In this application, there is a proxy that set-up to backend server in the `package.json` file of the frontend application. This is useful when frontend and backend are not running on the same domain, and we want to avoid issues with CORS (Cross-Origin Resource Sharing).

The port number (e.g., `5000`, `3000`, etc) is the "door" through which your application communicates with the server. Different applications running on the same machine must use different port numbers to avoid conflicts. If you have multiple applications (like servers or services) running on the same machine, each one needs to listen on a different port number. This is because a port can only be used by one application at a time.
