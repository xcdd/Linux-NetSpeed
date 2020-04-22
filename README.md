
<!DOCTYPE html>
<html lang="en">




      
  <div id="readme" class="Box-body readme blob js-code-block-container px-5">
    <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-linux-netspeed" class="anchor" aria-hidden="true" href="#linux-netspeed"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Linux-NetSpeed</h1>
<p><strong>支持系统：</strong><code>Centos 6+</code>/<code>Debian 7+</code>/<code>Ubuntu 14+</code>，<code>BBR</code>魔改版不支持<code>Debian 8</code>。<br><strong>注意：</strong>该脚本在<code>Vultr</code>各个系统均测试通过，如果期间有出现任何问题，可向原作者反映帮助改善。<br>运行以下命令：</p><pre><code>wget -N --no-check-certificate "https://raw.githubusercontent.com/dlxg/Linux-NetSpeed/master/tcp.sh" &amp;&amp; chmod +x tcp.sh &amp;&amp; ./tcp.sh
</code></pre><h2><a id="user-content-使用说明" class="anchor" aria-hidden="true" href="#使用说明"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>使用说明</h2><p>使用脚本后会出现如下选项：<br><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/60f74ef37751f2cd13f83ad0a229bed77bc303f6/68747470733a2f2f7777772e6d6f65726174732e636f6d2f7573722f706963747572652f7169616e79696e676262722831292e706e67"><img src="https://raw.githubusercontent.com/dlxg/Linux-NetSpeed/master/Snipaste_2020-04-23_00-42-15.png" data-canonical-src="https://github.com/dlxg/Linux-NetSpeed/blob/master/Snipaste_2020-04-23_00-42-15.png" style="max-width:100%;"></a><br><br>根据自己需求操作，重启后再使用<code>./tcp.sh</code>命令接着操作。<br><br>脚本会自动检测安装的情况，请注意脚本菜单下的状态检测即可。</p><p>如果在删除内核环节出现这样一张图，注意选择<code>NO</code>，然后根据提示重启系统。<br><br><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/b047b125b25b3c5d441394e1d891691a209b8dbc/68747470733a2f2f7777772e6d6f65726174732e636f6d2f7573722f706963747572652f7169616e79696e676262722832292e706e67"><img src="https://camo.githubusercontent.com/b047b125b25b3c5d441394e1d891691a209b8dbc/68747470733a2f2f7777772e6d6f65726174732e636f6d2f7573722f706963747572652f7169616e79696e676262722832292e706e67" data-canonical-src="https://www.moerats.com/usr/picture/qianyingbbr(2).png" style="max-width:100%;"></a></p>
</article>
  </div>

</body>
</html>

