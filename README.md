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

<Note>The free plan is limited to one silo only.</Note>
<Note>For first-timers, you will be redirected to the onboarding page automatically.</Note>

<img className="rounded" height="200" noZoom src="/images/view-silo/silo-setting.png" />

<img className="rounded" height="200" noZoom src="/images/view-silo/silo-setting-1.png" />

<img className="rounded" height="200" noZoom src="/images/view-silo/silo-setting-2.png" />