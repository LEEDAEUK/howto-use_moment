## npm install

`npm i vue-momentjs`  
`npm i moment`  
`npm i moment-timezone`  
   
 main.js

```jsx
import VueMomentJS from 'vue-momentjs';

var moment = require('moment-timezone');
Vue.use(VueMomentJS, moment);
```

   
App.vue

```jsx
let tokyo_current_time = this.$moment(new Date()).tz('Asia/Seoul').format('YYYY-MM-DD HH:mm');
```
