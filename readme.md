# Upload CurseForge Modpack

## Example usage

``` yml
uses: henkelmax/upload-curseforge-modpack-action@v1.0.0
with:
  api-token: '<YOUR TOKEN>'
  project-id: '1234'
  modpack-path: './modpack.zip'
  modpack-server-path: './modpack-server.zip' # Optional
  changelog: 'Added new features' # Optional
  changelog-format: 'text' # Optional
  game-version: '1.16.5' # Optional
  display-name: 'My Awesome Modpack'
  server-display-name: 'My Awesome Modpack Server'
  release-type: 'beta'
```
