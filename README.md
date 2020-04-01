# Fleet test docker action

This action runs `flt test` on your git repo. https://github.com/rancher/fleet#quick-start

## Inputs

### `directory-to-bundle`

## Example usage

```yaml
uses: actions/flt-test@v0.0.1
with:
  directory-to-bundle: './dir/to/bundle'
```