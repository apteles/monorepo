# Install packages by workspaces

Inside the folder of the module, run the commands bellow

```bash
yarn workspace @clients/user add @babel/cli @babel/core @babel/preset-env @babel/preset-react babel-loader css-loader file-loader style-loader webpack webpack-cli webpack-dev-server
```

```bash
yarn workspace @clients/admin add @babel/cli @babel/core @babel/preset-env @babel/preset-react babel-loader css-loader file-loader style-loader webpack webpack-cli webpack-dev-server
```

# Installing dev dependencies

```bash
yarn workspace @clients/user add @babel/plugin-transform-runtime -D
```