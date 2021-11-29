# Skip Dependency

**_Note: This is only designed to work with Yarn, not NPM, nor pnpm!!!_**

**Note2: This might work with pnpm "overrides", however it is untested.**

This is for when some dependency you're pulling in is forcing some other dependency you just don't like.
You can use skip-dependency to force the skipping of said dependency.

Just add the following to your `package.json`:

```json
{
  "resolutions": {
    "package-you-really-want-to-skip": "https://registry.yarnpkg.com/@favware/skip-dependency/-/skip-dependency-1.1.3.tgz"
  }
}
```
