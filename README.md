# jv
jv (for jsonviewer) helps you view your JSON.

[![asciicast](https://asciinema.org/a/123606.png)](https://asciinema.org/a/123606)

## Installation
```
go get -u github.com/maxzender/jv
```

## Example usage
```
jv file.json
```
Or by reading from `stdin`:
```
jv < file.json
echo '{"foo": "bar"}' | jv
```
