# Compass + Docker
Compile compass projects using a docker container.

# Usage

```
docker run --rm -ti -v $(pwd)/test:/app dmwl/compass
```

To run more easily, add this to your `~/.zshrc`, `~/.bashrc`, or
`~/.profile` file

```
alias compass='docker run --rm -ti -v $(pwd)/test:/app dmwl/compass'
```
