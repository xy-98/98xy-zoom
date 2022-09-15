# Vue3.2+-ZoomGlass

 使用 [lodash-es](www.lodashjs.com)，支持 [Vue.js](https://vuejs.org/) 3.2+。

![](展示图片.png)

## 安装 & 使用
### npm

~~~shell
$ npm install xy-zoom
~~~



## 局部引入

~~~vue
<script setup>
  import Zoom from '98xy-zoom'
  </script>

  <template>
    <Zoom
      class="zoom"
      imgSrc="图片地址"
    />
  </template>

  <style scoped>
    .zoom {
      width: 100px;
      height: 100px;
    }
  </style>

~~~
