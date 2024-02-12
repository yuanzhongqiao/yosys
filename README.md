<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>yosys -- Yosys Open SYnthesis Suite

Copyright (C) 2012 - 2020  Claire Xenia Wolf &lt;claire@yosyshq.com&gt;

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
</code></pre><div class="zeroclipboard-container">
     
  </div></div>
<h1 tabindex="-1" dir="auto"><a id="user-content-yosys--yosys-open-synthesis-suite" class="anchor" aria-hidden="true" tabindex="-1" href="#yosys--yosys-open-synthesis-suite"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">yosys – Yosys 开放综合套件</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是 RTL 综合工具的框架。它目前拥有广泛的 Verilog-2005 支持，并为各种应用领域提供了一组基本的综合算法。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Yosys 可以通过使用综合脚本组合现有的通道（算法）来执行任何综合作业，并根据需要通过扩展 yosys C++ 代码库添加其他通道。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Yosys 是根据 ISC 许可证（一种 GPL 兼容许可证，类似于 MIT 许可证或 2 条款 BSD 许可证）授权的免费软件。</font></font></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-web-site-and-other-resources" class="anchor" aria-hidden="true" tabindex="-1" href="#web-site-and-other-resources"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网站和其他资源</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更多信息和文档可以在 Yosys 网站上找到：</font></font></p>
<ul dir="auto">
<li><a href="https://yosyshq.net/yosys/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://yosyshq.net/yosys/</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网站上的“文档”页面包含更多资源的链接，包括甚至描述了一些 Yosys 内部结构的手册：</font></font></p>
<ul dir="auto">
<li><a href="https://yosyshq.net/yosys/documentation.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://yosyshq.net/yosys/documentation.html</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该目录</font></font><code>guidelines</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包含为有兴趣使用 Yosys C++ API 的人们提供的附加信息。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对形式化验证感兴趣的用户可能希望使用 Yosys、SymbiYosys 的形式化验证前端：</font></font></p>
<ul dir="auto">
<li><a href="https://symbiyosys.readthedocs.io/en/latest/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://symbiyosys.readthedocs.io/en/latest/</font></font></a></li>
<li><a href="https://github.com/YosysHQ/SymbiYosys"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/YosysHQ/SymbiYosys</font></font></a></li>
</ul>
<h1 tabindex="-1" dir="auto"><a id="user-content-installation" class="anchor" aria-hidden="true" tabindex="-1" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Yosys 是</font></font><a href="https://www.yosyshq.com/tabby-cad-datasheet" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tabby CAD 套件</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/YosysHQ/oss-cad-suite-build"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OSS CAD 套件</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的一部分！使用yosys最简单的方法是安装二进制软件套件，其中包含所有必需的依赖项和相关工具。</font></font></p>
<ul dir="auto">
<li><a href="https://www.yosyshq.com/contact" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">联系 YosysHQ</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取</font></font><a href="https://www.yosyshq.com/tabby-cad-datasheet" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tabby CAD 套件</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">评估许可证和下载链接</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者访问</font></font><a href="https://github.com/YosysHQ/oss-cad-suite-build/releases"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/YosysHQ/oss-cad-suite-build/releases</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载免费的 OSS CAD 套件</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按照</font></font><a href="https://github.com/YosysHQ/oss-cad-suite-build#installation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub 上的安装说明进行操作</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您需要工业级 SystemVerilog 和 VHDL 解析器等功能，请确保获得 Tabby CAD 套件评估许可证！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关 Tabby CAD Suite 和 OSS CAD Suite 之间差异的更多信息，请访问</font></font><a href="https://www.yosyshq.com/tabby-cad-datasheet" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://www.yosyshq.com/tabby-cad-datasheet</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">许多 Linux 发行版还提供 Yosys 二进制文件，其中一些比其他版本更新。请与您的包管理器联系！</font></font></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-building-from-source" class="anchor" aria-hidden="true" tabindex="-1" href="#building-from-source"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从源头构建</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您需要一个支持 C++11 的 C++ 编译器（建议使用最新的 CLANG 或 GCC）以及一些标准工具，例如 GNU Flex、GNU Bison 和 GNU Make。 TCL、readline 和 libffi 是可选的（请参阅</font></font><code>ENABLE_*</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Makefile 中的设置）。 Xdot（graphviz）被</font></font><code>show</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">yosys中的命令用来显示原理图。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，在 Ubuntu Linux 16.04 LTS 上，以下命令将安装构建 yosys 的所有先决条件：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ sudo apt-get install build-essential clang bison flex \
	libreadline-dev gawk tcl-dev libffi-dev git \
	graphviz xdot pkg-config python3 libboost-system-dev \
	libboost-python-dev libboost-filesystem-dev zlib1g-dev
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ sudo apt-get install build-essential clang bison flex \
	libreadline-dev gawk tcl-dev libffi-dev git \
	graphviz xdot pkg-config python3 libboost-system-dev \
	libboost-python-dev libboost-filesystem-dev zlib1g-dev" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类似地，在 Mac OS X 上，Homebrew 可用于安装依赖项（从克隆的 yosys 存储库中）：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ brew tap Homebrew/bundle &amp;&amp; brew bundle
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ brew tap Homebrew/bundle &amp;&amp; brew bundle" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或 Mac 端口：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ sudo port install bison flex readline gawk libffi \
	git graphviz pkgconfig python36 boost zlib tcl
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ sudo port install bison flex readline gawk libffi \
	git graphviz pkgconfig python36 boost zlib tcl" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 FreeBSD 上，使用以下命令安装所有必备组件：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code># pkg install bison flex readline gawk libffi\
	git graphviz pkgconf python3 python36 tcl-wrapper boost-libs
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# pkg install bison flex readline gawk libffi\
	git graphviz pkgconf python3 python36 tcl-wrapper boost-libs" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 FreeBSD 系统上使用 gmake 而不是 make。要运行测试，请使用： % MAKE=gmake CC=cc gmake test</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于 Cygwin，请使用以下命令安装所有先决条件，或选择这些附加软件包：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>setup-x86_64.exe -q --packages=bison,flex,gcc-core,gcc-g++,git,libffi-devel,libreadline-devel,make,pkg-config,python3,tcl-devel,boost-build,zlib-devel
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="setup-x86_64.exe -q --packages=bison,flex,gcc-core,gcc-g++,git,libffi-devel,libreadline-devel,make,pkg-config,python3,tcl-devel,boost-build,zlib-devel" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要将构建系统配置为使用特定编译器，请使用以下之一</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ make config-clang
$ make config-gcc
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ make config-clang
$ make config-gcc" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于其他编译器和构建配置，可能需要对 Makefile 的配置部分进行一些更改。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ vi Makefile            # ..or..
$ vi Makefile.conf
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ vi Makefile            # ..or..
$ vi Makefile.conf" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要构建 Yosys，只需在此目录中键入“make”即可。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ make
$ sudo make install
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ make
$ sudo make install" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，这还会下载、构建和安装 ABC（使用 yosys-abc 作为可执行文件名称）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试位于测试子目录中，可以使用测试目标执行。请注意，您需要 gawk 以及最新版本的 iverilog（即从 git 构建）。然后，通过以下方式执行测试：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ make test
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ make test" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要使用单独的（树外）构建目录，请提供 Makefile 的路径。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ mkdir build; cd build
$ make -f ../Makefile
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ mkdir build; cd build
$ make -f ../Makefile" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树外构建需要干净的源树。</font></font></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-getting-started" class="anchor" aria-hidden="true" tabindex="-1" href="#getting-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">入门</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Yosys 可以与交互式命令 shell、综合脚本或命令行参数一起使用。让我们使用交互式命令 shell 执行一个简单的综合工作：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ ./yosys
yosys&gt;
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ ./yosys
yosys>" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该命令</font></font><code>help</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可用于打印所有可用命令的列表以及</font></font><code>help &lt;command&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打印指定命令的详细信息：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>yosys&gt; help help
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="yosys> help help" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Verilog 前端阅读和阐述设计：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>yosys&gt; read -sv tests/simple/fiedler-cooley.v
yosys&gt; hierarchy -top up3down5
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="yosys> read -sv tests/simple/fiedler-cooley.v
yosys> hierarchy -top up3down5" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以 Yosys 内部使用的 RTLIL 格式将设计写入控&ZeroWidthSpace;&ZeroWidthSpace;制台：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>yosys&gt; write_rtlil
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="yosys> write_rtlil" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将进程（</font></font><code>always</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">块）转换为网表元素并执行一些简单的优化：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>yosys&gt; proc; opt
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="yosys> proc; opt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用以下方式显示设计网表</font></font><code>xdot</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>yosys&gt; show
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="yosys> show" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>gv</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与后记查看器</font><font style="vertical-align: inherit;">使用相同的东西：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>yosys&gt; show -format ps -viewer gv
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="yosys> show -format ps -viewer gv" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将网表转换为门逻辑并执行一些简单的优化：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>yosys&gt; techmap; opt
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="yosys> techmap; opt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将设计网表写入新的 Verilog 文件：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>yosys&gt; write_verilog synth.v
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="yosys> write_verilog synth.v" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或使用简单的合成脚本：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ cat synth.ys
read -sv tests/simple/fiedler-cooley.v
hierarchy -top up3down5
proc; opt; techmap; opt
write_verilog synth.v

$ ./yosys synth.ys
</code></pre><div class="zeroclipboard-container">

  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果在 Yosys 构建配置中启用了 ABC 并且在 liberty 文件中给出了单元库</font></font><code>mycells.lib</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，则以下综合脚本将为给定的单元库进行综合：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code># read design
read -sv tests/simple/fiedler-cooley.v
hierarchy -top up3down5

# the high-level stuff
proc; fsm; opt; memory; opt

# mapping to internal cell library
techmap; opt

# mapping flip-flops to mycells.lib
dfflibmap -liberty mycells.lib

# mapping logic to mycells.lib
abc -liberty mycells.lib

# cleanup
clean
</code></pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您没有 liberty 文件但想要测试此综合脚本，您可以使用</font></font><code>examples/cmos/cmos_cells.lib</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">yosys 源中的文件作为简单示例。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可在此处找到有关免费和开放 ASIC 标准单元库的 Liberty 文件下载和信息：</font></font></p>
<ul dir="auto">
<li><a href="http://www.vlsitechnology.org/html/libraries.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.vlsitechnology.org/html/libraries.html</font></font></a></li>
<li><a href="http://www.vlsitechnology.org/synopsys/vsclib013.lib" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.vlsitechnology.org/synopsys/vsclib013.lib</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该命令</font></font><code>synth</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供了一个很好的默认综合脚本（请参阅 参考资料
</font></font><code>help synth</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>read -sv tests/simple/fiedler-cooley.v
synth -top up3down5

# mapping to target cells
dfflibmap -liberty mycells.lib
abc -liberty mycells.lib
clean
</code></pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该命令</font></font><code>prep</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供了一个良好的默认字级综合脚本，用于基于 SMT 的形式验证。</font></font></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-unsupported-verilog-2005-features" class="anchor" aria-hidden="true" tabindex="-1" href="#unsupported-verilog-2005-features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不支持的 Verilog-2005 功能</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Yosys 不支持以下 Verilog-2005 功能，目前没有计划添加对它们的支持：</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IEC 62142(E):2005 / IEEE Std. 中定义的不可合成语言功能1364.1(E):2002</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>tri</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font><font style="vertical-align: inherit;">网络</font></font><code>triand</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型</font></font><code>trior</code><font style="vertical-align: inherit;"></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>config</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关键字</font></font><code>disable</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和库映射文件</font></font></p>
</li>
</ul>
<h1 tabindex="-1" dir="auto"><a id="user-content-verilog-attributes-and-non-standard-features" class="anchor" aria-hidden="true" tabindex="-1" href="#verilog-attributes-and-non-standard-features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Verilog 属性和非标准功能</font></font></h1>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持 case 语句上的属性</font></font><code>full_case</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（也是非标准</font></font><code>// synopsys full_case</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指令）</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持 case 语句上的属性</font></font><code>parallel_case</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（也是非标准</font></font><code>// synopsys parallel_case</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指令）</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
还支持</font></font><code>// synopsys translate_off</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font><font style="vertical-align: inherit;">指令（但</font><font style="vertical-align: inherit;">
强烈建议使用 ）。</font></font><code>// synopsys translate_on</code><font style="vertical-align: inherit;"></font><code>`ifdef .. `endif</code><font style="vertical-align: inherit;"></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模块或数组上的属性</font></font><code>nomem2reg</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">禁止将数组自动提前转换为单独的寄存器。这是有潜在危险的。通常前端有充分的理由将数组转换为寄存器列表。禁止此步骤可能会导致不正确的合成结果。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模块或数组上的属性</font></font><code>mem2reg</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">强制数组尽早转换为单独的寄存器。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模块或数组上的属性</font></font><code>nomeminit</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">禁止创建已初始化的内存。这实际上将</font></font><code>mem2reg</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
写入</font></font><code>initial</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">块中的所有存储器（而不是 ROM）放入其中。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模块或始终块上的属性</font></font><code>nolatches</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">禁止生成锁存器的逻辑循环。相反，所有未显式分配的值都默认为 x 位。这不会影响时钟存储元件，例如触发器。</font></font></p>
</li>
<li>
<p dir="auto">The <code>nosync</code> attribute on registers prohibits the generation of a
storage element. The register itself will always have all bits set
to 'x' (undefined). The variable may only be used as blocking assigned
temporary variable within an always block. This is mostly used internally
by Yosys to synthesize Verilog functions and access arrays.</p>
</li>
<li>
<p dir="auto">The <code>nowrshmsk</code> attribute on a register prohibits the generation of
shift-and-mask type circuits for writing to bit slices of that register.</p>
</li>
<li>
<p dir="auto">The <code>onehot</code> attribute on wires mark them as one-hot state register. This
is used for example for memory port sharing and set by the fsm_map pass.</p>
</li>
<li>
<p dir="auto">The <code>blackbox</code> attribute on modules is used to mark empty stub modules
that have the same ports as the real thing but do not contain information
on the internal configuration. This modules are only used by the synthesis
passes to identify input and output ports of cells. The Verilog backend
also does not output blackbox modules on default. <code>read_verilog</code>, unless
called with <code>-noblackbox</code> will automatically set the blackbox attribute
on any empty module it reads.</p>
</li>
<li>
<p dir="auto">The <code>noblackbox</code> attribute set on an empty module prevents <code>read_verilog</code>
from automatically setting the blackbox attribute on the module.</p>
</li>
<li>
<p dir="auto">The <code>whitebox</code> attribute on modules triggers the same behavior as
<code>blackbox</code>, but is for whitebox modules, i.e. library modules that
contain a behavioral model of the cell type.</p>
</li>
<li>
<p dir="auto">The <code>lib_whitebox</code> attribute overwrites <code>whitebox</code> when <code>read_verilog</code>
is run in <code>-lib</code> mode. Otherwise it's automatically removed.</p>
</li>
<li>
<p dir="auto">The <code>dynports</code> attribute is used by the Verilog front-end to mark modules
that have ports with a width that depends on a parameter.</p>
</li>
<li>
<p dir="auto">The <code>hdlname</code> attribute is used by some passes to document the original
(HDL) name of a module when renaming a module. It should contain a single
name, or, when describing a hierarchical name in a flattened design, multiple
names separated by a single space character.</p>
</li>
<li>
<p dir="auto">The <code>keep</code> attribute on cells and wires is used to mark objects that should
never be removed by the optimizer. This is used for example for cells that
have hidden connections that are not part of the netlist, such as IO pads.
Setting the <code>keep</code> attribute on a module has the same effect as setting it
on all instances of the module.</p>
</li>
<li>
<p dir="auto">The <code>keep_hierarchy</code> attribute on cells and modules keeps the <code>flatten</code>
command from flattening the indicated cells and modules.</p>
</li>
<li>
<p dir="auto">The <code>init</code> attribute on wires is set by the frontend when a register is
initialized "FPGA-style" with <code>reg foo = val</code>. It can be used during
synthesis to add the necessary reset logic.</p>
</li>
<li>
<p dir="auto">The <code>top</code> attribute on a module marks this module as the top of the
design hierarchy. The <code>hierarchy</code> command sets this attribute when called
with <code>-top</code>. Other commands, such as <code>flatten</code> and various backends
use this attribute to determine the top module.</p>
</li>
<li>
<p dir="auto">The <code>src</code> attribute is set on cells and wires created by to the string
<code>&lt;hdl-file-name&gt;:&lt;line-number&gt;</code> by the HDL front-end and is then carried
through the synthesis. When entities are combined, a new |-separated
string is created that contains all the string from the original entities.</p>
</li>
<li>
<p dir="auto">The <code>defaultvalue</code> attribute is used to store default values for
module inputs. The attribute is attached to the input wire by the HDL
front-end when the input is declared with a default value.</p>
</li>
<li>
<p dir="auto">The <code>parameter</code> and <code>localparam</code> attributes are used to mark wires
that represent module parameters or localparams (when the HDL front-end
is run in <code>-pwires</code> mode).</p>
</li>
<li>
<p dir="auto">Wires marked with the <code>hierconn</code> attribute are connected to wires with the
same name (format <code>cell_name.identifier</code>) when they are imported from
sub-modules by <code>flatten</code>.</p>
</li>
<li>
<p dir="auto">The <code>clkbuf_driver</code> attribute can be set on an output port of a blackbox
module to mark it as a clock buffer output, and thus prevent <code>clkbufmap</code>
from inserting another clock buffer on a net driven by such output.</p>
</li>
<li>
<p dir="auto">The <code>clkbuf_sink</code> attribute can be set on an input port of a module to
request clock buffer insertion by the <code>clkbufmap</code> pass.</p>
</li>
<li>
<p dir="auto">The <code>clkbuf_inv</code> attribute can be set on an output port of a module
with the value set to the name of an input port of that module.  When
the <code>clkbufmap</code> would otherwise insert a clock buffer on this output,
it will instead try inserting the clock buffer on the input port (this
is used to implement clock inverter cells that clock buffer insertion
will "see through").</p>
</li>
<li>
<p dir="auto">The <code>clkbuf_inhibit</code> is the default attribute to set on a wire to prevent
automatic clock buffer insertion by <code>clkbufmap</code>. This behaviour can be
overridden by providing a custom selection to <code>clkbufmap</code>.</p>
</li>
<li>
<p dir="auto">The <code>invertible_pin</code> attribute can be set on a port to mark it as
invertible via a cell parameter.  The name of the inversion parameter
is specified as the value of this attribute.  The value of the inversion
parameter must be of the same width as the port, with 1 indicating
an inverted bit and 0 indicating a non-inverted bit.</p>
</li>
<li>
<p dir="auto">The <code>iopad_external_pin</code> attribute on a blackbox module's port marks
it as the external-facing pin of an I/O pad, and prevents <code>iopadmap</code>
from inserting another pad cell on it.</p>
</li>
<li>
<p dir="auto">The module attribute <code>abc9_lut</code> is an integer attribute indicating to
<code>abc9</code> that this module describes a LUT with an area cost of this value, and
propagation delays described using <code>specify</code> statements.</p>
</li>
<li>
<p dir="auto">The module attribute <code>abc9_box</code> is a boolean specifying a black/white-box
definition, with propagation delays described using <code>specify</code> statements, for
use by <code>abc9</code>.</p>
</li>
<li>
<p dir="auto">The port attribute <code>abc9_carry</code> marks the carry-in (if an input port) and
carry-out (if output port) ports of a box. This information is necessary for
<code>abc9</code> to preserve the integrity of carry-chains. Specifying this attribute
onto a bus port will affect only its most significant bit.</p>
</li>
<li>
<p dir="auto">The module attribute <code>abc9_flop</code> is a boolean marking the module as a
flip-flop. This allows <code>abc9</code> to analyse its contents in order to perform
sequential synthesis.</p>
</li>
<li>
<p dir="auto">The frontend sets attributes <code>always_comb</code>, <code>always_latch</code> and
<code>always_ff</code> on processes derived from SystemVerilog style always blocks
according to the type of the always. These are checked for correctness in
<code>proc_dlatch</code>.</p>
</li>
<li>
<p dir="auto">The cell attribute <code>wildcard_port_conns</code> represents wildcard port
connections (SystemVerilog <code>.*</code>). These are resolved to concrete
connections to matching wires in <code>hierarchy</code>.</p>
</li>
<li>
<p dir="auto">In addition to the <code>(* ... *)</code> attribute syntax, Yosys supports
the non-standard <code>{* ... *}</code> attribute syntax to set default attributes
for everything that comes after the <code>{* ... *}</code> statement. (Reset
by adding an empty <code>{* *}</code> statement.)</p>
</li>
<li>
<p dir="auto">In module parameter and port declarations, and cell port and parameter
lists, a trailing comma is ignored. This simplifies writing Verilog code
generators a bit in some cases.</p>
</li>
<li>
<p dir="auto">Modules can be declared with <code>module mod_name(...);</code> (with three dots
instead of a list of module ports). With this syntax it is sufficient
to simply declare a module port as 'input' or 'output' in the module
body.</p>
</li>
<li>
<p dir="auto">When defining a macro with `define, all text between triple double quotes
is interpreted as macro body, even if it contains unescaped newlines. The
triple double quotes are removed from the macro body. For example:</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>`define MY_MACRO(a, b) """
   assign a = 23;
   assign b = 42;
"""
</code></pre><div class="zeroclipboard-container">
 
  </div></div>
</li>
<li>
<p dir="auto">The attribute <code>via_celltype</code> can be used to implement a Verilog task or
function by instantiating the specified cell type. The value is the name
of the cell type to use. For functions the name of the output port can
be specified by appending it to the cell type separated by a whitespace.
The body of the task or function is unused in this case and can be used
to specify a behavioral model of the cell type for simulation. For example:</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>module my_add3(A, B, C, Y);
  parameter WIDTH = 8;
  input [WIDTH-1:0] A, B, C;
  output [WIDTH-1:0] Y;
  ...
endmodule

module top;
  ...
  (* via_celltype = "my_add3 Y" *)
  (* via_celltype_defparam_WIDTH = 32 *)
  function [31:0] add3;
    input [31:0] A, B, C;
    begin
      add3 = A + B + C;
    end
  endfunction
  ...
endmodule
</code></pre><div class="zeroclipboard-container">
    
  </div></div>
</li>
<li>
<p dir="auto">The <code>wiretype</code> attribute is added by the verilog parser for wires of a
typedef'd type to indicate the type identifier.</p>
</li>
<li>
<p dir="auto">Various <code>enum_value_{value}</code> attributes are added to wires of an enumerated type
to give a map of possible enum items to their values.</p>
</li>
<li>
<p dir="auto">The <code>enum_base_type</code> attribute is added to enum items to indicate which
enum they belong to (enums -- anonymous and otherwise -- are
automatically named with an auto-incrementing counter). Note that enums
are currently not strongly typed.</p>
</li>
<li>
<p dir="auto">A limited subset of DPI-C functions is supported. The plugin mechanism
(see <code>help plugin</code>) can be used to load .so files with implementations
of DPI-C routines. As a non-standard extension it is possible to specify
a plugin alias using the <code>&lt;alias&gt;:</code> syntax. For example:</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>module dpitest;
  import "DPI-C" function foo:round = real my_round (real);
  parameter real r = my_round(12.345);
endmodule

$ yosys -p 'plugin -a foo -i /lib/libm.so; read_verilog dpitest.v'
</code></pre><div class="zeroclipboard-container">
   
  </div></div>
</li>
<li>
<p dir="auto">Sized constants (the syntax <code>&lt;size&gt;'s?[bodh]&lt;value&gt;</code>) support constant
expressions as <code>&lt;size&gt;</code>. If the expression is not a simple identifier, it
must be put in parentheses. Examples: <code>WIDTH'd42</code>, <code>(4+2)'b101010</code></p>
</li>
<li>
<p dir="auto">The system tasks <code>$finish</code>, <code>$stop</code> and <code>$display</code> are supported in
initial blocks in an unconditional context (only if/case statements on
expressions over parameters and constant values are allowed). The intended
use for this is synthesis-time DRC.</p>
</li>
<li>
<p dir="auto">There is limited support for converting <code>specify</code> .. <code>endspecify</code>
statements to special <code>$specify2</code>, <code>$specify3</code>, and <code>$specrule</code> cells,
for use in blackboxes and whiteboxes. Use <code>read_verilog -specify</code> to
enable this functionality. (By default these blocks are ignored.)</p>
</li>
<li>
<p dir="auto">The <code>reprocess_after</code> internal attribute is used by the Verilog frontend to
mark cells with bindings which might depend on the specified instantiated
module. Modules with such cells will be reprocessed during the <code>hierarchy</code>
pass once the referenced module definition(s) become available.</p>
</li>
<li>
<p dir="auto">The <code>smtlib2_module</code> attribute can be set on a blackbox module to specify a
formal model directly using SMT-LIB 2. For such a module, the
<code>smtlib2_comb_expr</code> attribute can be used on output ports to define their
value using an SMT-LIB 2 expression. For example:</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>(* blackbox *)
(* smtlib2_module *)
module submod(a, b);
  input [7:0] a;
  (* smtlib2_comb_expr = "(bvnot a)" *)
  output [7:0] b;
endmodule
</code></pre><div class="zeroclipboard-container">

  </div></div>
</li>
</ul>
<h1 tabindex="-1" dir="auto"><a id="user-content-non-standard-or-systemverilog-features-for-formal-verification" class="anchor" aria-hidden="true" tabindex="-1" href="#non-standard-or-systemverilog-features-for-formal-verification"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>Non-standard or SystemVerilog features for formal verification</h1>
<ul dir="auto">
<li>
<p dir="auto">Support for <code>assert</code>, <code>assume</code>, <code>restrict</code>, and <code>cover</code> is enabled
when <code>read_verilog</code> is called with <code>-formal</code>.</p>
</li>
<li>
<p dir="auto">The system task <code>$initstate</code> evaluates to 1 in the initial state and
to 0 otherwise.</p>
</li>
<li>
<p dir="auto">The system function <code>$anyconst</code> evaluates to any constant value. This is
equivalent to declaring a reg as <code>rand const</code>, but also works outside
of checkers. (Yosys also supports <code>rand const</code> outside checkers.)</p>
</li>
<li>
<p dir="auto">The system function <code>$anyseq</code> evaluates to any value, possibly a different
value in each cycle. This is equivalent to declaring a reg as <code>rand</code>,
but also works outside of checkers. (Yosys also supports <code>rand</code>
variables outside checkers.)</p>
</li>
<li>
<p dir="auto">The system functions <code>$allconst</code> and <code>$allseq</code> can be used to construct
formal exist-forall problems. Assumptions only hold if the trace satisfies
the assumption for all <code>$allconst/$allseq</code> values. For assertions and cover
statements it is sufficient if just one <code>$allconst/$allseq</code> value triggers
the property (similar to <code>$anyconst/$anyseq</code>).</p>
</li>
<li>
<p dir="auto">Wires/registers declared using the <code>anyconst/anyseq/allconst/allseq</code> attribute
(for example <code>(* anyconst *) reg [7:0] foobar;</code>) will behave as if driven
by a <code>$anyconst/$anyseq/$allconst/$allseq</code> function.</p>
</li>
<li>
<p dir="auto">The SystemVerilog tasks <code>$past</code>, <code>$stable</code>, <code>$rose</code> and <code>$fell</code> are
supported in any clocked block.</p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该语法</font></font><code>@($global_clock)</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可用于创建没有显式时钟输入（</font></font><code>$ff</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单元）的 FF。使用
</font></font><code>@(posedge &lt;netname&gt;)</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或当</font><font style="vertical-align: inherit;">
标有Verilog 属性</font></font><code>@(negedge &lt;netname&gt;)</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">时也可以实现同样的效果</font><font style="vertical-align: inherit;">。</font></font><code>&lt;netname&gt;</code><font style="vertical-align: inherit;"></font><code>(* gclk *)</code><font style="vertical-align: inherit;"></font></p>
</li>
</ul>
<h1 tabindex="-1" dir="auto"><a id="user-content-supported-features-from-systemverilog" class="anchor" aria-hidden="true" tabindex="-1" href="#supported-features-from-systemverilog"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SystemVerilog 支持的功能</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当</font></font><code>read_verilog</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 调用时</font></font><code>-sv</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，它接受来自 SystemVerilog 的一些语言特性：</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SystemVerilog 的语句</font></font><code>assert</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以其最基本的形式得到支持。在模块上下文中：</font></font><code>assert property (&lt;expression&gt;);</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以及在always块中：</font></font><code>assert(&lt;expression&gt;);</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。它转变为</font></font><code>$assert</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">细胞。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">还支持 SystemVerilog 中的</font></font><code>assume</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>restrict</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font><font style="vertical-align: inherit;">语句。</font></font><code>cover</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与该</font></font><code>assert</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">声明相同的限制也适用。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持</font><font style="vertical-align: inherit;">关键字</font></font><code>always_comb</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>always_ff</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">and </font></font><code>always_latch</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>logic</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
and 。</font></font><code>bit</code><font style="vertical-align: inherit;"></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持使用</font></font><code>rand</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font><font style="vertical-align: inherit;">声明自由变量。</font></font><code>rand const</code><font style="vertical-align: inherit;"></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持不带端口列表、不需要实例化（但行为类似于命名块）的检查器。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持 SystemVerilog 包。一旦使用 读取 SystemVerilog 文件到设计中</font></font><code>read_verilog</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，其所有包都可供随后读入同一设计的 SystemVerilog 文件使用。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持 typedef（包括内部包）</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目前不支持类型转换</font></font></li>
</ul>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持枚举（包括内部包）</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">但目前不是强类型的</font></font></li>
</ul>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持打包结构和联合</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目前不支持打包结构/联合数组</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目前不支持结构文字</font></font></li>
</ul>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持多维数组</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目前不支持解压数组的数组赋值</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目前不支持数组文字</font></font></li>
</ul>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持 SystemVerilog 接口 (SVI)。支持用于指定端口是输入还是输出的 Modports。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持表达式内的赋值。</font></font></p>
</li>
</ul>
<h1 tabindex="-1" dir="auto"><a id="user-content-building-the-documentation" class="anchor" aria-hidden="true" tabindex="-1" href="#building-the-documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建文档</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，如果您只是想阅读手册，则无需构建手册。只需访问</font></font><a href="https://yosys.readthedocs.io/en/latest/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://yosys.readthedocs.io/en/latest/</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">即可。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">除了上面列出的用于从源代码构建 Yosys 的软件包之外，还使用以下软件包来构建网站：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ sudo apt-get install pdf2svg faketime
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ sudo apt-get install pdf2svg faketime" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在网站的构建过程中还需要大多数 LaTeX 发行版中包含的 PDFLaTeX。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要 Python 包 Sphinx 以及以下中列出的包
</font></font><code>docs/source/requirements.txt</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ pip install -U sphinx -r docs/source/requirements.txt
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ pip install -U sphinx -r docs/source/requirements.txt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从存储库的根目录运行</font></font><code>make docs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.这将在从 yosys 帮助命令生成网站文档之前根据需要构建/重建 yosys。要构建 pdf 而不是 html，请调用
</font></font><code>make docs DOC_TARGET=latexpdf</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
</article></div>
