# Discarded
 Move to [devlink](https://github.com/developerlinks/devlink)

# Amo-cli

🎳 cli tool for creating apps

currently available templates：

- react-webpack-template
- vue3-vite-template

# Feature

- [x] ejs Custom templates are dynamically rendered via ejs
- [x] Support users to manually upload templates！！  

# Start

```bash
npm install -g @amo-cli/core

or

yarn global add @amo-cli/core

```

# Create project

Select the project you want to initialize through the command line

```bash
amo init
```

Force empty current directory

```bash
amo init --force
```

# Other API

clear cache

The templates downloaded by the scaffolding will be cached locally for faster initialization for the second time. If some impact is caused by this, you can manually delete the cache.

```bash
amo clean
```

debug

In debug mode, you can view more installation information to troubleshoot errors

```bash
amo --debug
```


> If you want to add your template, please write your warehouse address in pr
