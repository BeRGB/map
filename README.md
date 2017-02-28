# Fruškać Map
#### Fruška gora, Srbija

The map is to be used in an `iFrame` element. Initial could be passed in via `src` attribute. The Map will expose API to it's parent element to allow Map control. Usages could be found in [examples](https://github.com/fruskac/map/tree/master/examples) directory.

## Contributing

##### Branching model
We are using `git-flow` as our brancing model. Read more at [nvie.com/posts/a-successful-git-branching-model](http://nvie.com/posts/a-successful-git-branching-model/)

###### Installing `git-flow`
Ream more about `git-flow` and how to install it [github.com/nvie/gitflow](https://github.com/nvie/gitflow)

##### Tools
To be able to build source files, you need to have `npm` and `node` installed. After that run
```
npm install
```
This will install `Gulp` and other libraries needed for development.

##### Build
To create build, run
```
gulp
```

###### Build separate JS, LESS, HTML and Docs
Build can be run by specific type, like
```
gulp js
gulp less
gulp html
gulp docs
```

##### Development
While doing development, start watcher which will react on file changes and start appropriate tasks to update build
```
gulp watch
```