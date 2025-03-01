---
title: Configurations
layout: home
---

This section may also be known "Things to do after installing Asahi Linux." As you may have seen such videos and pages. This could also be useful items to "not live without" from a daily Mac user. No order of importance. 

I am using Vim which already comes put together neatly with highlights, etc. Kind of nice. 


1. TOC
{:toc}

### Disable Akonadi/Calendar Reminders
1. Disable KDE Plasma Calendar Reminders (takes up too much memory, and I don't use it). Also known as Akonadi

    -- Edit `/$HOME/.config/akonadi/akonadiserverrc` and set `StartServer=false`. Versus `true`, obviously.
    ``` bash
    [Debug]
    Tracer=null

    [%General]
    Driver=QMYSQL

    [QMYSQL]
    DataDir=/home/jesse/.local/share/akonadi/db_data
    Host=
    Name=akonadi
    Options="UNIX_SOCKET=/run/user/1000/akonadi/mysql.socket"
    ServerPath=/usr/libexec/mysqld
    StartServer=false

    ```

### Screenshots
2. I use `command+shift+s` which will bring up `Spectable.`

This is vital for my day-to-day work life. I always need to take screenshots to minimize the amount of questions brought forward by JR devs :D. 



### Apple Keyboard and Mouse

As a daily Mac user. I also use an Apple Keyboard, and Apple Mice device. The latter which no-one should use as it is a horrific ergonomic device. Plus it works awful in Asahi--or Linux in general. It tries to simulate a three button device, which at first drove me nuts thinking my something was wrong. It also seems off while scrolling, and navigating around windows or dragging them. I eventually changed to a Logic Ergo Device which works 10 times better. 

The keyboard works great. Connect it first to the laptop, disconnect. Then bluetooth pair. Works great waking up just like it would on Mac OS. 

For an alternative mouse option. This is the perfect compatible device I am now using [Logitech M575](https://www.amazon.com/Logitech-910-005867-M575-Latin-America/dp/B08TLYK78K/ref=sr_1_3?crid=OOU0I7DPI1QA&dib=eyJ2IjoiMSJ9.2iGlZoqGxBjs6rbLCRIzDlI11L4XreG2OxF-Xx_AsZSQqwmUY89p--OA4k9gZimBi8KEG6UqusEd0CiXDjOxy3-2G1PX640Jm-Z_aeuBy5LrwbtqfitwT7euieW8OLKsnPMS9HQyNszVvCX8bNxzZJ4L4CLVUA_W2P8-OOXt4YjHmUa54PYx0qE1xSJJyVIi2N-ToV-xk82I2cfIp8bvUtfMybpOW9xAbpBTTzw9Y7o.EyxqTMGWAOJtcYVIh99t1kE2AxO4DDFjStszWyl8i90&dib_tag=se&keywords=logitech+ergo+mouse&qid=1740789379&sprefix=logitech+ergo+mouse%2Caps%2C206&sr=8-3)

----
