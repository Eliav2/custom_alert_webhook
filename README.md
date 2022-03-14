# Splunk custom http alert app

the webhook shipped with Splunk-Enterprise is simple and many times does is not sufficient.

this webhook also allowed adding custom headers, and forwarding the search results as is without any modification.

### Add to your splunk app

to add this app to your splunk instance, you need to add clone this repository and add it to `$SPLUNK_HOME$/etc/apps`. for example `$SPLUNK_HOME$/etc/apps/custom_alert_webhook`.

after go to `http://<splunk-domain>:<port>/en-US/debug/refresh` and click on `refresh` button.

after that, you could see the new custom webhook options ape the new alert dialog:

add action:
![image](https://user-images.githubusercontent.com/47307889/158244598-e52a879c-8e01-4ea3-86ca-116f83c455ea.png)

the app form:
![image](https://user-images.githubusercontent.com/47307889/158244451-fe7368a7-6b11-496a-b1d4-b54fa426337c.png)

which allows you to add custom headers and forward the search results as is without any modification.
