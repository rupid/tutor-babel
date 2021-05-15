<!--
 * @Desc: 
 * @FilePath: /tutor-babel/docs/md/version.md
 * @Author: liujianwei1
 * @Date: 2021-05-14 20:47:30
 * @LastEditors: liujianwei1
 * @Reference Desc: 
-->

目前，[npmjs](https://www.npmjs.com/)网站上有Babel@6和Babel@7两个版本 。但是，大部分项目中使用的Babe版本基本是[Babel@7](https://www.npmjs.com/package/@babel/core)

### 如何区分不同的版本
- Babel@7 采用scope域的方式发布npm包，相关的包都在`@babel`/下面，表现上为`@babel/core`,`@babel/cli`。源代码采用[lerna](https://github.com/lerna/lerna)管理。
- Babel@6 表现为`babel-core`,`babel-cli`

>不同版本之间的包，不能相互混用，例如`@babel/core`,不能同 `babel-cli`一起使用