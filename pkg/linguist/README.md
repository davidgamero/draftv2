# linguist

Go port of github linguist.

## Updating linguist

To update to the latest version of linguist, run

```
git clone https://github.com/github/linguist data/linguist
GO111MODULE=off go generate .
GO111MODULE=off go generate ./data
rm -rf data/linguist
```
