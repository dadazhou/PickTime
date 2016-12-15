# PickTime
## 日期选择控件 ##


### 截图


<div style="background-color:rgb(43,43,43);padding:30">
<img src="image/all.jpg" height="320" width="180" style="margin-left:100"/>
<img src="image/ymdhm.jpg" height="320" width="180" style="margin-left:100"/>
<img src="image/ymdh.jpg" height="320" width="180" style="margin-left:100"/>
<img src="image/ymd.jpg" height="320" width="180" style="margin-left:100"/>
<img src="image/hm.jpg" height="320" width="180" style="margin-left:100"/>
</div>

### DateType

- TYPE_ALL--年、月、日、星期、时、分
- TYPE_YMDHM--年、月、日、时、分
- TYPE_YMDH--年、月、日、时
- TYPE_YMD--年、月、日
- TYPE_HM--时、分

### 设置

```java
            DatePickDialog dialog = new DatePickDialog(this);
            //设置上下年分限制
            dialog.setYearLimt(5);
            //设置标题
            dialog.setTitle("选择时间");
            //设置类型
            dialog.setType(DateType.TYPE_ALL);
            //设置消息体的显示格式，日期格式
            dialog.setMessageFormat("yyyy-MM-dd HH:mm");
            //设置选择回调
            dialog.setOnChangeLisener(null);
            //设置点击确定按钮回调
            dialog.setOnSureLisener(null);
            dialog.show();
```




