# JHCalendar
JHCalendar is a calendar for ios

JHCalendar的使用
-------------

1、把项目中的JHCalendar文件夹拖入到自己的项目中<br> 
2、在ViewController.m文件中导入头文件 #import "JHCalendarMainView.h"<br> 
3、在viewDidLoad方法中加入如下代码即可<br> 
```oc
JHCalendarMainView *calendar = [[JHCalendarMainView alloc] init];
[self.view addSubview:calendar];
