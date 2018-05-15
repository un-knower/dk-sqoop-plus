<div style="line-height:1.7;color:#000000;font-size:14px;font-family:Arial"><div style="line-height: 1.5; font-family: Verdana;"><h1 style="box-sizing: border-box; margin-right: 0px; margin-bottom: 16px; margin-left: 0px; line-height: 1.25; padding-bottom: 0.3em; border-bottom: 1px solid rgb(234, 236, 239); color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; margin-top: 0px !important;">DK-Sqoop-plus</h1></div><div style="line-height: 1.5; font-family: Verdana;">本项目在原生sqoop&nbsp;<span style="color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;">(</span><a href="http://sqoop.apache.org/" rel="nofollow" style="box-sizing: border-box; color: rgb(3, 102, 214); text-decoration-line: none; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;">http://sqoop.apache.org/</a><span style="color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;">)&nbsp;</span>的基础上进行更多实用功能的扩展。</div><div style="line-height: 1.5; font-family: Verdana;">暂时只支持&nbsp; RDBMS（mysql 、oracle 、sqlserver） to Elasticsearch&nbsp; 和 HDFS to Elasticsearch 等功能，后续可能支持 Elasticsearch to RDBMS 等功能 。</div><div style="line-height: 1.5; font-family: Verdana;">项目编译参见原生sqoop。</div><div style="line-height: 1.5; font-family: Verdana;"><h2 style="box-sizing: border-box; margin-top: 24px; margin-bottom: 16px; line-height: 1.25; padding-bottom: 0.3em; border-bottom: 1px solid rgb(234, 236, 239); color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;;">Versions</h2></div><div style="line-height: 1.5; font-family: Verdana;"><table style="box-sizing: border-box; border-spacing: 0px; border-collapse: collapse; margin-top: 0px; margin-bottom: 16px; display: block; width: 888px; overflow: auto; color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;"><thead style="box-sizing: border-box;"><tr style="box-sizing: border-box; border-top: 1px solid rgb(198, 203, 209);"><th style="color: rgb(0, 0, 0); box-sizing: border-box; padding: 6px 13px; border: 1px solid rgb(223, 226, 229);">DK-Sqoop-plus</th><th style="color: rgb(0, 0, 0); box-sizing: border-box; padding: 6px 13px; border: 1px solid rgb(223, 226, 229);">Sqoop version</th><th style="color: rgb(0, 0, 0); box-sizing: border-box; padding: 6px 13px; border: 1px solid rgb(223, 226, 229);">ES version</th></tr></thead><tbody style="box-sizing: border-box;"><tr style="box-sizing: border-box; background-color: rgb(246, 248, 250); border-top: 1px solid rgb(198, 203, 209);"><td style="color: rgb(0, 0, 0); box-sizing: border-box; padding: 6px 13px; border: 1px solid rgb(223, 226, 229);">master</td><td style="color: rgb(0, 0, 0); box-sizing: border-box; padding: 6px 13px; border: 1px solid rgb(223, 226, 229);">&nbsp;1.x -&gt; master</td><td style="color: rgb(0, 0, 0); box-sizing: border-box; padding: 6px 13px; border: 1px solid rgb(223, 226, 229);">&nbsp;5.x -&gt; master</td></tr></tbody><tbody style="box-sizing: border-box;"><tr style="box-sizing: border-box; background-color: rgb(246, 248, 250); border-top: 1px solid rgb(198, 203, 209);"><td style="color: rgb(0, 0, 0); box-sizing: border-box; padding: 6px 13px; border: 1px solid rgb(223, 226, 229);">1.5.1</td><td style="color: rgb(0, 0, 0); box-sizing: border-box; padding: 6px 13px; border: 1px solid rgb(223, 226, 229);">&nbsp;1.5.4</td><td style="color: rgb(0, 0, 0); box-sizing: border-box; padding: 6px 13px; border: 1px solid rgb(223, 226, 229);">&nbsp;5.6.8</td></tr></tbody></table></div><div style="line-height: 1.5; font-family: Verdana;"><div><br /></div><h2 style="box-sizing: border-box; margin-top: 24px; margin-bottom: 16px; line-height: 1.25; padding-bottom: 0.3em; border-bottom: 1px solid rgb(234, 236, 239); color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;;">Install</h2><p style="line-height: 1.5; box-sizing: border-box; margin-top: 0px; margin-bottom: 16px; color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;">1.下载</p><p style="line-height: 1.5; box-sizing: border-box; margin-top: 16px; margin-bottom: 16px; color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;">编译后的安装包下载地址:&nbsp;<a href="https://github.com/dkhadoop/dk-sqoop-plus/releases/download/1.5.1/sqoop-1.4.5-plus-1.5.1.tar.gz" style="box-sizing: border-box; background-color: transparent; color: rgb(3, 102, 214); text-decoration-line: none;">https://github.com/dkhadoop/dk-sqoop-plus/releases/download/1.5.1/sqoop-1.4.5-plus-1.5.1.tar.gz</a></p><p style="line-height: 1.5; box-sizing: border-box; margin-top: 16px; margin-bottom: 16px; color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;">关于sqoop的相关配置请参考sqoop官网。</p></div><div style="line-height: 1.5; font-family: Verdana;"><h2 style="box-sizing: border-box; margin-top: 24px; margin-bottom: 16px; line-height: 1.25; padding-bottom: 0.3em; border-bottom: 1px solid rgb(234, 236, 239); color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;;">Quick Example</h2></div><div style="line-height: 1.5; font-family: Verdana;"><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;"><span style="font-weight: bold;"><b>1.MySQL to Elasticsearch</b></span></p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（1）进入安装bin目录执行：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop import --connect jdbc:mysql://192.168.1.31:3306/quick4j --username root --password 123456 --table permission -m 1 --target-dir 192.168.1.99:9200@dkes@dksqoop2/mysql</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（2）执行语句说明：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; sqoop import&nbsp; #固定，默认</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --connect jdbc:mysql://192.168.1.31:3306/quick4j&nbsp; #为MySQL数据库的连接信息，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --username root #MySQL数据库用户名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --password 123456 #MySQL数据库密码，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --table permission #MySQL要导入到elasticsearch的数据库表，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; -m 1&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;#指定导入时产生的mr的数量。注意：如果RDBMS数据库表中没有主键，则-m的值只能是1</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --target-dir 192.168.1.31:9200@dkes@dksqoop2/mysql&nbsp; #--target-dir的值包含三部分由“@”分隔，“@”前一部分192.168.1.99:9200为指定elasticsearch的主机地址和端口号，“@”中间一部分dkes为elasticsearch的集群名称,“@”后一部分dksqoop2/mysql包含两部分，由“/”分隔，“/”前一部分dksqoop2为elasticsearch的索引名称，“/”后一部分mysql为elasticsearch的类型名称。使用时请修改es的IP、索引名和类型名。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;"><b>2.Oracle to Elasticsearch</b></p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（1）进入安装bin目录执行：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop import --connect jdbc:oracle:thin:@192.168.1.35:1521:orcl --username system --password dkss --table DK10 -m 1 --target-dir 192.168.1.99:9200@dkes@dksqoop2/oracle</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（2）执行语句说明：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; sqoop import&nbsp; #固定，默认</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --connect jdbc:oracle:thin:@192.168.1.35:1521:orcl&nbsp; #为Oracle数据库的连接信息，使用时请修改。&nbsp;&nbsp;</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --username system&nbsp; #Oracle数据库用户名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --password dkss&nbsp; &nbsp; #Oracle数据库密码，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --table DK10&nbsp; &nbsp; &nbsp; &nbsp;#Oracle要导入到elasticsearch的数据库表，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; -m 1&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;#指定导入时产生的mr的数量。注意：如果RDBMS数据库表中没有主键，则-m的值只能是1</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --target-dir 192.168.1.99:9200@dkes@dksqoop2/oracle&nbsp; #--target-dir的值包含三部分由“@”分隔，“@”前一部分192.168.1.99:9200为指定elasticsearch的主机地址和端口号，“@”中间一部分dkes为elasticsearch的集群名称,“@”后一部分dksqoop2/oracle包含两部分，由“/”分隔，“/”前一部分dksqoop2为elasticsearch的索引名称，“/”后一部分oracle为elasticsearch的类型名称。使用时请修改es的IP、索引名和类型名。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;"><b>3.HDFS to Elasticsearch</b></p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（1）进入安装bin目录执行：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop export --connect "<a href="mailto:es@192.168.1.31">es@192.168.1.31</a>:9200@dkes@hdfs/sqoop"&nbsp; --export-dir aaa --fields-terminated-by '@' -m 1</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（2）执行语句说明：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; sqoop export&nbsp; #固定，默认</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --connect "<a href="mailto:es@192.168.1.126">es@192.168.1.126</a>:9200@dkes@hdfs/sqoop"&nbsp; &nbsp;#--connect的值包含四部分由“@”分隔,第一部分es为固定默认值，第二部分192.168.1.31:9200为连接elasticsearch的主机地址和端口，第三部分dkes为elasticsearch的集群名称，第四部分hdfs/sqoop为elasticsearch的索引名/类型名。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --export-dir aaa&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; #指的是要导出的hdfs文件所在的目录。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --fields-terminated-by '@'&nbsp; #--fields-terminated-by指的是hdfs文件内容各字段间的字段分隔符，如果不指定则默认为','分隔。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; -m 1&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;#指定导入时产生的mr的数量。mr数不能小于文件内容的记录条数。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;"><br /></p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">其它更多sqoop功能请参考sqoop&nbsp;<span style="color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;">(</span><a href="http://sqoop.apache.org/" rel="nofollow" style="box-sizing: border-box; color: rgb(3, 102, 214); text-decoration-line: none; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;">http://sqoop.apache.org/</a><span style="color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;">)&nbsp;</span><span style="text-indent: 0pt;">官方主页。</span></p><div style="line-height: 1.5; box-sizing: border-box; color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;"><h2 style="box-sizing: border-box; margin-top: 24px; margin-bottom: 16px; line-height: 1.25; padding-bottom: 0.3em; border-bottom: 1px solid rgb(234, 236, 239);">大快搜索（<a href="http://www.dkhadoop.com">http://www.dkhadoop.com</a>）</h2><div style="line-height: 1.5;"><p class="p1" style="line-height: 2; box-sizing: border-box; margin: 5px; font-size: 15px; text-indent: 2em; color: rgb(102, 102, 102); font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif;">人类从钻木取火，到发现希格斯玻色子；从简陋的牛郎星，到无所不在的移动计算；从达特默斯会议，到“大数据”时代的来临，这些改变人类生活方式的发现和创造，其灵魂皆为数学。</p><p class="p1" style="line-height: 2; box-sizing: border-box; margin: 5px; font-size: 15px; text-indent: 2em; color: rgb(102, 102, 102); font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif;">我们是一群信仰“算法能改变世界”的志同道合者组成的创业团队。我们相信数学是打开未来之门的钥匙。</p><p class="p1" style="line-height: 2; box-sizing: border-box; margin: 5px; font-size: 15px; text-indent: 2em; color: rgb(102, 102, 102); font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif;">大快搜索”是领先的大数据和人工智能基础软件供应商，提供商业发型版Hadoop集成生态环境（DKH）和大数据与人工智能一体化开发框架（Freerch）；以帮助大数据（软件）公司减少代码编写量，提升开发效率，降低成本为己任，将复杂的搜索、大数据、机器学习、流计算、图计算、自然语言处理、神经网络等，变成简单易用的接口和类库，底层技术从此触手可及！</p><p class="p1" style="line-height: 2; box-sizing: border-box; margin: 5px; font-size: 15px; text-indent: 2em; color: rgb(102, 102, 102); font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif;">大快，正引领着大数据与ai技术的发展，从自然语言处理到机器学习；从搜索引擎到大数据处理；从智能交通到金融风控；大快的基础软件，帮助众多大数据与人工智能项目，实现最高可达5倍的计算性能提升。</p><p class="p1" style="line-height: 2; box-sizing: border-box; margin: 5px; font-size: 15px; text-indent: 2em; color: rgb(102, 102, 102); font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif;">众多知名软件和大数据企业，均采用大快的基础软件，开发和部署大数据与人工智能应用。</p><p class="p1" style="line-height: 2; box-sizing: border-box; margin: 5px; font-size: 15px; text-indent: 2em; color: rgb(102, 102, 102); font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif;">大快，大数据技术的中国标准！</p></div></div></div></div>
