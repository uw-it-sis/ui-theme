# UW Bootstrap Theme

Currently using Bootstrap v4

## Using Bootstrap Variable Overrides

This option would be if you only wanted to import the UW specific overrides for the Bootstrap variables.

#### Install Bootstrap and ui-theme to your app:
```console
npm install bootstrap@4.6.1 @uw-it-sis/ui-theme
```

#### Create your styles file:
```console
touch src/index.scss
```

#### Import the variables within the styles file (index.scss):
```scss
// import the UW ui-theme variables
@import "~@uw-it-sis/ui-theme/lib/scss/uw-bootstrap-overrides";
// import Bootstrap
@import "~bootstrap/scss/bootstrap";

// Rest of of app specific styles or imports to other SCSS files goes here
```

#### Import your styles to the app (index.js):
```js
import './index.scss';
```

## Using Customized Bootstrap CSS

This option would be the full package, you just want to import the fully customized Bootstrap css directly within your application.

#### Install the ui-theme to your app:
```console
npm install @uw-it-sis/ui-theme
```

#### Create your styles file:
```console
touch src/index.css
```

#### Import the CSS within the styles file (index.css):
```scss
// import the unminified version of the css
@import "~@uw-it-sis/ui-theme/lib/css/uw-bootstrap.css";

// OR

// import the minified version of the css
@import "~@uw-it-sis/ui-theme/lib/css/uw-bootstrap.min.css";

// Rest of app specific styling goes here
```

#### Import your styles to the app (index.js):
```js
import './index.css';
```
