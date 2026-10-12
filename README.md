> **These are the docs for Finic's former browser automation product, which no longer exists. They are no longer maintained. Finic's current docs are at [docs.finic.ai](https://docs.finic.ai).** Finic now builds AI to stop fraud, abuse and financial crimes: [Finic Grayson](https://docs.finic.ai), a decision model API for real-time fraud and risk decisions, and agents for fraud investigations. See [finic.ai](https://finic.ai).

# Mintlify Starter Kit

Click on `Use this template` to copy the Mintlify starter kit. The starter kit contains examples including

- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Publishing Changes

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard. 

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
