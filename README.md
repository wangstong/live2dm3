### 使用官方的sdk封装的js文件，可以使用moc3
参考了大佬的博客https://blog.csdn.net/weixin_44128558/article/details/104792345
对里面的一些内容进行修改

### 使用方法
```html
<!-- Live2DCubismCore script -->
<script src="https://cdn.jsdelivr.net/gh/wangstong/mycdn/live2d/js/live2dcubismcore.js"></script>
<!-- Build script -->
<script src="https://cdn.jsdelivr.net/gh/wangstong/mycdn/live2d/js/bundle.js"></script>

<!-- 这里可以定义画布的大小位置 -->
<canvas id="live2d" width="500" height="500" class="live2d" style="position: fixed; opacity: 1; right: 0px; bottom: -20px; z-index: 99999; pointer-events: none;"></canvas>

<script type="text/javascript">
  var resourcesPath = 'https://cdn.jsdelivr.net/gh/wangstong/mycdn/live2d/model/'; // 指定资源文件（模型）保存的路径
  var backImageName = ''; // 指定背景图片
  var modelDir = ['Hiyori']; // 指定需要加载的模型
  initDefine(resourcesPath, backImageName, modelDir); // 初始化模型
</script>
```
