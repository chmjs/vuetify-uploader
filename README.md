[![npm](https://img.shields.io/npm/v/@nsoft/vuetify-uploader.svg)](https://www.npmjs.com/package/@nsoft/vuetify-uploader) 
[![Build Status](https://travis-ci.org/nsftx/vuetify-uploader.svg?branch=master)](https://travis-ci.org/nsftx/vuetify-uploader)
[![codebeat badge](https://codebeat.co/badges/a97d1a44-c643-484b-805f-35d83d5125c2)](https://codebeat.co/projects/github-com-nsftx-vuetify-uploader-master)
[![codecov](https://codecov.io/gh/nsftx/vuetify-uploader/branch/master/graph/badge.svg)](https://codecov.io/gh/nsftx/vuetify-uploader) [![Greenkeeper badge](https://badges.greenkeeper.io/nsftx/vuetify-uploader.svg)](https://greenkeeper.io/)

# vuetify-uploader

> Upload component for Vuetify framework

## Installation

```bash
# npm
npm install @nsoft/vuetify-uploader
```

## Using

### Import

```javascript
import Vue from 'vue';
import { VUploader } from '@nsoft/vuetify-uploader';
import App from './App';

Vue.config.productionTip = false;
Vue.use(VUploader);

/* eslint-disable no-new */
new Vue({
  el: '#app',
  template: '<App/>',
  components: { App },
});
```

### Import locally

```javascript
import { VUploader } from '@nsoft/vuetify-uploader';

export default {
  name: 'app',
  components: {
    VUploader,
  },
};
```

### Use in template

```html
<template>
  <div id="app">
    <VUploader/>
  </div>
</template>
```
