## lazyload图片懒加载
#### 页面中引入img标签
~~~
<img class="lazy" data-original="images/02.jpg" width="640" height="480">
~~~
#### 先引入jQuery
~~~
<script src="./js/jquery-1.8.2.min.js"></script>
~~~
#### 再引入lazyload.js插件
~~~
<script src="./js/jquery.lazyload.min.js"></script>
~~~
#### 调用
~~~
$(document).ready(function () {
        $("img.lazy").lazyload();
});
~~~
