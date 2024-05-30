# Understand Front-End Side

## Proxy

A proxy server acts as an intermediary between an application and another server. The proxy is typically used to forward API requests from the frontend (running on one server) to the backend (running on another server).

In this application, there is a proxy that set-up to backend server in the `package.json` file of the frontend application. This is useful when frontend and backend are not running on the same domain, and we want to avoid issues with CORS (Cross-Origin Resource Sharing).

The port number (e.g., `5000`, `3000`, etc) is the "door" through which your application communicates with the server. Different applications running on the same machine must use different port numbers to avoid conflicts. If you have multiple applications (like servers or services) running on the same machine, each one needs to listen on a different port number. This is because a port can only be used by one application at a time.

# Axios

Axios is a popular, promise-based HTTP client that works both in the browser and in a **node.js** environment. It provides a single API for dealing with `XMLHttpRequests` and node's http interface. It has features like automatic transformation of JSON data, client-side protection against XSRF, and easy handling of error status codes.


# devDependencies 

In a `package.json` file, `dependencies` are the packages your project needs to run, like libraries that provide functionality code uses, while `devDependencies` are packages that are only needed for development and testing. These might be testing libraries, build tools, or other packages that help develop project but aren't needed for the project to run.

* `autoprefixer`: This is a tool to parse CSS and add vendor prefixes to CSS rules using values from the **Can I Use** website. It's used to make sure CSS works with different browsers.

* `concurrently`: This is a tool for running multiple npm scripts concurrently on the same console. It's useful when run server and frontend at the same time during development.

* `postcss`: This is a tool for transforming CSS with JavaScript. It's often used with `autoprefixer` and other plugins to process CSS.

* `tailwindcss`: This is a utility-first CSS framework for rapidly building custom user interfaces. It's different from other CSS frameworks like Bootstrap or Foundation because it's lower-level.


