# vue-feather-icon

Vue component for [Feather](https://feathericons.com)

Patched version from @ChikuwaJB.

## install

```shell
yarn add https://github.com/MickaelBergem/vue-feather-icon.git
```

## usage

### global component
```javascript
// main.js
import Vue = from 'vue'
import VueFeatherIcon from 'vue-feather-icon'

Vue.use(VueFeatherIcon)
```

```vue
<template>
  <feather-activity></feather-activity>
  <!-- or -->
  <feather-icon type="activity"></feather-icon>
</template>
```


### local component

```vue
<script>
  import { Activity } from 'vue-feather-icon'

  export default {
    components: {
      ActivityIcon: Activity
    }
  }
</script>

<template>
  <activity-icon></activity-icon>
</template>
```
