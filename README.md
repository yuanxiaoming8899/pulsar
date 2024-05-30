<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text">
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/b940de6b743938a99d5a4c8f557f7ca27390c4aebcef4749e1f26d3b13857bb8/68747470733a2f2f70756c7361722e6170616368652e6f72672f696d672f70756c7361722e737667"><img src="https://camo.githubusercontent.com/b940de6b743938a99d5a4c8f557f7ca27390c4aebcef4749e1f26d3b13857bb8/68747470733a2f2f70756c7361722e6170616368652e6f72672f696d672f70756c7361722e737667" alt="标识" data-canonical-src="https://pulsar.apache.org/img/pulsar.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://hub.docker.com/r/apachepulsar/pulsar" rel="nofollow"><img src="https://camo.githubusercontent.com/3a782d853d5667b43e802adaff9dc0de94dadb8f184dd5a30e28772bde61620b/68747470733a2f2f696d672e736869656c64732e696f2f646f636b65722f70756c6c732f61706163686570756c7361722f70756c7361722d616c6c2e737667" alt="docker pull" data-canonical-src="https://img.shields.io/docker/pulls/apachepulsar/pulsar-all.svg" style="max-width: 100%;"></a>
<a href="https://github.com/apache/pulsar/graphs/contributors"><img src="https://camo.githubusercontent.com/c80937511a25f54a4fe1cc23c91bace410a8e7745ed476beff0373d0cf0b0a2e/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f636f6e7472696275746f72732d616e6f6e2f6170616368652f70756c736172" alt="贡献者" data-canonical-src="https://img.shields.io/github/contributors-anon/apache/pulsar" style="max-width: 100%;"></a>
<a href="https://github.com/apache/pulsar/commits/master"><img src="https://camo.githubusercontent.com/914a07ecb59397c46346c4686edba2954af4567e733e32ce4d407fc18f5e15af/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6173742d636f6d6d69742f6170616368652f70756c736172" alt="最后提交" data-canonical-src="https://img.shields.io/github/last-commit/apache/pulsar" style="max-width: 100%;"></a>
<a href="https://pulsar.apache.org/download/" rel="nofollow"><img src="https://camo.githubusercontent.com/29ed7ac9e80609136e0a957c59cd72208caf81519e7c042c5fff7f3ea2631b9b/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f762f72656c656173652f6170616368652f70756c7361723f736f72743d73656d766572" alt="发布" data-canonical-src="https://img.shields.io/github/v/release/apache/pulsar?sort=semver" style="max-width: 100%;"></a>
<a href="https://pulsar.apache.org/download/" rel="nofollow"><img src="https://camo.githubusercontent.com/77169424a11f94052886244e4ef101044c7d65cf9a66a7b8232cd32e85057bea/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f646f776e6c6f6164732f6170616368652f70756c7361722f746f74616c" alt="下载" data-canonical-src="https://img.shields.io/github/downloads/apache/pulsar/total" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pulsar 是一个分布式发布-订阅消息平台，具有非常灵活的消息模型和直观的客户端 API。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解有关 Pulsar 的更多信息，请访问</font></font><a href="https://pulsar.apache.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://pulsar.apache.org</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主要特点</font></font></h2><a id="user-content-main-features" class="anchor" aria-label="永久链接：主要特点" href="#main-features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">水平可扩展（每秒发布数百万个独立主题和数百万条消息）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">强排序和一致性保证</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">低延迟持久存储</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主题和队列语义</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">负载均衡器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设计用于部署为托管服务：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多租户</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">验证</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">授权</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配额</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持混合不同的工作负载</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可选硬件隔离</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">跟踪消费者光标位置</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于配置、管理和统计的 REST API</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地理复制</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分区主题的透明处理</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">透明的消息批处理</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">存储库</font></font></h2><a id="user-content-repositories" class="anchor" aria-label="永久链接：存储库" href="#repositories"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此存储库是 Apache Pulsar 的主存储库。Pulsar PMC 还维护 Pulsar 生态系统中组件的其他存储库，包括连接器、适配器和其他语言客户端。</font></font></p>
<ul dir="auto">
<li><a href="https://github.com/apache/pulsar"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">脉冲星核心</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Helm Chart</font></font></h3><a id="user-content-helm-chart" class="anchor" aria-label="永久链接：Helm Chart" href="#helm-chart"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://github.com/apache/pulsar-helm-chart"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pulsar 头盔图</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生态系统</font></font></h3><a id="user-content-ecosystem" class="anchor" aria-label="永久链接：生态系统" href="#ecosystem"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://github.com/apache/pulsar-adapters"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pulsar 适配器</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户</font></font></h3><a id="user-content-clients" class="anchor" aria-label="永久链接：客户" href="#clients"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://github.com/apache/pulsar-dotpulsar"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.NET/C# 客户端</font></font></a></li>
<li><a href="https://github.com/apache/pulsar-client-cpp"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C++ 客户端</font></font></a></li>
<li><a href="https://github.com/apache/pulsar-client-go"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">前往客户端</font></font></a></li>
<li><a href="https://github.com/apache/pulsar-client-node"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NodeJS 客户端</font></font></a></li>
<li><a href="https://github.com/apache/pulsar-client-python"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python 客户端</font></font></a></li>
<li><a href="https://github.com/apache/pulsar-client-reactive"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">反应式 Java 客户端</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仪表板和管理工具</font></font></h3><a id="user-content-dashboard--management-tools" class="anchor" aria-label="永久链接：仪表板和管理工具" href="#dashboard--management-tools"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://github.com/apache/pulsar-manager"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pulsar 管理器</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网站</font></font></h3><a id="user-content-website" class="anchor" aria-label="永久链接：网站" href="#website"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://github.com/apache/pulsar-site"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">脉冲星站点</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">持续集成/持续交付</font></font></h3><a id="user-content-cicd" class="anchor" aria-label="固定链接: CI/CD" href="#cicd"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://github.com/apache/pulsar-test-infra"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">脉冲星CI</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">已归档/已停止</font></font></h3><a id="user-content-archivedhalted" class="anchor" aria-label="永久链接：已存档/已停止" href="#archivedhalted"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://github.com/apache/pulsar-connectors"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pulsar 连接器</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(捆绑为</font></font><a href="/apache/pulsar/blob/master/pulsar-io"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pulsar-io</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> )</font></font></li>
<li><a href="https://github.com/apache/pulsar-translation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">脉冲星翻译</font></font></a></li>
<li><a href="https://github.com/apache/pulsar-presto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pulsar SQL（Pulsar Presto 连接器）</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（捆绑为</font></font><a href="/apache/pulsar/blob/master/pulsar-sql"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pulsar-sql</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
<li><a href="https://github.com/apache/pulsar-client-ruby"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ruby 客户端</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pulsar Runtime Java 版本推荐</font></font></h2><a id="user-content-pulsar-runtime-java-version-recommendation" class="anchor" aria-label="永久链接：Pulsar Runtime Java 版本推荐" href="#pulsar-runtime-java-version-recommendation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pulsar ver &gt; 2.10 和 master 分支</font></font></li>
</ul>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成分</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java 版本</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">经纪人</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">17</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数/IO</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">17</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令行界面</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">17</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java 客户端</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8、11 或 17</font></font></td>
</tr>
</tbody>
</table>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.8 &lt;= pulsar 版本 &lt;= 2.10</font></font></li>
</ul>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成分</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java 版本</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">经纪人</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">11</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数/IO</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">11</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令行界面</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8 或 11</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java 客户端</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8 或 11</font></font></td>
</tr>
</tbody>
</table>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pulsar 版本 &lt; 2.8</font></font></li>
</ul>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成分</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java 版本</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全部</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8 或 11</font></font></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建 Pulsar</font></font></h2><a id="user-content-build-pulsar" class="anchor" aria-label="永久链接：构建 Pulsar" href="#build-pulsar"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要求</font></font></h3><a id="user-content-requirements" class="anchor" aria-label="固定链接：要求" href="#requirements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JDK</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pulsar 版本</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JDK 版本</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">master 和 2.11 +</font></font></td>
<td align="center"><a href="https://adoptium.net/?variant=openjdk17" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JDK 17</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.8 / 2.9 / 2.10</font></font></td>
<td align="center"><a href="https://adoptium.net/?variant=openjdk11" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JDK 11</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.7 -</font></font></td>
<td align="center"><a href="https://adoptium.net/?variant=openjdk8" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JDK 8</font></font></a></td>
</tr>
</tbody>
</table>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Maven 3.6.1+</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">压缩</font></font></p>
</li>
</ul>
<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目包含一个</font></font><a href="https://maven.apache.org/wrapper/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Maven Wrapper</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，可用于替代系统安装的 Maven。</font><font style="vertical-align: inherit;">在以下命令中，</font></font><code>mvn</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font><code>./mvnw</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux 上替换 ，在 Windows 上替换 即可使用它。</font></font><code>mvnw.cmd</code><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Windows 上最好使用 CMD 而不是 Powershell。因为 maven 将激活</font></font><code>windows</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行的配置文件</font></font><code>rename-netty-native-libs.cmd</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</blockquote>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建造</font></font></h3><a id="user-content-build" class="anchor" aria-label="永久链接：构建" href="#build"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编译并安装：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ mvn install -DskipTests</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ mvn install -DskipTests" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编译并安装单个模块</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ mvn -pl module-name (e.g: pulsar-broker) install -DskipTests</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ mvn -pl module-name (e.g: pulsar-broker) install -DskipTests" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最小构建（跳过大多数外部连接器和分层存储处理器）</font></font></h3><a id="user-content-minimal-build-this-skips-most-of-external-connectors-and-tiered-storage-handlers" class="anchor" aria-label="永久链接：最小构建（这将跳过大多数外部连接器和分层存储处理程序）" href="#minimal-build-this-skips-most-of-external-connectors-and-tiered-storage-handlers"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>mvn install -Pcore-modules,-main -DskipTests</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="mvn install -Pcore-modules,-main -DskipTests" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行单元测试：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ mvn <span class="pl-c1">test</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ mvn test" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行单个单元测试：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ mvn -pl module-name (e.g: pulsar-client) <span class="pl-c1">test</span> -Dtest=unit-test-name (e.g: ConsumerBuilderImplTest)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ mvn -pl module-name (e.g: pulsar-client) test -Dtest=unit-test-name (e.g: ConsumerBuilderImplTest)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行选定的测试包：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ mvn <span class="pl-c1">test</span> -pl module-name (for example, pulsar-broker) -Dinclude=org/apache/pulsar/<span class="pl-k">**</span>/<span class="pl-k">*</span>.java</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ mvn test -pl module-name (for example, pulsar-broker) -Dinclude=org/apache/pulsar/**/*.java" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启动独立的 Pulsar 服务：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ bin/pulsar standalone</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ bin/pulsar standalone" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看</font></font><a href="https://pulsar.apache.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://pulsar.apache.org</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解文档和示例。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建自定义 docker 镜像</font></font></h2><a id="user-content-build-custom-docker-images" class="anchor" aria-label="永久链接：构建自定义 docker 镜像" href="#build-custom-docker-images"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apache Pulsar 发布过程中使用的命令可以在</font></font><a href="https://pulsar.apache.org/contribute/release-process/#stage-docker-images" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发布过程文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中找到。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是构建自定义docker镜像的一些一般说明：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"></font><code>branch-2.7</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由于</font></font><a href="https://github.com/apache/pulsar/issues/8445" data-hovercard-type="issue" data-hovercard-url="/apache/pulsar/issues/8445/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ISSUE-8445</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，Docker 镜像必须使用 Java 8 或之前的分支来构建</font><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"></font><code>branch-2.8</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java 11 是、</font></font><code>branch-2.9</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font><font style="vertical-align: inherit;">中推荐的 JDK 版本</font></font><code>branch-2.10</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java 17 是推荐的 JDK 版本</font></font><code>master</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下命令构建docker镜像</font></font><code>apachepulsar/pulsar-all:latest</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>apachepulsar/pulsar:latest</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>mvn clean install -DskipTests
<span class="pl-c"><span class="pl-c">#</span> setting DOCKER_CLI_EXPERIMENTAL=enabled is required in some environments with older docker versions</span>
<span class="pl-k">export</span> DOCKER_CLI_EXPERIMENTAL=enabled
mvn package -Pdocker,-main -am -pl docker/pulsar-all -DskipTests</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="mvn clean install -DskipTests
# setting DOCKER_CLI_EXPERIMENTAL=enabled is required in some environments with older docker versions
export DOCKER_CLI_EXPERIMENTAL=enabled
mvn package -Pdocker,-main -am -pl docker/pulsar-all -DskipTests" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建镜像后，可以标记它们并将其推送到您的自定义存储库。以下是使用当前版本和 git 修订标记 docker 镜像并将其推送到 的 bash 脚本示例</font></font><code>localhost:32000/apachepulsar</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>image_repo_and_project=localhost:32000/apachepulsar
pulsar_version=<span class="pl-s"><span class="pl-pds">$(</span>mvn initialize help:evaluate -Dexpression=project.version -pl <span class="pl-c1">.</span> -q -DforceStdout<span class="pl-pds">)</span></span>
gitrev=<span class="pl-s"><span class="pl-pds">$(</span>git rev-parse HEAD <span class="pl-k">|</span> colrm 10<span class="pl-pds">)</span></span>
tag=<span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">${pulsar_version}</span>-<span class="pl-smi">${gitrev}</span><span class="pl-pds">"</span></span>
<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Using tag <span class="pl-smi">$tag</span><span class="pl-pds">"</span></span>
docker tag apachepulsar/pulsar-all:latest <span class="pl-smi">${image_repo_and_project}</span>/pulsar-all:<span class="pl-smi">$tag</span>
docker push <span class="pl-smi">${image_repo_and_project}</span>/pulsar-all:<span class="pl-smi">$tag</span>
docker tag apachepulsar/pulsar:latest <span class="pl-smi">${image_repo_and_project}</span>/pulsar:<span class="pl-smi">$tag</span>
docker push <span class="pl-smi">${image_repo_and_project}</span>/pulsar:<span class="pl-smi">$tag</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="image_repo_and_project=localhost:32000/apachepulsar
pulsar_version=$(mvn initialize help:evaluate -Dexpression=project.version -pl . -q -DforceStdout)
gitrev=$(git rev-parse HEAD | colrm 10)
tag=&quot;${pulsar_version}-${gitrev}&quot;
echo &quot;Using tag $tag&quot;
docker tag apachepulsar/pulsar-all:latest ${image_repo_and_project}/pulsar-all:$tag
docker push ${image_repo_and_project}/pulsar-all:$tag
docker tag apachepulsar/pulsar:latest ${image_repo_and_project}/pulsar:$tag
docker push ${image_repo_and_project}/pulsar:$tag" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置你的 IDE</font></font></h2><a id="user-content-setting-up-your-ide" class="anchor" aria-label="永久链接：设置你的 IDE" href="#setting-up-your-ide"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阅读</font></font><a href="https://pulsar.apache.org/contribute/setup-ide" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://pulsar.apache.org/contribute/setup-ide</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以设置 IntelliJ IDEA 或 Eclipse 来开发 Pulsar。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></h2><a id="user-content-documentation" class="anchor" aria-label="永久链接：文档" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关如何为 Pulsar 文档做出贡献，请参阅</font></font><a href="https://pulsar.apache.org/contribute/document-intro/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pulsar 文档贡献指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</blockquote>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接触</font></font></h2><a id="user-content-contact" class="anchor" aria-label="永久链接：联系方式" href="#contact"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h5 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">邮件列表</font></font></h5><a id="user-content-mailing-lists" class="anchor" aria-label="永久链接：邮件列表" href="#mailing-lists"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">姓名</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">订阅</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">取消订阅</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">档案</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><a href="mailto:users@pulsar.apache.org"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">users@pulsar.apache.org</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户相关讨论</font></font></td>
<td align="left"><a href="mailto:users-subscribe@pulsar.apache.org"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">订阅</font></font></a></td>
<td align="left"><a href="mailto:users-unsubscribe@pulsar.apache.org"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">取消订阅</font></font></a></td>
<td align="left"><a href="http://mail-archives.apache.org/mod_mbox/pulsar-users/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">档案</font></font></a></td>
</tr>
<tr>
<td align="left"><a href="mailto:dev@pulsar.apache.org"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">dev@pulsar.apache.org</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与发展相关的讨论</font></font></td>
<td align="left"><a href="mailto:dev-subscribe@pulsar.apache.org"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">订阅</font></font></a></td>
<td align="left"><a href="mailto:dev-unsubscribe@pulsar.apache.org"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">取消订阅</font></font></a></td>
<td align="left"><a href="http://mail-archives.apache.org/mod_mbox/pulsar-dev/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">档案</font></font></a></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h5 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">松弛</font></font></h5><a id="user-content-slack" class="anchor" aria-label="固定链接：Slack" href="#slack"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pulsar slack 频道：</font></font><a href="https://apache-pulsar.slack.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://apache-pulsar.slack.com/</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><a href="https://communityinviter.com/apps/apache-pulsar/apache-pulsar" rel="nofollow"><font style="vertical-align: inherit;">您可以在https://communityinviter.com/apps/apache-pulsar/apache-pulsar</font></a><font style="vertical-align: inherit;">进行自我注册</font></font><a href="https://communityinviter.com/apps/apache-pulsar/apache-pulsar" rel="nofollow"><font style="vertical-align: inherit;"></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安全策略</font></font></h2><a id="user-content-security-policy" class="anchor" aria-label="固定链接：安全政策" href="#security-policy"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您发现 Pulsar 存在安全问题，请</font></font><a href="https://pulsar.apache.org/security/#security-policy" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阅读安全政策</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。避免公开披露至关重要。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告安全漏洞</font></font></h3><a id="user-content-reporting-a-security-vulnerability" class="anchor" aria-label="永久链接：报告安全漏洞" href="#reporting-a-security-vulnerability"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要报告 Pulsar 的漏洞，请联系</font></font><a href="https://www.apache.org/security/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apache 安全团队。向</font></font></a><font style="vertical-align: inherit;"></font><a href="mailto:security@apache.org"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">security@apache.org</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告漏洞时</font><font style="vertical-align: inherit;">，您可以将电子邮件复制到</font></font><a href="mailto:private@pulsar.apache.org"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">private@pulsar.apache.org</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，以将报告发送给 Apache Pulsar 项目管理委员会。这是一个私人邮件列表。</font></font></p>
<p dir="auto"><a href="https://github.com/apache/pulsar/security/policy"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/apache/pulsar/security/policy</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包含更多详细信息。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h2><a id="user-content-license" class="anchor" aria-label="永久链接：许可证" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据 Apache 许可证 2.0 版授权：</font></font><a href="http://www.apache.org/licenses/LICENSE-2.0" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.apache.org/licenses/LICENSE-2.0</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">加密通知</font></font></h2><a id="user-content-crypto-notice" class="anchor" aria-label="永久链接：加密通知" href="#crypto-notice"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本发行版包含加密软件。您目前居住的国家/地区可能对加密软件的进口、拥有、使用和/或再出口到其他国家/地区有所限制。在使用任何加密软件之前，请检查您所在国家/地区有关进口、拥有、使用和再出口加密软件的法律、法规和政策，看看是否允许这样做。</font><font style="vertical-align: inherit;">有关更多信息，请参阅</font></font><a href="http://www.wassenaar.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">《瓦森纳协议》 。</font></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">美国政府商务部工业和安全局 (BIS) 已将此软件归类为出口商品控制编号 (ECCN) 5D002.C.1，其中包括使用或执行非对称算法加密功能的信息安全软件。此 Apache 软件基金会发行版的形式和方式使其符合许可例外 ENC 技术软件不受限制 (TSU) 例外（参见 BIS 出口管理条例第 740.13 节）的出口条件，适用于目标代码和源代码。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下面提供了有关所包含的加密软件的更多详细信息：Pulsar 使用由</font></font><a href="http://www.bouncycastle.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.bouncycastle.org</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编写的 Bouncy Castle 的 SSL 库。</font></font></p>
</article></div>
