
### Oracle Attack Methodology

```
oscanner -s 192.168.1.200 -P 1521
nmap --script=oracle-tns-version
nmap -p 1521 -A TARGET
nmap --script=oracle-brute 
auxiliary/scanner/oracle/tnslsnr_version ( Oracle - Version)
auxiliary/scanner/oracle/tnspoison_checker
auxiliary/scanner/oracle/sid_enum
auxiliary/admin/oracle/sid_brute
auxiliary/scanner/http/oracle_ilom_login
```

### MSSQL

```
nmap -sU --script=ms-sql-info 192.168.1.108 192.168.1.156
auxiliary/scanner/mssql/mssql_ping
auxiliary/admin/mssql/mssql_enum
auxiliary/scanner/oracle/tnspoison_checker
```
