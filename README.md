# Dockerfiles 🐳

Dockerfiles that ships with dependencies for running Vapor projects (including [CStack](https://github.com/nodes-vapor/cstack)) on Linux. These images are used in [our Circle CI scripts](https://github.com/nodes-vapor/readme/tree/master/Configuration/.circleci).

## Updating the docker images

Currently we have two images:

- `Dockerfile-Swift3` which is using Swift 3 and is supposed to be used for Vapor 1 projects. The image is pushed to [here](https://hub.docker.com/r/brettrtoomey/vapor1-ci/).
- `Dockerfile-Swift4` which is using Swift 4 and is supposed to be used for Vapor 2 projects. The image is pushed to [here](https://hub.docker.com/r/brettrtoomey/vapor-ci/)

A guide for building new images based on dockerfiles can be found [here](https://circleci.com/docs/2.0/custom-images/).

## 🏆 Credits

This package is developed and maintained by the Vapor team at [Nodes](https://www.nodesagency.com).
The package owner for this project is [Steffen](https://github.com/steffendsommer).


## 📄 License

This package is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)