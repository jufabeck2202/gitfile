# gitfile [![Build Status](https://travis-ci.com/jufabeck2202/gitfile.svg?token=1Za7rzts3zF37XsfSaDq&branch=master)](https://travis-ci.com/jufabeck2202/gitfile) [![Version](https://img.shields.io/npm/v/gitfile-dl.svg)](https://www.npmjs.com/package/gitfile-dl)


> download single files from github 


## Install

```
$ npm install -g gitfile-dl
```


## Usage
```bash
    gitfile <GitHubFileURL/GistFileURL>
    gitfile <filename> <githubURL>
```
Directly download files into the current folder.

## Example

```bash
    gitfile https://github.com/jufabeck2202/gitfile/blob/master/cli.js
```
```bash
    gitfile index.js https://github.com/jufabeck2202/gitfile/blob/master/cli.js
```
Save to index.js
## License

MIT © [Julian Beck](https://github.com/jufabeck2202)