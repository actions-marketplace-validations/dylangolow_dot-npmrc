# dot-npmrc v2

## Example usage

```yaml
uses: dylangolow/dot-npmrc@v2.0.0
with:
  registry: https://registry.npmjs.org # or other registry
  token: ${{secrets.NPM_AUTH_TOKEN}} # use secrets
  org: ORG_NAME # replace with your registry org name
  addOrgPrefix: true # omit this if undesired
```
