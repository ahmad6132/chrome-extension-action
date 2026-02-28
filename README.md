# Chrome Extension Upload & Publish
api_index/

## Inputs

### `refresh-token`
Your Google OAuth2 refresh token

### `extension-id`
Your Google Extension id

### `client-id`
Your Google OAuth2 Client ID

### `client-secret`
Your Google OAuth2 Client Secret

### `extension-file`
Zipped file version of the extension

### `publish`
Should it be published after the upload? True or False

### `tester`
Release only for trusted test users. True or False


## Example usage

```
uses: furkanipek/chrome-extension-action@$VERSION
with:
  refresh-token: 'xxxxxxxxxxxx'
  extension-id: 'xxxxxxxxxxx'
  client-id: 'xxxxxxxx'
  client-secret: 'xxxxxxxxxxxx'
  extension-file: 'xxxxxxxxx-xxxx'
  publish: true
  tester: false
```
