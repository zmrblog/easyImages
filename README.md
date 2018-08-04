![例子](https://img.545141.com/images/201808/daf111c0b24a5753.png "例子")
# EasyImage 简单图床 介绍
  之前一直用的图床程序是:PHP多图长传程序2.4.3
  由于版本过老并且使用falsh上传，在当前html5流行大势所趋下，遂利用基础知识新写了一个以html5为默认上传并且支持flash,兼容至IE9。
  
  本代码受到PHP多图片上传程序2.4.3启发,以练习PHP为目而写。
  js不要设置分片上传大小，此会导致部分图片上传失败。
  当上传失败时默认最大尝试3次。
  **使用前请注意先修改config.php中的domain域名为自己的！**
  
 * 支持设置图片质量
 * 支持文字/图片水印 可自定义文字颜色
 * 支持文字水印背景颜色
 * 支持文字水印透明度
 * 支持上传图片转换为指定格式
 * 支持设置图片指定宽/高
 * 支持限制最低宽度/高度上传
 * 支持静态文件CDN/本地切换
 * 支持浏览最近上传图片
 * 支持设置广告
 * - 待开发：
   -  上传图片至远程存储路径
   -  完善管理设置
   -  修复中文水印乱码

---
* 2018-8-4 v1.3.2
 - 添加广告设置
 - 完善引入机制
 
* 2018-8-3 v1.2.2
 - [重要]修复水印图片不能添加
 - 添加随机浏览上传图片 可以设定浏览数量和关闭浏览
 - 优化代码，删除无用文件
 - 完善一键CDN静态文件

* 2018-08-02 v1.1.2
 - [重要] 修复gif上传添加水印成静态的问题
 - 修复文字水印背景色不显示问题
 - 修复在linux下的权限错误
 -  一些优化更改
 
* 2018-08-01 v1.0.1
 - 更改相关文件目录
 - 优化代码
 
* 2018-07-30 v1.0.0
 - 最初模型
 
 ### 兼容性 
文件上传视图不支持IE9以下的浏览器。
文件上传视图提供文件列表管理和文件批量上传功能，允许拖拽（需要 HTML5  支持）来添加上传文件，支持大文件分片上传，优先使用    HTML5 文件上传功能，旧的浏览器自动使用 Flash 和  Silverlight 的方式兼容。
   
----
  - 感谢: [verot](https://www.verot.net "verot") 提供非常好用的class.upload.php上传类  
  - 感谢: [ZUI](http://zui.sexy/ "ZUI") 提供css框架
  - 感谢: cctv让我能上Github
  - 本源码遵循 GNU Public License