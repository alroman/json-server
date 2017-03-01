First install `json-server` node module.

```sh
$ npm install -g json-server
```

Then, clone this directory and run:

`json-server db.json --static ./assets`

That will serve the image assets in the `assets` dir.

To access an asset, it'll be somethign like `http://localhost:3000/icon/asset.png`

Full reference:

* https://github.com/typicode/json-server