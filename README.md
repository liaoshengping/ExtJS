>教程：https://www.w3cschool.cn/extjs/extjs_containers.html

## hello word
````html
<!DOCTYPE html>
<html>
   <head>
      <link href="https://cdn.bootcss.com/extjs/6.0.0/classic/theme-classic/resources/theme-classic-all.css" rel="stylesheet">
      <script src="https://cdn.bootcss.com/extjs/6.0.0/ext-all.js"></script>
      <script type="text/javascript">
         Ext.onReady(function() {
         Ext.create('Ext.Panel', {
            renderTo: 'helloWorldPanel',
            height: 200,
            width: 600,
            title: 'Hello world',
            html: 'First Ext JS Hello World Program'
            });
         });
      </script>
   </head>
   <body>
      <div id="helloWorldPanel" />
   </body>
</html>
````
## 弹窗
````javascript
 Ext.MessageBox.alert('Tab one', 'Tab One was clicked.');
````
- [表单](form/index.md)
- [容器](container/index.md)
- [列表](list/index.html)

