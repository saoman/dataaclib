
{
        "uuid": "F6A6C801B7197603",                 //用户标识
        "t"   : "",
        "acData" : {
             "type"    : "ACCERR",     		        //上报数据类型：代码异常数据
             "path"    : "www.domain.com/w/w/w/", //事件发生页面的url
             "sTme"    : "1591760073422",	        //事件上报时间
             "msg"     : "script error",          //异常摘要
             "line"    : "301",  		              //代码行数
             "col"     : "13",  		              //代码列下标
             "err"     : "error message",         //错误信息
         }
}

              
{
        "uuid": "F6A6C801B7197603",                         //用户标识
        "t"   : "",
        "acData" : {
             "type"        : "ACSCERR",     		            //上报数据类型：资源加载异常数据
             "path"        : "www.domain.com/w/w/w/",       //事件发生页面地址
             "sTme"        : "1591760073422",	              //事件上报时间
             "fileName"    : "test.js",                     //文件名
             "resourceUri" : "http://isjs.cn/js/test.js",   //资源地址
             "tagName"     : "script",  		                //标签类型
             "outerHTML"   : "script ...",                  //标签内容
          }
}


{
        "uuid": "F6A6C801B7197603",                      //用户标识
        "t"   : "",
        "acData" : {
            "type"        : "ACPRERR",     		           //上报数据类型：Promise 异常数据
            "path"        : "www.domain.com/w/w/w/",     //事件发生页面地址
            "sTme"        : "1591760073422",	           //事件上报时间
            "reason"      : "reason"                     //异常说明
         }
}       
              
              
{
        "uuid": "F6A6C801B7197603",                      //用户标识
        "t"   : "",
        "acData" : {
            "type"          : "ACVUERR",     		         //上报数据类型：Vue异常监控数据
            "path"          : "www.domain.com/w/w/w/",   //事件发生页面地址
            "sTme"          : "1591760073422",	         //事件上报时间
            "componentName" : "Button"                   //组件名
            "fileName"      : "button.js"                //组件文件
            "propsData"     : "{}"                       //组件props
            "err"           : "..."                      //错误堆栈
            "info"          : "信息"                      //错误信息
            "msg"           : "1"                        //异常摘要
         }
}

//search
uuid,type,path,sTme,
//list
uuid,type,path,sTme,data
uuid,类型,路径,时间,数据