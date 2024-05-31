# Gleef Starter Kit

The Gleef documentation is based on Mintlify.
Follow the intructions bellow to update the documentation.

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Clone this repo, and run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Publishing Changes

Any change merged to the main branch is automatically published at [docs.gleef.eu](https://docs.gleef.ey).

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
