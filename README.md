# agile-wysiwyg-prod
## Usage

<h1>NOTE: CUSTOM BUILD</h1>
<p>This version is based on the information below but is a custom build for specific use with a specific project. This is not intended to be a branch of the main project as the changes made will not work universally.
   If you found this git looking for a vue-wysiwyg, please visit the original vue-wysiwyg here <a href="https://github.com/chmln/vue-wysiwyg">https://github.com/chmln/vue-wysiwyg</a>
</p>

### Install agile-wysiwyg

``` bash
meteor npm install agile-npm@https://github.com/skwerlzu/agile-wysiwyg-prod.git --save
```

In your `main.js`:

```js
import wysiwyg from "agile-wysiwyg";
Vue.use(wysiwyg, {}); // config is optional. more below
```