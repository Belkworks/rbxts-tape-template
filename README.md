
# rbxts-tape-template

This template combines [roblox-ts](https://github.com/roblox-ts/roblox-ts) with [tape](https://github.com/belkworks/tape)!

## Foreword

This template was made with [pnpm](https://pnpm.io/) in mind, but you can use npm or yarn if you want.

## Output

See [dist.lua](https://github.com/Belkworks/rbxts-tape-template/blob/master/dist.lua).

## Getting Started

With GitHub:
[Click here](https://github.com/belkworks/rbxts-tape-template/generate)

With [degit](https://github.com/Rich-Harris/degit):
```sh
degit belkworks/rbxts-tape-template my-project
cd my-project
```

## Installation

```sh
pnpm install
```

## Building

```sh
pnpm build
```

Additional parameters will be passed to `tape`.

```sh
pnpm build --output build.lua
```

## Cleaning

Depending on your application, you may want to do a clean build. This will remove the `out` directory and all of its contents.

```sh
pnpm clean
```
