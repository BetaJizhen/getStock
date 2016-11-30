# getStock

###SINA财经的数据来源分析

沪市A股：http://vip.stock.finance.sina.com.cn/mkt/#sh_a
    
深市A股：http://vip.stock.finance.sina.com.cn/mkt/#sz_a
    
创业板数据：http://vip.stock.finance.sina.com.cn/mkt/#cyb_root
    
    url  	http://vip.stock.finance.sina.com.cn/quotes_service/api/json_v2.php/Market_Center.getHQNodeData?page=1&num=40&sort=symbol&asc=1&node=cyb&_s_r_a=init
    GET/POST	GET
    发送的头信息（request header）	Referer         http://vip.stock.finance.sina.com.cn/mkt/#cyb_root 
                                 Content-Type    application/x-www-form-urlencoded
                                 其他的，都是常见header的值，此处无需再赘述，但要注意到写代码的时候，还是要加上的

    希望返回的数据（request body）	包含我们所要的sz300001的json字符串

   
### 通过BS4等库抓取数据


###将数据存储在数据库中

###对数据进行清理，加工

###对数据进行分析，设定相应的策略

###导出分析后的结果
