# vue-accordion
A Vuejs accordion component.   
# Install
Using npm:   
```bash
$ npm i @parsilver/vue-accordion
```
# Usage:
Add the following code to your main.js

```
import accordion from '@parsilver/vue-accordion'
Vue.use(breadCrump);
```

Then use the component in desired .vue component like this:

```
<template>
  <accordion :title="FAQ" :items="items" />
</template>

<script>
    export default {
        name: "your-component",
        data: function () {
            return {
                items:[
                  {
                    title: "Question 1",
                    content: "Answer 1",
                    isExpanded: true,
                  },
                  {
                    title: "Question 2",
                    content: "Answer 2",
                    isExpanded: false,
                  }
                ]
            }
        },
    }
</script>

```

# Credit:
html and css from https://codepen.io/kathykato/pen/MoZJom
