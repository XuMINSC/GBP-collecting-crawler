### Use Python to collect GBP-RMB exchange rates（用Python爬取人民币-英镑汇率）

#### 本项目共包含两个子文件：
##### *1.爬取当天汇率+邮件提醒*
无需指定任何参数，即可从中国银行网站上爬取英镑汇率；并根据提前设定的标准来判断是否符合买入条件，如果符合，则自动发邮件提醒买入

##### *2.爬取某个期间的英镑汇率-需指定区间*
需要指定一个时间范围，如’2020-03-01‘到’2020-04-01‘，程序会自动爬取这期间内中国银行发布的所有英镑汇率

----
##### ***注意：为了避免对网站造成过大负担，两个文件均设置了一定休眠时间，如需短时间内大量爬取，可使用IP代理池及多线程/进程***
                                                                                 
                                                                           by Xu Min 闵旭
