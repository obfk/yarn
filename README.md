# Yarn Playground

## Setup

1. `brew install yarn`
2. `export PATH="$PATH:`yarn global bin``

## [Git URLs as Dependencies](https://docs.npmjs.com/files/package.json#git-urls-as-dependencies)

Dependencies can be specified in several formats, including the following shorthand syntax.

```json
{
  "name": "foo",
  "version": "0.0.0",
  "dependencies": {
    "express": "visionmedia/express",
    "mocha": "visionmedia/mocha#4727d357ea"
  }
}
```

