IDEAS
=====

* Pytonize get-bacula-jobs-json.py: less bash, more python
* Allow to use both absolute and relative paths in conf.py
* Merge notify.py and notify_operator.py
* Get not only job name, but also job type and for backup jobs - backup type:
	item["job1","backup","full"]
	item["job1","backup","diff"]
	item["job1","backup","inc"]
	item["job2","verify",""]
	item["job3","restore",""]
* Make trigger - WARNING if full backup job had 0 bytes written.

BUGS
====

* Spare lest argument for notify_operator.py (not used)
* Return non-zero status if zabbix_sender failed (See EXIT_STATUS at https://www.zabbix.com/documentation/2.2/manpages/zabbix_sender)
