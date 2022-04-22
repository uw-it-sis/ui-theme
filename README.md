# UW ui-theme

## Using Bootstrap Variable Overrides

Install in app:
```console
npm install bootstrap @uw-it-sis/ui-theme
```

Create your your styles file:
```console
touch src/index.scss
```

Import the variables within the styles file (index.scss):
```scss
@import "~@uw-it-sis/ui-theme/lib/scss/uw-bootstrap-overrides";
@import "~bootstrap/scss/bootstrap";


// Rest of of app specific styles or imports to other SCSS files goes here
```

Import your styles to the app (index.js):
```js
import './index.scss';
```

---

## Using Customized Bootstrap CSS

Install in app:
```console
npm install @uw-it-sis/ui-theme
```

Create your your styles file:
```console
touch src/index.css
```

Import the CSS within the styles file (index.css):
```scss
@import "~@uw-it-sis/ui-theme/lib/css/uw-bootstrap.css";
// OR for minified version...
@import "~@uw-it-sis/ui-theme/lib/css/uw-bootstrap.min.css";

// Rest of app specific styling goes here
```

Import your styles to the app (index.js):
```js
import './index.css';
```
