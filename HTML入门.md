# HTML入门
1. HTML 是谁发明的
   
   * 1990年左右，名叫Tim Berners-Lee(李爵士)发明了WWW（World Wide Web）
   * 同时还发明了HTML（网页）、HTTP（服务器）、URL（域名）
<hr>

2. HTML 起手应该写什么
   
    起手内容如下：

        <!DOCTYPE html>文档类型
        <html lang="zh-CN">语言
        <head>
            <meta charset="UTF-8">文件的字符编码
            <meta name="viewport" content="width=device-width, initial-scale=1.0">禁用缩写，手机兼容
            <meta http-equiv="X-UA-Compatible" content="ie=edge">使用IE最新内核
            <title>Document</title>文档标题
        </head>
        <body>
            文档内容
        </body>
        </html>
<hr>

3. 常用的表章节的标签有哪些，分别是什么意思



        <body>
            <header>
                今天我要写一篇文章（头部）
            </header>
            <div class="middle-content">
                <main>
                    <h1>第一章（章标题）</h1>
                    <section>
                        <p>这是文档章节标题综述（综述内容）</p>
                        <section>
                            <h2>1.1节（节标题）</h2>
                            <p>第一章第一节段落内容</p>
                        </section>
                        <section>
                            <h2>1.2节</h2>
                            <p>第一章第二节段落内容</p>
                        </section>
                    </section>
                </main>
                <aside>
                    参考资料（旁支内容）
                </aside>
            </div>
            <footer>&copy;版权声明（尾注）
            </footer>
        </body>

   * h1~h6：标题（headline）标签，一级标题字体最大，6级标题最小
   * div:划分成块
   * section:划分章节
   * 其他看代码内容
<hr>

4. 全局属性有哪些
* class 类，用于编辑样式
* contenteditable 内容可见，可将style标签显示
* hidden 隐藏属性
* id 给标签取名字，多用于编写JS
* style 样式
* tabindex 用Tab键控制顺序,可赋值负数(不能访问)，0（最后访问），正数（按数值大小顺序访问）
* tittle 显示完整的标题内容，与标题样式{ white-space:nowrap;  over-flow:hidden;   text-overflow:ellipsis;}配合使用
<hr>

5. 常用的内容标签有哪些，分别是什么意思
   
* ol+li：有序列表
* ul+li：无序列表
* dl+dt+dd：描述列表
* pre：保留多个空格
* hr：水平分割线
* br：断行
* a：插入连接
* em：语气强调
* strong：内容强调
* code：插入代码
* quote：引用
* blockquote：块状化引用


        <body>
        <div>
                <p>下面是有序列表</p>
                <ol>
                    <li>唱</li>
                    <li>跳</li>
                    <li>RAP</li>
                    <li>篮球</li>
                </ol>

                <p>下面是无序列表</p>
                <ul>
                    <li>高压锅</li>
                    <li>电饭煲</li>
                    <li>铁锅</li>
                    <li>电磁炉</li>
                </ul>

                <dl>
                    <dt>我的座右铭</dt>
                    <dd>路漫漫其修远兮，吾将上下而求索</dd>
                </dl>

                <pre>“pre”表示可以留多个空       格</pre>

                <code>
                    var x=y;
                    x.innerHTMl="";
                </code>

                <hr>
                <a href="#xxx">插入连接</a>
                <em>强调语气（emphasis）</em>
                <strong>强调内容</strong>

                <quote>“br”用于断行</quote>
                <br>
                周总理说过<blockquote>为中华之崛起而读书。</blockquote>
            </div>
        </body>
