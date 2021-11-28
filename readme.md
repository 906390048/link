# 自建短链接跳转
启动GitHub Pages，复制以下内容到\*\*\*.html
```html
<html>
<script>
window.onload=function(){window.location.replace("此处替换为要跳转的网址");}
</script>
</html>
```
访问仓库pages/\*\*\*就会跳转到设置好的网址。*例：git.html跳转到github.com https://用户名.github.io/仓库名/git -> https://github.com*

有条件可以给仓库的pages一个自己的域名，效果更好。*如：https://example.com/git -> https://github.com*

优点是免费，毕竟网上的短链接用的太多或设置有效期太长就会收费，主流的自建方案还要云主机，这个完全不花钱；另外你可以自己决定短链接的用的域名，更加自由。

缺点是设好的短链接和对应的网址都能被看到（但我相信public仓库里不会出现不该出现的东西）；而且有先加载js脚本再跳转的过程，会稍微慢一丁点。

也可以用国内Gitee的pages。

