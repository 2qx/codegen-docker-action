# Codegen docker action

## Inputs

### `i`

Location of input openapi3 specification

## Generator

### `g`

Generator template

## Outputs

### `o`

Output directory

## Example usage

```yaml
uses: actions/codegen-docker-action@master
with:
  i:    'swagger/api.yml'
  g:    'typescript-express-server'
  o:    'generated/server'
```
