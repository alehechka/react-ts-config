# @alehechka/prettier-config

A Prettier [shareable config](https://prettier.io/docs/en/configuration.html#sharing-configurations)
for projects using **[Prettier](https://prettier.io/)** and
**[JavaScript Standard Style](https://standardjs.com/)** as ESLint rules or
separate processes.

## Installation

```
npm install --save-dev @alehechka/prettier-config
```

```
yarn add @alehechka/prettier-config --dev
```

_This is only a shareable configuration. It does not install Prettier, Standard,
ESLint, or any other part of the tool chain._

## Usage

Reference it in `package.json` using the `prettier` property:

```json
{
	"name": "my-projects-name",
	"prettier": "@alehechka/prettier-config",
	"devDependencies": {
		"@alehechka/prettier-config": "^1.0.0"
	}
}
```
