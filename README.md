### create .env.local

### npm start (default port 3000)

### add routes:

E.g: create route for upload site

1. create Upload/index.js in src/pages
2. -- import Upload from '~/pages/Upload' -- in src/routes/index.js
3. add obj: path, component, layout in pulicRoutes array (in src/routes/index.js)

### add layout

E.g create UploadLayout

1. create UploadLayout/index.js in src/components/Layout/
2. -- export { default as UploadLayout } from './UploadLayout' -- in src/components/Layout/index.js
3. import Layout in src/routes/index.js

### add css

src/components/GlobalStyles/GlobalStyles.scss

### add custome css

1. replicate GlobalStyles structure
2. add in index.js or somewhere depends
