My blog source using hexo(not static web pages)

## usage

### clone it

### install node.js

add our source and install:
```
npm config set registry="http://registry.cnpmjs.org"

npm install
```

### install theme packages
```
npm install hexo-renderer-pug --save
npm install hexo-renderer-sass --save
```

### deploy:
```
npm install hexo-deployer-git --save
```

or using travis-ci to deploy, see .travis.yml.