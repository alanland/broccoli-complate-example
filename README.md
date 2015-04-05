# broccoli-complate-example

## 支持

- html
- jade
- css
- stylus
- sass
- javascript
- typescript
- coffeescritp

混合书写

## 运行
```bash
npm install
# the second build is you output directory
npm build build 
```

## 文件结构
build 是输出目录.

```
.
├── Brocfile.js
├── app
│   ├── css
│   │   ├── app.styl
│   │   ├── base.styl
│   │   └── reset.styl
│   ├── images
│   │   ├── 01.png
│   │   ├── 02.png
│   │   ├── 03.png
│   │   └── 04.png
│   ├── js
│   │   ├── a.coffee
│   │   ├── b
│   │   │   ├── b.coffee
│   │   ├── helper.js
│   │   ├── main.js
│   │   ├── t.js.map
│   └── views
│       ├── components
│       │   ├── my-component.html
│       │   └── my-component.jade
│       ├── index.html
│       ├── index.jade
│       └── partials
│           ├── _my-partial.html
│           └── _my-partial.jade
├── build
│   └── production
│       ├── css
│       │   └── app.css
│       ├── images
│       │   ├── 01.png
│       │   ├── 02.png
│       │   ├── 03.png
│       │   └── 04.png
│       ├── js
│       │   └── app.js
│       └── views
│           ├── components
│           │   └── my-component.html
│           └── index.html
└── package.json
```

1441 directories, 5983 files
