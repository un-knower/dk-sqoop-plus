<div style="line-height: 1.5; font-family: Verdana;"><h1 style="box-sizing: border-box; margin-right: 0px; margin-bottom: 16px; margin-left: 0px; line-height: 1.25; padding-bottom: 0.3em; border-bottom: 1px solid rgb(234, 236, 239); color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; margin-top: 0px !important;">DK-Sqoop-plus</h1></div><div style="line-height: 1.5; font-family: Verdana;">本项目在原生sqoop&nbsp;<span style="color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;">(</span><a href="http://sqoop.apache.org/" rel="nofollow" style="box-sizing: border-box; color: rgb(3, 102, 214); text-decoration-line: none; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;">http://sqoop.apache.org/</a><span style="color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;">)&nbsp;</span>的基础上进行更多实用功能的扩展。</div><div style="line-height: 1.5; font-family: Verdana;">暂时只支持&nbsp; RDBMS（mysql 、oracle 、sqlserver） to Elasticsearch&nbsp; 和 HDFS to Elasticsearch 等功能，后续可能支持 Elasticsearch to RDBMS 等功能 。</div><div style="line-height: 1.5; font-family: Verdana;">项目编译参见原生sqoop。</div><div style="line-height: 1.5; font-family: Verdana;"><h2 style="box-sizing: border-box; margin-top: 24px; margin-bottom: 16px; line-height: 1.25; padding-bottom: 0.3em; border-bottom: 1px solid rgb(234, 236, 239); color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;;">Versions</h2></div><div style="line-height: 1.5; font-family: Verdana;"><table style="box-sizing: border-box; border-spacing: 0px; border-collapse: collapse; margin-top: 0px; margin-bottom: 16px; display: block; width: 888px; overflow: auto; color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;"><thead style="box-sizing: border-box;"><tr style="box-sizing: border-box; border-top: 1px solid rgb(198, 203, 209);"><th style="color: rgb(0, 0, 0); box-sizing: border-box; padding: 6px 13px; border: 1px solid rgb(223, 226, 229);">DK-Sqoop-plus version</th><th style="color: rgb(0, 0, 0); box-sizing: border-box; padding: 6px 13px; border: 1px solid rgb(223, 226, 229);">ES version</th></tr></thead><tbody style="box-sizing: border-box;"><tr style="box-sizing: border-box; border-top: 1px solid rgb(198, 203, 209);"><td style="color: rgb(0, 0, 0); box-sizing: border-box; padding: 6px 13px; border: 1px solid rgb(223, 226, 229);">master</td><td style="color: rgb(0, 0, 0); box-sizing: border-box; padding: 6px 13px; border: 1px solid rgb(223, 226, 229);">5.x -&gt; master</td></tr><tr style="box-sizing: border-box; background-color: rgb(246, 248, 250); border-top: 1px solid rgb(198, 203, 209);"><td style="color: rgb(0, 0, 0); box-sizing: border-box; padding: 6px 13px; border: 1px solid rgb(223, 226, 229);">1.5.4</td><td style="color: rgb(0, 0, 0); box-sizing: border-box; padding: 6px 13px; border: 1px solid rgb(223, 226, 229);">5.6.8</td></tr></tbody></table></div><div style="line-height: 1.5; font-family: Verdana;"><h2 style="box-sizing: border-box; margin-top: 24px; margin-bottom: 16px; line-height: 1.25; padding-bottom: 0.3em; border-bottom: 1px solid rgb(234, 236, 239); color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;;">Install</h2><p style="line-height: 1.5; box-sizing: border-box; margin-top: 0px; margin-bottom: 16px; color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;">1.下载</p><p style="line-height: 1.5; box-sizing: border-box; margin-top: 16px; margin-bottom: 16px; color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;">编译后的安装包下载地址:&nbsp;<a href="https://github.com/dkhadoop/dk-sqoop-plus/releases/download/1.5.1/sqoop-1.4.5-plus-1.5.1.tar.gz" style="box-sizing: border-box; background-color: transparent; color: rgb(3, 102, 214); text-decoration-line: none;">https://github.com/dkhadoop/dk-sqoop-plus/releases/download/1.5.1/sqoop-1.4.5-plus-1.5.1.tar.gz</a></p><p style="line-height: 1.5; box-sizing: border-box; margin-top: 16px; margin-bottom: 16px; color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;">关于sqoop的相关配置请参考sqoop官网。</p></div><div style="line-height: 1.5; font-family: Verdana;"><h2 style="box-sizing: border-box; margin-top: 24px; margin-bottom: 16px; line-height: 1.25; padding-bottom: 0.3em; border-bottom: 1px solid rgb(234, 236, 239); color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;;">Quick Example</h2></div><div style="line-height: 1.5; font-family: Verdana;"><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;"><span style="font-weight: bold;"><b>1.MySQL to Elasticsearch</b></span></p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（1）进入安装bin目录执行：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop import --connect jdbc:mysql://192.168.1.31:3306/quick4j --username root --password 123456 --table permission -m 1 --target-dir 192.168.1.99:9200@dkes@dksqoop2/mysql</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（2）执行语句说明：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; sqoop import&nbsp; #固定，默认</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --connect jdbc:mysql://192.168.1.31:3306/quick4j&nbsp; #为MySQL数据库的连接信息，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --username root #MySQL数据库用户名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --password 123456 #MySQL数据库密码，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --table permission #MySQL要导入到elasticsearch的数据库表，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; -m 1&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;#指定导入时产生的mr的数量。注意：如果RDBMS数据库表中没有主键，则-m的值只能是1</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --target-dir 192.168.1.31:9200@dkes@dksqoop2/mysql&nbsp; #--target-dir的值包含三部分由“@”分隔，“@”前一部分192.168.1.99:9200为指定elasticsearch的主机地址和端口号，“@”中间一部分dkes为elasticsearch的集群名称,“@”后一部分dksqoop2/mysql包含两部分，由“/”分隔，“/”前一部分dksqoop2为elasticsearch的索引名称，“/”后一部分mysql为elasticsearch的类型名称。使用时请修改es的IP、索引名和类型名。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;"><b>2.Oracle to Elasticsearch</b></p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（1）进入安装bin目录执行：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop import --connect jdbc:oracle:thin:@192.168.1.35:1521:orcl --username system --password dkss --table DK10 -m 1 --target-dir 192.168.1.99:9200@dkes@dksqoop2/oracle</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（2）执行语句说明：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; sqoop import&nbsp; #固定，默认</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --connect jdbc:oracle:thin:@192.168.1.35:1521:orcl&nbsp; #为Oracle数据库的连接信息，使用时请修改。&nbsp;&nbsp;</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --username system&nbsp; #Oracle数据库用户名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --password dkss&nbsp; &nbsp; #Oracle数据库密码，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --table DK10&nbsp; &nbsp; &nbsp; &nbsp;#Oracle要导入到elasticsearch的数据库表，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; -m 1&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;#指定导入时产生的mr的数量。注意：如果RDBMS数据库表中没有主键，则-m的值只能是1</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --target-dir 192.168.1.99:9200@dkes@dksqoop2/oracle&nbsp; #--target-dir的值包含三部分由“@”分隔，“@”前一部分192.168.1.99:9200为指定elasticsearch的主机地址和端口号，“@”中间一部分dkes为elasticsearch的集群名称,“@”后一部分dksqoop2/oracle包含两部分，由“/”分隔，“/”前一部分dksqoop2为elasticsearch的索引名称，“/”后一部分oracle为elasticsearch的类型名称。使用时请修改es的IP、索引名和类型名。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;"><b>3.HDFS to Elasticsearch</b></p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（1）进入安装bin目录执行：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop export --connect "es@192.168.1.31:9200@dkes@hdfs/sqoop"&nbsp; --export-dir aaa --fields-terminated-by '@' -m 1</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（2）执行语句说明：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; sqoop export&nbsp; #固定，默认</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --connect "es@192.168.1.126:9200@dkes@hdfs/sqoop"&nbsp; &nbsp;#--connect的值包含四部分由“@”分隔,第一部分es为固定默认值，第二部分192.168.1.31:9200为连接elasticsearch的主机地址和端口，第三部分dkes为elasticsearch的集群名称，第四部分hdfs/sqoop为elasticsearch的索引名/类型名。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --export-dir aaa&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; #指的是要导出的hdfs文件所在的目录。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --fields-terminated-by '@'&nbsp; #--fields-terminated-by指的是hdfs文件内容各字段间的字段分隔符，如果不指定则默认为','分隔。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; -m 1&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;#指定导入时产生的mr的数量。mr数不能小于文件内容的记录条数。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;"><span style="font-weight: bold;"><b>4.MySQL to Hbase(导入hbase时指定的hbase表必须存在)</b></span></p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（1）进入安装bin目录执行：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop import --connect jdbc:mysql://192.168.1.31:3306/quick4j --username root --password 123456 --table permission --columns "id,permission_name,permission_sign" --hbase-table mysql2hbase --column-family info&nbsp; --hbase-row-key id --split-by id -m 1</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">执行语句说明：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">./sqoop import #固定，默认</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --connect jdbc:mysql://dk31:3306/quick4j #为MySQL数据库的连接信息，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --username root #为MySQL数据库的用户名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --password 123456 #为MySQL数据库的密码，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --table permission #MySQL要导入到hbase的数据库表，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --columns "id,permission_name,permission_sign" #指定需要导入hbase表的mysql表中的字段。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --hbase-table mysql2hbase #指定hbase中的表名，hbase-1.2.0需要提前在hbase中手动建表。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --column-family info #指定hbase表中的列族名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --hbase-row-key id #hbase行键 指定rowkey时，是从mysql中选一个没有重复的字段 。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --split-by id #sqoop依据mysql的主键导入数据，如果没有主键，设置根据那个字段切割。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; -m 1&nbsp; #指定导入时产生的mr的数量。mr数不能小于文件内容的记录条数。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;"><span style="font-weight: bold;"><b>5.Oracle to Hbase</b></span></p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（1）进入安装bin目录执行：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop import --connect jdbc:oracle:thin:@192.168.1.35:1521:orcl --username system --password dkss --table dk002 --table permission --columns "id,permission_name,permission_sign" --hbase-table mysql2hbase --column-family info --hbase-create-table --hbase-row-key id --split-by id -m 1</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（2）执行语句说明：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop import #固定，默认</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --connect jdbc:oracle:thin:@192.168.1.35:1521:orcl #为Oracle数据库的连接信息，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --username root #为Oracle数据库的用户名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --password 123456 #为Oracle数据库的密码，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --table permission #Oracle要导入到hbase的数据库表，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --columns "id,permission_name,permission_sign" #指定需要导入hbase表的Oracle表中的字段。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --hbase-table mysql2hbase #指定hbase中的表名，hbase-1.2.0需要提前在hbase中手动建表。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --column-family info #指定hbase表中的列族名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --hbase-row-key id #hbase行键 指定rowkey时，是从Oracle中选一个没有重复的字段&nbsp;</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --split-by id #sqoop依据Oracle的主键导入数据，如果没有主键，设置根据那个字段切割</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; -m 1&nbsp; #指定导入时产生的mr的数量。mr数不能小于文件内容的记录条数。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;"><span style="font-weight: bold;"><b>6.MySQL to HDFS</b></span></p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（1）进入安装bin目录执行：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop import --connect jdbc:mysql://192.168.1.31/quick4j --username root --password 123456 --table permission --target-dir permission --m 1</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（2）执行语句说明：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop import #固定，默认</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --connect jdbc:mysql://dk31:3306/quick4j #为MySQL数据库的连接信息，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --username root #为MySQL数据库的用户名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --password 123456 #为MySQL数据库的密码，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --table permission #MySQL要导入到hbase的数据库表，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --columns "id,permission_name,permission_sign" #指定需要导入hbase表的mysql表中的字段。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --hbase-table mysql2hbase #指定hbase中的表名，hbase-1.2.0需要提前在hbase中手动建表。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --column-family info #指定hbase表中的列族名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --hbase-create-table</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --hbase-row-key id #hbase行键 指定rowkey时，是从mysql中选一个没有重复的字段&nbsp;</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --split-by id #sqoop依据mysql的主键导入数据，如果没有主键，设置根据那个字段切割</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; -m 1&nbsp; #指定导入时产生的mr的数量。mr数不能小于文件内容的记录条数。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;"><span style="font-weight: bold;"><b>7.Oracle to HDFS</b></span></p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（1）进入安装bin目录执行：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop import --connect jdbc:oracle:thin:@192.168.1.35:1521:orcl --username system --password dkss --table DK10 --target-dir dk10 -m 1</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（2）执行语句说明：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop import #固定，默认</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --connect jdbc:oracle:thin:@192.168.1.35:1521:orcl #为Oracle数据库的连接信息，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --username system #为Oracle数据库的用户名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --password dkss #为Oracle数据库的密码，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --table permission #Oracle要导入到hbase的数据库表，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --columns "id,permission_name,permission_sign" #指定需要导入hbase表的Oracle表中的字段。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --hbase-table oracle2hbase #指定hbase中的表名，hbase-1.2.0需要提前在hbase中手动建表。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --column-family info #指定hbase表中的列族名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --hbase-create-table</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --hbase-row-key id #hbase行键 指定rowkey时，是从Oracle中选一个没有重复的字段&nbsp;</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --split-by id #sqoop依据mysql的主键导入数据，如果没有主键，设置根据那个字段切割</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; -m 1&nbsp; #指定导入时产生的mr的数量。mr数不能小于文件内容的记录条数。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;"><span style="font-weight: bold;"><b>8.HDFS to MySQL</b></span></p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（1）进入安装bin目录执行：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop export --connect jdbc:mysql://192.168.1.31:3306/quick4j --username root --password 123456 --table shopassoc&nbsp; --fields-terminated-by '\t' --export-dir /user/root/output/part</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（2）执行语句说明：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; sqoop export #固定，默认</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --connect jdbc:mysql://dk31:3306/quick4j #为MySQL 数据库的连接信息，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --username root #为MySQL 数据库的用户名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --password 123456 #为MySQL 数据库的密码，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --table shopassoc&nbsp; #指定需要导入MySQL的哪张表。需提前创建。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --fields-terminated-by '\t' #指定HDFS上文件的分隔符。默认为'\t’。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --export-dir /user/root/output/part #指定需要从HDFS导出的文件所在的目录。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;"><span style="font-weight: bold;"><b>9.HDFS to Oracle</b></span></p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（1）进入安装bin目录执行：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop export --connect jdbc:oracle:thin:@192.168.1.35:1521:orcl --username sys --password dkss --table shopassoc&nbsp; --fields-terminated-by '\t' --export-dir /user/root/output/part</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（2）执行语句说明：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; sqoop export #固定，默认</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --connect jdbc:oracle:thin:@192.168.1.35:1521:orcl#为Oracle 数据库的连接信息，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --username sys #为Oracle 数据库的用户名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --password dkss #为Oracle 数据库的密码，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --table shopassoc&nbsp; #指定需要导入Oracle 的哪张表。需提前创建。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --fields-terminated-by '\t' #指定HDFS上文件的分隔符。默认为'\t’。使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --export-dir /user/root/output/part #指定需要从HDFS导出的文件所在的目录。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;"><span style="font-weight: bold;"><b>10.MySQL to hive</b></span></p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（1）进入安装bin目录执行：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop import --connect jdbc:mysql://192.168.1.31/quick4j --username root --password 123456 --table permission --fields-terminated-by "\t" --hive-import --hive-database default --hive-table mysql2hive --delete-target-dir --hive-overwrite</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（2）执行语句说明：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop import #固定，默认</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --connect jdbc:mysql://dk31/quick4j #为MySQL 数据库的连接信息，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --username root #为MySQL 数据库的用户名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --password 123456 #为MySQL 数据库的密码，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --table permission #为MySQL要导入到hive的数据库表，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --fields-terminated-by "\t" #指定hive的分隔符。使用时可默认。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --hive-import #固定，默认。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --hive-database default #指定导入hive的数据库。--hive-table #指定导入hive中的表名。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --delete-target-dir #删除已存在的目录。固定，默认。--hive-overwrite #覆盖原有内容的方式导入hive表，使用时可修改。可修改为追加写入或者覆盖写入。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;"><span style="font-weight: bold;"><b>11.Oracle to hive</b></span></p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（1）进入安装bin目录执行：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop import --connect jdbc:oracle:thin:@192.168.1.35:1521:orcl --username system --password dkss --table DK10 --fields-terminated-by "\t"&nbsp; --hive-import --hive-database default --hive-table oracle2hive --delete-target-dir --hive-overwrite -m 1</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">（2）执行语句说明：</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; ./sqoop import #固定，默认</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --connect jdbc:oracle:thin:@192.168.1.35:1521:orcl#为Oracle 数据库的连接信息，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --username system #为Oracle 数据库的用户名，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --password dkss #为Oracle 数据库的密码，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --table permission #Oracle 要导入到hive的数据库表，使用时请修改。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --fields-terminated-by "\t" #指定hive的分隔符。使用时可默认。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --hive-import #固定，默认。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --hive-database default #指定导入hive的数据库。无需提前创建。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --hive-table #指定导入hive中的表名。无需提前创建。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">&nbsp; &nbsp; --delete-target-dir #删除已存在的目录。固定，默认。--hive-overwrite #覆盖原有内容的方式导入hive表，使用时可修改。可修改为追加写入或者覆盖写入。</p><p class="MsoNormal" align="justify" style="line-height: 20pt; margin-right: 0pt; margin-left: 0pt; text-indent: 0pt; text-align: justify;">其它更多sqoop功能请参考sqoop官方主页。</p><div style="line-height: 1.5; box-sizing: border-box; color: rgb(36, 41, 46); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;; font-size: 16px;"><h2 style="box-sizing: border-box; margin-top: 24px; margin-bottom: 16px; line-height: 1.25; padding-bottom: 0.3em; border-bottom: 1px solid rgb(234, 236, 239);">大快搜索</h2><div style="line-height: 1.5;"><p class="p1" style="line-height: 2; box-sizing: border-box; margin: 5px; font-size: 15px; text-indent: 2em; color: rgb(102, 102, 102); font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif;">人类从钻木取火，到发现希格斯玻色子；从简陋的牛郎星，到无所不在的移动计算；从达特默斯会议，到“大数据”时代的来临，这些改变人类生活方式的发现和创造，其灵魂皆为数学。</p><p class="p1" style="line-height: 2; box-sizing: border-box; margin: 5px; font-size: 15px; text-indent: 2em; color: rgb(102, 102, 102); font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif;">我们是一群信仰“算法能改变世界”的志同道合者组成的创业团队。我们相信数学是打开未来之门的钥匙。</p><p class="p1" style="line-height: 2; box-sizing: border-box; margin: 5px; font-size: 15px; text-indent: 2em; color: rgb(102, 102, 102); font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif;">大快搜索”是领先的大数据和人工智能基础软件供应商，提供商业发型版Hadoop集成生态环境（DKH）和大数据与人工智能一体化开发框架（Freerch）；以帮助大数据（软件）公司减少代码编写量，提升开发效率，降低成本为己任，将复杂的搜索、大数据、机器学习、流计算、图计算、自然语言处理、神经网络等，变成简单易用的接口和类库，底层技术从此触手可及！</p><p class="p1" style="line-height: 2; box-sizing: border-box; margin: 5px; font-size: 15px; text-indent: 2em; color: rgb(102, 102, 102); font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif;">大快，正引领着大数据与ai技术的发展，从自然语言处理到机器学习；从搜索引擎到大数据处理；从智能交通到金融风控；大快的基础软件，帮助众多大数据与人工智能项目，实现最高可达5倍的计算性能提升。</p><p class="p1" style="line-height: 2; box-sizing: border-box; margin: 5px; font-size: 15px; text-indent: 2em; color: rgb(102, 102, 102); font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif;">众多知名软件和大数据企业，均采用大快的基础软件，开发和部署大数据与人工智能应用。</p><p class="p1" style="line-height: 2; box-sizing: border-box; margin: 5px; font-size: 15px; text-indent: 2em; color: rgb(102, 102, 102); font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif;">大快，大数据技术的中国标准！</p></div></div></div>
