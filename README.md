# kurumi-web

是从 [约战手游官网](http://www.datealive.com/)扣下来的三三  
并封装了一个 loadkurumi(id)的方法  
演示 : [GithubPage演示站点](https://mikaguran.github.io/kurumi-web/index.html)

## 用法
1.引用js
```html
<script src="https://mikaguran.github.io/kurumi-web/kurumi.js"></script>
```
ps : 觉得慢的话可以把仓库拉下来放本地  
  
2.创建canvas标签
```html
<canvas id="kurumi" width="500" height="505" class="live2d"></canvas>
```
3.初始化live2d
```html
<script>
    loadkurumi("kurumi"); //kurumi也就是上面canvas标签里的id
</script>
```