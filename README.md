# yaddns

DDNS Yandex

My shell script for dynamic DNS services provided by <http://pdd.yandex.ru>.

## Instructions:

 1. Get **token** at [Token management](https://pddimp.yandex.ru/token/index.xml) page.
 2. Edit **yaddns** in a text editor, and modify the *DOMAIN*, *TOKEN* and *SUBDOMAIN* (for loop: subdomain1, subdomain2 etc) fields.
 3. Use system's cron to schedule the updates.

## Dependencies:

 1. nodejs jq curl: ```apt install nodejs jq curl```
 2. xml2json: ```npm install -g xml2json```
