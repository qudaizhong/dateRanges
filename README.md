# dateRanges
二次封装时间选择插件laydate5.0.7
相对绝对时间范围选择
包含功能：单周，双周，单月，季度，自定义范围选择
相对时间选择，最近7天，最近14天，最近30天，最近90天

配置项：

          type: 'date' //控件类型，支持：year/month/date/time/datetime
          
        , range: false //是否开启范围选择，即双控件
        
        , format: 'yyyy-MM-dd' //默认日期格式
        
        , value: null //默认日期，支持传入new Date()，或者符合format参数设定的日期格式字符
        
        , min: '1900-1-1' //有效最小日期，年月日必须用“-”分割，时分秒必须用“:”分割。注意：它并不是遵循 format 设定的格式。
        
        , max: '2199-12-31' //有效最大日期，同上
        
        , trigger: 'focus' //呼出控件的事件
        
        , show: false //是否直接显示，如果设置true，则默认直接显示控件
        
        , showBottom: true //是否显示底部栏
        
        , btns: ['clear', 'confirm'] //右下角显示的按钮，会按照数组顺序排列
        
        , lang: 'cn' //语言，只支持cn/en，即中文和英文
        
        , theme: 'default' //主题
        
        , position: null //控件定位方式定位, 默认absolute，支持：fixed/absolute/static
        
        , calendar: false //是否开启公历重要节日，仅支持中文版
        
        , mark: {} //日期备注，如重要事件或活动标记
        
        , zIndex: null //控件层叠顺序
        
        , done: null //控件选择完毕后的回调，点击清空/现在/确定也均会触发
        
        , change: null //日期时间改变后的回调
        
        , Interval: true //开启区间范围
        
        , time:'absolute' //默认绝对时间 relative 相对时间
        
        , cycle:'week' //默认选择单周:week,双周：double-week,自然月：month,自然季度：quarterly,自定义：self
        

        单周选择
        
<img src="http://www.bloggeng.com/wp-content/uploads/2017/11/week.png" draggable="false" alt="">
        
        双周选择
        
        
<img src=" http://www.bloggeng.com/wp-content/uploads/2017/11/double.png" draggable="false" alt="">
       
       自然月
       
       
<img src=" http://www.bloggeng.com/wp-content/uploads/2017/11/month.png" draggable="false" alt="">
       
       自然季度
       
<img src=" http://www.bloggeng.com/wp-content/uploads/2017/11/jidu.png" draggable="false" alt="">
       
       自定义
       
<img src=" http://www.bloggeng.com/wp-content/uploads/2017/11/self.png" draggable="false" alt="">
       
      相对时间
      
<img src=" http://www.bloggeng.com/wp-content/uploads/2017/11/xiang.png" draggable="false" alt="">
      
      
     