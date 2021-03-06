# 🚗 Vue Product Spinner (Under Active Development, still buggy)

[![Build Status](https://travis-ci.org/micheleriva/vue-product-spinner.svg?branch=master)](https://travis-ci.org/micheleriva/vue-product-spinner)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Vue Version](https://img.shields.io/badge/vue-2.5.17-green.svg)](https://vuejs.org/)

A 3D product spinner with no dependencies built for Vue.js

# Demo

Live demo [here](https://micheleriva.github.io/vue-product-spinner/)

![Vue Product Spinner](/docs/VueProductSpinner.gif)

# Installation

**npm**
```sh
npm i vue-product-spinner
```

**yarn**
```sh
yarn add vue-product-spinner
```

# Usage

```html
<template>
  <VueProductSpinner :imgs="imgs" />
</template>

<script>
  import VueProductSpinner from 'vue-product-spinner'

  export default {
    data() {
      return {
        imgs: [
          'img1.jpg',
          'img2.jpg',
          'img3.jpg'
        ]
      }
    },

    components: {
      VueProductSpinner
    }
  }
</script>

```

# Roadmap

- [ ] Solve basic bugs
- [x] Add slider support
- [x] Add touchscreen support
- [ ] Add "mouse move" support

# License
[MIT](/LICENSE.md)