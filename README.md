
`rninit` is an alternative to [react-native-cli](https://www.npmjs.com/package/react-native-cli). With a `--source` argument, you can use a specific [react-native](http://www.npmjs.org/react-native) version to initialize a new project.

## Install

``` bash
npm i -g rninit
```

## Usage

Create a new react-native project using latest react-native version
``` bash
rninit init [Project Name]
```

Create a new react-native project using a specific react-native version
``` bash
rninit init [Project Name] --source react-native@0.14.2
```

Or using a github repo.
``` bash
rninit init [Project Name] --source git+https://github.com/facebook/react-native.git#v0.14.2
```

Please refer to [npm install](https://docs.npmjs.com/cli/install) for valid `--source` format.

As the original [react-native-cli](https://www.npmjs.com/package/react-native-cli), we also support `--verbose` argument:
``` bash
rninit init [Project Name] --source react-native@0.14.2 --verbose
```