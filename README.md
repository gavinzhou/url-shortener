# url-shortener

tutorial about bblot and vgo

## build

### create empty go.mod file

```sh
touch go.mod
```
### download mod

```sh
vgo build
```

### replase some package

```bash
require (
	github.com/gofrs/uuid v3.1.0+incompatible
	github.com/shurcooL/sanitized_anchor_name v0.0.0-20170918181015-86672fcb3f95 // indirect
	gopkg.in/russross/blackfriday.v2 v2.0.1
)

replace gopkg.in/russross/blackfriday.v2 v2.0.1 => github.com/russross/blackfriday/v2 v2.0.1
```