# `bbb`

(Bearable Builder in Bash)

### Usage

```bash
bin/bbb         # run the 'build' file from the current working directory
bin/bbb FILE    # run the given FILE from its directory
bin/bbb FILE -D # run the given FILE from its directory with debug output
```

### Examples

A simple [C example](examples/c):
```bash
bin/bbb examples/c/build   # build the hello_world binary
examples/c/bin/hello_world # run the hello_world binary
bin/bbb examples/c/clean   # clean up all built files
```
