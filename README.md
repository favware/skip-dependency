# Skip Dependency

**_Note: This is only designed to work with Yarn version 1, not NPM, not pnpm and also not Yarn version 2 (codename berry)!!!_**

This is for when some dependency you're pulling in is forcing some other dependency you just don't like.
You can use skip-dependency to force the skipping of said dependency.

Just add the following to your `package.json`:

```json
{
  "resolutions": {
    "package-you-really-want-to-skip": "https://registry.yarnpkg.com/@favware/skip-dependency/-/skip-dependency-1.1.0.tgz"
  }
}
```
