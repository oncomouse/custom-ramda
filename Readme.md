# @oncomouse/custom-ramda

This is the partial-build script of [Ramda](https://github.com/ramda/ramda) as a stand-alone executable. It is used to create smaller, custom builds of Ramda for use in production.

## Usage

Once installed, provide the binary with a list of Ramda functions to include, like so:

```bash
npx --no-install @oncomouse/custom-ramda compose add pipe
```

Which will produce a build of Ramda with only `compose`, `add`, and `pipe`
