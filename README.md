# how-to-jump-the-wall

#### Install Shadowsocks
Follow the 2 choice to install shadowsocks-qt5 from github: https://www.litcc.com/2016/12/29/Ubuntu16-shadowsocks-pac/index.html

REMEMBER: use AppImage file.

#### Get band wagon host
Try to find a 'CN2 server'<br>
https://bandwagonhost.com/

Bandwagon host is a very good choice.

Follow this:
http://www.huizhanzhang.com/2017/05/bandwagon-one-key-shadowsocks.html

after purchasing a server, go to KiviVM Control Panel

If there is no install shadowsocks button, go to this url, you should see the button now:
https://kiwivm.64clouds.com/preloader.php?load=/main-exec.php?mode=extras_shadowsocks

I think you need vpn to follow this guide:https://www.cnlinode.com/ban_wa_gong_qu_xiao_le_yi_jian_an_zhuang_shadowsocks_zui_xin_ban_wa_gong_ss_jiao_cheng/

#### Firfox switchy omega

https://diveng.io/firefox-and-chrome-browser-extensions-proxy-switchyomega-instructions-for-use.html

There is a switchy omega bak file here, download that file and load:
https://freessr.win/use.html

#### Privoxy

Use privoxy for 'global proxy'
http://www.renhl.com/linux/2017/02/03/use-shadowsocks-and-privoxy

at the last step, put these into your bashrc:

```
export http_proxy=http://localhost:8118
export https_proxy=http://localhost:8118
```

then reload your bashrc, or restart:

`source ~/.bashrc`

other guides:
https://docs.lvrui.io/2016/12/12/Linux%E4%B8%AD%E4%BD%BF%E7%94%A8ShadowSocks-Privoxy%E4%BB%A3%E7%90%86/

to test your privoxy:

`curl ip.gs` or `curl ip.sb`
the ip should be the same as your bandwagon ip
