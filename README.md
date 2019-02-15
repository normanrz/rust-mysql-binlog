`mysql_binlog` is a clean, idomatic Rust implementation of a MySQL binlog parser, including support for the JSONB type introduced in MySQL 5.7.

Its primary purpose is handling row-based logging messages, but it has rudimentary support for older statement-based replication. It's been tested against Percona XtraDB (MySQL) 5.6 and 5.7.

This library seeks be competitive with `mysqlbinlog` at parsing full logs, and is already several orders of magnitude faster than `go-mysql`, `python-mysql-replication`, or Ruby's `mysql_binlog`
