## realtime_dw_cloud
### 说明
* realtime_dw_cloud etl 的调用接口
* demo 详见 etl_task/dwd_appoint_task.py

### 补充
*  dwd_XXX.xml中特殊字符的处理：
    &lt; < 小于号
    &gt; > 大于号
    &amp; & 和
    &apos; ' 单引号
    &quot; " 双引号
    https://blog.csdn.net/wu920604/article/details/74990835



###
    # 对输入的参数进行判断
    # python etl_main_cloud.py : 直接退出
    # python etl_main_cloud.py dwd_appoint_task : 执行增量
    # python etl_main_cloud.py dwd_appoint_task test : 测试模式执行增量