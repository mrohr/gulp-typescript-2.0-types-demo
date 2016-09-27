#1 gulp-typescript 2.0 @types bug demonstration
gulp-typescript 3.0.1 configured with tsconfig.json is not correctly loading types installed using typescript 20 style @type 
```
git clone https://github.com/mrohr/gulp-typescript-2.0-types-demo.git
cd gulp-typescript-2.0-types-demo
npm install
tsc
rm src/*.js*
gulp
```
tsc compile will be successful, gulp compile will fail with `error TS2304: Cannot find name '$'.`
