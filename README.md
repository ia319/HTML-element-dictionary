 <pre><code>
    	I.  文本格式化
基础文本：
&ltb&gt 元素用于将文本加粗。它表示文本的视觉样式，而不一定表达文本的语义。以下是 &ltb&gt 元素的基本格式和使用示例：

&ltb&gt加粗文本&lt/b&gt

&ltbase&gt 元素用于指定文档中所有相对 URL 的基本 URL。它通常放在 &lthead&gt 元素内。以下是 &ltbase&gt 元素的基本格式和常用属性：

&ltbase href="基础 URL" target="目标窗口"&gt
常用属性
	1. href: 定义文档中相对 URL 的基础 URL。所有相对链接都将以此 URL 为基础。
	2. target: 定义在何处打开文档中的链接。可选值包括：
			o _blank：在新窗口或标签页中打开链接。
			o _self：在相同的框架或窗口中打开链接（默认值）。
			o _parent：在父框架中打开链接。
			o _top：在整个窗口中打开链接。

&lti&gt 元素用
于表现因某些原因需要区分普通文本的一系列文本。例如技术术语、外文短语或是小说中人物的思想活动等，它的内容通常以斜体显示。以下是 &lti&gt 元素的基本格式：

&lti&gt斜体文本&lt/i&gt

&ltstrong&gt 元素用于表示重要的文本，通常会加粗显示。以下是 &ltstrong&gt 元素的基本格式：

&ltstrong&gt重要文本&lt/strong&gt

&ltmark&gt 元素
表示为引用或符号目的而标记或突出显示的文本，这是由于标记的段落在封闭上下文中的相关性或重要性造成的。
以下是 &ltmark&gt 元素的基本格式：

&ltmark&gt突出显示的文本&lt/mark&gt

&lts&gt 元素 使用删除线来渲染文本。使用 &lts&gt 元素来表示不再相关，或者不再准确的事情。但是当表示文档编辑时，不提倡使用 &lts&gt ；为此，提倡使用 &ltdel&gt 和 &ltins&gt 元素。以下是 &lts&gt 元素的基本格式：

&lts&gt被删除的文本&lt/s&gt

&ltem&gt 元素
将文本标记为强调（emphasis）格式。&ltem&gt 元素可以嵌套，嵌套层次越深，则强调的程度越深。通常会以斜体显示。以下是 &ltem&gt 元素的基本格式：

&ltem&gt强调文本&lt/em&gt

&ltsub&gt 元素用于表示下标文本。以下是 &ltsub&gt 元素的基本格式：

&ltsub&gt下标文本&lt/sub&gt

&ltsup&gt 元素用于表示上标文本。以下是 &ltsup&gt 元素的基本格式：

&ltsup&gt上标文本&lt/sup&gt

&ltsmall&gt 元素代表旁注和小字印刷（如版权和法律文本），与其样式的呈现方式无关。默认情况下，它以比其中的文本小一号的字体大小呈现，例如从 small 变为 x-small。。以下是 &ltsmall&gt 元素的基本格式：

&ltsmall&gt较小的文本&lt/small&gt

&ltu&gt 元素用于
表示行内文本拥有一个非文本形式的注释，该注释需要以某种方式渲染出来。默认情况下渲染为一个实线下划线，可以用 CSS 替换。

警告：此元素以前在旧版本的 HTML 中称为“下划线”元素，但有时仍会以这种方式被滥用。要为文本加下划线，你应该应用包含 CSS text-decoration 属性设置为 underline 的样式。
。以下是 &ltu&gt 元素的基本格式：

&ltu&gt带下划线的文本&lt/u&gt

&ltbig&gt 元素用于将文本显示得比周围的文本大。该元素已弃用，建议使用 CSS 进行样式设置。以下是 &ltbig&gt 元素的基本格式：

&ltbig&gt较大的文本&lt/big&gt

&lttt&gt 元素用于表示等宽字体（typewriter text），它已被弃用，建议使用 CSS 来实现相同的效果。以下是 &lttt&gt 元素的基本格式：

&lttt&gt等宽字体文本&lt/tt&gt

引用和引用

&ltq&gt 元素表示一个封闭的并且是短的行内引用的文本。这个标签是用来引用短的文本，所以请不要引入换行符; 对于长的文本的引用请使用 &ltblockquote&gt 替代。以下是 &ltq&gt 元素的基本格式：

&ltq&gt引用文本&lt/q&gt

&ltblockquote&gt 元素用于表示长引用的内容，通常会有一个缩进。以下是 &ltblockquote&gt 元素的基本格式：

&ltblockquote cite="引用来源"&gt
    引用内容
&lt/blockquote&gt
常用属性:
	1. cite: 提供引用的来源 URL。

&ltcite&gt 元素用于表示引用的来源或作品的标题。以下是 &ltcite&gt 元素的基本格式：

&ltcite&gt引用来源或作品标题&lt/cite&gt

&ltcode&gt 元素用于表示计算机代码。以下是 &ltcode&gt 元素的基本格式：

&ltcode&gt代码内容&lt/code&gt

&ltsamp&gt 元素用于表示计算机程序的输出。以下是 &ltsamp&gt 元素的基本格式：

&ltsamp&gt程序输出文本&lt/samp&gt

&ltkbd&gt 元素用于表示用户输入的文本。以下是 &ltkbd&gt 元素的基本格式：

&ltkbd&gt键盘输入&lt/kbd&gt

&ltvar&gt 元素用于表示变量名，通常会用斜体显示。以下是 &ltvar&gt 元素的基本格式：

&ltvar&gt变量名&lt/var&gt

删除线和替代文本

&ltdel&gt 元素用于表示文档中删除的内容。以下是 &ltdel&gt 元素的基本格式：

&ltdel cite="来源" datetime="删除时间"&gt删除的内容&lt/del&gt
&ltp&gt这个内容已于 &ltdel datetime="2024-07-30T14:00"&gt删除&lt/del&gt。&lt/p&gt
常用属性:
	1. cite: 提供删除内容的来源 URL。
	2. datetime: 定义删除的时间。

&ltins&gt 元素用于表示已插入的文本。以下是 &ltins&gt 元素的基本格式：

&ltins datetime="插入日期时间"&gt插入文本&lt/ins&gt
常用属性:
	1. datetime: 定义文本插入的日期和时间。

&ltstrike&gt 元素用于表示文本的删除线效果。它已被弃用，建议使用 CSS text-decoration: line-through; 替代。以下是 &ltstrike&gt 元素的基本格式：

&ltstrike&gt删除线文本&lt/strike&gt

定义和说明:

&ltdfn&gt 元素用于标识一个定义的术语。以下是 &ltdfn&gt 元素的基本格式：

&ltdfn&gt术语&lt/dfn&gt

&ltabbr&gt 元素用于定义缩写或首字母缩略词，并且可以提供一个完整的描述。基本格式如下：
&ltabbr title="完整描述"&gt缩写&lt/abbr&gt

&ltacronym&gt 元素在 HTML5 中已被弃用，但了解它的格式和用法仍然有助于理解旧的 HTML 代码。以下是 &ltacronym&gt 元素的基本格式：

&ltacronym title="完整描述"&gt缩写&lt/acronym&gt

与 &ltabbr&gt 类似，&ltacronym&gt 元素的 title 属性用于提供缩写的完整描述。

	II. 结构性元素

文档结构:

&lthtml&gt 元素是文档的根元素。以下是 &lthtml&gt 元素的基本格式：

&lt!DOCTYPE html&gt
&lthtml lang="语言代码"&gt
    &lthead&gt
        &ltmeta charset="UTF-8"&gt
        &lttitle&gt文档标题&lt/title&gt
    &lt/head&gt
    &ltbody&gt
        内容
    &lt/body&gt
&lt/html&gt
常用属性:
	1. lang: 定义文档的语言（例如 en 表示英语，zh 表示中文）。

&lthead&gt 元素包含文档的元数据和链接资源。以下是 &lthead&gt 元素的基本格式：

&lthead&gt
    &ltmeta charset="UTF-8"&gt
    &lttitle&gt文档标题&lt/title&gt
    &ltlink rel="stylesheet" href="styles.css"&gt
    &ltscript src="script.js"&gt&lt/script&gt
&lt/head&gt

&ltbody&gt 元素定义文档的主体内容。以下是 &ltbody&gt 元素的基本格式：

&ltbody&gt
    页面内容
&lt/body&gt

&ltheader&gt 元素用于定义文档或部分的头部。以下是 &ltheader&gt 元素的基本格式：

&ltheader&gt
    页头内容
&lt/header&gt

&ltfooter&gt 元素用于定义文档或部分的页脚。以下是 &ltfooter&gt 元素的基本格式：

&ltfooter&gt
    页脚内容
&lt/footer&gt

&ltmain&gt 元素用于定义文档的主要内容区域。以下是 &ltmain&gt 元素的基本格式：

&ltmain&gt
    主要内容
&lt/main&gt

&lth1&gt 元素用于定义文档中的最高级别标题。以下是 &lth1&gt 元素的基本格式：

&lth1&gt标题内容&lt/h1&gt

&ltp&gt 元素用于定义段落。以下是 &ltp&gt 元素的基本格式：

&ltp&gt段落内容&lt/p&gt

&ltsection&gt 元素用于定义文档中的节或区域，通常包含标题和内容。以下是 &ltsection&gt 元素的基本格式：

&ltsection&gt
    &lth2&gt节标题&lt/h2&gt
    &ltp&gt节内容&lt/p&gt
&lt/section&gt

&ltarticle&gt 元素用于表示文档、页面、应用或网站中的独立结构，其内容应具有独立的意义。这个元素适合用来表示诸如博客文章、新闻报道、用户评论、论坛帖子等内容。以下是 &ltarticle&gt 元素的基本格式和一些使用示例：

&ltarticle&gt
    内容
&lt/article&gt

&ltmenu&gt 元素用于定义菜单列表，通常用于菜单项。以下是 &ltmenu&gt 元素的基本格式：

&ltmenu&gt
    &ltli&gt菜单项 1&lt/li&gt
    &ltli&gt菜单项 2&lt/li&gt
&lt/menu&gt

&ltaside&gt 元素用于表示页面内容之外的部分，比如侧栏、广告、引用的侧栏内容等。这个元素的内容通常是与周围内容相关的补充信息，但如果被移除，仍不会影响周围内容的主体结构。以下是 &ltaside&gt 元素的基本格式和一些使用示例：

&ltaside&gt
    内容
&lt/aside&gt

&lthgroup&gt 元素用于将一组标题（&lth1&gt 至 &lth6&gt）组合在一起，这个元素已被弃用。以下是 &lthgroup&gt 元素的基本格式：

&lthgroup&gt
    &lth1&gt主要标题&lt/h1&gt
    &lth2&gt副标题&lt/h2&gt
&lt/hgroup&gt

容器和分区:

&ltdiv&gt HTML 元素是流式内容的通用容器。它对内容或布局没有影响。除非以某种方式使用 CSS 对其进行样式设置（例如，直接应用样式，或者对其父元素应用某种布局模型，否则它对内容或布局没有影响。以下是 &ltdiv&gt 元素的基本格式：
&ltdiv&gt
    内容
&lt/div&gt

&ltspan&gt 元素用于定义内联区域，可以用于样式化或脚本化文本。以下是 &ltspan&gt 元素的基本格式：

&ltspan&gt内联内容&lt/span&gt

&ltform&gt 元素用于定义一个用户提交数据的表单。以下是 &ltform&gt 元素的基本格式：

&ltform action="提交地址" method="提交方法" enctype="编码类型"&gt
    表单控件
&lt/form&gt
常用属性:
	1. action: 定义表单数据提交到的 URL。
	2. method: 定义提交表单的 HTTP 方法，通常为 GET 或 POST。
	3. enctype: 定义表单数据的编码类型（例如 application/x-www-form-urlencoded、multipart/form-data、text/plain）。

&ltfieldset&gt 元素用于将表单中的一组控件进行分组，并通常与 &ltlegend&gt 元素结合使用，以提供描述。以下是 &ltfieldset&gt 元素的基本格式：

&ltfieldset&gt
    &ltlegend&gt组标题&lt/legend&gt
    表单控件
&lt/fieldset&gt

&ltlegend&gt 元素用于为 &ltfieldset&gt 元素提供标题。以下是 &ltlegend&gt 元素的基本格式：

&ltfieldset&gt
    &ltlegend&gt组标题&lt/legend&gt
    表单控件
&lt/fieldset&gt

&ltdl&gt
（或 HTML 描述列表元素）是一个包含术语定义以及描述的列表，通常用于展示词汇表或者元数据 (键 - 值对列表)。以下是 &ltdl&gt 元素的基本格式：

&ltdl&gt
    &ltdt&gt术语&lt/dt&gt
    &ltdd&gt术语的定义&lt/dd&gt
&lt/dl&gt

&ltdt&gt 元素用于定义定义列表（&ltdl&gt）中的术语。以下是 &ltdt&gt 元素的基本格式：

&ltdl&gt
    &ltdt&gt术语&lt/dt&gt
    &ltdd&gt术语的定义&lt/dd&gt
&lt/dl&gt

&ltdd&gt 元素用于定义定义列表（&ltdl&gt）中每个定义的描述。以下是 &ltdd&gt 元素的基本格式：

&ltdl&gt
    &ltdt&gt术语&lt/dt&gt
      &ltdd&gt术语的定义&lt/dd&gt
&lt/dl&gt

&ltul&gt 元素用于定义无序列表。以下是 &ltul&gt 元素的基本格式：

&ltul&gt
    &ltli&gt列表项 1&lt/li&gt
    &ltli&gt列表项 2&lt/li&gt
&lt/ul&gt

&ltol&gt 元素用于定义有序列表。以下是 &ltol&gt 元素的基本格式：

&ltol&gt
    &ltli&gt列表项 1&lt/li&gt
    &ltli&gt列表项 2&lt/li&gt
&lt/ol&gt

&ltli&gt 元素用于定义列表项，通常与 &ltul&gt 或 &ltol&gt 元素结合使用。以下是 &ltli&gt 元素的基本格式：

&ltul&gt
    &ltli&gt列表项 1&lt/li&gt
    &ltli&gt列表项 2&lt/li&gt
&lt/ul&gt

&lttable&gt 元素用于定义表格。以下是 &lttable&gt 元素的基本格式：
&lttable border="1"&gt
    &lttr&gt
        &ltth&gt姓名&lt/th&gt
        &ltth&gt年龄&lt/th&gt
    &lt/tr&gt
    &lttr&gt
        &lttd&gt张三&lt/td&gt
        &lttd&gt25&lt/td&gt
    &lt/tr&gt
&lt/table&gt

&ltthead&gt 元素用于定义表格的表头部分。以下是 &ltthead&gt 元素的基本格式：

&lttable&gt
    &ltthead&gt
        &lttr&gt
            &ltth&gt表头1&lt/th&gt
            &ltth&gt表头2&lt/th&gt
        &lt/tr&gt
    &lt/thead&gt
    &lttbody&gt
        &lttr&gt
            &lttd&gt数据1&lt/td&gt
            &lttd&gt数据2&lt/td&gt
        &lt/tr&gt
    &lt/tbody&gt
&lt/table&gt

&lttbody&gt 元素用于在表格中定义表格主体部分。以下是 &lttbody&gt 元素的基本格式：

&lttable&gt
    &ltthead&gt
        &lttr&gt
            &ltth&gt表头1&lt/th&gt
            &ltth&gt表头2&lt/th&gt
        &lt/tr&gt
    &lt/thead&gt
    &lttbody&gt
        &lttr&gt
            &lttd&gt数据1&lt/td&gt
            &lttd&gt数据2&lt/td&gt
        &lt/tr&gt
    &lt/tbody&gt
    &lttfoot&gt
        &lttr&gt
            &lttd&gt页脚1&lt/td&gt
            &lttd&gt页脚2&lt/td&gt
        &lt/tr&gt
    &lt/tfoot&gt
&lt/table&gt

&lttfoot&gt 元素用于定义表格的页脚部分。以下是 &lttfoot&gt 元素的基本格式：

&lttable&gt
    &ltthead&gt
        &lttr&gt
            &ltth&gt表头1&lt/th&gt
            &ltth&gt表头2&lt/th&gt
        &lt/tr&gt
    &lt/thead&gt
    &lttbody&gt
        &lttr&gt
            &lttd&gt数据1&lt/td&gt
            &lttd&gt数据2&lt/td&gt
        &lt/tr&gt
    &lt/tbody&gt
    &lttfoot&gt
        &lttr&gt
            &lttd&gt页脚1&lt/td&gt
            &lttd&gt页脚2&lt/td&gt
        &lt/tr&gt
    &lt/tfoot&gt
&lt/table&gt
&ltth&gt 元素用于定义表格的表头单元格。以下是 &ltth&gt 元素的基本格式：

&lttr&gt
    &ltth&gt表头数据&lt/th&gt
&lt/tr&gt
常用属性:
	· colspan: 定义表头单元格跨越的列数。
	· rowspan: 定义表头单元格跨越的行数。

&lttr&gt 元素用于定义表格中的行。以下是 &lttr&gt 元素的基本格式：

&lttr&gt
    &lttd&gt单元格数据&lt/td&gt
&lt/tr&gt

&lttd&gt 元素用于在表格中定义单元格数据。以下是 &lttd&gt 元素的基本格式：

&lttr&gt
    &lttd&gt单元格数据&lt/td&gt
&lt/tr&gt
常用属性:
	· &lttd&gt 元素可以使用所有全局属性，例如 class、id、style 等。
	· colspan: 定义单元格跨越的列数。
	· rowspan: 定义单元格跨越的行数。

&ltcaption&gt 元素用于为 &lttable&gt 表格添加标题。以下是 &ltcaption&gt 元素的基本格式：

&lttable&gt
    &ltcaption&gt表格标题&lt/caption&gt
    &lt!-- 表格内容 --&gt
&lt/table&gt

&ltcolgroup&gt 元素用于定义表格中一组列的属性。以下是 &ltcolgroup&gt 元素的基本格式：

&ltcolgroup&gt
    &ltcol span="列数" style="样式"&gt
    &lt!-- 更多 &ltcol&gt 元素 --&gt
&lt/colgroup&gt

&ltcol&gt 元素用于定义表格中 &ltcolgroup&gt 元素中的列的属性。以下是 &ltcol&gt 元素的基本格式：

&ltcol span="列数" style="样式"&gt
常用属性:
	1. span: 定义该列覆盖的列数。
	2. style: 定义列的样式（如背景色、宽度等）。

	III. 超链接和导航

链接:

&lta&gt 元素（锚点元素）用于创建超链接。它的基本格式如下：

&lta href="URL"&gt链接文本&lt/a&gt
&lta href="mailto:example@example.com"&gt发送电子邮件&lt/a&gt

这里是 &lta&gt 元素的一些常用属性及其作用：
	1. href: 指定链接的目标 URL。例如，href="https://www.example.com"。
	2. target: 指定在何处打开链接。常用值包括：
			· _self（默认值，在同一框架中打开）
			· _blank（在新窗口或新标签页中打开）
			· _parent（在父框架中打开）
			· _top（在整个窗口中打开）
	3. title: 为链接提供额外的信息，当用户悬停在链接上时会显示此信息。
	4. rel: 指定当前文档与被链接文档之间的关系。例如，rel="noopener noreferrer" 用于安全地在新窗口中打开链接。
	5. download: 提示浏览器下载链接目标而不是导航到它。可以指定下载文件的名称。

&ltlink&gt 元素用于链接外部资源，通常用于定义文档的样式表。以下是 &ltlink&gt 元素的基本格式：

&ltlink rel="关系" href="资源路径" type="类型" media="媒介"&gt
常用属性:
	1. rel: 定义与链接资源的关系（例如 stylesheet）。
	2. href: 定义链接资源的 URL。
	3. type: 定义资源的 MIME 类型（通常用于样式表）。
	4. media: 定义样式表应用的媒介（例如 screen、print）。

&ltnav&gt 元素用于定义文档中的导航链接区域，通常包含链接到不同部分的菜单或链接。以下是 &ltnav&gt 元素的基本格式：

&ltnav&gt
    &ltul&gt
        &ltli&gt&lta href="链接1"&gt链接文本1&lt/a&gt&lt/li&gt
        &ltli&gt&lta href="链接2"&gt链接文本2&lt/a&gt&lt/li&gt
        &ltli&gt&lta href="链接3"&gt链接文本3&lt/a&gt&lt/li&gt
    &lt/ul&gt
&lt/nav&gt
常用属性:
	· &ltnav&gt 元素可以使用所有全局属性，例如 class、id、style 等。
	· &lta&gt 元素的常用属性包括 href、target 和 title。
	· &ltul&gt 元素用于创建无序列表。
	· &ltli&gt 元素用于定义列表项。
	· &ltnav&gt: 表示导航区域，用于包含导航链接。
	· &ltul&gt: 定义无序列表，通常用于容纳导航链接。
	· &ltli&gt: 列表项，用于定义导航链接项。
	· &lta&gt: 链接，用于定义点击后跳转的目标。

&ltmap&gt 元素用于定义图像映射区域的集合。以下是 &ltmap&gt 元素的基本格式：

&ltmap name="地图名称"&gt
    区域定义
&lt/map&gt

&ltmap name="example-map"&gt
    &ltarea shape="rect" coords="34,44,270,350" href="https://www.example.com" alt="Example Link"&gt
&lt/map&gt
&ltimg src="image.jpg" usemap="#example-map" alt="示例图像"&gt

常用属性:
	1. name: 定义图像映射的名称，用于在 &ltimg&gt 元素中引用。

&ltarea&gt 元素用于在图像映射（image map）中定义可点击的区域。它通常与 &ltmap&gt 元素结合使用。以下是 &ltarea&gt 元素的基本格式和一些常用属性：

&ltarea shape="区域形状" coords="坐标" href="链接" alt="替代文本"&gt
常用属性
	1. shape: 定义区域的形状。可选值包括：
			o rect（矩形）
			o circle（圆形）
			o poly（多边形）
			o default（图像的全部区域）
	2. coords: 定义区域的坐标，根据 shape 属性的不同，格式会有所变化。
			o 对于 rect，格式为 x1,y1,x2,y2。
			o 对于 circle，格式为 x,y,r（中心点的 x 和 y 坐标及半径）。
			o 对于 poly，格式为 x1,y1,x2,y2,...,xn,yn（每个顶点的 x 和 y 坐标）。
	3. href: 定义点击区域时导航到的 URL。
	4. alt: 提供区域的替代文本。
	5. target: 指定在何处打开链接（类似于 &lta&gt 元素的 target 属性）。
	6. title: 为区域提供额外的信息，当用户悬停在区域上时会显示此信息。
示例
	1. 矩形区域：

&ltmap name="example-map"&gt
    &ltarea shape="rect" coords="34,44,270,350" href="https://www.example.com" alt="Example Link"&gt
&lt/map&gt
&ltimg src="image.jpg" usemap="#example-map" alt="Example Image"&gt

	IV. 嵌入内容

多媒体:

&ltaudio&gt 元素用于嵌入音频内容，允许在网页上播放音频文件。以下是 &ltaudio&gt 元素的基本格式和一些常用属性：

&ltaudio controls autoplay loop muted preload="预加载行为"&gt
    &ltsource src="音频文件路径" type="音频类型"&gt
    Your browser does not support the audio element.
&lt/audio&gt
常用属性
	1. controls: 启用音频播放器控件（如播放、暂停、音量等）。
	2. autoplay: 页面加载时自动播放音频。
	3. loop: 播放完毕后自动重新开始。
	4. muted: 静音音频。
	5. preload: 指定音频的预加载行为。可选值包括：
			o auto: 浏览器应该预加载整个音频文件。
			o metadata: 浏览器仅预加载音频的元数据（如时长）。
			o none: 浏览器不预加载音频文件。

&ltvideo&gt 元素用于嵌入视频。以下是 &ltvideo&gt 元素的基本格式：

&ltvideo src="视频路径" controls width="宽度" height="高度"&gt
    &ltsource src="视频路径" type="视频类型"&gt
    您的浏览器不支持视频标签。
&lt/video&gt
常用属性:
	1. src: 定义视频的 URL。
	2. controls: 如果存在，显示视频控件（如播放、暂停按钮）。
	3. width: 定义视频的宽度。
	4. height: 定义视频的高度。
	5. autoplay: 如果存在，视频会自动播放。
	6. loop: 如果存在，视频播放结束后会循环播放。
	7. muted: 如果存在，视频会静音播放。
示例:
	1. 基本使用：



&ltvideo controls width="640" height="360"&gt
    &ltsource src="video.mp4" type="video/mp4"&gt
    &ltsource src="video.webm" type="video/webm"&gt
    您的浏览器不支持视频标签。
&lt/video&gt

&ltpicture&gt 元素用于提供不同版本的图像以适应不同的设备和屏幕尺寸。以下是 &ltpicture&gt 元素的基本格式：

&ltpicture&gt
    &ltsource srcset="图片路径" media="媒体查询"&gt
    &ltimg src="默认图片路径" alt="替代文本"&gt
&lt/picture&gt
常用属性:
	1. srcset: 定义不同分辨率或尺寸的图像 URL。
	2. media: 定义与之匹配的媒体查询。
	3. alt: 提供图像的替代文本。

&ltsource&gt 元素用于为 &ltaudio&gt 和 &ltvideo&gt 元素指定多个资源。以下是 &ltsource&gt 元素的基本格式：

&ltsource src="资源路径" type="媒体类型"&gt
常用属性:
	1. src: 定义媒体资源的 URL。
type: 定义资源的 MIME 类型。

&lttrack&gt 元素用于为 &ltvideo&gt 和 &ltaudio&gt 元素提供文本轨道，例如字幕。以下是 &lttrack&gt 元素的基本格式：
常用属性:
	1. src: 定义轨道文件的 URL。
	2. kind: 定义轨道的类型。可能的值包括 subtitles（字幕）、captions（隐藏字幕）、descriptions（音频描述）、chapters（章节） 和 metadata（元数据）。
	3. srclang: 定义轨道的语言（使用语言代码，例如 en、zh）。
	4. label: 提供轨道的标签，这通常用于显示在用户界面中。
示例:
	1. 基本使用：



&ltvideo controls&gt
    &ltsource src="video.mp4" type="video/mp4"&gt
    &lttrack src="subtitles-en.vtt" kind="subtitles" srclang="en" label="English"&gt
    &lttrack src="subtitles-zh.vtt" kind="subtitles" srclang="zh" label="Chinese"&gt
    您的浏览器不支持视频标签。
&lt/video&gt

&ltimg&gt 元素用于在页面中嵌入图像。以下是 &ltimg&gt 元素的基本格式：

&ltimg src="图像路径" alt="替代文本" width="宽度" height="高度"&gt
常用属性:
	1. src: 定义图像的 URL。
	2. alt: 提供图像的替代文本。
	· Referrer/CORS 控制，保证安全与隐私：详见 crossorigin 和 referrerpolicy 属性。
	· 使用 width 和 height 设置图像的固有尺寸（intrinsic size）：这将设置图像应占用的空间，以确保图像被加载之前页面的布局是稳定的。
	3. width: 定义图像的宽度（像素）。
	4. height: 定义图像的高度（像素）。

&ltfigure&gt 元素用于包含图像、图表、插图等，并与 &ltfigcaption&gt 元素结合使用以提供说明。以下是 &ltfigure&gt 元素的基本格式：

&ltfigure&gt
    &ltimg src="图片路径" alt="图片描述"&gt
    &ltfigcaption&gt图像说明&lt/figcaption&gt
&lt/figure&gt

&ltfigcaption&gt 元素用于为 &ltfigure&gt 元素提供标题或说明。以下是 &ltfigcaption&gt 元素的基本格式：

&ltfigure&gt
    &ltimg src="图片路径" alt="图片描述"&gt
    &ltfigcaption&gt图像说明&lt/figcaption&gt
&lt/figure&gt

&ltobject&gt 元素用于嵌入外部对象，如图像、视频、音频或其他文档。以下是 &ltobject&gt 元素的基本格式：

&ltobject data="对象路径" type="类型" width="宽度" height="高度"&gt
    替代内容
&lt/object&gt
常用属性:
archive 已弃用
	用来指名对象资源列表的以空格分隔的 URI 列表。
border 已弃用
	元素周围的边框的宽度，单位为像素。
classid 已弃用
	对象实现的 URI，可以同时与 data 属性使用，或者使用 data 属性替代。
codebase 已弃用
	解析 classid，data 或者 archive 中定义的相对路径的根路径，如果没有定义，默认为当前文档的 base URI。
codetype 已弃用
	classid 定义的 data 的内容类型。
data
	一个合法的 URL 作为资源的地址，需要为 data 和 type 中至少一个设置值。
declare 已弃用
	取值为布尔的属性可以设置这个元素为仅声明的格式。对象必须被随后的 &ltobject&gt 元素实例化。在 HTML5 中，完整的重复 &ltobject&gt 元素，可以重用元素。
form
	对象元素关联的 form 元素（属于的 form）。取值必须是同一文档下的一个 &ltform&gt 元素的 ID。
height
	资源显示的高度，单位是 CSS 像素。
name
	浏览上下文名称（HTML5），或者控件名称（HTML 4）。
standby 已弃用
	对象的实现和数据加载过程中，浏览器可以显示的信息。
tabindex 已弃用
	当前元素在文档 Tab 导航中的顺序。
type
	data 指定的资源的 MIME 类型，需要为 data 和 type 中至少一个设置值。
usemap
	指向一个 &ltmap&gt 元素的 hash-name；格式为‘#’加 map 元素 name 元素的值。
width
	资源显示的宽度，单位是 CSS 像素。

&ltembed&gt 元素用于嵌入外部资源（如视频、音频、交互式内容等）。以下是 &ltembed&gt 元素的基本格式：

&ltembed src="资源路径" type="资源类型" width="宽度" height="高度"&gt
&ltembed src="example.pdf" type="application/pdf" width="600" height="400"&gt
常用属性:
	1. src: 定义嵌入资源的 URL。
	2. type: 定义资源的 MIME 类型。
	3. width: 定义嵌入内容的宽度（像素）。
	4. height: 定义嵌入内容的高度（像素）。

&ltiframe&gt 元素用于在当前文档中嵌入另一个文档。以下是 &ltiframe&gt 元素的基本格式：

&ltiframe src="子文档路径" width="宽度" height="高度" frameborder="边框" allowfullscreen&gt&lt/iframe&gt
常用属性:
	1. src: 定义嵌入文档的 URL。
	2. width: 定义嵌入文档的宽度（像素）。
	3. height: 定义嵌入文档的高度（像素）。
	4. frameborder: 定义是否显示边框（在 HTML5 中已废弃，使用 CSS 代替）。
	5. allowfullscreen: 允许全屏模式。

画布和图形:

&ltcanvas&gt 元素用于绘制图形。以下是 &ltcanvas&gt 元素的基本格式：

&ltcanvas width="宽度" height="高度"&gt&lt/canvas&gt
常用属性:
	1. width: 定义画布的宽度（像素）。
	2. height: 定义画布的高度（像素）。

	V. 表单控件

表单元素:

&ltinput&gt 元素用于创建各种类型的用户交互控件。以下是 &ltinput&gt 元素的基本格式：

&ltinput type="类型" name="名称" value="值" placeholder="占位符" maxlength="最大长度"&gt
常用属性:
	1. type: 定义输入控件的类型（例如 text、password、submit）。
	2. name: 定义控件的名称，表单提交时作为标识符。
	3. value: 定义控件的默认值。
	4. placeholder: 提供控件的占位符文本。
	5. maxlength: 定义输入的最大字符长度。

&lttextarea&gt 元素用于定义多行文本输入区域。以下是 &lttextarea&gt 元素的基本格式：

&lttextarea name="textarea名称" rows="行数" cols="列数"&gt默认文本&lt/textarea&gt
常用属性:
	1. name: 定义文本区域的名称，用于表单提交。
	2. rows: 定义文本区域的行数。
	3. cols: 定义文本区域的列数。
	4. placeholder: 提供文本区域的占位符文本。
	5. readonly: 如果存在，文本区域将为只读。
	6. disabled: 如果存在，文本区域将禁用。
示例:
	1. 基本使用：

&lttextarea name="message" rows="4" cols="50" placeholder="输入您的消息......"&gt&lt/textarea&gt

&ltprogress&gt 元素用于显示任务的进度。以下是 &ltprogress&gt 元素的基本格式：

&ltprogress value="当前值" max="最大值"&gt&lt/progress&gt
常用属性:
	1. value: 定义当前的进度值。
	2. max: 定义进度的最大值。

&ltbutton&gt 元素用于创建按钮。以下是 &ltbutton&gt 元素的基本格式：

&ltbutton type="button" name="buttonName" value="buttonValue"&gt按钮文本&lt/button&gt
常用属性:
	1. type: 定义按钮的类型。可选值包括：
			o button：普通按钮。
			o submit：提交按钮。
			o reset：重置按钮。
	2. name: 定义按钮的名称。
	3. value: 定义按钮的值。
	4. disabled: 禁用按钮。

&ltselect&gt 元素用于定义下拉列表。以下是 &ltselect&gt 元素的基本格式：

&ltselect name="选择名称"&gt
    &ltoption value="值1"&gt选项 1&lt/option&gt
    &ltoption value="值2"&gt选项 2&lt/option&gt
&lt/select&gt
常用属性:
	1. name: 定义下拉列表的名称，用于表单提交。
	2. size: 定义下拉列表中显示的选项数（多选模式下使用）。

&ltoption&gt 元素用于定义 &ltselect&gt 元素中的选项。以下是 &ltoption&gt 元素的基本格式：

&ltoption value="值" selected&gt选项文本&lt/option&gt
常用属性:
	1. value: 定义选项的值。
	2. selected: 如果存在，则表示选项为默认选择项。

&ltoptgroup&gt 元素用于将 &ltselect&gt 元素中的选项分组。以下是 &ltoptgroup&gt 元素的基本格式：

&ltselect&gt
    &ltoptgroup label="分组标签"&gt
        &ltoption value="值1"&gt选项 1&lt/option&gt
        &ltoption value="值2"&gt选项 2&lt/option&gt
    &lt/optgroup&gt
&lt/select&gt
常用属性:
	1. label: 定义分组的标签。

&ltlabel&gt 元素用于为表单控件提供标签。以下是 &ltlabel&gt 元素的基本格式：

&ltlabel for="控件ID"&gt标签文本&lt/label&gt
常用属性:
	1. for: 指定与之关联的表单控件的 ID。

&ltfieldset&gt 元素用于将表单中的一组控件进行分组，并通常与 &ltlegend&gt 元素结合使用，以提供描述。以下是 &ltfieldset&gt 元素的基本格式：

&ltfieldset&gt
    &ltlegend&gt组标题&lt/legend&gt
    表单控件
&lt/fieldset&gt

&ltlegend&gt 元素用于为 &ltfieldset&gt 元素提供标题。以下是 &ltlegend&gt 元素的基本格式：

&ltfieldset&gt
    &ltlegend&gt组标题&lt/legend&gt
    表单控件
&lt/fieldset&gt

&ltoutput&gt 元素用于表示计算或用户操作的结果。以下是 &ltoutput&gt 元素的基本格式：

&ltoutput for="计算对象" name="名称"&gt结果&lt/output&gt
常用属性:
	1. for: 定义生成结果的计算对象。
	2. name: 定义结果的名称。

&ltdatalist&gt 元素用于定义一个预定义选项列表，用于 &ltinput&gt 元素的自动完成。以下是 &ltdatalist&gt 元素的基本格式：

&ltinput list="dataListId"&gt
&ltdatalist id="dataListId"&gt
    &ltoption value="选项1"&gt
    &ltoption value="选项2"&gt
    &ltoption value="选项3"&gt
&lt/datalist&gt

&ltmeter&gt 元素用于表示度量数据，通常用于显示一个有限范围内的值。以下是 &ltmeter&gt 元素的基本格式：

&ltmeter value="当前值" min="最小值" max="最大值" low="低值" high="高值" optimum="最佳值"&gt&lt/meter&gt

&ltmeter value="70" min="0" max="100" low="30" high="80" optimum="50"&gt&lt/meter&gt
常用属性:
	1. value: 定义当前的度量值。
	2. min: 定义值的最小范围。
	3. max: 定义值的最大范围。
	4. low: 定义低范围值。
	5. high: 定义高范围值。
	6. optimum: 定义最佳值。

	VI. 布局和样式

布局:

&ltbr&gt 元素用于在文本中插入换行符

&lthr&gt 元素用于在文档中插入水平线

&ltwbr&gt 元素用于建议浏览器在某个位置换行。以下是 &ltwbr&gt 元素的基本格式：

长文本&ltwbr&gt可能在此处换行
常用属性:
	· &ltwbr&gt 元素没有特定属性，仅作为换行建议。

&ltpre&gt 元素用于表示预格式化的文本，保留文本中的空白和换行。以下是 &ltpre&gt 元素的基本格式：

&ltpre&gt预格式化文本&lt/pre&gt

&ltstyle&gt 元素用于在文档中嵌入 CSS 样式。以下是 &ltstyle&gt 元素的基本格式：

&ltstyle&gt
    /* CSS 规则 */
&lt/style&gt

&lttemplate&gt 元素用于定义模板内容，该内容不会被渲染，直到通过 JavaScript 动态插入到文档中。以下是 &lttemplate&gt 元素的基本格式：

&lttemplate&gt
    &lt!-- 模板内容 --&gt
&lt/template&gt

&ltcenter&gt 元素用于将文本或其他元素居中显示。该元素已弃用，建议使用 CSS 进行样式设置。以下是 &ltcenter&gt 元素的基本格式：

&ltcenter&gt居中文本&lt/center&gt

实验性和废弃:

&ltfencedframe&gt 元素是一个实验性元素，用于嵌入子文档。以下是 &ltfencedframe&gt 元素的基本格式：

&ltfencedframe src="子文档路径"&gt&lt/fencedframe&gt
常用属性:
	1. src: 定义子文档的 URL。

&ltportal&gt 元素是实验性的，用于创建与其他文档或资源进行交互的框架。以下是 &ltportal&gt 元素的基本格式：

&ltportal src="资源路径"&gt&lt/portal&gt
常用属性:
	1. src: 定义要嵌入的资源或文档的 URL。

&ltdir&gt 元素用于定义目录列表，该元素已弃用。以下是 &ltdir&gt 元素的基本格式：

&ltdir&gt
    &ltli&gt目录项1&lt/li&gt
    &ltli&gt目录项2&lt/li&gt
&lt/dir&gt

&ltFont&gt 元素（&ltfont&gt）定义了该内容的字体大小、顏色与表现。元素已弃用
color 已弃用
这个属性使用颜色名称或是十六进制的 #RRGGBB 格式，来设置文字的颜色。

&ltnoframes&gt 元素用于为不支持 &ltframeset&gt 的浏览器提供备用内容。它已被弃用，建议使用现代技术替代。以下是 &ltnoframes&gt 元素的基本格式：

&ltnoframes&gt备用内容&lt/noframes&gt

&ltnoembed&gt 元素用于提供在不支持 &ltembed&gt 元素的浏览器中显示的替代内容。它已被弃用，建议使用其他现代技术。以下是 &ltnoembed&gt 元素的基本格式：

&ltnoembed&gt替代内容&lt/noembed&gt

&ltnobr&gt 元素用于防止文本自动换行。它已被弃用，建议使用 CSS 进行控制。以下是 &ltnobr&gt 元素的基本格式：

&ltnobr&gt不换行的文本&lt/nobr&gt

&ltxmp&gt 元素用于表示原始文本内容。该元素已被弃用，建议使用 &ltpre&gt 元素代替。以下是 &ltxmp&gt 元素的基本格式：

&ltxmp&gt
    原始文本内容
&lt/xmp&gt

&ltplaintext&gt 元素用于显示原始文本内容，忽略任何 HTML 标签。它已被弃用，建议使用 &ltpre&gt 元素代替。以下是 &ltplaintext&gt 元素的基本格式：

&ltplaintext&gt
    原始文本内容
&lt/plaintext&gt

&ltsearch&gt 元素实验性，尚未被广泛接受。以下是 &ltsearch&gt 元素的基本格式：

&ltsearch&gt
    &lt!-- 搜索内容 --&gt
&lt/search&gt
常用属性:
	· &ltsearch&gt 元素可以使用所有全局属性，例如 class、id、style 等。

&ltruby&gt 元素用于标记 Ruby 注释，用于对东亚字符的注释。以下是 &ltruby&gt 元素的基本格式：

&ltruby&gt
    字符&ltrt&gt注释&lt/rt&gt
&lt/ruby&gt

&ltrt&gt 元素用于提供 Ruby 注释文本，通常与 &ltruby&gt 元素一起使用。以下是 &ltrt&gt 元素的基本格式：

&ltruby&gt
    &ltrb&gt基本文本&lt/rb&gt
    &ltrt&gt注释文本&lt/rt&gt
&lt/ruby&gt

&ltrtc&gt 元素用于提供 Ruby 注释的文本修饰。它已被弃用，建议使用现代技术。以下是 &ltrtc&gt 元素的基本格式：

&ltruby&gt
    &ltrb&gt基本文本&lt/rb&gt
    &ltrtc&gt修饰文本&lt/rtc&gt
    &ltrt&gt注释文本&lt/rt&gt
&lt/ruby&gt

&ltrb&gt 元素用于表示 Ruby 注释的基本文本。它已被弃用，建议使用现代技术。以下是 &ltrb&gt 元素的基本格式：

&ltruby&gt
    &ltrb&gt基本文本&lt/rb&gt
    &ltrt&gt注释文本&lt/rt&gt
&lt/ruby&gt

&ltrp&gt 元素用于为那些不能使用 &ltruby&gt 元素展示 ruby 注解的浏览器，提供随后的圆括号。Ruby 注解用于展示东亚文字的发音，例如使用日语罗马音和汉语拼音的文字。 &ltrp&gt 元素用于不支持 &ltruby&gt 元素的情况。 &ltrp&gt 的内容提供了应该展示的东西，通常是圆括号，以便表示 ruby 注解的存在。以下是 &ltrp&gt 元素的基本格式：

&ltruby&gt
    漢字&ltrp&gt(&lt/rp&gt&ltrt&gtかんじ&lt/rt&gt&ltrp&gt)&lt/rp&gt
&lt/ruby&gt

	VII. 特殊和杂项

数据和元数据:

&ltmeta&gt 元素用于提供关于文档的元数据（如字符集、作者、描述等）。以下是 &ltmeta&gt 元素的基本格式：

&ltmeta name="名称" content="内容" charset="字符集"&gt
常用属性:
charset: 定义文档的字符编码。
&ltmeta charset="UTF-8"&gt
 name: 定义元数据的名称（用于常规元数据）。
	· description: 定义页面的简短描述。

&ltmeta name="description" content="这是一个示例页面"&gt
	· keywords: 定义页面的关键字。

&ltmeta name="keywords" content="HTML, CSS, JavaScript"&gt
	· author: 定义页面的作者。

&ltmeta name="author" content="John Doe"&gt
	· viewport: 定义视口设置，以便在移动设备上优化显示。

&ltmeta name="viewport" content="width=device-width, initial-scale=1.0"&gt
  http-equiv: 提供 HTTP 头部的信息（通常用于缓存控制和刷新）。
	· refresh: 刷新页面的时间间隔和新 URL。

&ltmeta http-equiv="refresh" content="30;url=https://www.example.com"&gt
	· cache-control: 定义缓存控制策略。

&ltmeta http-equiv="cache-control" content="no-cache, no-store, must-revalidate"&gt
  property: 用于 Open Graph 协议，提供社交媒体的元数据。
	· og
: 定义社交媒体分享的标题。

&ltmeta property="og:title" content="示例标题"&gt
	· og
: 定义社交媒体分享的描述。

&ltmeta property="og:description" content="示例描述"&gt
	· og
: 定义社交媒体分享的图片。

&ltmeta property="og:image" content="https://www.example.com/image.jpg"&gt
	· og: 定义社交媒体分享的 URL。

&ltmeta property="og:url" content="https://www.example.com"&gt

&ltdata&gt 元素用于关联内容与机器可读的值，以便在客户端或服务器端进行数据处理。以下是 &ltdata&gt 元素的基本格式：

&ltdata value="机器可读值"&gt显示的文本&lt/data&gt
&ltp&gt该书籍的 ISBN 号是 &ltdata value="978-3-16-148410-0"&gt978-3-16-148410-0&lt/data&gt。&lt/p&gt
常用属性:
	1. value: 定义与内容关联的机器可读值。

&lttime&gt 元素用于表示时间或日期。以下是 &lttime&gt 元素的基本格式：

&lttime datetime="日期时间"&gt显示时间&lt/time&gt
常用属性:
	1. datetime: 定义时间或日期的机器可读格式（例如，2024-08-01T12:00）。

&lttitle&gt 元素用于定义文档的标题，显示在浏览器的标题栏或标签页中。以下是 &lttitle&gt 元素的基本格式：

&lttitle&gt文档标题&lt/title&gt

&ltaddress&gt 元素用于定义联系信息，通常用于作者或拥有者的联系信息。以下是 &ltaddress&gt 元素的基本格式和一些使用示例：
&ltaddress&gt
    联系信息内容
&lt/address&gt

&ltslot&gt 元素是——Web 组件技术套件的一部分——它是一个在 web 组件内部的占位符，你可以使用自己的标记来填充该占位符，从而创建单独的 DOM 树并将其一起呈现。。以下是 &ltslot&gt 元素的基本格式：

&ltslot name="slot名称"&gt&lt/slot&gt
常用属性:
	1. name: 定义插槽的名称，用于匹配 &ltslot&gt 元素中的内容。

&ltparam&gt 元素用于为 &ltobject&gt 元素定义参数。它已被弃用，建议使用其他现代技术。以下是 &ltparam&gt 元素的基本格式：

&ltobject data="对象数据" type="对象类型"&gt
    &ltparam name="参数名" value="参数值"&gt
&lt/object&gt

文档和脚本:

&ltscript&gt 元素用于定义客户端脚本，如 JavaScript。以下是 &ltscript&gt 元素的基本格式：

&ltscript src="脚本路径" type="类型"&gt
    // JavaScript 代码
&lt/script&gt
内联脚本：

&ltscript&gt
    console.log('Hello, World!');
&lt/script&gt
外部脚本：

&ltscript src="script.js"&gt&lt/script&gt

常用属性:
	1. src: 定义外部脚本的 URL。
	2. type: 定义脚本的 MIME 类型（默认是 text/javascript）。
	3. async: 如果存在，脚本会异步加载。
	4. defer: 如果存在，脚本会在文档解析完成后执行。

&ltnoscript&gt 元素用于定义在浏览器不支持脚本（如 JavaScript）时显示的内容。以下是 &ltnoscript&gt 元素的基本格式：

&ltnoscript&gt
    不支持脚本时显示的内容
&lt/noscript&gt

&lttemplate&gt 元素用于定义模板内容，该内容不会被渲染，直到通过 JavaScript 动态插入到文档中。以下是 &lttemplate&gt 元素的基本格式：

&lttemplate&gt
    &lt!-- 模板内容 --&gt
&lt/template&gt

	VIII.  其它

标记和说明:

&ltbdi&gt 元素用于隔离一段文本的双向格式，以确保其在不同语言方向的文本中正确显示。它通常用于在包含多种语言文本的网页中保持文本的方向性。以下是 &ltbdi&gt 元素的基本格式和常用属性：

&ltbdi&gt需要隔离的文本&lt/bdi&gt

&ltbdo&gt 元素用于控制文本的双向排版方向。它允许你覆盖文本的默认方向。以下是 &ltbdo&gt 元素的基本格式和常用属性：

&ltbdo dir="ltr"&gt文本内容&lt/bdo&gt
常用属性:
	1. dir: 定义文本的方向。可选值包括：
			o ltr：从左到右（默认值）。
			o rtl：从右到左。

&ltdialog&gt 元素用于表示对话框或模态窗口。以下是 &ltdialog&gt 元素的基本格式：

&ltdialog open&gt
    对话框内容
    &ltbutton onclick="this.closest('dialog').close()"&gt关闭&lt/button&gt
&lt/dialog&gt

&ltbutton onclick="document.getElementById('myDialog').showModal()"&gt打开对话框&lt/button&gt
&ltdialog id="myDialog"&gt
   &ltp&gt这是一个对话框示例。&lt/p&gt
   &ltbutton onclick="document.getElementById('myDialog').close()"&gt关闭&lt/button&gt &lt/dialog&gt
常用属性:
	1. open: 定义对话框是否打开。

&ltsummary&gt 元素用于定义 &ltdetails&gt 元素的可见标题。以下是 &ltsummary&gt 元素的基本格式：

&ltdetails&gt
    &ltsummary&gt标题&lt/summary&gt
    内容
&lt/details&gt

&ltdetails&gt 元素用于提供用户可以展开和折叠的详细信息。以下是 &ltdetails&gt 元素的基本格式：

&ltdetails&gt
    &ltsummary&gt总结或标题&lt/summary&gt
    详细内容
&lt/details&gt

	IX. 不推荐或实验性

废弃元素:

&ltacronym&gt 元素在 HTML5 中已被弃用，但了解它的格式和用法仍然有助于理解旧的 HTML 代码。以下是 &ltacronym&gt 元素的基本格式：

&ltacronym title="完整描述"&gt缩写&lt/acronym&gt
与 &ltabbr&gt 类似，&ltacronym&gt 元素的 title 属性用于提供缩写的完整描述。

&ltbig&gt 元素用于将文本显示得比周围的文本大。该元素已弃用，建议使用 CSS 进行样式设置。以下是 &ltbig&gt 元素的基本格式：

&ltbig&gt较大的文本&lt/big&gt

&ltcenter&gt 元素用于将文本或其他元素居中显示。该元素已弃用，建议使用 CSS 进行样式设置。以下是 &ltcenter&gt 元素的基本格式：

&ltcenter&gt居中文本&lt/center&gt

&ltmarquee&gt 元素用于创建滚动文本或图像效果。它已被弃用，不推荐使用。以下是 &ltmarquee&gt 元素的基本格式：

&ltmarquee&gt滚动文本或图像&lt/marquee&gt
常用属性:
	1. direction: 定义滚动的方向。可能的值包括 left、right、up、down。
	2. behavior: 定义滚动行为。可能的值包括 scroll（滚动）、slide（滑动）、alternate（交替）。
	3. scrollamount: 定义每次滚动的像素数。
	4. scrolldelay: 定义滚动之间的延迟时间，以毫秒为单位。

&ltnobr&gt 元素用于防止文本自动换行。它已被弃用，建议使用 CSS 进行控制。以下是 &ltnobr&gt 元素的基本格式：

&ltnobr&gt不换行的文本&lt/nobr&gt

&ltstrike&gt 元素用于表示文本的删除线效果。它已被弃用，建议使用 CSS text-decoration: line-through; 替代。以下是 &ltstrike&gt 元素的基本格式：

&ltstrike&gt删除线文本&lt/strike&gt

&lttt&gt 元素用于表示等宽字体（typewriter text），它已被弃用，建议使用 CSS 来实现相同的效果。以下是 &lttt&gt 元素的基本格式：

&lttt&gt等宽字体文本&lt/tt&gt

&ltframeset&gt 元素用于定义一个包含多个 &ltframe&gt 元素的框架集。它已被弃用，建议使用 &ltiframe&gt 元素代替。以下是 &ltframeset&gt 元素的基本格式：

&ltframeset rows="行数" cols="列数"&gt
    &ltframe src="框架内容的URL" name="框架名称" scrolling="滚动" noresize&gt
    &lt!-- 更多 frame 元素 --&gt
&lt/frameset&gt
常用属性:
	1. rows: 定义框架集的行数和高度。格式为 高度,高度,...，例如 50%, 50%。
	2. cols: 定义框架集的列数和宽度。格式为 宽度,宽度,...，例如 25%, 75%。
	3. border: 设定框架的边框宽度（HTML 4.01 及以前版本使用，不再推荐）。


 </code></pre>
