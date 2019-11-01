
timeFlag判断时间精度
#
最优
sys_date_time
#
sys_date_period:日期段  
最优判断{true,false,false,false}
某月 某年 某星期 （精度达不到天）
 #
sys_date 精确日期 

最优判断{true,true,false,false}

达成条件timeFlag[1] = true timeFlag[2] = false timeFlag[3] = false
 #
 
sys_time_period 时间段   下午 中午 上午 后续可添加



最优判断timeFlag[2] = true timeFlag[3] = false

达成条件timeFlag[2] = true
#

sys_time精确时间

最优判断timeFlag[3] = true

达成条件timeFlag[3] = true