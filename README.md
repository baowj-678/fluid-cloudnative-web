# Fluid 官网源码

采用vuepress 1.8版本构建网站，且定制`theme-default`主题的[Home.vue](docs/.vuepress/theme/components/Home.vue)和[Navbar.vue](docs/.vuepress/theme/components/Navbar.vue)。

## 编译和运行

```shell
npm install .
npm run docs:dev
```

## 打包和上传

```shell
npm run docs:build
```

打出来的脚本和静态文件在`docs/.vuepress/dist`目录下，将所有的内容拷贝并替换`https://github.com/fluid-cloudnative-test-xliu/fluid-cloudnative-test-xliu.github.io`仓库的所有的内容，最后提交PR到Fluid官方，实现更新。
