# finder-pipe

The utiltity tools for Archive/Directory/File.

## Installation

- [ ] Describe the installation process

## Usage

This example is some workflow.

> directory -> filter items -> archieve -> dist

```js
function processDir(dirPath){}
function rejectItem(item){
	return function filter(){};
}
function archieveDir(dirPath){}

var FinderChain = require("finder-chain");
var chain = new FinderChain("path/to/dir");
chiain(rejectItem)
	.then(processDir)
	.then(archieveDir);
	.dist("path/to/dir");
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

MIT
