---
title: About me
layout: page
comments: true
---

<script>
$(function(){
$('nav a').eq(1).addClass("activepage");
})
</script>

<div class="desc">
<img class="profileimg" src="/assets/template/mouse-90.gif" alt="Forever" />
</div>

<div class="links">

<a class="button" href="https://x.com/zhaohao" target="\_blank"> <i class="fa fa-twitter-square fa-fw" aria-hidden="true"></i></a>

<a class="button" href="https://t.me/zhaohao" target="\_blank"> <i class="fa fa-telegram fa-fw" aria-hidden="true"></i></a>

<a class="button" href="https://github.com/zhaohao" target="\_blank"> <i class="fa fa-github-alt fa-fw" aria-hidden="true"></i></a>

<a class="button" href=" javascript:location.href ='mailto:'+['zhaohao','outlook.com'].join('@')"> <i class="fa fa-envelope fa-fw"></i> </a>

</div>

<p>仅仅为了记录，记录下消逝了的和即将消逝的点点滴滴，在回首的时候，能够知道，我曾经来过……</p>
<p>你嘴角微翘，我看见阳光满地……</p>
<p>你回眸一望，我看见晴空万里……</p>

<p>Email:hao(at)zhao.im | Diary(at)live.com | Notebook(at)live.com</p>

<table border="0">
<tr>
  <td>
  <div id="qrcode" style="box-shadow: inset #287a7b 0px 0px 6px 6px; float: left; padding: 10px; margin:.5em 1em .5em 0;" ></div>
  </td>

<td>
    <span class="">页面编译时间: {{site.time | date:"%Y-%m-%d %H:%M:%S %Z"}}</span>
    <br>
    <span class="">页面固定链接: <a href="{{ site.url }}{{ page.url }}">{{ site.url }}{{ page.url }}</a></span>
  </td>
</tr>
</table>