Bower to Yarn
=============

A simple tool for moving bower dependencies to yarn or npm.  
Forked from https://github.com/DinkDonk/bower-to-yarn for personal use. 

---

### Installation

```bash
$ yarn global add boweryarn
```

### Usage

In the root of your chosen project:

```bash
$ boweryarn
```

### Options

| Option    | Description | Default |
| :-------- |:------------| :-------|
| --version | Show version number |  |
| --help | Show help |  |
| --config, -c | The path to the `config.yaml` file |  |
| --package-name-prefix, -p | String to inject as a prefix to the package name in package.json |  |
| --bower-file, -i | The path to the bower.json file | `./bower.json` |
| --package-file, -o | The path to the package.json file | `./package.json` |
| --overwrite-duplicates | If set to `true`, duplicate dependecies will resolve to the dependency defined in bower.json | `false` |
