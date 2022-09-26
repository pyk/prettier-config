<h2>
    <span>@pyk/prettier-config</span>
    <span><a href="https://www.npmjs.com/package/@pyk/prettier-config"><img src="https://badgen.net/npm/v/@pyk/prettier-config?color=black&labelColor=black"></a></span>
</h2>

pyk's personal [Prettier](https://pyk.sh/what-is-prettier) configuration.

### Installation

Use the following command to install `@pyk/prettier-config`:

```sh
# npm
npm install --save-dev --save-exact prettier @pyk/prettier-config@latest

# pnpm
pnpm add --save-dev --save-exact prettier @pyk/prettier-config@latest
```

### Usage

Add the following fields in your `package.json`:

```json
{
    "scripts": {
        "prettier:check": "prettier --check ."
        "prettier:write": "prettier --write ."
    },
    "prettier": "@pyk/prettier-config"
}
```

> **Note** You can ignore files by adding it to `.prettierignore`.

Then you can use `pnpm prettier:check` or `npm run prettier:check` to check the
file formatting.

### Resources

-   [What is prettier?](https://pyk.sh/what-is-prettier)
-   [How to create shareable or reusable prettier configuration](https://pyk.sh/create-shareable-prettier-configuration/)
