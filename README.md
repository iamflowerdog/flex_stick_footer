## 移动端天猫flex 布局

* 给容器设置 `display: flex`
* 给伸缩项目设置。`flex:1 `实际解析成:

```
   flex: 1;
    flex-grow: 1;
    flex-shrink: 1;
    flex-basis: 0%;
```

* 兼容老版本浏览器
```
//容器
display: -webkit-box;

//伸缩项目
-webkit-box-flex: 1;

```

## 经典粘连布局

* 思想: 给整个上内容区两个div 一个 wrap 一个main
* wrap 的高度设置为 `min-height: 100%;`
* main 内容区的padding `padding-bottom: 50px;`
* 下面的footer margin-top `margin-top: -50px;`

* 整个footer就会跟随main区移动










