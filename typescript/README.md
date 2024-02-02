<div align="center">

# @kaydafox/typescript-config

My main typescript configurations

</div>

**Table**

- [@kaydafox/typescript-config](#kaydafoxts-config)
  - [Installation](#installation)
    - [Usage](#usage)

## Installation

This can be installed by using the below command. Just replace `yarn add` with your package manager if you use a different one

```sh
yarn add -D @kaydafox/typescript-config
```

## Usage

This contains a few different tsconfigs depending on what I need

- `@kaydafox/typescript-config/base` / `@kaydafox/typescript-config`
- `@kaydafox/typescript-config/strict`
- `@kaydafox/typescript-config/no-decorators`

I always recommend the base config to be added and the rest used as needed.
They can be used by adding them to your `tsconfig` inside of `extends: []`

---

The `base` config is the default and is set up in a way that suits the majority of the projects I have

The `strict` config just adds a few options on to the base config for more strict type checking

Lastly, `no-decorators` is recommended to add to a project if decorators aren't going to be used. It's on by default in the `base` config because personally I love using decorators
