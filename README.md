# Atlas icons Vue

#### Open source [icons library](http://atlasicons.vectopus.com/), Icons available in SVG format, Font, Figma, Adobe XD and Iconjar Libraries.

##### _Made by [Vectopus](http://vectopus.com/)._

### How to use
Install Vue package.
```html
npm i @vectopus/atlas-icons-vue
```
Use Atlas Icons package in your ```main.js```
```js
import {createApp} from 'vue'
import App from './App.vue'
import Atlas from '@vectopus/atlas-icons-vue'
const app = createApp(App)
app.use(Atlas);
app.mount('#app')
```

Embed icon selector into component template.

```html
<Atlas icon="AudioAlbum" :size="24" />
```


### Related Packages
- [Atlas Icons React](https://github.com/Vectopus/Atlas-icons-react)
- [Atlas Icons Webfont](https://github.com/Vectopus/Atlas-icons-font)
- [Atlas Icons Flutter](https://github.com/Vectopus/Atlas-icons-flutter)

### License
MIT © [Atlas Icons](https://github.com/Vectopus/Atlas-icons-vue/blob/main/LICENSE)
