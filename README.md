# VoltStream settings

Every VoltStream box reads `config.json` from here each time the app opens.

- **servers**: the server addresses customers sign in to. They only ever type a username and password; the app tries each server in order until the login works. To move to a new address, change the `url` and save. Every box picks it up next time it opens.
- **message**: text shown on every customer's home screen (leave as `""` for none).
- **addons**: Stremio addon links to give every box, e.g. `"https://example.com/manifest.json"`.
- **pickServer**: set to `true` to let customers choose a server by name on sign in.

Keep the commas and quotes exactly as they are, or the boxes will ignore the file and keep the last good copy.
