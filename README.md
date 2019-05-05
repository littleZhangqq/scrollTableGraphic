
能解决某些特殊应用情况下的问题( 如navigationBar会根据tableView的位移改变透明度的时候)
先看效果:  UITableView的frame = 全屏大小
可以解决的问题:
向上滑动的时候头部悬停位置不在屏幕的最上方, 在我指定的一个位置悬停.

![这是图片](https://github.com/littleZhangqq/scrollTableGraphic/blob/master/TableTest/Untitled.gif)

// 实现方式:


UITableView初始化的时候UITableViewStyle使用plain样式, 不要用grouped样式(grouped默认不会悬停)
实现代理方法:






