# `containers`

Source repository for custom container images.

## Images

| Image                                     | Repository                                                                  | Tags           | Description                                                                                  |
| ----------------------------------------- | --------------------------------------------------------------------------- | -------------- | -------------------------------------------------------------------------------------------- |
| [`kicad-full`](./kicad-full/)             | [`loozhengyuan/kicad`](https://hub.docker.com/r/loozhengyuan/kicad)         | `X.Y.Z-full`   | Includes [missing 3D models](https://gitlab.com/kicad/packaging/kicad-cli-docker/-/issues/6) |
| [`verdaccio-unsafe`](./verdaccio-unsafe/) | [`loozhengyuan/verdaccio`](https://hub.docker.com/r/loozhengyuan/verdaccio) | `X.Y.Z-unsafe` | Includes config for unauthenticated publish                                                  |

## License

[MIT](https://choosealicense.com/licenses/mit/)
