# ts-template-test
从零一步一步搭建TypeScript+webpack4开发环境 参考文章（https://segmentfault.com/a/1190000021703736）

1、安装依赖 npm i
2、npm run build 打包 打包之后的文件dist/dist.mim.js
3、使用
（1）`<!DOCTYPE html>
      <html lang="en">
      <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
      </head>
      <body>

      </body>
      <script src="../dist/main.js"></script>
      <script>
        console.log(gde,'你好呀')
      </script>
      </html>`
 (2) import {src/index.ts导出的函数名、变量名、类名} from 'dist.min.js'
