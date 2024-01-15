# 免费的自托管 Zendesk 和 Help Scout 替代方案

<div align="center">

<img src="https://raw.githubusercontent.com/freescout-helpdesk/freescout/master/public/img/logo-300.png" width="180" height="180" />
<br/><br/>

[![PHP version](https://freescout-helpdesk.github.io/img/badges/PHP-7.1%2B-blue.svg)](https://github.com/freescout-helpdesk/freescout#requirements) [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Ffreescout-helpdesk%2Ffreescout&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

</div>

FreeScout是使用 PHP（Laravel 框架）构建的超轻量级且功能强大的免费开源帮助台和共享收件箱。现在，您可以享受免费的 Zendesk 和 Help Scout，而无需放弃隐私或将自己锁定在您无法控制的服务中。FreeScout 是从头开始开发的，不使用任何受版权保护的 Help Scout 或 Zendesk 材料。

如果您想支持该项目，请随时为该存储库加注星标。它有助于提高项目的知名度，让人们知道它是有价值的。感谢您的支持！

![FreeScout](https://freescout-helpdesk.github.io/img/screenshots/screenshot.png)

 
<h2 tabindex="-1" dir="auto"><a id="user-content-table-of-contents" class="anchor" aria-hidden="true" tabindex="-1" href="#table-of-contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录</font></font></h2>
<ul dir="auto">
<li><a href="#demo"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示</font></font></a></li>
<li><a href="#features"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特征</font></font></a></li>
<li><a href="#mobile-apps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">移动应用程序</font></font></a></li>
<li><a href="#requirements"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要求</font></font></a></li>
<li><a href="#installation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></a></li>
<li><a href="#cloud-hosted"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">云托管</font></font></a></li>
<li><a href="#modules"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模块</font></font></a></li>
<li><a href="#tools--integrations"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工具与集成</font></font></a></li>
<li><a href="#news--updates"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新闻与更新</font></font></a></li>
<li><a href="#contributing"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></a></li>
<li><a href="#screenshots"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">截图</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-demo" class="anchor" aria-hidden="true" tabindex="-1" href="#demo"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示</font></font></h2>
<p dir="auto"><strong><a href="https://demo.freescout.net" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现场演示</font></font></a></strong></p>
<h2 tabindex="-1" dir="auto" class=""><a id="user-content-features" class="anchor" aria-hidden="true" tabindex="-1" href="#features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特征</font></font></h2>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户数量、工单、邮箱等无限制。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">100% 适合移动设备。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多语言：英语、中文、克罗地亚语、捷克语、丹麦语、荷兰语、芬兰语、法语、德语、意大利语、日语、韩语、挪威语、波斯语、波兰语、葡萄牙语、俄语、西班牙语、斯洛伐克语、瑞典语。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无缝电子邮件集成。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持现代 Microsoft Exchange 身份验证。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网络安装程序和更新程序。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">已加星标的对话。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">转发对话。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">合并对话。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在邮箱之间移动对话。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">电话交谈。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一次向多个收件人发送新对话。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">冲突检测 – 当两个代理打开同一对话时会显示通知。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推送通知。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">经过一段对话。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动回复。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内部注释。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动刷新对话列表，无需重新加载页面。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将剪贴板中的屏幕截图粘贴到回复区域。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于每个用户配置通知。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开跟踪。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编辑线程。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">搜索。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和更多…</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">还需要什么吗？</font></font><a href="https://freescout.net/request-feature/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在这里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建议功能</font><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-mobile-apps" class="anchor" aria-hidden="true" tabindex="-1" href="#mobile-apps"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">移动应用程序</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">移动应用程序支持与 FreeScout 安装的 Web 版本相同的功能和模块。</font><font style="vertical-align: inherit;">支持代理和管理员都可以使用移动应用程序。</font></font></p>
<p dir="auto"><a href="https://freescout.net/android-app/" rel="nofollow"><img alt="安卓应用程序" src="https://camo.githubusercontent.com/81aeb5c763e859ccaafe1f9e03eb26cb2880d35174a1a7930b9a7b0b7ee6a474/68747470733a2f2f6672656573636f75742d68656c706465736b2e6769746875622e696f2f696d672f617070732f616e64726f69642e706e67" width="200px" data-canonical-src="https://freescout-helpdesk.github.io/img/apps/android.png" style="max-width: 100%;"></a> <a href="https://freescout.net/ios-app/" rel="nofollow"><img alt="iOS应用程序" src="https://camo.githubusercontent.com/847f71f2a69984a5dd036ccd58b90e3950782e71d915088339794a4442e5a0f9/68747470733a2f2f6672656573636f75742d68656c706465736b2e6769746875622e696f2f696d672f617070732f696f732e706e673f763d31" width="200px" data-canonical-src="https://freescout-helpdesk.github.io/img/apps/ios.png?v=1" style="max-width: 100%;"></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-requirements" class="anchor" aria-hidden="true" tabindex="-1" href="#requirements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要求</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FreeScout 是一个纯 PHP/MySQL 应用程序，因此即使在共享主机上也可以轻松部署。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nginx / 阿帕奇 / IIS</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PHP 7.1 - 8.2</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MySQL 5.0+ / MariaDB 5.0+ / PostgreSQL</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">没有最低系统要求（CPU / RAM） - FreeScout 可以在任何系统上运行。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-installation" class="anchor" aria-hidden="true" tabindex="-1" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2>
<p dir="auto"><a href="https://github.com/freescout-helpdesk/freescout/wiki/Installation-Guide"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装指南</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图像和一键安装：</font></font></p>
<ul dir="auto">
<li><a href="http://freescout.net/docker/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker 镜像</font></font></a></li>
<li><a href="http://www.softaculous.com/apps/customersupport/FreeScout" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Softaculous</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（cPanel、Plesk、ISPmanager、H-Sphere、DirectAdmin、InterWorx）</font></font></li>
<li><a href="http://ff3.netenberg.com/visitors/scripts/freescout/view" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fantastico</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（cPanel、DirectAdmin、ISP 管理器、ISP 配置）</font></font></li>
<li><a href="https://cloudron.io/store/net.freescout.cloudronapp.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">云龙</font></font></a></li>
<li><a href="https://github.com/freescout-helpdesk/freescout/wiki/Installation-Guide#interactive-installation-bash-script-ubuntu"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ubuntu</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（bash 脚本）</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-cloud-hosted" class="anchor" aria-hidden="true" tabindex="-1" href="#cloud-hosted"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">云托管</font></font></h2>
<p dir="auto"><a href="https://freescout.net/cloud-hosted/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">云托管 FreeScout</font></font></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-modules" class="anchor" aria-hidden="true" tabindex="-1" href="#modules"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模块</font></font></h2>
<ul dir="auto">
<li><a href="https://freescout.net/modules/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">官方模块</font></font></a></li>
<li><a href="https://freescout.net/community-modules/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区模块</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-tools--integrations" class="anchor" aria-hidden="true" tabindex="-1" href="#tools--integrations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工具与集成</font></font></h2>
<ul dir="auto">
<li><a href="https://api-docs.freescout.net/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序编程接口</font></font></a></li>
<li><a href="http://freescout.net/migrate/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">迁移到 FreeScout</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（从任何服务台）</font></font></li>
<li><a href="https://freescout.net/zapier/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扎皮尔</font></font></a></li>
<li><a href="https://freescout.net/make-integration/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">制造</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（集成）</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-news--updates" class="anchor" aria-hidden="true" tabindex="-1" href="#news--updates"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新闻与更新</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不要错过新闻、更新和新模块！</font></font></p>
<p dir="auto"><a href="https://freescout.net/subscribe/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">电子邮件通讯</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| </font></font><a href="https://freescout.net/facebook/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">脸书</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| </font></font><a href="https://freescout.net/twitter/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推特</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| </font></font><a href="https://freescout.net/youtube/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YouTube</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> | </font></font><a href="https://freescout.net/telegram/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">电报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| </font></font><a href="https://freescout.net/feed/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RSS</font></font></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-contributing" class="anchor" aria-hidden="true" tabindex="-1" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h2>
<ul dir="auto">
<li><a href="https://github.com/freescout-helpdesk/freescout/issues/288" data-hovercard-type="issue" data-hovercard-url="/freescout-helpdesk/freescout/issues/288/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过留下反馈来支持该项目</font></font></a></li>
<li><a href="https://github.com/freescout-helpdesk/freescout/wiki/Development-Guide"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发指南</font></font></a></li>
<li><a href="https://github.com/freescout-helpdesk/freescout/labels/help%20wanted"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">待办事项清单</font></font></a></li>
<li><a href="https://github.com/freescout-helpdesk/freescout/wiki/Translate"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">翻译</font></font></a></li>
</ul>
 


 
## Screenshots

Dashboard:

![Dashboard](https://freescout-helpdesk.github.io/img/screenshots/dashboard.png)

Conversation:

![Conversation](https://freescout-helpdesk.github.io/img/screenshots/conversation.png)


Mailbox connection settings page:

![Mailbox connection settings page](https://freescout-helpdesk.github.io/img/screenshots/mailbox-connection.png)

Notifications:

![Notifications](https://freescout-helpdesk.github.io/img/screenshots/notifications.png)

Push notification:

![Push notification](https://freescout-helpdesk.github.io/img/screenshots/push.png)

Web installer:

![Web installer](https://freescout-helpdesk.github.io/img/screenshots/installer.png)

Login page:

![Login page](https://freescout-helpdesk.github.io/img/screenshots/freescout-login.png)
