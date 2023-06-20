# packwiz-action

This action runs `packwiz` to build your modpacks.

## Example usage

```yaml
uses: mkamadeus/packwiz-action@v1
with:
  path: '/path/to/modpack' # must contain a pack.toml
  type: 'modrinth' # or 'curseforge'
  filename: 'pack.modrinth'
```
