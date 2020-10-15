# NOTICE

This is an private built API but I made it open source now, so the code may not be generalized. You may need to modify the code before any uses.

It is a QQ API written in Python based on 小栗子 QQ frame with HTTPAPI plugin installed, so you will have those installed to make it work.

There are configs that can only be modified in code.

Notice that the API has a watchdog that keeps the lower API alive, it needs to be feed with ".getEvent()" action or directely with ".heartbeatClass.feed()" every 15 seconds by default(configable).

# USAGE

<strong> Do make sure you have started 小栗子 QQ frame with HTTPAPI plugin installed </strong>

<strong> If you haven't done that, go to https://bbs.xiaolz.cn/forum.php </strong>

  1. edit the config file
  
  2. place "remote_controller.py" in the same directory with "小栗子框架-快载.exe" and start "remote_controller.py" executer service

  3. import "QQAPI_Cody.py" api file in other code or in console
