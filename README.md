# Introduction-to-Node.js

Synchronous Tasks
---------------------
- wait for each task to complete before moving to the next, causing blocking.
- allows us to proceed to the next task without wanting for the prior one to finish.

Asynchronous Tasks
---------------------
- employs callbacks
- allows non-blocking execution, enabling the program to while waiting for input and output operation to complete.


Node globals
---------------------
- are built-in objects or functions accessible globally in node.js without requiring explicit importing, such as the keyword 'console'


Third-Party Packages
---------------------
- Node Packages Manager (NPM), a tool managing packages, which are collections of one or more modules
- widely used package is Lodash


Package.json files
--------------------
- to install all packages, we can create a package.json file, which maintaina a list of project dependencies.
- To create the package.json file
  > go to terminal
  > enter npm init

- For a quick package.json creation with defaults
  > use npm init --yes

Node Modules
-------------------
- There are two prominent areas are network and disk access.

