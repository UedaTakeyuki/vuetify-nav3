# Out-of-the-box Vuetify navigation menu component, with Toolbar, Navigation Drawers, Menus, and QR code

Provide Toolbar with Navigation drawer and drop down menu as follows:

### Toolbar
<img src="https://github.com/UedaTakeyuki/vuetify-nav/blob/main/img/ss.2021-05-28_8.26.04.png" width="90%"/> 


### Dropdown Menu
<img src="https://github.com/UedaTakeyuki/vuetify-nav/blob/main/img/ss.2021-05-28_8.25.43.png" width="90%"/>


### Navigation Drawers
<img src="https://github.com/UedaTakeyuki/vuetify-nav/blob/main/img/ss.2021-05-28_8.26.18.png" width="90%"/>


## Install
By npm

```bash:
npm install vuetify-nav 

# or

yarn add vuetify-nav 
```

Or CDN.   
For more detail, refer [wiki](https://github.com/UedaTakeyuki/vuetify-nav/wiki/Install).

## How to use
Just set ``<Navbar/>`` component to your ``App.vue`` file as follows:

```vue:
<template>
  <v-app>
    <Navbar titleStr="Demo App" :links="links" />
  </v-app>
</template>

<script>
import {Navbar} from 'vuetify-nav'
export default {
  components: { Navbar},
  data: () => ({
    links: [
      { icon: 'home', text: 'Home', route: '/'},
      { icon: 'face', text: 'Account', route: '/account'},
      { icon: 'shop', text: 'Purchase', route: '/purchase'},
    ]
  }),
};
</script>
```

for more detail refer [wiki](https://github.com/UedaTakeyuki/vuetify-nav/wiki/Users-Guide)


## Demo
Demo site is available at [here](https://vue-faui-user-fe-sample.uedasoft.com/).

## Q&A
Github [issues](https://github.com/UedaTakeyuki/vuetify-nav/issues) are available. Any questions, suggestions, request, and reports are welcome!

## Author
[Dr. Takeyuki UEDA](https://atelierueda.uedasoft.com/)

## Version
- vuetify-nav@2: for Vue2
- vuetify-nav@3: for Vue3

## History
- 1.0.0 2023.03.12 forked from [vuetify-nav](https://github.com/UedaTakeyuki/vuetify-nav)@3 for the candidate of successor for **Vue3**.
