# Vue DAG drawing experiment

An experiment in drawing DAGs in Vue using SVG. So far, this experiment shows:

- creating nodes as ellipses
- nodes can be dragged around the viewport
- graph edges that use Vue reactivity to responsively update
  when nodes move
- SVG marker on the end of the directed edge
- add new node
- select and delete multiple nodes
- clear canvas
- draw edges on dbl click on 2 nodes

## Project setup

```sh
yarn install
```

### Compiles and hot-reloads for development

```sh
yarn serve
```

### Compiles and minifies for production

```sh
yarn build
```

### Run your unit tests

```sh
yarn test:unit
```

### Lints and fixes files

```sh
yarn lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
