### vim 快速注释和取消注释

```javascript
#注释方法一
5,11 s/^/#  按下enter
#注释方法二
ctrl键 + v(VISUAL模式)  >  j(小写j向下滚动)  > shift + i(编辑) > #(输入＃号) > esc (需要按两次)

大D 删除引号后面所有 ，大A插入模式

#取消注释方法一
5,11 s/#/   按下enter
#取消注释方法二
ctrl键 + v(VISUAL模式)  >  j(小写j向下滚动)  > d(小写d批量删除#号)
```
