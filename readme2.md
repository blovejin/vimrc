<article class="_2rhmJa"><h2>使用的配置</h2>
<div class="_2Uzcx_"><button class="VJbwyy" type="button" aria-label="复制代码"><i aria-label="icon: copy" class="anticon anticon-copy"><svg viewBox="64 64 896 896" focusable="false" class="" data-icon="copy" width="1em" height="1em" fill="currentColor" aria-hidden="true"><path d="M832 64H296c-4.4 0-8 3.6-8 8v56c0 4.4 3.6 8 8 8h496v688c0 4.4 3.6 8 8 8h56c4.4 0 8-3.6 8-8V96c0-17.7-14.3-32-32-32zM704 192H192c-17.7 0-32 14.3-32 32v530.7c0 8.5 3.4 16.6 9.4 22.6l173.3 173.3c2.2 2.2 4.7 4 7.4 5.5v1.9h4.2c3.5 1.3 7.2 2 11 2H704c17.7 0 32-14.3 32-32V224c0-17.7-14.3-32-32-32zM350 856.2L263.9 770H350v86.2zM664 888H414V746c0-22.1-17.9-40-40-40H232V264h432v624z"></path></svg></i></button><pre class="line-numbers  language-cpp"><code class="  language-cpp">https<span class="token operator">:</span><span class="token operator">/</span><span class="token operator">/</span>github<span class="token punctuation">.</span>com<span class="token operator">/</span>amix<span class="token operator">/</span>vimrc
<span aria-hidden="true" class="line-numbers-rows"><span></span></span></code></pre></div>
<h2>安装很简单</h2>
<div class="_2Uzcx_"><button class="VJbwyy" type="button" aria-label="复制代码"><i aria-label="icon: copy" class="anticon anticon-copy"><svg viewBox="64 64 896 896" focusable="false" class="" data-icon="copy" width="1em" height="1em" fill="currentColor" aria-hidden="true"><path d="M832 64H296c-4.4 0-8 3.6-8 8v56c0 4.4 3.6 8 8 8h496v688c0 4.4 3.6 8 8 8h56c4.4 0 8-3.6 8-8V96c0-17.7-14.3-32-32-32zM704 192H192c-17.7 0-32 14.3-32 32v530.7c0 8.5 3.4 16.6 9.4 22.6l173.3 173.3c2.2 2.2 4.7 4 7.4 5.5v1.9h4.2c3.5 1.3 7.2 2 11 2H704c17.7 0 32-14.3 32-32V224c0-17.7-14.3-32-32-32zM350 856.2L263.9 770H350v86.2zM664 888H414V746c0-22.1-17.9-40-40-40H232V264h432v624z"></path></svg></i></button><pre class="line-numbers  language-ruby"><code class="  language-ruby">git clone <span class="token operator">--</span>depth<span class="token operator">=</span><span class="token number">1</span> https<span class="token punctuation">:</span><span class="token operator">/</span><span class="token operator">/</span>github<span class="token punctuation">.</span>com<span class="token operator">/</span>amix<span class="token regex">/vimrc.git ~/</span><span class="token punctuation">.</span>vim_runtime
sh <span class="token operator">~</span><span class="token operator">/</span><span class="token punctuation">.</span>vim_runtime<span class="token operator">/</span>install_awesome_vimrc<span class="token punctuation">.</span>sh
<span aria-hidden="true" class="line-numbers-rows"><span></span><span></span></span></code></pre></div>
<h2>ack 插件</h2>
<div class="_2Uzcx_"><button class="VJbwyy" type="button" aria-label="复制代码"><i aria-label="icon: copy" class="anticon anticon-copy"><svg viewBox="64 64 896 896" focusable="false" class="" data-icon="copy" width="1em" height="1em" fill="currentColor" aria-hidden="true"><path d="M832 64H296c-4.4 0-8 3.6-8 8v56c0 4.4 3.6 8 8 8h496v688c0 4.4 3.6 8 8 8h56c4.4 0 8-3.6 8-8V96c0-17.7-14.3-32-32-32zM704 192H192c-17.7 0-32 14.3-32 32v530.7c0 8.5 3.4 16.6 9.4 22.6l173.3 173.3c2.2 2.2 4.7 4 7.4 5.5v1.9h4.2c3.5 1.3 7.2 2 11 2H704c17.7 0 32-14.3 32-32V224c0-17.7-14.3-32-32-32zM350 856.2L263.9 770H350v86.2zM664 888H414V746c0-22.1-17.9-40-40-40H232V264h432v624z"></path></svg></i></button><pre class="line-numbers  language-csharp"><code class="  language-csharp">系统需要安装 ack<span class="token operator">-</span>grep<span class="token punctuation">,</span> ubuntu安装命令：sudo apt<span class="token operator">-</span><span class="token keyword">get</span> install ack<span class="token operator">-</span>grep
<span aria-hidden="true" class="line-numbers-rows"><span></span></span></code></pre></div>
<h2>常用命令</h2>
<ol>
<li><p>全局查找文件(ctrlp插件)<br>
<strong><code>ctrl + f</code></strong>      --打开全局文件搜索面板<br>
<strong><code>Esc</code></strong>               --退出全局文件搜索面板</p></li>
<li><p>tab(标签)相关<br>
<strong><code>gt</code></strong>                --后一个标签<br>
<strong><code>gT</code></strong>                --前一个标签<br>
<strong><code>num + gt</code></strong>        --跳转至第num个标签<br>
<strong><code>,tl</code></strong>           --上一次的标签<br>
<strong><code>:q</code></strong>                --关闭标签<br>
<strong><code>:Te</code></strong>           --新建标签，并打开当前文件目录<br>
<strong><code>,tn</code></strong>           --新建空白标签</p></li>
<li><p>目录树(NERD_tree插件)<br>
<strong><code>,nn</code></strong>           --打开目录树<br>
<strong><code>,nn</code></strong>           --关闭目录树</p></li>
<li><p>窗口相关<br>
<strong><code>ctrl + w + q</code></strong>      --关闭窗口<br>
<strong><code>:q</code></strong>                --关闭窗口，窗口只有一个tab的情况<br>
<strong><code>ctrl + w + w</code></strong>  --切换窗口<br>
<strong><code>:sp</code></strong>           --竖直方向上拆分当前窗口<br>
<strong><code>:vsp</code></strong>          --水平方向上拆分当前窗口</p></li>
<li><p>如何打开一个工程<br>
在某个工程的根目录下输入打开vim，则该vim窗口的文件操作默认为整个工程，比如全局搜索文件或字段</p></li>
<li><p>全局搜索字段(ack插件)<br>
<strong><code>,g</code></strong>                --打开全局字段搜索面板，默认大小写敏感，-i 不区分大小写，-w 全词匹配<br>
<strong><code>q</code></strong>                 --退出全局字段搜索面板</p></li>
<li><p>当前文件所在的目录<br>
<strong><code>:E</code></strong>                --打开当前目录，一般用于切换当前目录的文件<br>
<strong><code>:Te</code></strong>             --新建标签并打开当前目录，一般用于打开当前目录下的其它文件</p></li>
<li><p>查看最近打开的文件列表<br>
<strong><code>,f</code></strong>               --打开面板<br>
<strong><code>q</code></strong>                --退出面板</p></li>
<li><p>当前文件下搜索<br>
<strong><code>*</code></strong>               --按下<em>即可搜索光标所在的单词或当前选中的内容，不区分大小写<br>
<strong><code>gd</code></strong>           --光标移动至单词，按下</em>即可搜索该单词，区分大小写<br>
<strong><code>/</code></strong>             --输入单词向下搜索<br>
<strong><code>？</code></strong>            --输入单词向上搜索，一般用于查log，配合G跳转至文件底部使食</p></li>
<li><p>显示行修改标志<br>
<strong><code>,d</code></strong>              --显示与不显示逐一切换</p></li>
<li><p>光标停留的位置记录<br>
<strong><code>ctrl + o</code></strong>        --上一个时间点光标停留的位置<br>
<strong><code>ctrl + i</code></strong>        --下一个时间点光标停留的位置</p></li>
<li><p>文件刷新，即重新载入<br>
<strong><code>:e</code></strong>              --重新载入<br>
<strong><code>:e!</code></strong>             --放弃当前修改，强制重新载入<br>
<strong><code>:e file_dir</code></strong>     --载入 file_dir 路径下的某个文件</p></li>
<li><p>粘贴0号寄存器的内容<br>
<strong><code>ctrl + r + 0</code></strong>    --比如y复制选中的内容后粘贴到命令输入框</p></li>
<li><p>折叠命令<br>
<strong><code>za</code></strong>              --打开或关闭当前折叠<br>
<strong><code>zM</code></strong>             --关闭所有折叠<br>
<strong><code>zR</code></strong>              --打开所有折叠</p></li>
<li><p>跳出双引号继续编辑<br>
有些时候输入完字符串需要移动光标至双引号外继续输入<br>
<strong><code>"</code></strong>                 --在 " 处输入 " ，即可将光标跳转至当前双引号之外</p></li>
<li><p>文件路径<br>
<strong><code>:f</code></strong>                --查看当前文件路径</p></li>
<li><p>变量名补全<br>
<strong><code>ctrl + n</code></strong>          --自动补全变量名，再次输入匹配下一个</p></li>
<li><p>代码块补全，只需输入部分代码，然后按tab键<br>
lua为例：<br>
<strong><code>if + tab</code></strong>      --if代码块<br>
<strong><code>forp + tab</code></strong>        --for i,v in pairs() do end 代码块<br>
<strong><code>fori + tab</code></strong>        --for i,v in ipairs() do end 代码块<br>
<strong><code>fun + tab</code></strong>         --函数模板代码块</p></li>
<li><p>代码检错<br>
<strong><code>:ALEToggle</code></strong>    --启动检错</p></li>
<li><p>代码注释<br>
<strong><code>gcc</code></strong>           --注释当前行，再次输入则撤销注释<br>
<strong><code>num + gcc</code></strong>         --注释num行<br>
<strong><code>gc</code></strong>                --注释选中部分</p></li>
<li><p>取消搜索高亮<br>
<strong><code>:nohl</code></strong></p></li>
<li><p>多窗口显示<br>
<strong><code>:sp</code></strong>           --水平切分窗口<br>
<strong><code>:vsp</code></strong>              --垂直切分窗口</p></li>
</ol>
<h2>vim 编辑相关</h2>
<ol>
<li><p>范围命令<br>
<strong><code>w</code></strong>                 --光标所在的位置至单词末尾的部分或一个单词，包括单词后的空格<br>
<strong><code>iw</code></strong>                --光标所在位置的一个单词，不包括单词后的空格<br>
<strong><code>aw</code></strong>                --光标所在位置的一个单词，包括单词后的空格<br>
<strong><code>b</code></strong>                 --与 w 相反<br>
<strong><code>e</code></strong>                 --end of word，至单词结尾<br>
<strong><code>$</code></strong>                 --至当前行结尾<br>
<strong><code>0</code></strong>             --至当前行开头</p></li>
<li><p>操作命令<br>
<strong><code>d</code></strong>: delete<br>
<strong><code>dd</code></strong>                --删除当前行<br>
<strong><code>diw</code></strong>           --删除光标所在单词<br>
<strong><code>dw</code></strong>                --正向删除一个单词（光标后的部分）<br>
<strong><code>db</code></strong>                --逆向删除一个单词（光标前的部分）<br>
<strong><code>d$</code></strong>                --删除光标所在的位置至本行末尾<br>
<strong><code>d0</code></strong>                --删除光标所在的位置至本行首部<br>
<strong><code>c</code></strong>: change, 与 d 的区别只在于操作后进入插入状态<br>
<strong><code>y</code></strong>: yank, 与 d 的区别在于跟范围命令组合后全部为复制操作</p></li>
<li><p>操作命令（少与范围命令组合）<br>
<strong><code>~</code></strong>                 --大小写字母转换<br>
<strong><code>s</code></strong>                 --删除一个字母，删除后进入插入模式<br>
<strong><code>x</code></strong>                 --删除一个字母，删除后处于命令模式<br>
<strong><code>r</code></strong>                 --即replace，修改替换一个字母，并且替换过后仍然处于命令模式<br>
<strong><code>R</code></strong>                 --修改替换无限多个在字母</p></li>
</ol>
</article>
