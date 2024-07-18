# Hi there 👋 I'm Simonzha_ng (Simonzhang8 张先淼) !   
<img src="https://raw.githubusercontent.com/Simonzhang8/Simonzhang8/main/image/avatar.jpg" width="150" height="150"  alt="Simonzha_ng" /> <img src="https://github-readme-stats.vercel.app/api?username=Simonzhang8&count_private=true&show_icons=true" /> <img src="https://raw.githubusercontent.com/Simonzhang8/Simonzhang8/main/image/reward.jpg" width="180" height="180" alt="赞赏码" />
## 初来乍到，请多指教
- 🤔 一名理工科在读学渣大学生
- 🌱 目前买了个云服务器瞎玩玩
- 🔭 以下是我在服务器上部署的网站：

| 网站链接 | 相应项目 |
| ------- | ------- |
| <a href="https://www.zxm86.cn/">个人网站（博客）</a> | <a href="https://github.com/WordPress/WordPress">WordPress</a> |
| <a href="https://portal.zxm86.cn/">网址导航</a> | <a href="https://github.com/hslr-s/sun-panel">Sun-Panel</a> |
| <a href="https://al.zxm86.cn/">Alist存储</a> | <a href="https://github.com/alist-org/alist">Alist</a>（我的最爱❤） |
| <a href="https://sso.zxm86.cn/">全局登录</a> | <a href="https://github.com/casdoor/casdoor">Casdoor</a> |
| <a href="https://waline.zxm86.cn/">评论系统（暂时 for Alist）</a> | <a href="https://github.com/walinejs/waline">Waline</a> |

*其他也有些别的项目，但是不方便公开链接使用，就不放出来了~*

*由于云服务器性能问题，不能访问可能是出现了宕机，需要等待手动重启，请谅解*
- ⚡ 下面做几个小小的优惠推广：
  - <a href="https://www.alipan.com/cpx/member?userCode=MTA0Mjgx/">阿里云盘会员特惠</a>
  - <a href="https://bonus.vip35.cn/">视听会员话费电影充值特惠</a>
- 📫 contact@zxm86.cn（网站相关） zhangxianmiao86@163.com（个人相关）
- 目前正在初步学习（但其实只会一点点）：

<img src="https://skillicons.dev/icons?perline=10&i=windows,cpp,c,python,html,js,php,wordpress,mysql,sqlite,nginx,workers,cloudflare,docker,github,matlab,npm," />

- 目前正在“研究”的事：
  - 为alist部署评论系统（Waline）
    - 当前进展：成功
    - 操作方法：将Waline所需css添加在alist自定义头部中，将Waline主代码放在Markdown中，将相应Markdown通过元信息或README.md添加到Alist相应文件夹
    - 目前困难：Waline和Alist账号不互通（和Casdoor账号也无法互通）、Waline主代码必须依赖Markdown文件，不能独立部署（会被部分外部资源Alist V3/V2的README.md覆盖）
  - alist前后端分离，前端运行在Cloudflare Pages和Vercel上（参考项目：<a href="https://github.com/Simonzhang8/alist-web-zxm/">alist-web-zxm</a>）
    - 当前进展：成功在Cloudflare Pages和Vercel上部署前端
    - 操作方法：将前端alist-web fork到自己的github上，然后在cloudflare pages和vercel上使用这个仓库，并使用npm run build编译命令即可（Vercel还需要加一条环境安装命令pnpm install）<a href="https://github.com/alist-org/alist/discussions/6680#discussioncomment-9942683">（参考讨论）</a>
    - 目前困难：语言包不知道怎么在线部署编译（因为只能填写一条命令）【考虑弃了】、alist后台设置的自定义头部和内容在前端不生效（需要编辑index.html）
  - alist前后端分离，前端运行在Github Pages上（参考项目：<a href="https://github.com/Simonzhang8/alist-web-zxm/">alist-web-zxm</a>）
    - 目前困难：Github编译各种报错【考虑弃了】<a href="https://github.com/alist-org/alist/issues/6730">（参考Issue）</a>
  - alist-proxy部署到其他边缘函数平台
    - 当前进展：尝试部署到腾讯EdgeOne上
    - 操作方法：将源代码ts形式（export）修改为js形式（addEventListener）后部署【因为EO不支持ts module形式代码】
    - 目前困难：使用几次后再也无法正常使用，提示403或sign mismatch或文件不存在等
  - Casdoor单点登录到Cloudflare Zerotrust实现身份验证
    - 目前困难：POST信息识别报错
  - 边缘函数劫持head实现为不支持html编辑的网站添加Chatra聊天窗口
    - 当前进展：部署到腾讯EdgeOne和Cloudflare Workers上
    - 操作方法：部署相应js代码
    - 目前困难：部署后nginx上配置的301/302跳转失效，和其他边缘函数产生冲突
  - 待补充……

*如果有大佬感兴趣且有解决思路的，欢迎加我微信：Simonzha_ng交流，鄙人感激不尽！（加微信请备注来意）*
<!--
Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
