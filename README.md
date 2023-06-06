# private-npm-registry

Private NPM registry created with [Verdaccio](https://github.com/verdaccio/verdaccio).

## Run

```
$ docker compose up
```

## Home page

http://localhost:4873/

## Default user

username: publisher

password: publisher

## Use

Define in your .npmrc a registry field.

`.npmrc` file:

```
registry=http://localhost:4873
```

## Publish a package

```
$ npm login --registry=http://localhost:4873
$ npm publish --registry=http://localhost:4873
```

## 参考

[Docker 搭建 Verdaccio](https://www.zhihu.com/question/484035649)
