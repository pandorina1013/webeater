# WebEater

crawl web site by wget

## How to run

create url list in eater.sh


```shell=
timeout 300 wget -r -l 2 -p -E -k –random-wait -o /dev/stdout --no-check-certificate --restrict-file-names=nocontrol -nc -P webfile <url>
timeout 300 wget -r -l 2 -p -E -k –random-wait -o /dev/stdout --no-check-certificate --restrict-file-names=nocontrol -nc -P webfile <url>
timeout 300 wget -r -l 2 -p -E -k –random-wait -o /dev/stdout --no-check-certificate --restrict-file-names=nocontrol -nc -P webfile <url>
timeout 300 wget -r -l 2 -p -E -k –random-wait -o /dev/stdout --no-check-certificate --restrict-file-names=nocontrol -nc -P webfile <url>
...
```

Run it


```shell=
sh eater.sh
```