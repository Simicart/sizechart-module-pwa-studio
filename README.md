# SizeChart module for Magento PWA Studio

This module acts as an add-on for [Mageplaza's SizeChart extension](https://www.mageplaza.com/magento-2-size-chart/) to make it work with Magento PWA Studio.

End result: https://sizechart.pwa-commerce.com/juno-sweater.html

## Requirements

- Magento version 2.4.* or >= 2.3.5
- Got [Mageplaza SizeChart extension](https://www.mageplaza.com/magento-2-size-chart/) and [SizeChart GraphQL](https://github.com/mageplaza/magento-2-size-chart-graphql) installed

## Installation

### 1. Init project
```
git clone https://github.com/Simicart/simi-studio --branch release/2.0.0
cd simi-studio
yarn add @material-ui/core
```

### 2. Start the project

From the root directory of the project you created above, clone the repository:

```
  git clone https://github.com/Simicart/sizechart-module-pwa-studio ./@simicart/sizechart
```

### 3. Modify .env

Change the .env MAGENTO_BACKEND_URL with your Magento site URL, or use our demo URL:

```
  MAGENTO_BACKEND_URL=https://mpmed.pwa-commerce.com/
```
### 4. Modify package.json

Modify the dependencies of your project to add SizeChart extension.

```
  "dependencies": {
    ...
    "@simicart/sizechart": "link:./@simicart/sizechart"
  },
```

### 5. Install and Start Project

```
  yarn install && yarn watch
```
