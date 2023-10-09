### hicard-frontend

hicard是一款在线名片交换微信小程序，使用uniapp+vue2+uView2开发。

#### uview2安装

npm安装方式

```bash
# 下载依赖
npm install uview-ui@2.0.36
# main.js中引入
import uView from 'uview-ui'
Vue.use(uView)
#  uni.scss中引入全局SCSS样式
@import 'uview-ui/theme.scss';
```

在App.vue的style中首行引入

```vue
<style lang="scss">
	/* 注意要写在第一行，同时给style标签加入lang="scss"属性 */
	@import "uview-ui/index.scss";
</style>
```







