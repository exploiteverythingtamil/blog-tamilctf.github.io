# Chirpy

ð [English](../README.md) â¢ ç®ä½ä¸­æ

[![Build Status](https://github.com/cotes2020/jekyll-theme-chirpy/workflows/build/badge.svg?event=push)](https://github.com/cotes2020/jekyll-theme-chirpy/actions?query=event%3Apush)
[![GitHub license](https://img.shields.io/github/license/cotes2020/jekyll-theme-chirpy.svg)](https://github.com/cotes2020/jekyll-theme-chirpy/blob/master/LICENSE)
[![996.icu](https://img.shields.io/badge/link-996.icu-%23FF4D5B.svg)](https://996.icu)

ä¸ä¸ªä¸ä¸æ ·ç Jekyll ä¸»é¢ï¼éç¨ååºå¼è®¾è®¡ï¼æ¹ä¾¿è®°å½ãç®¡çãåäº«ä½ çç¥è¯åç»éªã[æçè¿ Â»](https://chirpy.cotes.info)

[![Devices Mockup](https://raw.githubusercontent.com/cotes2020/jekyll-theme-chirpy/master/assets/img/sample/devices-mockup.png)](https://chirpy.cotes.info)

> â ï¸ ä¸­æçææ¡£å­å¨æ´æ°ä¸åæ¶çé£é©ï¼å¼æºææ¡£ä»¥è±æä¸ºä¸»ï¼è¯·è§è°ï¼ãå¦æåç°ä¸­ãè±æåå®¹ä¸å¹éçæåµï¼ä¸åä»¥è±æçåå®¹ä¸ºåãå¦ææ¨æ¿æçè¯ï¼å¯æäº¤ issuse æéä½èæ´æ°ä¸­æç READMEï¼è°¢è°¢ã

## ç®å½

* [åè½é¢è§](#åè½é¢è§)
* [å®è£](#å®è£)
* [è¿è¡æå](#è¿è¡æå)
* [åä¸è´¡ç®](#åä¸è´¡ç®)
* [æè°¢](#æè°¢)
* [èµå©](#èµå©)
* [è®¸å¯è¯ä¹¦](#è®¸å¯è¯ä¹¦)

## åè½é¢è§

* æç« ç½®é¡¶
* å¯éç½®çå¨å±ä¸»é¢é¢è²
* æç« æåä¿®æ¹æ¥æ
* æç« ç®å½
* èªå¨æ¨èç¸å³æç« 
* è¯­æ³é«äº®
* äºçº§ç®å½
* æ°å­¦è¡¨è¾¾å¼
* æç´¢
* Atom è®¢é
* Disqus è¯è®º
* Google åæ
* GA æµè§æ¥åï¼é«çº§åè½ï¼
* SEO ä¼å
* ç½ç«æ§è½ä¼å


## å®è£

### åå¤å·¥ä½

æç§ [Jekyll å®æ¹ææ¡£](https://jekyllrb.com/docs/installation/) å®æåºç¡ç¯å¢çå®è£ (`Ruby`ï¼`RubyGem`ï¼`Bundler`)ã

ä¸ºäºä½¿ç¨é¡¹ç®ååè´¹æä¾çèæ¬å·¥å·å¢è¿åä½ä½éªï¼å¦æä½ çæºå¨ç³»ç»æ¯ Debian æè macOSï¼åéè¦ç¡®ä¿å®è£äº [GNU coreutils](https://www.gnu.org/software/coreutils/)ãå¦åï¼éè¿ä»¥ä¸æ¹å¼è·å¾ï¼

* Debian

 ```console
 $ sudo apt-get install coreutils
 ```

* macOS

 ```console
 $ brew install coreutils
 ```

æ¥çï¼[fork](https://github.com/cotes2020/jekyll-theme-chirpy/fork) ä¸ä»½ä»£ç ï¼ç¶ååéä½  Fork çä»åºå°æ¬å°æºå¨ä¸ã

```console
$ git clone git@github.com:USER/jekyll-theme-chirpy.git -b master
```

æä¸è¿°ç`USER` æ¿æ¢ä¸ºä½ ç GitHub usernameã


### å®è£ Jekyll æä»¶

æ¬å°é¦æ¬¡è¿è¡æç¼è¯ï¼è¯·å¨é¡¹ç®æ ¹ç®å½ä¸è¿è¡:

```terminal
$ bundle install
```
`bundle` å½ä»¤ä¼èªå¨å®è£ `Gemfile` åå£°æçä¾èµæä»¶.



## è¿è¡æå

### æä»¶ç®å½

ä¸é¢æ¯ä¸»è¦çæä»¶ç®å½ï¼

```sh
jekyll-theme-chirpy/
âââ _data
âââ _includes      
âââ _layouts
âââ _posts          # posts stay here
âââ _scripts
âââ .travis.yml     # remove it
âââ .github         # remove this, too
âââ assets      
âââ tabs
âÂ Â  âââ about.md    # the ABOUT page
âââ .gitignore
âââ 404.html
âââ Gemfile
âââ LICENSE
âââ README.md
âââ _config.yml     # configuration file
âââ tools           # script tools
âââ docs
âââ feed.xml
âââ index.html
âââ robots.txt
âââ sitemap.xml
```


ä½ éè¦å°ä»¥ä¸æä»¶æç®å½å é¤:

- .travis.yml
- .github


### éç½®æä»¶

æ ¹æ®ä¸ªäººéè¦å»ä¿®æ¹ `_config.yml` çåéï¼å¤§é¨åé½ææ³¨éä»ç»ç¨æ³ã

* `url`
    
    å®ä¹ç½ç« URLï¼æ³¨æç»å°¾ä¸å¸¦ `/`ãæ ¼å¼ï¼ `<protocol>://<domain>`.

* `avatar`
    
    å®ä¹å¤´åï¼ç¤ºä¾çæä»¶æ¾ç½®å¨ï¼`/assets/img/sample/avatar.jpg`. æå®æ¢æä½ èªå·±çå¤´åï¼è·¯å¾ä¸éå®ï¼è¶å°è¶å¥½ã(åç¼©å¾åä½ç§¯å¯ä¸è¿ä¸ªç½ç«ï¼*<https://tinypng.com/>* ).

* `timezone`

    å®ä¹æ¶åº ï¼é»è®¤ä¸º `äºæ´²/ä¸æµ·`ï¼å¦æèèº«ç¿»å¢è¦æ¢åå¸å¯å¨æ­¤åè¡¨æ¾å°ï¼ [TimezoneConverter](http://www.timezoneconverter.com/cgi-bin/findzone/findzone) æè [Wikipedia](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones).

* `theme_mode`
  
    å®ä¹é¢è²æ¹æ¡ï¼æä¸ç§å¯éï¼:
    
    - **dual**  - èªå¨è·éç³»ç»ç `æ·±è²`/`æµè²` è®¾ç½®ï¼å½ç³»ç»æèæµè§å¨ä¸æ¯ææ·±è²æ¨¡å¼ï¼åé»è®¤æ¾ç¤ºä¸ºæµè²æ¨¡å¼ãæ è®ºå¦ä½ï¼ä¾§è¾¹æ å·¦ä¸è§é½ä¼æ¾ç¤ºä¸ä¸ªé¢è²åæ¢æé®ã
    - **dark**  - å¨ç¨æ·±è²æ¨¡å¼ã
    - **light** - å¨ç¨æµè²æ¨¡å¼ã


###  æ¬å°è¿è¡

ä½¿ç¨ä»¥ä¸å·¥å·å¯è½»æ¾è¿è¡:

```terminal
$ bash tools/run.sh
```

è®¿é®æ¬å°æå¡ï¼ <http://localhost:4000>

å¦æä½ æ³å¨æ¬å°æå¡è¿è¡åï¼æä¿®æ¹æºæä»¶çæ´æ¹å®æ¶å·æ°ï¼å¯ä½¿ç¨éé¡¹ `-r` (æ `--realtime`)ï¼ä¸è¿è¦åå®è£ä¾èµ [**fswatch**](http://emcrisostomo.github.io/fswatch/) ã

###  é¨ç½²å° GitHub Pages

é¨ç½²å¼å§åï¼æ  `_config.yml` ç `url` æ¹ä¸º `https://<username>.github.io`(æèä½ çç§æååï¼å¦ï¼`https://yourdomain.com`)ãå¦å¤ï¼å¦æä½ æ³ä½¿ç¨ [Project ç±»åç½ç«](https://help.github.com/en/github/working-with-github-pages/about-github-pages#types-of-github-pages-sites)ï¼ä¿®æ¹éç½®æä»¶ç `baseurl` ä¸ºé¡¹ç®åç§°ï¼ä»¥ææ å¼å¤´ï¼å¦ï¼`/project`ã

#### æ¹æ³ 1: ç± GitHub Pages çæç«ç¹

ä¾ç§æ¬æ¹æ³ï¼ä½ å¯ä»¥ç´æ¥ææºç æ¨éå°è¿ç«¯ä»åºã

> **æ³¨**: å¦æä½ æ³ä½¿ç¨ä»»ä½ä¸å¨è¿ä¸ª[åè¡¨](https://pages.github.com/versions/)ä¸çæä»¶ï¼è¶è¿æ­¤æ¹æ³ï¼ç´æ¥ç [*æ¹æ³ 2: æ¬å°æå»º*](#æ¹æ³-2-æ¬å°æå»º).

**1**. ä»åºæ¹åä¸º:

|ç«ç¹ç±»å | ä»åºåç§°|
|:---|:---|
|User or Organization | `<username>.github.io`|
|Project| `<username>.github.io` ä»¥å¤çåå­ï¼è­¬å¦ `project`|

**2**. æäº¤æ¬å°æ´æ¹ï¼ç¶åè¿è¡:

```console
$ bash tools/init.sh
```

>**æ³¨**: *æåæ´æ°* åè¡¨æ ¹æ®æç« ç git ä¿®æ¹è®°å½çæï¼æä»¥è¿è¡ååæ `_posts` ç®å½çä¿®æ¹æäº¤ã

å®ä¼èªå¨çææç« ç *æåä¿®æ¹æ¥æ* å *åç±» / æ ç­¾* é¡µé¢ï¼å¹¶èªå¨æäº¤ä¸ä¸ª commitãè¾åºæ¥å¿ç±»ä¼¼å¦ä¸ï¼

```terminal
[INFO] Success to update lastmod for 4 post(s).
[INFO] Succeed! 3 category-pages created.
[INFO] Succeed! 4 tag-pages created.
[Automation] Updated the Categories, Tags, Lastmod for post(s).
 11 files changed, 46 insertions(+), 3 deletions(-)
 ...
Updated the Categories, Tags, Lastmod for post(s).
```


**3**. æ¨éå° `origin/master` ç¶åå° GitHub ç½é¡µä¸ºè¯¥é¡¹ç®å¼å¯ Pages æå¡ã

**4**. ç½ç«å°è¿è¡å¨ï¼

|ç«ç¹ç±»å | ç½ç« URL |
|:---|:---|
|User or Organization | `https://<username>.github.io/`|
|Project| `https://<username>.github.io/project/`|


#### æ¹æ³ 2: æ¬å°æå»º

ç±äºå®å¨åå ï¼GitHub Pages ä¸åè®¸ç¬¬ä¸æ¹æä»¶è¿è¡ï¼å¦æä½ æ³çªç ´è§åï¼å°±è¦æ¬å°æå»ºç«ç¹åå®¹ã

**1**. å° GitHub ç½é¡µï¼åå»ºä¸ä¸ªæ°çä»åºï¼æ ¹æ®ä»¥ä¸è§åå½å: 

|ç«ç¹ç±»å | ä»åºåç§°|
|:---|:---|
|User or Organization | `<username>.github.io`|
|Project| `<username>.github.io` ä»¥å¤çåå­ï¼ ä¾å¦ `project`|

ç¶å Clone æ°ä»åºå°æ¬å°ã

**2**. æå»ºç«ç¹:

```console
$ bash tools/build.sh -d /path/to/local/project/
```
> `project` ä¸ºæ°ä»åºåç§°ã

çæçéææä»¶å°ä¼å¨ `/path/to/local/project`. ææ°ä»åºçä¿®æ¹æäº¤å¹¶æ¨éå°è¿ç«¯ `master` åæ¯.

**3**. åå° GithHub ç½é¡µï¼ä¸ºè¯¥ä»åºå¼å¯ Pages æå¡ã

**4**. ç½ç«å°è¿è¡å¨:

|ç«ç¹ç±»å | ç«ç¹ URL |
|:---|:---|
|User or Organization | `https://<username>.github.io/`|
|Project| `https://<username>.github.io/project/`|

#### ç»æå·¥ä½

æ è®ºä½ éæ©äºåªç§æ¹å¼é¨ç½²ç½ç«å° GitHub Pages, è¯·å¼å¯ `HTTPS` åè½ãå·ä½ç»èåèå®æ¹è¯´æï¼[Configuring a publishing source for your GitHub Pages site](https://help.github.com/en/github/working-with-github-pages/securing-your-github-pages-site-with-https)ã

### ææ¡£

è¥æ³è¦æ´å¤ç»èä»¥åæ´ä½³çéè¯»ä½éªï¼è¯·åé [çº¿ä¸æç¨](https://chirpy.cotes.info/categories/tutorial/)ã ä¸æ­¤åæ¶ï¼[Wiki](https://github.com/cotes2020/jekyll-theme-chirpy/wiki) ä¹æä¸ä»½æç¨çæ·è´ã


## åä¸è´¡ç®

ä¸äººè¡å¿ææå¸ï¼æ¬¢è¿ææ¥å bug, å¸®å©æ¹è¿ä»£ç è´¨éï¼æèæäº¤æ°åè½ãå·ä½æä½è§åè¯·åè [è´¡ç®æå](../.github/CONTRIBUTING.md)ï¼è°¢è°¢ ðã

## æè°¢

è¿ä¸ªä¸»é¢çå¼åä¸»è¦åºäº [Jekyll](https://jekyllrb.com/) çæã[Bootstrap](https://getbootstrap.com/)ã[Font Awesome](https://fontawesome.com/) åå¶ä»ä¸äºåºè²çå·¥å· (ç¸å³æä»¶ä¸­å¯ä»¥æ¾å°è¿äºå·¥å·ççæä¿¡æ¯).

:tada:æè°¢ææåä¸ä»£ç è´¡ç®çå°ä¼ä¼´, ä»ä»¬ç GayHub ID å¨è¿ä¸ª[åè¡¨](https://github.com/cotes2020/jekyll-theme-chirpy/graphs/contributors)ã å¦å¤, æäº¤è¿ issues(æèæªè¢«åå¹¶ PR) çé«å¯å¸åç½å¯ç¾ä¹ä¸ä¼è¢«éå¿,ä»/å¥¹ä»¬å¸®å©æ¥å bugãåäº«æ°ç¹å­æèå¯åäºæååºæ´éä¿ææçææ¡£ã


## èµå©

å¦ææ¨åæ¬¢è¿ä¸ªä¸»é¢æèå®å¯¹æ¨æå¸®å©ï¼è¯·èèæèµä½èï¼å¨ [é¡¹ç®ä¸»é¡µ](https://github.com/cotes2020/jekyll-theme-chirpy) ç¹å»æé® <kbd>:heart:Sponsor</kbd> éæ©éåçé¾æ¥å³å¯å®æï¼å½åä¸è¬éç¬¬äºä¸ªé¾æ¥ï¼æ¯ä»å®/å¾®ä¿¡èµå©ï¼ï¼æ¨çæèµå°ä¼æå¤§å°é¼å±ä½èï¼å¹¶å¸®å©ä½èæ´å¥½å°ç»´æ¤é¡¹ç®ï¼


## è®¸å¯è¯ä¹¦

æ¬é¡¹ç®å¼æºï¼åºäº [MIT](https://github.com/cotes2020/jekyll-theme-chirpy/blob/master/LICENSE) è®¸å¯ã
