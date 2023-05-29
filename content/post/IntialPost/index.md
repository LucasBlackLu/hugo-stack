---
title: "第一篇文章亦或不是"
date: 2023-03-18T22:07:31+08:00
draft: false
tags: [Blog,Hugo,隨筆]
image: Hello-World.jpg
categories:
    - Daily

---
## 前言
早在去年初旬，我就創建了一個Github Pag，打開就一個空白頁面，留下一行字“Lucasblacklu.github.io”，那時候並不知曉什麼主題也不懂什麼Hexo,Hugo。後來，去年剛開學不久看到班上的同學在show他的Blog，於是便粗略的看了一下，自己並沒有什麼想法去搭建；直到後來，在班上的老師展示他的Blog，用hexo和js搭建的，後來便開始了，我自己摸索搭建Blog。剛開始慢慢看教程，然後不斷碰壁，一開始我看到的優質教程是[RemBlog的教程](https://huangno1.github.io/hugo_theme_change/)以及啓發RemBlog的[教程](https://medium.com/@chswei/%E5%9C%A8-github-%E9%83%A8%E7%BD%B2-hugo-%E9%9D%9C%E6%85%8B%E7%B6%B2%E7%AB%99-9c40682dfe40),也就是因爲這個教程，我懂得了如何搭建Hugo Blog，也就是從這裏開始我愛上Hugo的快速部署，而不是Hexo的豐富且美觀的主題。


## 一波多折
前面談到Hugo快速，但是缺乏優質主題，畢竟顏值是第一動力，後來我挑了很多個主題，一開始是這個主題stack，但是由於自己不會如何配置，遇上很多問題，例如部署出來的Blog沒有正確顯示主題，也就是CSS配置出錯，但我當時並不知道什麼是CSS，後來又試了好幾個，最後折騰到凌晨，無奈只好選擇一個簡單的主題。之後，我在一個telegram看到一個[教程](https://wol.moe/%E5%9F%BA%E4%BA%8Ehugo-github-actions-cloudflare-pages%E7%9A%84%E8%87%AA%E6%9E%84%E5%BB%BA%E5%8D%9A%E5%AE%A2%E7%B3%BB%E7%BB%9F%E7%9A%84%E9%83%A8%E7%BD%B2/)教人使用三個倉庫，自動化部署Blog僅需上傳markdown文件即可，這對於當時並不瞭解Github Action和Workflow的我，無疑是巨大的誘惑，然後我按照他的教程試了好久還是不行，我甚至都不知道設定Token,後來也就不了了之，之前問過他裏面的bash腳本怎麼使用（還包括sed命令），可是我現在只看懂一些。也是因爲此，於是我便下定決定要搭建個Hugo+~~Github Action~~(Github Action暫時出問題，暫時用回兩個倉庫的方式) 的自動化部署Blog,後來在Workflow的多次踩坑當中學會了如何使用Token,加上那段時間在折騰Rom 編譯學會了不少Git和一些Linux 命令。

## 最後
我爲什麼又選擇這個主題，是因爲之前在Hugo Shoka碰壁發現，很多是自己的問題，加上我有認識不同國家的人，而Stack支持多語言輸出，只需要寫出一篇中文文章，把他發給chatgpt可以幫忙去潤色，再創建其他語言的markdown文件，例如我原始文件是index.md，英文的則是index.en.md。人的慾望是難以滿足的，最後我是再三抉擇才決定使用Stack主題，未來有更好的，可能是我會選擇遷移到新的主題或新的驅動。再者是爲什麼我選擇繁體中文，一是現在簡中環境真的爛，二是如何是繁中則看到我的Blog大多數繁中用戶，加上不想被受到簡中的推薦和審查，三則是對比兩者，繁中字體更加美觀。

