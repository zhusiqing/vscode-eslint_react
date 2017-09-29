# vscode eslint 安装与配置
# eslint安装
## eslint需要依赖nodejs 6+
## 在vscode中下载插件`ESLint`
# 安装npm 依赖
``` js
//全局安装eslint
npm i eslint -g

//如果用到html中的js校验(如果想单独可以不加-g，只在独立项目里安装)
npm i eslint-plugin-html -g

//如果用到es6语法
//全局安装
npm i babel-eslint -g
//单独项目安装
npm i babel-eslint

//安装识别react语法校验
npm i eslint-plugin-react
```
# 在项目创建eslint配置文件
## 创建`.eslintrc.json`文件
## eslint会根据.eslintrc.json定义的规则进行代码校验
> [eslint官方给出的一些有关react配置的文档](https://github.com/yannickcr/eslint-plugin-react)

