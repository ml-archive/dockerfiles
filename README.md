# Dockerfiles 🐳

Dockerfiles that ships with dependencies for running Vapor projects (including [CStack](https://github.com/nodes-vapor/cstack)) on Linux. These images are used in [our Circle CI scripts](https://github.com/nodes-vapor/readme/tree/master/Configuration/.circleci).

Currently we have the following images:

- `Dockerfile-Swift3` which is using Swift 3 and is supposed to be used for Vapor 1 projects. The image is pushed to [here](https://hub.docker.com/r/brettrtoomey/vapor1-ci/).
- `Dockerfile-Swift4` which is using Swift 4 and is supposed to be used for Vapor 2 projects. The image is pushed to [here](https://hub.docker.com/r/brettrtoomey/vapor-ci/)
- `Dockerfile-Swift4.1` which is using Swift 4.1 and is supposed to be used for Vapor 2 or 3 projects. The image is pushed to [here](https://hub.docker.com/r/nodesvapor/vapor-ci) with tag "swift-4.1".
- `Dockerfile-Swift4.2` which is using Swift 4.2 (release) and is supposed to be used for Vapor 2 or 3 projects. The image is pushed to [here](https://hub.docker.com/r/nodesvapor/vapor-ci) with tag "swift-4.2".
- `Dockerfile-Swift5` which is using Swift 5.0 and is supposed to be used for Vapor 3 or 4 projects. The image is pushed to [here](https://hub.docker.com/r/nodesvapor/vapor-ci) with tag "swift-5.0".

## 🛠 Updating the Docker images

A guide for building new images based on Dockerfiles can be found [here](https://circleci.com/docs/2.0/custom-images/).

## ☁️ Hosting

To make it easier to run a Vapor app through a Docker container, we have the following Dockerfiles for guidance:

- `Hosting/Docilerfile-Swift4.1` which is using Swift 4.1 and is supposed to be used for Vapor 2 or Vapor 3 projects.

## 👌 Testing

To make it easier to test Vapor apps locally on Linux using Docker, we have made the following Dockerfiles:

- `Testing/Dockerfile-Swift4.1` which is using Swift 4.1 and is supposed to be used for Vapor 2 or Vapor 3 projects.

## 🏆 Credits

This package is developed and maintained by the Vapor team at [Nodes](https://www.nodesagency.com).
The package owner for this project is [Steffen](https://github.com/steffendsommer).

## 📄 License

This package is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
