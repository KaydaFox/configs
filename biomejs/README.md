<div align="center">

# @kaydafox/biome-config

My main biome configuration

</div>

**Table**

- [@kaydafox/biome-config](#kaydafoxbiome-config)
  - [Installation](#installation)
    - [Usage](#usage)

## Installation

This can be installed by using the below command. Just replace `yarn add` with your package manager if you use a different one

```sh
yarn add -D @kaydafox/biome-config
```

## Usage

This contains a few different tsconfigs depending on what I need

- `@kaydafox/biome-config/` / `@kaydafox/biome-config`
- `@kaydafox/biome-config/no-lint`
- `@kaydafox/biome-config/no-format`

I always recommend the base config to be added and the rest used as needed.
They can be used by adding them to your `biome.config` inside of `extends: []`

---

The `base` config is the default and is set up in a way that suits the majority of the projects I have, it does both formatting and linting

The `no-lint` config turns off the linter rules for biome

Lastly, `no-format` config turns off the format rules

I'd only use one of those if I was to use Prettier or ESLint along side biomejs though
