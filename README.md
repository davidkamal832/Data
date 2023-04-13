

```shell
$ npm install @jiaminghi/data-view
```

### 使用

```js
import Vue from 'vue'
import DataV from '@jiaminghi/data-view'

Vue.use(DataV)

// 按需引入
import { borderBox1 } from '@jiaminghi/data-view'
Vue.use(borderBox1)
```

详细文档及示例请移步[HomePage](http://datav.jiaminghi.com).

### UMD版

`UMD`版可直接使用`script`标签引入，`UMD`版文件位于项目`dist`目录下，引入后将自动把所有组件注册为**Vue全局组件**，引入`DataV`前请确保已引入`Vue`。

[UMD版使用示例](./umdExample.html)

### TODO

* **地图组件**
* **TS**重构组件库底层依赖

### 致谢

组件库的开发基于个人学习和兴趣，由于技术水平及经验的限制，组件尚有许多不完善之处，如有BUG可及时提交[issue](https://github.com/DataV-Team/DataV/issues/new?template=bug_report.md)或添加反馈群进行反馈，也欢迎提供指正和建议，感谢各位的支持。

### 反馈
![Feedback](./QQGroup.png)

### Demo

Demo页面使用了全屏组件，请F11全屏后查看。

* [施工养护综合数据](http://datav.jiaminghi.com/demo/construction-data/index.html)

![construction-data](./demoImg/construction-data.jpg)

* [机电运维管理台](http://datav.jiaminghi.com/demo/manage-desk/index.html)

![manage-desk](./demoImg/manage-desk.jpg)

* [机电设备电子档案](http://datav.jiaminghi.com/demo/electronic-file/index.html)

![electronic-file](./demoImg/electronic-file.jpg)
