# 学习webback

```
npm install --save-dev webpack
npm install --save-dev webpack-cli
```

安装lodash
```
npm install --save lodash
```

创建webpack.config.js
```
const path = require('path');

module.exports = {
  entry: './src/index.js',
  output: {
    filename: 'bundle.js',
    path: path.resolve(__dirname, 'dist')
  }
};
```

使用webpack.config.js进行构建 --config能指定文件
```
npx webpack --config webpack.config.js
```

加载css
```
npm install --save-dev style-loader css-loader
```

加载图片
```
npm install --save-dev file-loader
```