bash
====

bash scripts

this script works CentOS 6 . 6.5 and 7
need sensors to install

How to create and run script?

1. vi systemstats.sh
2. save 
3. chmod +x systemstats.sh
4. ./systemstats.sh

NOTE:
remove comments before 

#> /etc/motd

and put before

exit 0

do the task in the cronetab

*/5 * * * * root /pat/to/systemstats.sh

you will get dynamic motd
