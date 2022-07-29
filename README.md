# Movies App with vanilla Kubernetes clusters

This example shows how to leverage [Okteto CLI](https://github.com/okteto/okteto) to develop a Node.js + React Sample App directly in a vanilla Kubernetes. The Node + React Sample App is deployed using a [Helm Chart](https://github.com/okteto/movies/tree/main/chart). It creates the following components:

- A *React* based front-end, using [webpack](https://webpack.js.org) as bundler and *hot-reload server* for development.
- A very simple Node.js API using [Express](https://expressjs.com).
- A [MongoDB](https://www.mongodb.com) database.
