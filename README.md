# angularDateTimePicker.html
使用angualr的directive实现bootstrap插件datetimepicker

使用方法：

1.引入指令

 app.directive('dateandtime', ['dateFilter', function (dateFilter) {.....
 
2.dom中使用


\<dateandtime ng-model="times"
                 format="dat"
                 language="Ch"
                 todaybtn
                 autoclose
                 ....
                 style="width: 200px">
 \</dateandtime>
 
 
 
属性配置

/**<br>
     * 默认值<br>
     * format：date显示日期，不填或者其他显示日期和时间。属性必须有<br>
     * language:Ch(中文)<br>
     * weekStart:7（周日）<br>
     * minView:自动设置，与format匹配<br>
     *
     * 以下属性有就会显示，否则不显示<br>
     * clearBtn<br>
     * todayBtn<br>
     * autoclose<br>
     */<br>
