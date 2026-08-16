# Awesome Python 资源大全中文版 with stars

[awesome-python](https://github.com/vinta/awesome-python) ⭐ 314,320 | 🐛 16 | 🌐 Python | 📅 2026-08-16 是 vinta 发起维护的 Python 资源列表，内容包括：Web 框架、网络爬虫、网络内容提取、模板引擎、数据库、数据可视化、图片处理、文本处理、自然语言处理、机器学习、日志、代码分析等。由「开源前哨」和「Python开发者」微信公号团队维护更新。

### 本项目的参与者

* 维护者：[「开源前哨」和「Python开发者」微信公号团队](https://github-1255921244.cos.ap-nanjing.myqcloud.com/awesome-python-cn.png)。「开源前哨」会定期在知乎专栏分享最新、有趣和热门的开源项目，每个项目都有详细的介绍和示例。传送门：<https://www.zhihu.com/column/c_1317124962785062912>

* 贡献者：[唐尤华](https://github.com/orgs/jobbole/people/tangyouhua)、[qtvspa](https://github.com/qtvspa)、[艾凌风](https://github.com/hanxiaomax)、Namco、[Daetalus](https://github.com/Daetalus)、黄利民、atupal、rainbow、[木头lbj](https://github.com/mutoulbj)、beyondwu、[cissoid](https://github.com/cissoid)、[李广胜](https://github.com/liguangsheng)、[polyval](https://github.com/polyval)、冰斌、赵叶宇、л stalgic、硕恩、[strongit](https://github.com/strongit)、yuukilp、[chenjiandongx](https://github.com/chenjiandongx)、[autopenguin](https://github.com/autopenguin)、[visonforcoding](https://github.com/visonforcoding)、[Super赛亚人](https://github.com/No-96)、[Since-future](https://github.com/Since-future)、[knktc](https://github.com/knktc)、[zhucebuliaopx](https://github.com/zhucebuliaopx)、[wardseptember](https://github.com/wardseptember)、[vmp65l3](https://github.com/vmp65l3)、[JiaxingZhao](https://github.com/JiaxingZhao)、[zhtyyx](https://github.com/zhtyyx)、[Lynn Cao](https://github.com/caolincn)、[River](https://github.com/lihuafengzi)、You

注：名单不分排名，不定期补充更新

## 资源列表

### 环境管理

管理 Python 版本和环境的工具

* [pyenv](https://github.com/yyuu/pyenv) ⭐ 45,016 | 🐛 56 | 🌐 Shell | 📅 2026-08-16：简单的 Python 版本管理工具。
* [p](https://github.com/qw3rtman/p) ⭐ 775 | 🐛 25 | 🌐 Shell | 📅 2019-11-01：非常简单的交互式 Python 版本管理工具。
* [Vex](https://github.com/sashahart/vex) ⭐ 370 | 🐛 10 | 🌐 Python | 📅 2021-10-30：可以在虚拟环境中执行命令。
* [virtualenv](https://pypi.python.org/pypi/virtualenv)：创建独立 Python 环境的工具。
* [virtualenvwrapper](https://pypi.python.org/pypi/virtualenvwrapper)：virtualenv 的一组扩展。
* [buildout](http://www.buildout.org/en/latest)：在隔离环境初始化后使用声明性配置管理。

### 包管理

管理包和依赖的工具。

* [pipenv](https://github.com/pypa/pipenv) ⭐ 25,043 | 🐛 19 | 🌐 Python | 📅 2026-08-15：Python 官方推荐的新一代包管理工具。
* [pip-tools](https://github.com/nvie/pip-tools) ⭐ 8,009 | 🐛 175 | 🌐 Python | 📅 2026-08-15：保证 Python 包依赖关系更新的一组工具。
* [conda](https://github.com/conda/conda/) ⭐ 7,485 | 🐛 681 | 🌐 Python | 📅 2026-08-15：跨平台的 Python 二进制包管理工具。
* [pip](https://pip.pypa.io/)：Python 包和依赖关系管理工具。
* [PyPI](https://pypi.org/)：Python 正式的第三方包软件存储库。
* [poetry](https://poetry.eustace.io)：可完全取代 setup.py 的包管理工具。
* [Curdling](http://clarete.li/curdling/)：管理 Python 包的命令行工具。
* [wheel](http://pythonwheels.com/)：Python 分发的新标准，意在取代 eggs。

### 包仓库

本地 PyPI 仓库服务和代理。

* [warehouse](https://github.com/pypa/warehouse) ⭐ 4,129 | 🐛 575 | 🌐 Python | 📅 2026-08-15：下一代 PyPI。
* [localshop](https://github.com/mvantellingen/localshop) ⭐ 400 | 🐛 47 | 🌐 Less | 📅 2023-04-21：本地 PyPI 服务（自定义包并且自动对 PyPI 镜像）。
* [bandersnatch](https://bitbucket.org/pypa/bandersnatch)：PyPA 提供的 PyPI 镜像工具。
* [devpi](http://doc.devpi.net/)：PyPI 服务和打包/测试/分发工具。

### 分发

打包为可执行文件以便分发。

* [PyInstaller](https://github.com/pyinstaller/pyinstaller) ⭐ 13,069 | 🐛 289 | 🌐 Python | 📅 2026-08-16：将 Python 程序转换成独立的执行文件（跨平台）。
* [pyarmor](https://github.com/dashingsoft/pyarmor) ⭐ 5,167 | 🐛 12 | 🌐 Python | 📅 2026-08-14：一个用于加密 python 脚本的工具，也可以将加密后的脚本绑定到固件上，或设置已加密脚本的有效期。
* [shiv](https://github.com/linkedin/shiv) ⭐ 1,945 | 🐛 63 | 🌐 Python | 📅 2026-05-22：一个命令行工具，可用于构建完全独立的 zip 应用（PEP 441 所描述的那种），同时包含了所有的依赖项。
* [cx\_Freeze](https://cx-freeze.readthedocs.io/en/latest/index.html)：将python程序转换为带有一个动态链接库的可执行文件。
* [dh-virtualenv](http://dh-virtualenv.readthedocs.org/)：构建并将 virtualenv 虚拟环境作为一个 Debian 包来发布。
* [Nuitka](http://nuitka.net/)：将脚本、模块、包编译成可执行文件或扩展模块。
* [py2app](http://pythonhosted.org/py2app/)：将 Python 脚本变为独立软件包（Mac OS X）。
* [py2exe](http://www.py2exe.org/)：将 Python 脚本变为独立软件包（Windows）。
* [pynsist](http://pynsist.readthedocs.org/)：一个用来创建 Windows 安装程序的工具，可以在安装程序中打包 Python 本身。

### 构建工具

将源码编译成软件。

* [PlatformIO](https://github.com/platformio/platformio) ⭐ 9,405 | 🐛 317 | 🌐 Python | 📅 2026-08-11：多平台命令行构建工具。
* [PyBuilder](https://github.com/pybuilder/pybuilder) ⭐ 2,033 | 🐛 103 | 🌐 Python | 📅 2026-04-02：纯 Python 实现的持续化构建工具。
* [buildout](http://www.buildout.org/)：一个构建系统，从多个组件来创建，组装和部署应用。
* [BitBake](http://www.yoctoproject.org/docs/1.6/bitbake-user-manual/bitbake-user-manual.html)：针对嵌入式 Linux 的类似 make 的构建工具。
* [fabricate](https://code.google.com/archive/p/fabricate)：对任何语言自动找到依赖关系的构建工具。
* [SCons](http://www.scons.org/)：软件构建工具。

### 交互式解析器

交互式 Python 解析器。

* [IPython](https://github.com/ipython/ipython) ⭐ 16,770 | 🐛 1,294 | 🌐 Python | 📅 2026-08-07：功能丰富的工具，非常有效的使用交互式 Python。
* [ptpython](https://github.com/jonathanslenders/ptpython) ⭐ 5,446 | 🐛 264 | 🌐 Python | 📅 2025-11-21：高级交互式 Python 解析器， 构建于 [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) ⭐ 10,554 | 🐛 705 | 🌐 Python | 📅 2026-07-26 之上。
* [bpython](https://github.com/bpython/bpython) ⭐ 2,771 | 🐛 149 | 🌐 Python | 📅 2026-07-20：界面丰富的 Python 解析器。
* [Jupyter Notebook (IPython)](https://jupyter.org)：一个能够让你最大限度地以交互式方式使用 Python 的丰富工具包。
  * [awesome-jupyter](https://github.com/markusschanta/awesome-jupyter) ⭐ 4,661 | 🐛 16 | 📅 2026-08-15

### 文件

文件管理和 MIME（多用途的网际邮件扩充协议）类型检测。

* [watchdog](https://github.com/gorakhargosh/watchdog) ⭐ 7,395 | 🐛 242 | 🌐 Python | 📅 2026-08-15：管理文件系统事件的 API 和 shell 工具。
* [aiofiles](https://github.com/Tinche/aiofiles) ⭐ 3,253 | 🐛 54 | 🌐 Python | 📅 2026-07-18：基于 asyncio，提供文件异步操作。
* [python-magic](https://github.com/ahupp/python-magic) ⭐ 2,915 | 🐛 27 | 🌐 Python | 📅 2026-07-20：文件类型检测的第三方库 libmagic 的 Python 接口。
* [PyFilesystem2](https://github.com/pyfilesystem/pyfilesystem2) ⭐ 2,105 | 🐛 117 | 🌐 Python | 📅 2025-05-17：Python 的文件系统抽象层。
* [path.py](https://github.com/jaraco/path.py) ⭐ 1,124 | 🐛 7 | 🌐 Python | 📅 2026-04-13：对 os.path 进行封装的模块。
* [Unipath](https://github.com/mikeorr/Unipath) ⭐ 510 | 🐛 9 | 🌐 Python | 📅 2022-01-11：用面向对象的方式操作文件和目录。
* [imghdr](https://docs.python.org/2/library/imghdr.html)：（Python 标准库）检测图片类型。
* [mimetypes](https://docs.python.org/2/library/mimetypes.html)：（Python 标准库）将文件名映射为 MIME 类型。
* [pathlib](https://pathlib.readthedocs.org/en/pep428/)：（Python3.4+ 标准库）跨平台的、面向对象的路径操作库。

### 日期和时间

操作日期和时间的类库。

* [arrow](https://github.com/crsmithdev/arrow) ⭐ 9,049 | 🐛 186 | 🌐 Python | 📅 2026-06-22：更好的 Python 日期时间操作类库。
* [pendulum](https://github.com/sdispater/pendulum) ⭐ 6,670 | 🐛 265 | 🌐 Python | 📅 2026-07-06：一个比 arrow 更具有明确的，可预测的行为的时间操作库。
* [maya](https://github.com/kennethreitz/maya) ⭐ 3,411 | 🐛 21 | 🌐 Python | 📅 2024-07-19：人性化的时间处理库。
* [dateutil](https://github.com/dateutil/dateutil) ⭐ 2,632 | 🐛 474 | 🌐 Python | 📅 2026-05-19：Python 标准包 [datetime](https://docs.python.org/3/library/datetime.html) 的扩展。
* [delorean](https://github.com/myusuf3/delorean/) ⭐ 1,822 | 🐛 0 | 🌐 Python | 📅 2026-08-01：解决 Python 中有关日期处理的棘手问题的库。
* [moment](https://github.com/zachwill/moment) ⭐ 741 | 🐛 6 | 🌐 Python | 📅 2023-04-24：一个处理日期/时间的库，灵感来自 [Moment.js](http://momentjs.com/)。
* [Chronyk](https://github.com/KoffeinFlummi/Chronyk) ⭐ 341 | 🐛 8 | 🌐 Python | 📅 2019-12-08：Python 3 的类库，用于解析手写格式的时间和日期。
* [when.py](https://github.com/dirn/When.py) ⚠️ Archived：提供用户友好的函数来帮助用户进行常用的日期和时间操作。
* [PyTime](https://github.com/shinux/PyTime) ⭐ 156 | 🐛 0 | 🌐 Python | 📅 2022-11-05：一个简单易用的 Python 模块，用于通过字符串来操作日期/时间。
* [dateutil](https://pypi.python.org/pypi/python-dateutil)：Python datetime 模块的扩展。
* [pytz](https://launchpad.net/pytz)：现代以及历史版本的世界时区定义。将时区数据库引入 Python。
* [pytz](https://launchpad.net/pytz)：支持跨平台时区计算，并将 [tz database](https://en.wikipedia.org/wiki/Tz_database) 引入 Python。

### 文本处理

用于解析和操作文本的库。

* 通用
  * [flashtext](https://github.com/vi3k6i5/flashtext) ⭐ 5,714 | 🐛 70 | 🌐 Python | 📅 2025-04-13：一个高效的文本查找替换库。
  * [pypinyin](https://github.com/mozillazg/python-pinyin) ⭐ 5,353 | 🐛 45 | 🌐 Python | 📅 2026-07-20：汉字拼音转换工具 Python 版。
  * [ftfy](https://github.com/LuminosoInsight/python-ftfy) ⭐ 4,056 | 🐛 25 | 🌐 Python | 📅 2024-10-30：让 Unicode 文本更完整更连贯。
  * [thefuzz](https://github.com/seatgeek/thefuzz) ⭐ 3,648 | 🐛 47 | 🌐 Python | 📅 2025-03-03：模糊字符串匹配。
  * [textdistance](https://github.com/orsinium/textdistance) ⭐ 3,538 | 🐛 10 | 🌐 Python | 📅 2025-04-18：支持 30 多种算法来计算序列之间的距离。
  * [chardet](https://github.com/chardet/chardet) ⭐ 2,657 | 🐛 0 | 🌐 Python | 📅 2026-08-16：字符编码检测器，兼容 Python 2 和 Python 3。
  * [shortuuid](https://github.com/stochastic-technologies/shortuuid) ⭐ 2,196 | 🐛 0 | 🌐 Python | 📅 2026-06-20：一个生成器库，用以生成简洁的，明白的，URL 安全的 UUID。
  * [simplejson](https://github.com/simplejson/simplejson) ⭐ 1,712 | 🐛 13 | 🌐 Python | 📅 2026-08-06：Python 的 JSON 编码、解码器。
  * [pyfiglet](https://github.com/pwaller/pyfiglet) ⭐ 1,580 | 🐛 2 | 🌐 Python | 📅 2026-08-02：figlet 的 Python 实现。
  * [Levenshtein](https://github.com/ztane/python-Levenshtein/) ⭐ 1,278 | 🐛 56 | 🌐 C | 📅 2021-08-11：快速计算编辑距离以及字符串的相似度。
  * [xpinyin](https://github.com/lxneng/xpinyin) ⭐ 831 | 🐛 9 | 🌐 Python | 📅 2025-06-02：一个用于把汉字转换为拼音的库。
  * [pangu.py](https://github.com/vinta/pangu.py) ⭐ 278 | 🐛 0 | 🌐 Python | 📅 2026-08-11：在中日韩语字符和数字字母之间添加空格。
  * [uniout](https://github.com/moskytw/uniout) ⭐ 157 | 🐛 2 | 🌐 Python | 📅 2022-04-05：打印可读的字符，而不是转义的字符串。
  * [difflib](https://docs.python.org/2/library/difflib.html)：(Python 标准库)帮助我们进行差异化比较。
  * [unidecode](https://pypi.python.org/pypi/Unidecode)：Unicode 文本的 ASCII 转换形式 。
* Slug 化
  * [python-slugify](https://github.com/un33k/python-slugify) ⭐ 1,622 | 🐛 17 | 🌐 Python | 📅 2026-04-27：Python slug 化库，可以把 unicode 转化为 ASCII。
  * [awesome-slugify](https://github.com/dimka665/awesome-slugify) ⭐ 491 | 🐛 18 | 🌐 Python | 📅 2020-04-17：一个 Python slug 化库，可以保持 Unicode。
  * [unicode-slugify](https://github.com/mozilla/unicode-slugify) ⭐ 325 | 🐛 11 | 🌐 Python | 📅 2024-01-27：一个 slug 工具，可以生成 unicode slugs ,需要依赖 Django 。
* 解析器
  * [phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) ⭐ 3,766 | 🐛 11 | 🌐 Python | 📅 2026-08-14：解析，格式化，储存，验证电话号码。
  * [python-phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) ⭐ 3,766 | 🐛 11 | 🌐 Python | 📅 2026-08-14：解析，格式化，存储，校验国际电话号码。
  * [python-user-agents](https://github.com/selwin/python-user-agents) ⭐ 1,514 | 🐛 47 | 🌐 Python | 📅 2023-02-16：浏览器 user agent 解析器。
  * [python-nameparser](https://github.com/derek73/python-nameparser) ⭐ 714 | 🐛 32 | 🌐 Python | 📅 2026-08-16：把一个人名分解为几个独立的部分。
  * [PLY](http://www.dabeaz.com/ply/)：lex 和 yacc 解析工具的 Python 实现。
  * [Pygments](http://pygments.org/)：通用语法高亮工具。
  * [pyparsing](http://pyparsing.wikispaces.com/)：生成通用解析器的框架。
  * [sqlparse](https://sqlparse.readthedocs.org/en/latest/)：一个无验证的 SQL 解析器。

### 特殊文本格式处理

一些用来解析和操作特殊文本格式的库。

* 通用
  * [tablib](https://github.com/kennethreitz/tablib) ⭐ 63 | 🐛 0 | 📅 2022-04-12：一个用来处理中表格数据的模块。
* Office
  * [python-docx](https://github.com/python-openxml/python-docx) ⭐ 5,694 | 🐛 512 | 🌐 Python | 📅 2026-08-01：读取，查询以及修改 Microsoft Word 2007/2008 docx 文件。
  * [python-pptx](https://github.com/scanny/python-pptx) ⭐ 3,492 | 🐛 534 | 🌐 Python | 📅 2024-08-07：可用于创建和修改 ppt 文件的 Python 库。
  * [unoconv](https://github.com/dagwieers/unoconv) ⚠️ Archived：在 LibreOffice/OpenOffice 支持的任意文件格式之间进行转换。
  * [docxtpl](https://github.com/elapouya/python-docx-template) ⭐ 2,692 | 🐛 175 | 🌐 Python | 📅 2026-07-07：通过 jinja2 模版编辑 docx 文档。
  * [pyexcel](https://github.com/pyexcel/pyexcel) ⭐ 1,293 | 🐛 11 | 🌐 Python | 📅 2026-07-01：一个提供统一 API，用来读写，操作 Excel 文件的库。
  * [xlwt](https://github.com/python-excel/xlwt) ⚠️ Archived / [xlrd](https://github.com/python-excel/xlrd) ⭐ 2,207 | 🐛 3 | 🌐 Python | 📅 2026-07-15：读写 Excel 文件的数据和格式信息。
  * [Marmir](https://github.com/brianray/mm) ⭐ 172 | 🐛 8 | 🌐 Python | 📅 2018-08-14：把输入的 Python 数据结构转换为电子表单。
  * [openpyxl](https://openpyxl.readthedocs.org/en/latest/)：一个用来读写 Excel 2010 xlsx/xlsm/xltx/xltm 文件的库。
  * [relatorio](http://relatorio.tryton.org/)：模板化 OpenDocument 文件。
  * [XlsxWriter](https://xlsxwriter.readthedocs.org/en/latest/)：一个用于创建 Excel .xlsx 文件的 Python 模块。
  * [xlwings](http://xlwings.org/)：一个使得在 Excel 中方便调用 Python 的库（反之亦然），基于 BSD 协议。
* PDF
  * [PyPDF2](https://github.com/mstamy2/PyPDF2) ⭐ 10,161 | 🐛 136 | 🌐 Python | 📅 2026-08-16：一个可以分割，合并和转换 PDF 页面的库。
  * [PDFMiner](https://github.com/euske/pdfminer) ⚠️ Archived：一个用于从 PDF 文档中抽取信息的工具。
  * [ReportLab](http://www.reportlab.com/opensource/)：快速创建富文本 PDF 文档。
* Markdown
  * [Python-Markdown](https://github.com/waylan/Python-Markdown) ⭐ 4,232 | 🐛 30 | 🌐 Python | 📅 2026-08-08：John Gruber’s Markdown 的 Python 版实现。
  * [Mistune](https://github.com/lepture/mistune) ⭐ 3,065 | 🐛 20 | 🌐 Python | 📅 2026-08-14：快速并且功能齐全的纯 Python 实现的 Markdown 解析器。
  * [Python-Markdown2](https://github.com/trentm/python-markdown2) ⭐ 2,820 | 🐛 93 | 🌐 Python | 📅 2026-08-01：纯 Python 实现的 Markdown 解析器，比 Python-Markdown 更快，更准确，可扩展。
* YAML
  * [PyYAML](http://pyyaml.org/)：Python 版本的 YAML 解析器。
* CSV
  * [csvkit](https://github.com/wireservice/csvkit) ⭐ 6,409 | 🐛 39 | 🌐 Python | 📅 2026-08-03：用于转换和操作 CSV 的工具。
* Archive
  * [unp](https://github.com/mitsuhiko/unp) ⭐ 455 | 🐛 12 | 🌐 Python | 📅 2017-05-17：一个用来方便解包归档文件的命令行工具。

### 自然语言处理

用来处理人类语言的库。

* [funNLP](https://github.com/fighting41love/funNLP) ⭐ 82,501 | 🐛 53 | 🌐 Python | 📅 2024-05-10：中文自然语言处理的工具和数据集。
* [jieba](https://github.com/fxsjy/jieba) ⭐ 35,118 | 🐛 700 | 🌐 Python | 📅 2024-08-21：中文分词工具。
* [gensim](https://github.com/piskvorky/gensim) ⭐ 16,480 | 🐛 436 | 🌐 Python | 📅 2025-11-01：人性化的话题建模库。
* [Stanza](https://github.com/stanfordnlp/stanza) ⭐ 7,861 | 🐛 93 | 🌐 Python | 📅 2026-08-15：斯坦福 NLP 集团的官方 Python 库，支持 60 多种语言。
* [pkuseg-python](https://github.com/lancopku/pkuseg-python) ⭐ 6,711 | 🐛 135 | 🌐 Python | 📅 2022-11-05：一个支持对不同领域进行中文分词的工具箱。
* [SnowNLP](https://github.com/isnowfy/snownlp) ⭐ 6,631 | 🐛 44 | 🌐 Python | 📅 2020-01-19：一个用来处理中文文本的库。
* [pytext](https://github.com/facebookresearch/pytext) ⚠️ Archived：基于 PyTouch 的自然语言模型框架。
* [langid.py](https://github.com/saffsd/langid.py) ⭐ 2,463 | 🐛 28 | 🌐 Python | 📅 2020-01-01：独立的语言识别系统。
* [polyglot](https://github.com/aboSamoor/polyglot) ⭐ 2,362 | 🐛 170 | 🌐 Python | 📅 2023-11-10：支持数百种语言的自然语言处理管道。
* [PyTorch-NLP](https://github.com/PetrochukM/PyTorch-NLP) ⚠️ Archived：一个支持快速深度学习 NLP 原型研究的工具包。
* [thulac](https://github.com/thunlp/THULAC-Python) ⭐ 2,086 | 🐛 87 | 🌐 Python | 📅 2022-01-31：清华大学自然语言处理与社会人文计算实验室研制推出的一套中文词法分析工具包。
* [TextGrocery](https://github.com/2shou/TextGrocery) ⭐ 683 | 🐛 14 | 🌐 C++ | 📅 2021-06-09：一简单高效的短文本分类工具，基于 LibLinear 和 Jieba。
* [NLTK](http://www.nltk.org/)：一个先进的平台，用以构建处理人类语言数据的 Python 程序。
* [Pattern](http://www.clips.ua.ac.be/pattern)：Python 网络信息挖掘模块。
* [TextBlob](http://textblob.readthedocs.org/en/latest/)：为进行普通自然语言处理任务提供一致的 API。
* [spacy](https://spacy.io/)：Python 和 Cython 中用于工业级自然语言处理的库。

### 文档

用以生成项目文档的库。

* [readthedocs](https://github.com/rtfd/readthedocs.org/) ⭐ 8,375 | 🐛 387 | 🌐 Python | 📅 2026-08-16：一个基于 Sphinx/MkDocs 的在线文档托管系统，对开源项目免费开放使用。
* [pdoc](https://github.com/BurntSushi/pdoc) ⭐ 2,511 | 🐛 70 | 🌐 Python | 📅 2026-07-01：一个可以替换 Epydoc 的库，可以自动生成 Python 库的 API 文档。
* [Pycco](https://github.com/pycco-docs/pycco) ⭐ 875 | 🐛 34 | 🌐 Python | 📅 2023-06-12：文学编程（literate-programming）风格的文档生成器。
* [Sphinx](http://www.sphinx-doc.org/en/latest/)：Python 文档生成器。
  * [awesome-sphinxdoc](https://github.com/yoloseem/awesome-sphinxdoc) ⭐ 980 | 🐛 8 | 🌐 HTML | 📅 2025-10-07
* [MkDocs](http://www.mkdocs.org/)：对 Markdown 友好的文档生成器。

### 配置

用来保存和解析配置的库。

* [hydra](https://github.com/facebookresearch/hydra) ⭐ 10,603 | 🐛 109 | 🌐 Python | 📅 2026-08-16：一个优雅地配置复杂应用程序的框架。
* [python-decouple](https://github.com/henriquebastos/python-decouple) ⭐ 3,039 | 🐛 22 | 🌐 Python | 📅 2024-11-28：将设置和代码完全隔离。
* [config](https://www.red-dove.com/config-doc/)：[logging](https://docs.python.org/2/library/logging.html) 模块作者写的分级配置模块。
* [ConfigObj](http://www.voidspace.org.uk/python/configobj.html)：INI 文件解析器，带验证功能。
* [ConfigParser](https://docs.python.org/2/library/configparser.html)：(Python 标准库) INI 文件解析器。
* [profig](http://profig.readthedocs.org/en/default/)：通过多种格式进行配置，具有数值转换功能。

### 命令行工具

用于创建命令行程序的库。

* 命令行程序开发
  * [python-fire](https://github.com/google/python-fire) ⭐ 28,206 | 🐛 192 | 🌐 Python | 📅 2026-07-01：Google 出品的一个基于 Python 类的构建命令行界面的库。
  * [Gooey](https://github.com/chriskiehl/Gooey) ⭐ 21,892 | 🐛 183 | 🌐 Python | 📅 2026-03-23：一条命令，将命令行程序变成一个 GUI 程序。
  * [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) ⭐ 10,554 | 🐛 705 | 🌐 Python | 📅 2026-07-26：一个用于构建强大的交互式命令行程序的库。
  * [clint](https://github.com/kennethreitz/clint) ⚠️ Archived：Python 命令行程序工具。
  * [cement](http://builtoncement.com/)：Python 的命令行程序框架。
  * [click](http://click.pocoo.org/dev/)：一个通过组合的方式来创建精美命令行界面的包。
  * [cliff](http://docs.openstack.org/developer/cliff/)：一个用于创建命令行程序的框架，可以创建具有多层命令的命令行程序。
  * [docopt](http://docopt.org/)：Python 风格的命令行参数解析器。
  * [Pythonpy](https://github.com/Russell91/pythonpy/wiki)：在命令行中直接执行任何 Python 指令。
* 终端呈现方式
  * [rich](https://github.com/willmcgugan/rich) ⭐ 57,076 | 🐛 370 | 🌐 Python | 📅 2026-06-23：一个在终端中支持富文本和格式美化的 Python 库， 同时提供了`RichHandler`日志处理程序。
  * [tqdm](https://github.com/tqdm/tqdm) ⭐ 31,283 | 🐛 592 | 🌐 Python | 📅 2026-08-10：一个可在循环和命令行中使用的快速、可扩展的进度条。
  * [alive-progress](https://github.com/rsalmei/alive-progress) ⭐ 6,294 | 🐛 17 | 🌐 Python | 📅 2026-05-24：一款新的进度条，具有实时吞吐量信息以及非常酷的动画。
  * [asciimatics](https://github.com/peterbrittain/asciimatics) ⭐ 4,299 | 🐛 17 | 🌐 Python | 📅 2026-07-04：跨平台，全屏终端包（即鼠标/键盘输入和彩色，定位文本输出），完整的复杂动画和特殊效果的高级 API。
  * [bashplotlib](https://github.com/glamp/bashplotlib) ⭐ 1,919 | 🐛 24 | 🌐 Python | 📅 2024-06-23：在终端中进行基本绘图。
  * [colorama](https://pypi.python.org/pypi/colorama)：跨平台彩色终端文本。
* 生产力工具
  * [thefuck](https://github.com/nvbn/thefuck) ⭐ 97,713 | 🐛 454 | 🌐 Python | 📅 2024-07-19：修正你之前的命令行指令。
  * [cookiecutter](https://github.com/audreyr/cookiecutter) ⭐ 25,058 | 🐛 312 | 🌐 Python | 📅 2026-04-01：从 cookiecutters（项目模板）创建项目的一个命令行工具。
  * [aws-cli](https://github.com/aws/aws-cli) ⭐ 17,185 | 🐛 701 | 🌐 Python | 📅 2026-08-14：Amazon Web Services 的通用命令行界面。
  * [howdoi](https://github.com/gleitz/howdoi) ⭐ 10,841 | 🐛 29 | 🌐 Python | 📅 2026-04-15：通过命令行获取即时的编程问题解答。
  * [PathPicker](https://github.com/facebook/PathPicker) ⭐ 5,223 | 🐛 26 | 🌐 Python | 📅 2024-09-05：从 bash 输出中选出文件。
  * [Invoke](https://github.com/pyinvoke/invoke#readme) ⭐ 4,767 | 🐛 459 | 🌐 Python | 📅 2026-04-07：用于管理面向 shell 的子进程，同时支持将可执行的 Python 代码组织成命令行可调用的状态。
  * [tmuxp](https://github.com/tony/tmuxp) ⭐ 4,559 | 🐛 138 | 🌐 Python | 📅 2026-08-16： [tmux](https://github.com/tmux/tmux) ⭐ 48,659 | 🐛 50 | 🌐 C | 📅 2026-08-16 会话管理器。
  * [doitlive](https://github.com/sloria/doitlive) ⭐ 3,576 | 🐛 14 | 🌐 Python | 📅 2026-08-11：一个用来在终端中进行现场演示的工具。
  * [copier](https://github.com/pykong/copier) ⭐ 3,526 | 🐛 150 | 🌐 Python | 📅 2026-08-14：用于呈现项目模板的库和命令行实用程序。
  * [percol](https://github.com/mooz/percol) ⭐ 3,326 | 🐛 51 | 🌐 Python | 📅 2023-12-30：向 UNIX shell 传统管道概念中加入交互式选择功能。
  * [pyftpdlib](https://github.com/giampaolo/pyftpdlib) ⭐ 1,816 | 🐛 139 | 🌐 Python | 📅 2026-04-23：一个速度极快和可扩展的 Python FTP 服务库。
  * [try](https://github.com/timofurrer/try) ⭐ 748 | 🐛 4 | 🌐 Python | 📅 2022-05-23：一个极其简单的命令行工具，用来试用 python 库。
  * [caniusepython3](https://github.com/brettcannon/caniusepython3) ⚠️ Archived：判断是哪个项目妨碍你你移植到 Python 3。
* 高级 CLI
  * [httpie](https://github.com/jkbrzt/httpie) ⭐ 38,426 | 🐛 330 | 🌐 Python | 📅 2024-12-17：一个命令行 HTTP 客户端，cURL 的替代品，易用性更好。
  * [pgcli](https://github.com/dbcli/pgcli) ⭐ 13,351 | 🐛 37 | 🌐 Python | 📅 2026-08-03：支持自动补全和语法高亮的 Postgres 命令行工具。
  * [mycli](https://github.com/dbcli/mycli) ⭐ 11,960 | 🐛 5 | 🌐 Python | 📅 2026-08-15：支持自动补全和语法高亮的 MySQL 命令行客户端
  * [SAWS](https://github.com/donnemartin/saws) ⭐ 5,302 | 🐛 39 | 🌐 Python | 📅 2024-04-02：一个加强版的 AWS 命令行。
  * [litecli](https://github.com/dbcli/litecli) ⭐ 3,290 | 🐛 46 | 🌐 Python | 📅 2026-06-18：支持自动补全和语法高亮的 SQLite 命令行工具。
  * [iredis](https://github.com/laixintao/iredis) ⭐ 2,740 | 🐛 50 | 🌐 Python | 📅 2026-07-27：支持自动补全和高亮显示的 redis 命令行工具。
  * [kube-shell](https://github.com/cloudnativelabs/kube-shell) ⭐ 2,391 | 🐛 67 | 🌐 Python | 📅 2022-11-02：K8S 命令行集成的 shell 工具。
* Shell
  * [xonsh](https://github.com/xonsh/xonsh/) ⭐ 9,604 | 🐛 73 | 🌐 Python | 📅 2026-08-16：一种基于 python 的跨平台，面向 unix 的 shell 语言和命令提示符。

### 下载器

用来进行下载的库.

* [akshare](https://github.com/jindaxiang/akshare) ⭐ 22,068 | 🐛 0 | 🌐 Python | 📅 2026-08-13：为方便人使用而创建的金融数据接口库。
* [s3cmd](https://github.com/s3tools/s3cmd) ⭐ 4,901 | 🐛 311 | 🌐 Python | 📅 2025-10-22：一个用来管理 Amazon S3 和 CloudFront 的命令行工具。
* [s4cmd](https://github.com/bloomreach/s4cmd) ⭐ 1,395 | 🐛 117 | 🌐 Python | 📅 2024-07-21：超级 S3 命令行工具，性能更加强劲。
* [you-get](https://www.soimort.org/you-get/)：一个 YouTube/Youku/Niconico 视频下载器，使用 Python 3 编写。
* [youtube-dl](http://rg3.github.io/youtube-dl/)：一个小巧的命令行程序，用来下载 YouTube 视频。

### 图像处理

用来操作图像的库.

* [face\_recognition](https://github.com/ageitgey/face_recognition) ⭐ 56,658 | 🐛 830 | 🌐 Python | 📅 2026-06-25：简单易用的 Python 人脸识别库。
* [thumbor](https://github.com/thumbor/thumbor) ⭐ 10,510 | 🐛 20 | 🌐 Python | 📅 2026-08-16：一个小型图像服务，具有剪裁，尺寸重设和翻转功能。
* [pywal](https://github.com/dylanaraps/pywal) ⚠️ Archived：由图像生成配色方案的工具。
* [python-qrcode](https://github.com/lincolnloop/python-qrcode) ⭐ 4,929 | 🐛 53 | 🌐 Python | 📅 2026-03-25：一个纯 Python 实现的二维码生成器。
* [PyMatting](https://github.com/pymatting/pymatting) ⭐ 1,914 | 🐛 11 | 🌐 Python | 📅 2026-04-07：支持 alpha matting 的库。
* [wand](https://github.com/dahlia/wand) ⭐ 1,480 | 🐛 29 | 🌐 Python | 📅 2026-08-06：[MagickWand ](http://www.imagemagick.org/script/magick-wand.php)的 Python 绑定。MagickWand 是 ImageMagick 的 C API 。
* [Quads](https://github.com/fogleman/Quads) ⭐ 1,232 | 🐛 2 | 🌐 Python | 📅 2022-12-26：基于四叉树的计算机艺术。
* [nude.py](https://github.com/hhatto/nude.py) ⭐ 922 | 🐛 9 | 🌐 Python | 📅 2020-11-23：裸体检测。
* [pyvips](https://github.com/libvips/pyvips) ⭐ 815 | 🐛 2 | 🌐 Python | 📅 2026-07-31：低内存消耗且快速的图像处理库。
* [python-barcode](https://github.com/WhyNotHugo/python-barcode) ⭐ 656 | 🐛 58 | 🌐 Python | 📅 2026-07-27：不借助其他库在 Python 程序中生成条形码。
* [pagan](https://github.com/daboth/pagan) ⭐ 307 | 🐛 5 | 🌐 Python | 📅 2025-01-24：基于输入和哈希的复古风图标（头像）生成工具。
* [hmap](https://github.com/rossgoodwin/hmap) ⭐ 214 | 🐛 0 | 🌐 Python | 📅 2019-11-04：图像直方图映射。
* [pillow](http://pillow.readthedocs.org/en/latest/)：Pillow 是一个更加易用版的 [PIL](http://www.pythonware.com/products/pil/)。
* [imgSeek](https://sourceforge.net/projects/imgseek/)：一个使用视觉相似性搜索一组图片集合的项目。
* [pygram](https://github.com/ajkumar25/pygram)：类似 Instagram 的图像滤镜。
* [scikit-image](http://scikit-image.org/)：一个用于（科学）图像处理的 Python 库。

### OCR

光学字符识别库。

* [paddleocr](https://github.com/PaddlePaddle/PaddleOCR) ⭐ 87,743 | 🐛 229 | 🌐 Python | 📅 2026-07-22: 除光学字符识别外还引入了表格识别。
* [pytesseract](https://github.com/madmaze/pytesseract) ⭐ 6,379 | 🐛 21 | 🌐 Python | 📅 2026-07-13：[Google Tesseract OCR](https://github.com/tesseract-ocr) 的一个封装。
* [pyocr](https://gitlab.gnome.org/World/OpenPaperwork/pyocr)：Tesseract 和 Cuneiform 的一个封装。

### 音频

用来操作音频的库

* [beets](https://github.com/beetbox/beets) ⭐ 15,545 | 🐛 708 | 🌐 Python | 📅 2026-08-16：一个音乐库管理器和 [MusicBrainz](https://musicbrainz.org/) 标记器。
* [pydub](https://github.com/jiaaro/pydub) ⭐ 9,791 | 🐛 421 | 🌐 Python | 📅 2026-03-19：通过简单、简洁的高层接口来操作音频文件。
* [librosa](https://github.com/librosa/librosa) ⭐ 8,560 | 🐛 47 | 🌐 Python | 📅 2026-08-11：音频音乐分析 Python 库。
* [dejavu](https://github.com/worldveil/dejavu) ⭐ 6,786 | 🐛 132 | 🌐 Python | 📅 2024-04-22：音频指纹提取和识别。
* [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis) ⭐ 6,254 | 🐛 205 | 🌐 Python | 📅 2025-08-04：音频特征提取，分类，分段和应用。
* [matchering](https://github.com/sergree/matchering) ⭐ 2,606 | 🐛 34 | 🌐 Python | 📅 2026-07-08：用于音频母带制作的库。
* [m3u8](https://github.com/globocom/m3u8) ⭐ 2,276 | 🐛 45 | 🌐 Python | 📅 2025-01-31：一个用来解析 m3u8 文件的模块。
* [kapre](https://github.com/keunwoochoi/kapre) ⭐ 947 | 🐛 16 | 🌐 Python | 📅 2026-05-17：Keras 音频处理器。
* [tinytag](https://github.com/devsnd/tinytag) ⭐ 832 | 🐛 6 | 🌐 Python | 📅 2026-08-10：一个用来读取 MP3, OGG, FLAC 以及 Wave 文件音乐元数据的库。
* [audiolazy](https://github.com/danilobellini/audiolazy) ⭐ 715 | 🐛 14 | 🌐 Python | 📅 2022-04-30：Python 的数字信号处理包。
* [pyechonest](https://github.com/echonest/pyechonest) ⭐ 680 | 🐛 25 | 🌐 Python | 📅 2015-10-09：[Echo Nest](http://developer.echonest.com/) API 的 Python 客户端。
* [audioread](https://github.com/beetbox/audioread) ⭐ 538 | 🐛 45 | 🌐 Python | 📅 2026-04-09：交叉库 (GStreamer + Core Audio + MAD + FFmpeg) 音频解码。
* [TimeSide](https://github.com/Parisson/TimeSide) ⭐ 394 | 🐛 33 | 🌐 Python | 📅 2024-10-14：开源 web 音频处理框架。
* [django-elastic-transcoder](https://github.com/StreetVoice/django-elastic-transcoder) ⭐ 67 | 🐛 8 | 🌐 Python | 📅 2021-12-25：Django + [Amazon Elastic Transcoder](http://aws.amazon.com/elastictranscoder/)。
* [beets](http://beets.io/)：一个音乐库管理工具及 [MusicBrainz](https://musicbrainz.org/) 标签添加工具。
* [eyeD3](http://eyed3.nicfit.net/)：一个用来操作音频文件的工具，具体来讲就是包含 ID3 元信息的 MP3 文件。
* [id3reader](http://nedbatchelder.com/code/modules/id3reader.py)：一个用来读取 MP3 元数据的 Python 模块。
* [mutagen](https://bitbucket.org/lazka/mutagen)：一个用来处理音频元数据的 Python 模块。
* [talkbox](http://scikits.appspot.com/talkbox)：一个用来处理演讲/信号的 Python 库。
* [mingus](http://bspaans.github.io/python-mingus/)：一个高级音乐理论和曲谱包，支持 MIDI 文件和回放功能。

### Video

用来操作视频和 GIF 的库。

* [vidgear](https://github.com/abhiTronix/vidgear) ⭐ 3,720 | 🐛 1 | 🌐 Python | 📅 2026-05-18： 强大的多线程视频处理框架。
* [scikit-video](https://github.com/aizvorski/scikit-video) ⭐ 153 | 🐛 6 | 🌐 Python | 📅 2020-02-28：SciPy 视频处理常用程序。
* [moviepy](http://zulko.github.io/moviepy/)：一个用来进行基于脚本的视频编辑模块，适用于多种格式，包括动图 GIFs。

### 地理位置

地理编码地址以及用来处理经纬度的库。

* [geopy](https://github.com/geopy/geopy) ⭐ 4,845 | 🐛 53 | 🌐 Python | 📅 2026-07-12：Python 地址编码工具箱。
* [django-countries](https://github.com/SmileyChris/django-countries) ⭐ 1,532 | 🐛 3 | 🌐 Python | 📅 2026-06-10：一个 Django 应用程序，提供用于表格的国家选择功能，国旗图标静态文件以及模型中的国家字段。
* [GeoIP2](https://github.com/maxmind/GeoIP2-python) ⭐ 1,217 | 🐛 5 | 🌐 Python | 📅 2026-08-10：GeoIP2 Webservice 客户端与数据库 Python API。
* [geojson](https://github.com/frewsxcv/python-geojson) ⭐ 993 | 🐛 24 | 🌐 Python | 📅 2026-06-06：GeoJSON 的 Python 绑定及工具。
* [pygeoip](https://github.com/appliedsec/pygeoip) ⚠️ Archived：Python GeoIP 接口。
* [GeoIP](https://github.com/maxmind/geoip-api-python) ⚠️ Archived：MaxMind GeoIP Legacy 数据库的 Python API。
* [GeoDjango](https://docs.djangoproject.com/en/dev/ref/contrib/gis/)：世界级地理图形 web 框架。

### HTTP

使用 HTTP 的库。

* [aiohttp](https://github.com/aio-libs/aiohttp) ⭐ 16,523 | 🐛 243 | 🌐 Python | 📅 2026-08-16：基于 asyncio 的异步 HTTP 网络库。
* [httpx](https://github.com/encode/httpx) ⭐ 15,424 | 🐛 143 | 🌐 Python | 📅 2026-03-29：下一代 Python HTTP 客户端。
* [grequests](https://github.com/kennethreitz/grequests) ⭐ 4,572 | 🐛 11 | 🌐 Python | 📅 2024-08-08：requests 库 + gevent ，用于异步 HTTP 请求。
* [urllib3](https://github.com/shazow/urllib3) ⭐ 4,051 | 🐛 210 | 🌐 Python | 📅 2026-08-10：一个具有线程安全连接池，支持文件 post，清晰友好的 HTTP 库。
* [treq](https://github.com/twisted/treq) ⭐ 604 | 🐛 55 | 🌐 Python | 📅 2026-08-08：类似 requests 的 Python API 构建于 Twisted HTTP 客户端之上。
* [httplib2](https://github.com/jcgregorio/httplib2) ⭐ 380 | 🐛 15 | 🌐 Python | 📅 2019-08-21：全面的 HTTP 客户端库。
* [requests](http://docs.python-requests.org/en/latest/)：人性化的 HTTP 请求库。

### 数据库

Python 实现的数据库。

* [pickleDB](https://pythonhosted.org/pickleDB/)：一个简单，轻量级键值储存数据库。
* [PipelineDB](https://www.pipelinedb.com/)：流式 SQL 数据库。
* [TinyDB](https://github.com/msiemens/tinydb) ⭐ 7,552 | 🐛 5 | 🌐 Python | 📅 2026-08-10：一个微型的，面向文档型数据库。
* [ZODB](http://www.zodb.org/en/latest/)：一个 Python 原生对象数据库。一个键值和对象图数据库。

### 数据库驱动

用来连接和操作数据库的库。

* MySQL：[awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/) 系列
  * [PyMySQL](https://github.com/PyMySQL/PyMySQL) ⭐ 7,843 | 🐛 17 | 🌐 Python | 📅 2026-08-05：纯 Python MySQL 驱动，兼容 mysql-python。
  * ysqlclient：[mysql-python](https://github.com/PyMySQL/mysqlclient-python) ⭐ 2,531 | 🐛 4 | 🌐 Python | 📅 2026-07-26 分支，支持 Python 3。
  * [aiomysql](https://github.com/aio-libs/aiomysql) ⭐ 1,895 | 🐛 117 | 🌐 Python | 📅 2026-03-27：基于 asyncio 的异步 MySQL 数据库操作库。
  * [mysql-python](https://sourceforge.net/projects/mysql-python/)：Python 的 MySQL 数据库连接器。
  * [oursql](https://pythonhosted.org/oursql/)：一个更好的 MySQL 连接器，支持原生预编译指令和 BLOBs。
* PostgreSQL
  * [queries](https://github.com/gmr/queries) ⭐ 254 | 🐛 5 | 🌐 Python | 📅 2021-11-16：psycopg2 库的封装，用来和 PostgreSQL 进行交互。
  * [psycopg2](http://initd.org/psycopg/)：Python 中最流行的 PostgreSQL 适配器。
  * [txpostgres](http://txpostgres.readthedocs.org/en/latest/)：基于 Twisted 的异步 PostgreSQL 驱动。
* 其他关系型数据库
  * [apsw](http://rogerbinns.github.io/apsw/)：另一个 Python SQLite 封装。
  * dataset：在数据库中存储 Python 字典
  * [pymssql](http://www.pymssql.org/en/latest/)：一个简单的 Microsoft SQL Server 数据库接口。
* NoSQL 数据库
  * [redis-py](https://github.com/andymccurdy/redis-py) ⭐ 13,609 | 🐛 85 | 🌐 Python | 📅 2026-08-10：Redis 的 Python 客户端。
  * [kafka-python](https://github.com/dpkp/kafka-python) ⭐ 5,900 | 🐛 17 | 🌐 Python | 📅 2026-08-16：Apache Kafka Python 客户端。
  * [cassandra-python-driver](https://github.com/datastax/python-driver) ⭐ 1,427 | 🐛 15 | 🌐 Python | 📅 2026-07-21：Cassandra 的 Python 驱动。
  * [asyncio-redis](https://github.com/jonathanslenders/asyncio-redis) ⭐ 549 | 🐛 51 | 🌐 Python | 📅 2020-08-11：基于 asyncio 的 redis 客户端 (PEP 3156)。
  * [pycassa](https://github.com/pycassa/pycassa) ⚠️ Archived：Cassandra 的 Python Thrift 驱动。
  * [txRedis](https://github.com/deldotdr/txRedis) ⭐ 127 | 🐛 8 | 🌐 Python | 📅 2021-12-26：基于 Twisted 的 Redis 客户端。
  * [telephus](https://github.com/driftx/Telephus) ⭐ 94 | 🐛 4 | 🌐 Python | 📅 2021-12-25：基于 Twisted 的 Cassandra 客户端。
  * [HappyBase](http://happybase.readthedocs.org/en/latest/)：一个为 Apache HBase 设计的，对开发者友好的库。
  * [Plyvel](https://plyvel.readthedocs.org/en/latest/)：一个快速且功能丰富的 LevelDB 的 Python 接口。
  * [py2neo](http://py2neo.org/2.0/)：Neo4j restful 接口的 Python 封装客户端。
  * [PyMongo](https://docs.mongodb.org/ecosystem/drivers/python/)：MongoDB 的官方 Python 客户端。
* 异步客户端
  * [motor](https://github.com/mongodb/motor) ⭐ 2,526 | 🐛 0 | 🌐 Python | 📅 2026-08-10：支持 MongoDB 的异步 Python 驱动程序。

### ORM

实现对象关系映射或数据映射技术的库。

* 关系型数据库
  * [Peewee](https://github.com/coleifer/peewee) ⭐ 11,984 | 🐛 0 | 🌐 Python | 📅 2026-08-14：一个小巧，富有表现力的 ORM。
  * [dataset](https://github.com/pudo/dataset) ⭐ 4,871 | 🐛 22 | 🌐 Python | 📅 2026-07-22：在数据库中存储字典，支持 SQLite，MySQL 和 PostgreSQL。
  * [pony](https://github.com/ponyorm/pony/) ⭐ 3,820 | 🐛 359 | 🌐 Python | 📅 2026-08-10：提供面向生成器的SQL接口的ORM。
  * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy) ⭐ 3,050 | 🐛 10 | 🌐 Python | 📅 2026-06-08 系列
  * [orm](https://github.com/encode/orm) ⚠️ Archived：一个异步的 ORM。
  * [orator](https://github.com/sdispater/orator) ⚠️ Archived：Orator ORM，提供了一个简单而美观的 ActiveRecord 实现。
  * [pydal](https://github.com/web2py/pydal/) ⭐ 536 | 🐛 149 | 🌐 Python | 📅 2026-08-05：纯 Python 数据库抽象接口层。
  * [Django Models](https://docs.djangoproject.com/en/dev/topics/db/models/)：Django 的一部分。
  * [SQLAlchemy](http://www.sqlalchemy.org/)：Python SQL 工具以及对象关系映射工具。
    * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy) ⭐ 3,050 | 🐛 10 | 🌐 Python | 📅 2026-06-08
  * [PonyORM](https://ponyorm.com/)：提供面向生成器的 SQL 接口的 ORM。
  * [python-sql](https://pypi.python.org/pypi/python-sql)：编写 Python 风格的 SQL 查询。
* NoSQL 数据库
  * [PynamoDB](https://github.com/jlafon/PynamoDB) ⭐ 2,649 | 🐛 318 | 🌐 Python | 📅 2026-05-29：[Amazon DynamoDB](https://aws.amazon.com/dynamodb/) 的一个 Python 风格接口。
  * [django-mongodb-engine](https://github.com/django-nonrel/mongodb-engine) ⭐ 868 | 🐛 90 | 🌐 Python | 📅 2021-12-25：Django MongoDB 后端。
  * [redisco](https://github.com/kiddouk/redisco) ⭐ 444 | 🐛 41 | 🌐 Python | 📅 2020-01-17：一个 Python 库，提供可以持续存在在 Redis 中的简单模型和容器。
  * [hot-redis](https://github.com/stephenmcd/hot-redis) ⭐ 295 | 🐛 8 | 🌐 Python | 📅 2024-04-03：为 Redis 提供 Python 丰富的数据类型。
  * [flywheel](https://github.com/mathcamp/flywheel) ⚠️ Archived：Amazon DynamoDB 的对象映射工具。
  * [MongoEngine](http://mongoengine.org/)：一个 Python 对象文档映射工具，用于 MongoDB。
* 其他
  * [butterdb](https://github.com/Widdershin/butterdb) ⭐ 339 | 🐛 9 | 🌐 Python | 📅 2015-06-12：Google Drive 电子表格的 Python ORM。

### Web 框架

全栈 Web 框架。

* [sanic](https://github.com/channelcat/sanic/) ⭐ 18,645 | 🐛 145 | 🌐 Python | 📅 2026-07-29：基于 Python3.5+ 的异步网络框架。
* [Masonite](https://github.com/MasoniteFramework/masonite) ⭐ 2,359 | 🐛 1 | 🌐 Python | 📅 2026-06-07：以开发者为中心的现代 Python Web 框架。
* [Django](https://www.djangoproject.com/)：Python 界最流行的 web 框架。
  * [awesome-django(by wsvincent)](https://github.com/wsvincent/awesome-django) ⭐ 11,199 | 🐛 10 | 🌐 Python | 📅 2026-08-15 系列
  * [awesome-django(by shahraizali)](https://github.com/shahraizali/awesome-django) ⭐ 1,914 | 🐛 8 | 📅 2026-03-22 系列
* [Flask](http://flask.pocoo.org/)：一个 Python 微型框架。
  * [awesome-flask](https://github.com/humiaozuzu/awesome-flask) ⭐ 12,747 | 🐛 72 | 📅 2024-08-18 系列
* [Pyramid](https://pylonsproject.org/)：一个小巧，快速，接地气的开源 Python web 框架。
  * [awesome-pyramid](https://github.com/uralbash/awesome-pyramid) ⭐ 576 | 🐛 0 | 📅 2021-07-08 系列
* [Bottle](http://bottlepy.org/docs/dev/index.html)：一个快速小巧，轻量级的 WSGI 微型 web 框架。
* [CherryPy](http://www.cherrypy.org/)：一个极简的 Python web 框架，服从 HTTP/1.1 协议且具有 WSGI 线程池。
* [TurboGears](http://www.turbogears.org/)：一个可以扩展为全栈解决方案的微型框架。
* [web.py](http://webpy.org/)：一个 Python 的 web 框架，既简单，又强大。
* [web2py](http://www.web2py.com/)：一个全栈 web 框架和平台，专注于简单易用。
* [Tornado](http://www.tornadoweb.org/en/latest/)：一个 web 框架和异步网络库。
* [starlette](https://www.starlette.io/)： 一款轻量级，高性能的 ASGI 框架。

### WebSocket

Web socket 相关库。

* [channels](https://github.com/django/channels) ⭐ 6,354 | 🐛 122 | 🌐 Python | 📅 2026-08-06：开发者友好的 Django 异步工具。
* [websockets](https://github.com/aaugustin/websockets) ⭐ 5,713 | 🐛 0 | 🌐 Python | 📅 2026-08-10：一个用于构建 WebSocket 服务器和客户端的库，着重于正确性和简单性。
* [autobahn-python](https://github.com/crossbario/autobahn-python) ⭐ 2,541 | 🐛 187 | 🌐 Python | 📅 2026-07-15：适用于 Twisted 和 asyncio 的 Python WebSocket 和 WAMP。

### 权限

允许或拒绝用户访问数据或功能的库。

* [django-guardian](https://github.com/django-guardian/django-guardian) ⭐ 3,911 | 🐛 38 | 🌐 Python | 📅 2026-07-30：Django 1.2+ ，实现了单个对象权限。
* [django-rules](https://github.com/dfunckt/django-rules) ⭐ 1,978 | 🐛 41 | 🌐 Python | 📅 2025-10-11：一个小巧但是强大的应用，提供对象级别的权限管理，且不需要使用数据库。
* [Carteblanche](https://github.com/neuman/python-carteblanche/) ⭐ 39 | 🐛 5 | 🌐 Python | 📅 2015-09-02：站在用户和设计者角度开发的一个代码对齐模块，很好地处理了代码导航及权限。

### CMS

内容管理系统。

* [odoo-cms](http://www.odoo.com)：一个开源的，企业级 CMS，基于 odoo。
* [django-cms](http://www.django-cms.org/en/)：一个开源的，企业级 CMS，基于 Django。
* [djedi-cms](http://djedi-cms.org/)：一个轻量级但却非常强大的 Django CMS ，考虑到了插件，内联编辑以及性能。
* [FeinCMS](http://www.feincms.org/)：基于 Django 构建的最先进的内容管理系统之一。
* [Kotti](http://kotti.pylonsproject.org/)：一个高级的，Python 范的 web 应用框架，基于 Pyramid 构建。
* [Mezzanine](http://mezzanine.jupo.org/)：一个强大的，持续的，灵活的内容管理平台。
* [Opps](http://opps.github.io/opps/)：一个为杂志，报纸网站以及大流量门户网站设计的 CMS 平台，基于 Django。
* [Plone](https://plone.org/)：一个构建于开源应用服务器 Zope 之上的 CMS。
* [Quokka](https://quintagroup.com/cms/python/quokka)：灵活，可扩展的小型 CMS，基于 Flask 和 MongoDB。
* [Wagtail](https://wagtail.io/)：一个 Django 内容管理系统。
* [Widgy](https://wid.gy/)：最新的 CMS 框架，基于 Django。
* [indico](https://github.com/indico/indico) ⭐ 2,099 | 🐛 887 | 🌐 Python | 📅 2026-08-14：一个功能丰富的事件管理系统，由 @[CERN](https://en.wikipedia.org/wiki/CERN) 开发。

### 电子商务

用于电子商务以及支付的框架和库。

* [django-shop](https://github.com/awesto/django-shop) ⭐ 3,320 | 🐛 106 | 🌐 Python | 📅 2023-10-19：一个基于 Django 的店铺系统。
* [merchant](https://github.com/agiliq/merchant) ⭐ 1,021 | 🐛 32 | 🌐 Python | 📅 2022-07-08：一个可以接收来自多种支付平台支付的 Django 应用。
* [Cartridge](https://github.com/stephenmcd/cartridge) ⭐ 712 | 🐛 32 | 🌐 Python | 📅 2024-02-22：一个基于 Mezzanine 构建的购物车应用。
* [forex-python](https://github.com/MicroPyramid/forex-python) ⭐ 709 | 🐛 23 | 🌐 Python | 📅 2025-05-22：外汇汇率，比特币价格指数和货币换算。
* [alipay](https://github.com/lxneng/alipay) ⭐ 326 | 🐛 0 | 🌐 Python | 📅 2017-11-22：非官方的 Python 支付宝 API。
* [money](https://github.com/carlospalol/money) ⭐ 237 | 🐛 12 | 🌐 Python | 📅 2023-04-08：一个货币类库。带有可选的 CLDR 后端本地化格式，提供可扩展的货币兑换解决方案。
* [python-currencies](https://github.com/Alir3z4/python-currencies) ⭐ 74 | 🐛 5 | 🌐 Python | 📅 2021-08-12：显示货币格式以及它的数值。
* [django-oscar](http://oscarcommerce.com/)：一个用于 Django 的开源的电子商务框架。
* [shoop](https://www.shoop.io/en/)：一个基于 Django 的开源电子商务平台。
* [saleor](http://getsaleor.com/)：一款兼容 Django 的电子商务平台。

### RESTful API

用来开发 RESTful APIs 的库

* Django
  * [django-formapi](https://github.com/5monkeys/django-formapi) ⭐ 35 | 🐛 4 | 🌐 Python | 📅 2022-04-12：为 Django 的表单验证，创建 JSON APIs 。
  * [django-rest-framework](http://www.django-rest-framework.org/)：一个强大灵活的工具，用来构建 web API。
  * [django-tastypie](http://tastypieapi.org/)：为 Django 应用开发 API。
* Flask
  * [flask-api-utils](https://github.com/marselester/flask-api-utils) ⭐ 54 | 🐛 0 | 🌐 Python | 📅 2015-10-15：为 Flask 处理 API 表示和验证。
  * [eve](https://github.com/nicolaiarocci/eve) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2018-05-07：REST API 框架，由 Flask, MongoDB 等驱动。
  * [flask-api](http://www.flaskapi.org/)：为 flask 开发的，可浏览 Web APIs 。
  * [flask-restful](http://flask-restful.readthedocs.org/en/latest/)：为 flask 快速创建 REST APIs 。
  * [flask-restless](https://flask-restless.readthedocs.org/en/latest/)：为 SQLAlchemy 定义的数据库模型创建 RESTful APIs 。
* Pyramid
  * [cornice](https://cornice.readthedocs.org/en/latest/)：一个 Pyramid 的 REST 框架 。
* 与框架无关的
  * [fastapi](https://github.com/tiangolo/fastapi) ⭐ 101,632 | 🐛 87 | 🌐 Python | 📅 2026-08-15：一个现代，快速，基于标准 Python 类型注解的的 web框架，可使用 Python3.6+ 版本构建 API。
  * [hug](https://github.com/hugapi/hug) ⭐ 6,884 | 🐛 188 | 🌐 Python | 📅 2024-07-04：一个为纯净公开的 API 打造的 Python 3 框架。
  * [apistar](https://github.com/encode/apistar) ⚠️ Archived：专为Python 3设计的智能 Web API 框架。
  * [sandman](https://github.com/jeffknupp/sandman) ⭐ 2,289 | 🐛 37 | 🌐 Python | 📅 2021-12-25：为现存的数据库驱动系统自动创建 REST APIs 。
  * [sandman2](https://github.com/jeffknupp/sandman2) ⭐ 2,041 | 🐛 45 | 🌐 Python | 📅 2026-08-10：为数据库驱动的系统自动生成 REST API。
  * [ripozo](https://github.com/vertical-knowledge/ripozo) ⭐ 200 | 🐛 16 | 🌐 Python | 📅 2018-05-06：快速创建 REST/HATEOAS/Hypermedia APIs。
  * [falcon](http://falconframework.org/)：一个用来建立云 API 和 web app 后端的高性能框架。
  * [restless](http://restless.readthedocs.org/en/latest/)：框架无关的 REST 框架 ，基于从 Tastypie 学到的知识。
  * [vibora](https://vibora.io/)：快速高效且支持异步的 Web 框架，灵感来源于 Flask。

### 验证

实现验证方案的库。

* OAuth
  * [django-allauth](https://github.com/pennersr/django-allauth) ⭐ 10,369 | 🐛 2 | 🌐 Python | 📅 2026-08-13：Django 的验证应用。
  * [authlib](https://github.com/lepture/authlib) ⭐ 5,400 | 🐛 140 | 🌐 Python | 📅 2026-08-11：一个强大的Python库，用来构建 OAuth 和 OpenID 服务端。包括：JWS, JWK, JWA, JWT。
  * [django-oauth-toolkit](https://github.com/evonove/django-oauth-toolkit) ⭐ 3,333 | 🐛 57 | 🌐 Python | 📅 2026-08-09：为 Django 用户准备的 OAuth2。
  * [python-oauth2](https://github.com/joestump/python-oauth2) ⭐ 3,009 | 🐛 76 | 🌐 Python | 📅 2024-04-09：一个完全测试的抽象接口。用来创建 OAuth 客户端和服务端。
  * [OAuthLib](https://github.com/idan/oauthlib) ⭐ 2,977 | 🐛 117 | 🌐 Python | 📅 2026-07-14：一个 OAuth 请求-签名逻辑通用、 完整的实现。
  * [python-social-auth](https://github.com/omab/python-social-auth) ⭐ 2,801 | 🐛 24 | 🌐 Python | 📅 2022-07-01：一个设置简单的社会化验证方式。
  * [rauth](https://github.com/litl/rauth) ⚠️ Archived：OAuth 1.0/a, 2.0, 和 Ofly 的 Python 库。
  * [Flask-OAuthlib](https://github.com/lepture/flask-oauthlib) ⭐ 1,446 | 🐛 75 | 🌐 Python | 📅 2024-07-19：OAuth 1.0/a, 2.0 客户端实现，供 Flask 使用。
  * [django-oauth2-provider](https://github.com/caffeinehit/django-oauth2-provider) ⭐ 337 | 🐛 68 | 🌐 Python | 📅 2024-08-12：为 Django 应用提供 OAuth2 接入。
  * [sanction](https://github.com/demianbrecht/sanction) ⭐ 189 | 🐛 11 | 🌐 Python | 📅 2024-03-28：一个超级简单的 OAuth2 客户端实现。
  * [Authomatic](http://peterhudec.github.io/authomatic/)：简单但是强大的框架，身份验证/授权客户端。
* 其他
  * [PyJWT](https://github.com/jpadilla/pyjwt) ⭐ 5,684 | 🐛 64 | 🌐 Python | 📅 2026-08-10：JSON Web 令牌草案 01。
  * [python-jose](https://github.com/mpdavis/python-jose/) ⭐ 1,758 | 🐛 119 | 🌐 Python | 📅 2026-04-14：python 版 JOSE 实现。
  * [python-jwt](https://github.com/davedoesdev/python-jwt) ⚠️ Archived：一个用来生成和验证 JSON Web 令牌的模块。
  * [python-jws](https://github.com/brianloveswords/python-jws) ⭐ 56 | 🐛 24 | 🌐 Python | 📅 2022-02-04：JSON Web 签名草案 02 的实现。

### 模板引擎

模板生成和词法解析的库和工具。

* [Jinja2](https://github.com/pallets/jinja) ⭐ 11,740 | 🐛 101 | 🌐 Python | 📅 2025-06-14：一个现代的，对设计师友好的模板引擎。
* [Chameleon](https://chameleon.readthedocs.org/en/latest/)：一个 HTML/XML 模板引擎。 模仿了 ZPT（Zope Page Templates）, 进行了速度上的优化。
* [Genshi](https://genshi.edgewall.org/)：Python 模板工具，用以生成 web 感知的结果。
* [Mako](http://www.makotemplates.org/)：Python 平台的超高速轻量级模板。

### 队列

处理事件以及任务队列的库。

* [huey](https://github.com/coleifer/huey) ⭐ 6,004 | 🐛 0 | 🌐 Python | 📅 2026-08-16：小型多线程任务队列。
* [daramatiq](https://github.com/Bogdanp/dramatiq) ⭐ 5,310 | 🐛 60 | 🌐 Python | 📅 2026-08-13：适用于Python 3的快速可靠的后台任务处理库。
* [mrq](https://github.com/pricingassistant/mrq) ⭐ 892 | 🐛 63 | 🌐 Python | 📅 2023-06-13：一个 Python 的分布式 worker 任务队列， 使用 Redis 和 gevent。
* [simpleq](https://github.com/rdegges/simpleq) ⭐ 159 | 🐛 6 | 🌐 Python | 📅 2026-04-13：一个简单的，可无限扩张的，基于亚马逊 SQS 的队列。
* [celery](http://www.celeryproject.org/)：一个异步任务队列/作业队列，基于分布式消息传递
* [rq](http://python-rq.org/)：简单的 Python 作业队列。

### 搜索

对数据进行索引和执行搜索查询的库和软件。

* [elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py) ⚠️ Archived：Elasticsearch 的官方高级 Python 客户端。
* [django-haystack](https://github.com/django-haystack/django-haystack) ⭐ 3,734 | 🐛 583 | 🌐 Python | 📅 2026-08-15：Django 模块化搜索。
* [pysolr](https://github.com/django-haystack/pysolr) ⭐ 701 | 🐛 24 | 🌐 Python | 📅 2026-08-15：支持 [Apache Solr](https://lucene.apache.org/solr/) 的轻量级 Python 装饰器。
* [solrpy](https://github.com/edsu/solrpy) ⭐ 41 | 🐛 23 | 🌐 Python | 📅 2026-05-19：[solr](http://lucene.apache.org/solr/) 的 Python 客户端。
* [elasticsearch-py](https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html)：Elasticsearch 的官方底层 Python 客户端。
* [Whoosh](http://whoosh.readthedocs.org/en/latest/)：一个快速的纯 Python 搜索引擎库。

### 动态消息

用来创建用户活动的库。

* [Stream-Framework](https://github.com/tschellenbach/Stream-Framework) ⭐ 4,742 | 🐛 76 | 🌐 Python | 📅 2025-12-04：使用 Cassandra 和 Redis 创建动态消息和通知系统。
* [django-activity-stream](https://github.com/justquick/django-activity-stream) ⭐ 2,439 | 🐛 25 | 🌐 Python | 📅 2025-12-15：从你的站点行为中生成通用活动信息流。

### Web 资源管理

管理、压缩、缩小网站资源的工具。

* [django-compressor](https://github.com/django-compressor/django-compressor) ⭐ 2,870 | 🐛 121 | 🌐 Python | 📅 2026-07-28：将链接和内联的 JavaScript 或 CSS 压缩到一个单独的缓存文件中。
* [django-pipeline](https://github.com/jazzband/django-pipeline) ⭐ 1,541 | 🐛 157 | 🌐 Python | 📅 2026-08-15：Django 的资源包装库。
* [jinja-assets-compressor](https://github.com/jaysonsantos/jinja-assets-compressor) ⚠️ Archived：一个 Jinja 扩展，用来编译和压缩你的资源。
* [django-storages](http://django-storages.readthedocs.org/en/latest/)：一个针对 Django 的自定义存储后端的工具集合。
* [fanstatic](http://www.fanstatic.org/en/latest/)：打包、优化，并且把静态文件依赖作为 Python 的包来提供。
* [File Conveyor](https://wimleers.com/fileconveyor/)：一个后台驻留的程序，用来发现和同步文件到 CDNs, S3 和 FTP。
* [Flask-Assets](http://flask-assets.readthedocs.org/en/latest/)：帮你将 web 资源整合到你的 Flask app 中。
* [webassets](http://webassets.readthedocs.org/en/latest/)：为你的静态资源打包、优化和管理生成独一无二的缓存 URL。

### 缓存

缓存数据的库。

* [django-cacheops](https://github.com/Suor/django-cacheops) ⭐ 2,274 | 🐛 22 | 🌐 Python | 📅 2026-04-15：具有自动颗粒化事件驱动失效功能的 ORM。
* [django-cache-machine](https://github.com/django-cache-machine/django-cache-machine) ⭐ 884 | 🐛 23 | 🌐 Python | 📅 2023-02-20：Django 模型的自动缓存和失效。
* [pylibmc](https://github.com/lericson/pylibmc) ⭐ 492 | 🐛 41 | 🌐 C | 📅 2025-04-12：[libmemcached](http://libmemcached.org/libMemcached.html) 接口的 Python 封装。
* [johnny-cache](https://github.com/jmoiron/johnny-cache) ⭐ 310 | 🐛 34 | 🌐 Python | 📅 2021-06-10：django 应用缓存框架。
* [django-viewlet](https://github.com/5monkeys/django-viewlet) ⭐ 61 | 🐛 5 | 🌐 Python | 📅 2022-04-07：渲染模板，同时具有额外的缓存控制功能。
* [Beaker](http://beaker.readthedocs.org/en/latest/)：一个缓存和会话库，可以用在 web 应用和独立 Python 脚本和应用上。
* [dogpile.cache](http://dogpilecache.readthedocs.org/en/latest/)：dogpile.cache 是 Beaker 的下一代替代品，由同一作者开发。
* [HermesCache](https://pypi.python.org/pypi/HermesCache)：Python 缓存库，具有基于标签的失效和 dogpile effect 保护功能。
* [python-diskcache](http://www.grantjenks.com/docs/diskcache/)：SQLite 和文件支持的缓存后端，具有比 memcached 和 redis 更快的查找速度。

### 电子邮件

用来发送和解析电子邮件的库。

* [modoboa](https://github.com/tonioo/modoboa) ⭐ 3,532 | 🐛 51 | 🌐 Python | 📅 2026-08-14：一个邮件托管和管理平台，具有现代的、简约的 Web UI。
* [inbox](https://github.com/nylas/sync-engine) ⚠️ Archived：一个开源电子邮件工具箱。
* [flanker](https://github.com/mailgun/flanker) ⭐ 1,651 | 🐛 78 | 🌐 Python | 📅 2026-04-08：一个 email 地址和 Mime 解析库。
* [inbox.py](https://github.com/kennethreitz/inbox.py) ⭐ 1,501 | 🐛 3 | 🌐 Python | 📅 2016-07-11：Python SMTP 服务器。
* [Talon](https://github.com/mailgun/talon) ⭐ 1,343 | 🐛 71 | 🌐 Python | 📅 2023-10-18：Mailgun 库，用来抽取信息和签名。
* [imbox](https://github.com/martinrusev/imbox) ⭐ 1,217 | 🐛 63 | 🌐 Python | 📅 2026-06-23：Python IMAP 库。
* [lamson](https://github.com/zedshaw/lamson) ⭐ 740 | 🐛 22 | 🌐 Python | 📅 2021-10-02：Python 风格的 SMTP 应用服务器。
* [marrow.mailer](https://github.com/marrow/mailer) ⭐ 294 | 🐛 21 | 🌐 Python | 📅 2025-05-21：高性能可扩展邮件分发框架。
* [mailer](https://github.com/marrow/mailer) ⭐ 294 | 🐛 21 | 🌐 Python | 📅 2025-05-21：一款高性能可扩展的邮件投递框架。
* [django-celery-ses](https://github.com/StreetVoice/django-celery-ses) ⭐ 32 | 🐛 4 | 🌐 Python | 📅 2026-06-04：带有 AWS SES 和 Celery 的 Django email 后端。
* [mailjet](https://github.com/WoLpH/mailjet) ⚠️ Archived：Mailjet API 实现，用来提供批量发送邮件，统计等功能。
* [salmon](https://github.com/moggers87/salmon) ⚠️ Archived：一个 Python 邮件服务器。
* [envelopes](http://tomekwojcik.github.io/envelopes/)：供人类使用的电子邮件库。
* [pyzmail](http://www.magiksys.net/pyzmail/)：创建，发送和解析电子邮件。
* [yagmail](https://pypi.org/project/yagmail/)：yagmail是一个GMAIL / SMTP客户端，旨在使其尽可能简单地发送电子邮件。

### 国际化

用来进行国际化的库。

* [Babel](http://babel.pocoo.org/en/latest/)：一个 Python 的国际化库。
* [Korean](https://korean.readthedocs.org/en/latest/)：一个韩语词态库。
* [PyICU](https://github.com/ovalhub/pyicu) ⚠️ Archived：一个封装了 [ICU](http://site.icu-project.org/) C++ 库的 Python 扩展。

### URL 处理

解析 URLs 的库

* [furl](https://github.com/gruns/furl) ⭐ 2,811 | 🐛 52 | 🌐 Python | 📅 2026-02-22：一个让处理 URL 更简单小型 Python 库。
* [webargs](https://github.com/sloria/webargs) ⭐ 1,408 | 🐛 8 | 🌐 Python | 📅 2026-08-13：一个解析 HTTP 请求参数的库，内置对流行 web 框架的支持，包括 Flask, Django, Bottle, Tornado 和 Pyramid。
* [pyshorteners](https://github.com/ellisonleao/pyshorteners) ⚠️ Archived：一个纯 Python URL 缩短库。
* [purl](https://github.com/codeinthehole/purl) ⭐ 303 | 🐛 14 | 🌐 Python | 📅 2023-08-04：一个简单的，不可变的 URL 类，具有简洁的 API 来进行询问和处理。
* [shorturl](https://github.com/Alir3z4/python-shorturl)：生成短小 URL 和类似 bit.ly 短链的 Python 实现。

### HTML 处理

处理 HTML 和 XML 的库。

* [xmltodict](https://github.com/martinblech/xmltodict) ⭐ 5,751 | 🐛 6 | 🌐 Python | 📅 2026-06-15：像处理 JSON 一样处理 XML。
* [xhtml2pdf](https://github.com/xhtml2pdf/xhtml2pdf) ⭐ 2,389 | 🐛 138 | 🌐 Python | 📅 2026-01-19：HTML/CSS 转 PDF 工具。
* [pyquery](https://github.com/gawel/pyquery) ⭐ 2,380 | 🐛 59 | 🌐 Python | 📅 2026-07-27：一个解析 HTML 的库，类似 jQuery。
* [html5lib](https://github.com/html5lib/html5lib-python) ⭐ 1,224 | 🐛 104 | 🌐 Python | 📅 2026-04-21：一个兼容标准的 HTML 文档和片段解析及序列化库。
* [MarkupSafe](https://github.com/pallets/markupsafe) ⭐ 695 | 🐛 15 | 🌐 Python | 📅 2025-09-27：为 Python 实现 XML/HTML/XHTML 标记安全字符串。
* [untangle](https://github.com/stchris/untangle) ⭐ 630 | 🐛 22 | 🌐 Python | 📅 2026-04-13：将 XML 文档转换为 Python 对象，使其可以方便的访问。
* [requests-html](https://github.com/kennethreitz/requests-html) ⭐ 327 | 🐛 1 | 🌐 Python | 📅 2024-06-19：人性化的，Pythonic 的 HTML 解析库。
* [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/bs4/doc/)：以 Python 风格的方式来对 HTML 或 XML 进行迭代，搜索和修改。
* [bleach](http://bleach.readthedocs.org/en/latest/)：一个基于白名单的 HTML 清理和文本链接库。
* [cssutils](https://pypi.python.org/pypi/cssutils/)：一个 Python 的 CSS 库。
* [lxml](http://lxml.de/)：一个非常快速，简单易用，功能齐全的库，用来处理 HTML 和 XML。
* [WeasyPrint](http://weasyprint.org)：用于HTML和CSS的可视化呈现引擎，并可以导出为 PDF。
* [xmldataset](https://xmldataset.readthedocs.io/en/latest/)：简单 XML 解析。

爬取网络站点的库

* [pyspider](https://github.com/binux/pyspider) ⚠️ Archived：一个强大的爬虫系统。
* [portia](https://github.com/scrapinghub/portia) ⚠️ Archived：Scrapy 可视化爬取。
* [MechanicalSoup](https://github.com/hickford/MechanicalSoup) ⭐ 4,890 | 🐛 39 | 🌐 Python | 📅 2026-08-04：用于自动和网络站点交互的 Python 库。
* [RoboBrowser](https://github.com/jmcarp/robobrowser) ⭐ 3,693 | 🐛 59 | 🌐 Python | 📅 2020-09-10：一个简单的，Python 风格的库，用来浏览网站，而不需要一个独立安装的浏览器。
* [ScrapydWeb](https://github.com/my8100/scrapydweb) ⭐ 3,412 | 🐛 64 | 🌐 Python | 📅 2025-02-19：一个用于 Scrapyd 集群管理的全功能 web UI，支持 Scrapy 日志分析和可视化，自动打包，定时器任务和邮件通知等特色功能。
* [cola](https://github.com/chineking/cola) ⚠️ Archived：一个分布式爬虫框架。
* [Demiurge](https://github.com/matiasb/demiurge) ⭐ 118 | 🐛 2 | 🌐 Python | 📅 2022-01-14：基于 PyQuery 的爬虫微型框架。
* [Scrapy](http://scrapy.org/)：一个快速高级的屏幕爬取及网页采集框架。
* [feedparser](http://pythonhosted.org/feedparser/)：通用 feed 解析器。
* [Grab](http://grablib.org/)：站点爬取框架。

### 网页内容提取

用于进行网页内容提取的库。

* [newspaper](https://github.com/codelucas/newspaper) ⭐ 15,141 | 🐛 514 | 🌐 Python | 📅 2026-08-09：使用 Python 进行新闻提取，文章提取以及内容策展。
* [textract](https://github.com/deanmalmgren/textract) ⭐ 4,691 | 🐛 69 | 🌐 HTML | 📅 2026-08-05：从任何格式的文档中提取文本，Word，PowerPoint，PDFs 等等。
* [python-goose](https://github.com/grangier/python-goose) ⭐ 4,103 | 🐛 107 | 🌐 HTML | 📅 2026-03-10：HTML 内容/文章提取器(python2)。
* [sumy](https://github.com/miso-belica/sumy) ⭐ 3,701 | 🐛 7 | 🌐 Python | 📅 2026-08-14：一个为文本文件和 HTML 页面进行自动摘要的模块。
* [python-readability](https://github.com/buriy/python-readability) ⭐ 2,895 | 🐛 37 | 🌐 Python | 📅 2026-01-26：arc90 公司 readability 工具的 Python 高速端口。
* [html2text](https://github.com/Alir3z4/html2text) ⭐ 2,168 | 🐛 95 | 🌐 Python | 📅 2025-10-28：将 HTML 转换为 Markdown 格式文本。
* [goose3](https://github.com/goose3/goose3) ⭐ 912 | 🐛 13 | 🌐 HTML | 📅 2026-07-23：HTML 内容/文章提取器(python3)。
* [micawber](https://github.com/coleifer/micawber) ⭐ 680 | 🐛 0 | 🌐 Python | 📅 2026-07-19：一个小型网页内容提取库，用来从 URLs 提取富内容。
* [lassie](https://github.com/michaelhelmick/lassie) ⭐ 629 | 🐛 11 | 🌐 HTML | 📅 2022-07-30：人性化的网页内容检索库。
* [opengraph](https://github.com/erikriver/opengraph) ⭐ 233 | 🐛 23 | 🌐 Python | 📅 2021-12-26：一个用来解析开放内容协议(Open Graph Protocol)的 Python 模块。
* [Haul](https://github.com/vinta/Haul) ⭐ 161 | 🐛 10 | 🌐 Python | 📅 2017-01-07：一个可以扩展的图像爬取工具。
* [sanitize](https://github.com/Alir3z4/python-sanitize) ⭐ 66 | 🐛 1 | 🌐 Python | 📅 2014-10-07：为杂乱的数据世界带来调理性。

### 表单

进行表单操作的库。

* [django-bootstrap3](https://github.com/dyve/django-bootstrap3) ⭐ 2,332 | 🐛 0 | 🌐 Python | 📅 2026-08-10：集成了 Bootstrap 3 的 Django。
* [django-bootstrap4](https://github.com/zostera/django-bootstrap4) ⭐ 1,025 | 🐛 17 | 🌐 Python | 📅 2026-08-10：集成了 Bootstrap 4 的 Django。
* [django-remote-forms](https://github.com/WiserTogether/django-remote-forms) ⭐ 219 | 🐛 22 | 🌐 Python | 📅 2024-05-07：一个平台独立的 Django 表单序列化工具。
* [Deform](http://deform.readthedocs.org/en/latest/)：Python HTML 表单生成库，受到了 formish 表单生成库的启发。
* [django-crispy-forms](http://django-crispy-forms.readthedocs.org/en/latest/)：一个 Django 应用，他可以让你以一种非常优雅且 DRY (Don't repeat yourself) 的方式来创建美观的表单。
* [WTForms](http://wtforms.readthedocs.org/en/latest/)：一个灵活的表单验证和呈现库。
* [WTForms-JSON](http://wtforms-json.readthedocs.org/en/latest/)：一个 WTForms 扩展，用来处理 JSON 数据。

### 数据验证

数据验证库。多用于表单验证。

* [jsonschema](https://github.com/Julian/jsonschema) ⭐ 4,972 | 🐛 61 | 🌐 Python | 📅 2026-08-15：[JSON Schema](http://json-schema.org/) 的 python 实现，用于 JSON 数据的验证。
* [schema](https://github.com/keleshev/schema) ⭐ 2,946 | 🐛 109 | 🌐 Python | 📅 2026-06-20：一个用于对 Python 数据结构进行验证的库。
* [Schematics](https://github.com/schematics/schematics) ⭐ 2,589 | 🐛 109 | 🌐 Python | 📅 2023-07-12：数据结构验证。
* [voluptuous](https://github.com/alecthomas/voluptuous) ⭐ 1,850 | 🐛 44 | 🌐 Python | 📅 2026-07-25：一个 Python 数据验证库。主要是为了验证传入 Python 的 JSON，YAML 等数据。
* [valideer](https://github.com/podio/valideer) ⭐ 261 | 🐛 9 | 🌐 Python | 📅 2026-07-08：轻量级可扩展的数据验证和适配库。
* [kmatch](https://github.com/ambitioninc/kmatch) ⚠️ Archived：一种用于匹配/验证/筛选 Python 字典的语言。
* [Cerberus](http://docs.python-cerberus.org/en/stable/)：一个映射验证器（mappings-validator）。支持多种规则，提供归一化功能，可以方便地定制为 Python 风格的 schema 定义。
* [colander](http://docs.pylonsproject.org/projects/colander/en/latest/)：一个用于对从 XML, JSON，HTML 表单获取的数据或其他同样简单的序列化数据进行验证和反序列化的系统。

### 序列化

复杂数据类型序列化相关库。

* [marshmallow](https://github.com/marshmallow-code/marshmallow) ⭐ 7,242 | 🐛 145 | 🌐 Python | 📅 2026-08-14：一个轻量级的库，用于将复杂对象与简单 Python 数据类型相互转换。
* [ultrajson](https://github.com/esnme/ultrajson) ⭐ 4,496 | 🐛 32 | 🌐 C++ | 📅 2026-08-13：使用 Python 绑定的，用 C 编写的快速 JSON 解码器和编码器。
* [pysimdjson](https://github.com/TkTech/pysimdjson) ⭐ 770 | 🐛 18 | 🌐 Python | 📅 2026-04-26：与 Python 绑定的 [simdjson](https://github.com/lemire/simdjson) ⭐ 24,155 | 🐛 136 | 🌐 C++ | 📅 2026-08-15 。
* [python-rapidjson](https://github.com/python-rapidjson/python-rapidjson) ⭐ 533 | 🐛 22 | 🌐 C++ | 📅 2026-08-09： [RapidJSON](https://github.com/Tencent/rapidjson) ⭐ 15,110 | 🐛 789 | 🌐 C++ | 📅 2025-02-05 的 Python 封装。

### 反垃圾技术

帮助你和电子垃圾进行战斗的库。

* [django-simple-captcha](https://github.com/mbi/django-simple-captcha) ⭐ 1,422 | 🐛 39 | 🌐 Python | 📅 2026-07-30：一个简单、高度可定制的 Django 应用，可以为任何 Django 表单添加验证码。
* [django-simple-spam-blocker](https://github.com/moqada/django-simple-spam-blocker) ⭐ 23 | 🐛 1 | 🌐 Python | 📅 2021-12-26：一个用于 Django 的简单的电子垃圾屏蔽工具。

### 标记

用来进行标记的库。

* [django-taggit](https://github.com/alex/django-taggit) ⭐ 3,444 | 🐛 108 | 🌐 Python | 📅 2026-06-29：简单的 Django 标记工具。

### 管理面板

管理界面库。

* [Ajenti](https://github.com/ajenti/ajenti) ⭐ 7,954 | 🐛 10 | 🌐 Python | 📅 2026-07-22：一个你的服务器值得拥有的管理面板。
* [flower](https://github.com/mher/flower) ⭐ 7,231 | 🐛 157 | 🌐 Python | 📅 2026-08-16：一个对 Celery 集群进行实时监控和提供 web 管理界面的工具。
* [flask-admin](https://github.com/flask-admin/flask-admin) ⭐ 6,069 | 🐛 128 | 🌐 Python | 📅 2026-08-16：一个用于 Flask 的简单可扩展的管理界面框架。
* [django-xadmin](https://github.com/sshwsfc/django-xadmin) ⭐ 4,750 | 🐛 386 | 🌐 Python | 📅 2025-12-16：Django admin 的一个替代品，具有很多不错的功能。
* [django-jet](https://github.com/geex-arts/django-jet) ⭐ 3,623 | 🐛 304 | 🌐 Python | 📅 2025-11-26：具有改进功能的现代响应式 Django 管理界面模板。
* [Wooey](https://github.com/wooey/wooey) ⭐ 2,243 | 🐛 57 | 🌐 Python | 📅 2026-08-04：一个 Django 应用，可以为 Python 脚本创建 web 用户界面。
* [jet-bridge](https://github.com/jet-admin/jet-bridge) ⭐ 1,797 | 🐛 11 | 🌐 Python | 📅 2026-06-15：管理面板框架，适用于任何具有良好 UI 的应用（例如 Django）。
* [django-suit](http://djangosuit.com/)：Django 管理界面的一个替代品（仅对于非商业用途是免费的）。
* [Grappelli](http://grappelliproject.com/)：Django 管理界面的一个漂亮的皮肤。
* [django-grappelli](https://grappelliproject.com/)：拥有绚丽外观的 Django Admin 界面。

### Serverless 框架

使用 Python 开发 Serverless 模型相关的库。

* [Zappa](https://github.com/Miserlou/Zappa) ⭐ 11,823 | 🐛 687 | 🌐 Python | 📅 2023-03-23：在 AWS Lambda 和 API Gateway 部署 WSGI 应用的工具。
* [python-lambda](https://github.com/nficano/python-lambda) ⚠️ Archived ：在 AWS Lambda 开发和部署 Python 代码的工具包。

### 静态站点生成器

静态站点生成器是一个软件，它把文本和模板作为输入，然后输出 HTML 文件。

* [Cactus](https://github.com/koenbok/Cactus/) ⭐ 3,467 | 🐛 99 | 🌐 Python | 📅 2023-08-28：为设计师设计的静态站点生成器。
* [makesite](https://github.com/sunainapai/makesite) ⭐ 1,869 | 🐛 7 | 🌐 Python | 📅 2023-03-04：简单轻量的站点/博客生成器（小于 130 行代码）。
* [Pelican](http://blog.getpelican.com/)：使用 Markdown 或 ReST 来处理内容， Jinja 2 来制作主题。支持 DVCS, Disqus.。AGPL 许可。
* [Hyde](http://hyde.github.io/)：基于 Jinja2 的静态站点生成器。
* [Nikola](https://www.getnikola.com/)：一个静态网站和博客生成器。
* [Tinkerer](http://tinkerer.me/)：Tinkerer 是一个博客引擎/静态站点生成器，由 Sphinx 驱动。
* [Lektor](https://www.getlektor.com/)：一个简单易用的静态 CMS 和博客引擎。

### 进程

操作系统进程启动及通信库。

* [sh](https://github.com/amoffat/sh) ⭐ 7,245 | 🐛 2 | 🌐 Python | 📅 2026-07-25：一个完备的 subprocess 替代库。
* [envoy](https://github.com/kennethreitz/envoy) ⚠️ Archived：比 Python [subprocess](https://docs.python.org/2/library/subprocess.html) 模块更人性化。
* [delegator.py](https://github.com/amitt001/delegator.py) ⭐ 1,743 | 🐛 12 | 🌐 Python | 📅 2022-12-01：人性化的 [Subprocesses](https://docs.python.org/3/library/subprocess.html) 2.0 版本。
* [sarge](http://sarge.readthedocs.org/en/latest/)：另一 种 subprocess 模块的封装。

### 并发和并行

用以进行并发和并行操作的库。

* [uvloop](https://github.com/MagicStack/uvloop) ⭐ 11,885 | 🐛 155 | 🌐 Cython | 📅 2026-07-14：在 libuv 之上超快速实现 asyncio 事件循环。
* [gevent](http://www.gevent.org/)：一个基于协程的 Python 网络库，使用 [greenlet](https://github.com/python-greenlet/greenlet) ⭐ 1,837 | 🐛 21 | 🌐 C++ | 📅 2026-08-10。
* [gevent](http://www.gevent.org/)：使用 [greenlet](https://github.com/python-greenlet/greenlet) ⭐ 1,837 | 🐛 21 | 🌐 C++ | 📅 2026-08-10 且基于协程的 Python 网络库。
* [Tomorrow](https://github.com/madisonmay/Tomorrow) ⭐ 1,447 | 🐛 5 | 🌐 Python | 📅 2020-02-16：用于产生异步代码的神奇的装饰器语法实现。
* [scoop](https://github.com/soravux/scoop) ⭐ 661 | 🐛 34 | 🌐 Python | 📅 2023-03-17：支持在 Python 中进行可伸缩并行操作。
* [multiprocessing](https://docs.python.org/2/library/multiprocessing.html)：(Python 标准库) 基于进程的“线程”接口。
* [threading](https://docs.python.org/2/library/threading.html)：(Python 标准库)更高层的线程接口。
* [eventlet](http://eventlet.net/)：支持 WSGI 的异步框架。
* [concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html)：(Python 标准库) 异步执行可调用对象的高级接口。

### 网络

用于网络编程的库。

* [trio](https://github.com/python-trio/trio) ⭐ 7,305 | 🐛 322 | 🌐 Python | 📅 2026-08-11：异步并发和 I/O 友好的库。
* [Toapi](https://github.com/gaojiuli/toapi) ⭐ 3,555 | 🐛 3 | 🌐 Python | 📅 2026-08-09：一个轻巧，简单，快速的 Flask 库，致力于为所有网站提供 API 服务。
* [pulsar](https://github.com/quantmind/pulsar) ⚠️ Archived：事件驱动的并发框架。
* [diesel](https://github.com/dieseldev/diesel) ⭐ 580 | 🐛 13 | 🌐 Python | 📅 2015-04-14：基于 Greenlet 的事件 I/O 框架。
* [txZMQ](https://github.com/smira/txZMQ) ⭐ 150 | 🐛 10 | 🌐 Python | 📅 2023-06-15：基于 Twisted 的 ZeroMQ 消息库的 Python 封装。
* [asyncio](https://docs.python.org/3/library/asyncio.html)：(Python 标准库) 异步 I/O，事件循环，协程以及任务。
* [Twisted](https://twistedmatrix.com/trac/)：一个事件驱动的网络引擎。
* [pyzmq](http://zeromq.github.io/pyzmq/)：一个 ZeroMQ 消息库的 Python 封装。

### WebSocket

帮助使用 WebSocket 的库。

* [AutobahnPython](https://github.com/crossbario/autobahn-python) ⭐ 2,541 | 🐛 187 | 🌐 Python | 📅 2026-07-15：给 Python、使用的 WebSocket & WAMP 基于 Twisted 和 [asyncio](https://docs.python.org/3/library/asyncio.html)。
* [Crossbar](https://github.com/crossbario/crossbar/) ⭐ 2,064 | 🐛 305 | 🌐 Python | 📅 2026-07-27：开源统一应用路由(Websocket & WAMP for Python on Autobahn)。
* [django-socketio](https://github.com/stephenmcd/django-socketio) ⭐ 1,314 | 🐛 32 | 🌐 Python | 📅 2021-05-17：给 Django 用的 WebSockets。
* [WebSocket-for-Python](https://github.com/Lawouach/WebSocket-for-Python) ⭐ 1,127 | 🐛 63 | 🌐 Python | 📅 2026-03-30：为 Python2/3 以及 PyPy 编写的 WebSocket 客户端和服务器库。

### WSGI 服务器

兼容 WSGI 的 web 服务器

* [gunicorn](https://pypi.python.org/pypi/gunicorn)：Pre-forked, 部分是由 C 语言编写的。
* [uwsgi](https://uwsgi-docs.readthedocs.org/en/latest/)：uwsgi 项目的目的是开发一组全栈工具，用来建立托管服务，由 C 语言编写。
* [bjoern](https://pypi.python.org/pypi/bjoern)：异步，非常快速，由 C 语言编写。
* [fapws3](http://www.fapws.org/)：异步 (仅对于网络端)，由 C 语言编写。
* [meinheld](https://pypi.python.org/pypi/meinheld)：异步，部分是由 C 语言编写的。
* [netius](https://github.com/hivesolutions/netius) ⭐ 118 | 🐛 14 | 🌐 Python | 📅 2026-06-21：异步，非常快速。
* [paste](http://pythonpaste.org/)：多线程，稳定，久经考验。
* [rocket](https://pypi.python.org/pypi/rocket)：多线程。
* [waitress](https://waitress.readthedocs.org/en/latest/)：多线程，是它驱动着 Pyramid 框架。
* [Werkzeug](http://werkzeug.pocoo.org/)：一个 WSGI 工具库，驱动着 Flask，而且可以很方便大嵌入到你的项目中去。

### ASGI 服务器

兼容 ASGI 的 web 服务器。

* [uvicorn](https://github.com/encode/uvicorn) ⭐ 10,909 | 🐛 78 | 🌐 Python | 📅 2026-08-16：使用 uvloop 和 httptools 实现的闪电般快速的 ASGI 服务器。
* [daphne](https://github.com/django/daphne) ⭐ 2,680 | 🐛 39 | 🌐 Python | 📅 2026-07-21：用于 ASGI 和 ASGI-HTTP 的，支持 HTTP，HTTP2 和 WebSocket 协议的服务器。

### RPC 服务器

兼容 RPC 的服务器。

* [zeroRPC](https://github.com/0rpc/zerorpc-python) ⭐ 3,235 | 🐛 55 | 🌐 Python | 📅 2025-02-08：zerorpc 是一个灵活的 RPC 实现，基于 [ZeroMQ](http://zeromq.org/) 和 [MessagePack](http://msgpack.org/)。
* [RPyC](https://github.com/tomerfiliba/rpyc) ⭐ 1,705 | 🐛 95 | 🌐 Python | 📅 2025-08-14 (Remote Python Call)：适用于 Python 的透明且对称的RPC库。
* [SimpleJSONRPCServer](https://github.com/joshmarshall/jsonrpclib/) ⭐ 452 | 🐛 39 | 🌐 Python | 📅 2022-03-15：这个库是 JSON-RPC 规范的一个实现。
* [SimpleXMLRPCServer](https://docs.python.org/2/library/simplexmlrpcserver.html)：(Python 标准库) 简单的 XML-RPC 服务器实现，单线程。

### 密码学

* [hashids](https://github.com/davidaurelio/hashids-python) ⭐ 1,413 | 🐛 8 | 🌐 Python | 📅 2023-07-04：在 Python 中实现 [hashids](http://hashids.org/) 。
* [PyNacl](https://github.com/pyca/pynacl) ⭐ 1,204 | 🐛 56 | 🌐 C | 📅 2026-07-30：网络和密码学(NaCl) 库的 Python 绑定。
* [cryptography](https://cryptography.io/en/latest/)：这个软件包意在提供密码学基本内容和方法提供给 Python 开发者。
* [Paramiko](http://www.paramiko.org/)：SSHv2 协议的 Python (2.6+, 3.3+) ，提供客户端和服务端的功能。
* [Passlib](https://pythonhosted.org/passlib/)：安全密码存储／哈希库。
* [PyCrypto](https://www.dlitz.net/software/pycrypto/)：Python 密码学工具箱。

### 图形用户界面

用来创建图形用户界面程序的库。

* [DearPyGui](https://github.com/RaylockLLC/DearPyGui/) ⭐ 15,580 | 🐛 329 | 🌐 C++ | 📅 2026-05-13：一个简单的可使用 GPU 加速的 Python GUI 框架。
* [PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI) ⭐ 13,813 | 🐛 705 | 🌐 Python | 📅 2026-08-16：tkinter，Qt，WxPython 和 Remi 的封装。
* [Eel](https://github.com/ChrisKnott/Eel) ⚠️ Archived：用于制作简单离线 HTML/JS GUI 应用的库。
* [pywebview](https://github.com/r0x0r/pywebview/) ⭐ 5,984 | 🐛 16 | 🌐 Python | 📅 2026-08-11：围绕网页视图组件的轻量级跨平台的原生包装。
* [Toga](https://github.com/pybee/toga) ⭐ 5,404 | 🐛 328 | 🌐 Python | 📅 2026-08-16：一个 Python 原生的，操作系统原生的 GUI 工具包。
* [Flexx](https://github.com/zoofIO/flexx) ⭐ 3,331 | 🐛 96 | 🌐 Python | 📅 2025-01-20：Flexx 是一个纯 Python 语言编写的用来创建 GUI 程序的工具集，它使用 web 技术进行界面的展示。
* [enaml](https://github.com/nucleic/enaml) ⭐ 1,578 | 🐛 60 | 🌐 Python | 📅 2026-08-03：使用类似 QML 的 Declaratic 语法来创建美观的用户界面。
* [curses](https://docs.python.org/2/library/curses.html#module-curses)：内建的 [ncurses](http://www.gnu.org/software/ncurses/) 封装，用来创建终端图形用户界面。
* [kivy](https://kivy.org/)：一个用来创建自然用户交互（NUI）应用程序的库，可以运行在 Windows, Linux, Mac OS X, Android 以及 iOS 平台上。
* [pyglet](https://bitbucket.org/pyglet/pyglet/wiki/Home)：一个 Python 的跨平台窗口及多媒体库。
* [PyQt](https://riverbankcomputing.com/software/pyqt/intro)：跨平台用户界面框架 [Qt](http://www.qt.io/) 的 Python 绑定 ，支持 Qt v4 和 Qt v5。
* [PySide](https://wiki.qt.io/PySide)：跨平台用户界面框架 [Qt](http://www.qt.io/) 的 Python 绑定 ，支持 Qt v4。
* [Tkinter](https://wiki.python.org/moin/TkInter)：Tkinter 是 Python GUI 的一个事实标准库。
* [urwid](http://urwid.org/)：一个用来创建终端 GUI 应用的库，支持组件，事件和丰富的色彩等。
* [wxPython](http://wxpython.org/)：wxPython 是 wxWidgets C++ 类库和 Python 语言混合的产物。
* [PyGObject](https://wiki.gnome.org/Projects/PyGObject)：GLib/GObject/GIO/GTK+ (GTK+3) 的 Python 绑定。

### 游戏开发

超赞的游戏开发库。

* [Cocos2d](http://cocos2d.org/)：cocos2d 是一个用来开发 2D 游戏， 示例和其他图形/交互应用的框架。基于 pyglet。
* [Panda3D](https://www.panda3d.org/)：由迪士尼开发的 3D 游戏引擎，并由卡内基梅陇娱乐技术中心负责维护。使用 C++ 编写, 针对 Python 进行了完全的封装。
* [Pygame](http://www.pygame.org/news.html)：Pygame 是一组 Python 模块，用来编写游戏。
* [PyOgre](http://www.ogre3d.org/tikiwiki/PyOgre)：Ogre 3D 渲染引擎的 Python 绑定，可以用来开发游戏和仿真程序等任何 3D 应用。
* [PyOpenGL](http://pyopengl.sourceforge.net/)：OpenGL 的 Python 绑定及其相关 APIs。
* [PySDL2](http://pysdl2.readthedocs.org/en/latest/)：SDL2 库的封装，基于 ctypes。
* [RenPy](https://www.renpy.org/)：一个视觉小说（visual novel）引擎。
* [Arcade](https://arcade.academy/index.html)：一个现代 Python 框架，用于制作具有引人入胜的图形与声音的游戏。
* [Harfang3D](http://www.harfang3d.com)：支持3D，VR 与游戏开发的 Python 框架。

### 日志

用来生成和操作日志的库。

* [loguru](https://github.com/Delgan/loguru) ⭐ 24,070 | 🐛 266 | 🌐 Python | 📅 2026-07-01：旨在带来愉悦体验的 Python 日志库。
* [sentry-python](https://github.com/getsentry/sentry-python) ⭐ 2,202 | 🐛 446 | 🌐 Python | 📅 2026-08-15：Python 版 Sentry SDK。
* [logging](https://docs.python.org/2/library/logging.html)：(Python 标准库) 为 Python 提供日志功能。
* [logbook](http://pythonhosted.org/Logbook/)：Logging 库的替代品。
* [Eliot](https://eliot.readthedocs.org/en/latest/)：为复杂的和分布式系统创建日志。
* [Raven](http://raven.readthedocs.org/en/latest/)：Sentry 的 Python 客户端。
* [Sentry](https://pypi.python.org/pypi/sentry)：实时记录和收集日志的服务器。
* [structlog](https://www.structlog.org/en/stable/)：结构化日志，让日志变得简单。

### 测试

进行代码库测试和生成测试数据的库。

* 测试框架
  * [Robot Framework](https://github.com/robotframework/robotframework) ⭐ 11,822 | 🐛 302 | 🌐 Python | 📅 2026-08-16：一个通用的自动化测试框架。
  * [hypothesis](https://github.com/DRMacIver/hypothesis) ⭐ 8,888 | 🐛 44 | 🌐 Python | 📅 2026-08-16：Hypothesis 是一个基于先进的 Quickcheck 风格特性的测试库。
  * [nose2](https://github.com/nose-devs/nose2) ⭐ 826 | 🐛 45 | 🌐 Python | 📅 2026-08-10 `nose`的继任者，基于 `unittest2`。
  * [green](https://github.com/CleanCut/green) ⭐ 806 | 🐛 8 | 🌐 Python | 📅 2024-11-12：干净，多彩的测试工具。
  * [contexts](https://github.com/benjamin-hodgson/Contexts) ⚠️ Archived：一个 Python 3.3+ 的 BDD 框架。受到 C#  Machine.Specifications 的启发。
  * [pyshould](https://github.com/drslump/pyshould) ⭐ 38 | 🐛 7 | 🌐 Python | 📅 2018-03-05：Should 风格的断言，基于 [PyHamcrest](https://github.com/hamcrest/PyHamcrest) ⭐ 804 | 🐛 28 | 🌐 Python | 📅 2026-02-12。
  * [unittest](https://docs.python.org/2/library/unittest.html)：(Python 标准库) 单元测试框架。
  * [nose](https://nose.readthedocs.org/en/latest/)：nose 扩展了 unittest 的功能。
  * [mamba](http://nestorsalceda.github.io/mamba/)：Python 的终极测试工具， 拥护 BDD。
  * [pytest](http://pytest.org/latest/)：一个成熟的全功能 Python 测试工具。
  * [pyvows](http://heynemann.github.io/pyvows/)：BDD 风格的测试工具，受 Vows.js 的启发。
  * [tox](https://tox.readthedocs.io/en/latest/)：自动化测试与发布的工具，支持多个 Python 版本。
* GUI / Web 测试
  * [locust](https://github.com/locustio/locust) ⭐ 28,075 | 🐛 4 | 🌐 Python | 📅 2026-08-10：使用 Python 编写的，可扩展的用户加载测试工具。
  * [PyAutoGUI](https://github.com/asweigart/pyautogui) ⭐ 12,663 | 🐛 584 | 🌐 Python | 📅 2024-08-20：PyAutoGUI 是一个人性化的跨平台 GUI 自动测试模块。
  * [Schemathesis](https://github.com/kiwicom/schemathesis) ⭐ 3,530 | 🐛 10 | 🌐 Python | 📅 2026-08-16：基于属性的自动测试工具，用于测试使用 Open API / Swagger 规范构建的 Web 应用程序。
  * [sixpack](https://github.com/seatgeek/sixpack) ⭐ 1,754 | 🐛 89 | 🌐 Python | 📅 2022-08-21：一个和语言无关的 A/B 测试框架。
  * [Selenium](https://pypi.python.org/pypi/selenium)：[Selenium](http://www.seleniumhq.org/) WebDriver 的 Python 绑定。
  * [splinter](https://splinter.readthedocs.org/en/latest/)：开源的 web 应用测试工具。
* Mock 测试
  * [freezegun](https://github.com/spulec/freezegun) ⭐ 4,522 | 🐛 163 | 🌐 Python | 📅 2025-08-19：通过伪造日期模块来生成不同的时间。
  * [responses](https://github.com/getsentry/responses) ⭐ 4,344 | 🐛 40 | 🌐 Python | 📅 2026-07-24：伪造 Python 中的 requests 库的一个通用库。
  * [VCR.py](https://github.com/kevin1024/vcrpy) ⭐ 2,982 | 🐛 157 | 🌐 Python | 📅 2026-08-11：在你的测试中记录和重放 HTTP 交互。
  * [httmock](https://github.com/patrys/httmock) ⭐ 472 | 🐛 15 | 🌐 Python | 📅 2023-09-29：针对 Python 2.6+ 和 3.2+ 生成 伪造请求的库。
  * [mocket](https://github.com/mindflayer/python-mocket) ⭐ 312 | 🐛 5 | 🌐 Python | 📅 2026-07-13：gevent/asyncio/SSL 支持的 socket mock 框架。
  * [mock](https://docs.python.org/3/library/unittest.mock.html)：(Python 标准库) 一个用于伪造测试的库。
  * [doublex](https://pypi.python.org/pypi/doublex)：Python 的一个功能强大的 doubles 测试框架。
  * [httpretty](http://falcao.it/HTTPretty/)：Python 的 HTTP 请求 mock 工具。
* 对象工厂
  * [mixer](https://github.com/klen/mixer) ⭐ 955 | 🐛 49 | 🌐 Python | 📅 2024-03-08：另外一个测试固件 (test fixtures) 替代库，支持 Django, Flask, SQLAlchemy, Peewee 等。
  * [factoryboy](https://github.com/rbarrois/factoryboy)：一个 Python 用的测试固件 (test fixtures) 替代库。
  * [modelmommy](https://github.com/vandersonmota/modelmommy)：为 Django 测试创建随机固件。
* 代码覆盖率
  * [coverage](https://pypi.python.org/pypi/coverage)：代码覆盖率测量。
  * [Codecov](https://codecov.io/)：一个代码覆盖率测试工具，为开源项目提供免费代码覆盖率测试服务。
* 伪数据
  * [mimesis](https://github.com/lk-geimfari/mimesis) ⭐ 4,840 | 🐛 12 | 🌐 Python | 📅 2026-08-05：一个帮助你生成伪数据的 Python 库。
  * [fake2db](https://github.com/emirozer/fake2db) ⭐ 2,349 | 🐛 7 | 🌐 Python | 📅 2019-11-25：伪数据库生成器。
  * [faker](http://www.joke2k.net/faker/)：一个 Python 库，用来生成伪数据。
  * [radar](https://pypi.python.org/pypi/radar)：生成随机的日期/时间。
* 错误处理
  * [FuckIt.py](https://github.com/ajalt/fuckitpy) ⭐ 5,289 | 🐛 13 | 🌐 Python | 📅 2023-08-12：使用最先进的技术来保证你的 Python 代码无论对错都能继续运行。

### 渗透测试

渗透测试相关框架和工具。

* [sqlmap](https://github.com/sqlmapproject/sqlmap) ⭐ 38,204 | 🐛 32 | 🌐 Python | 📅 2026-08-16：自动 SQL 注入和数据库接管工具。
* [setoolkit](https://github.com/trustedsec/social-engineer-toolkit) ⭐ 15,202 | 🐛 12 | 🌐 Python | 📅 2026-06-04：社会工程工具包。
* [fsociety](https://github.com/Manisso/fsociety) ⭐ 12,252 | 🐛 95 | 🌐 Python | 📅 2026-07-21：一款渗透测试框架。

### 代码分析和 Lint 工具

进行代码分析、解析和操作代码库的库和工具。

* 静态类型检查，也可以参考 [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing) ⭐ 1,976 | 🐛 7 | 📅 2026-06-19

  * [pyre-check](https://github.com/facebook/pyre-check) ⚠️ Archived：性能类型检查。
  * [typeshed](https://github.com/python/typeshed) ⭐ 5,109 | 🐛 368 | 🌐 Python | 📅 2026-08-16：带有静态类型的Python库存根的集合。
  * [mypy](http://mypy-lang.org/)：在编译期间检查变量类型。

* 代码分析
  * [vulture](https://github.com/jendrikseipp/vulture) ⭐ 4,767 | 🐛 69 | 🌐 Python | 📅 2026-04-30：用于发现和分析无效 Python 代码的工具。
  * [code2flow](https://github.com/scottrogowski/code2flow) ⭐ 4,603 | 🐛 38 | 🌐 Python | 📅 2025-07-27：把你的 Python 和 JavaScript 代码转换为流程图。
  * [prospector](https://github.com/PyCQA/prospector) ⭐ 2,085 | 🐛 34 | 🌐 Python | 📅 2026-08-14：分析 Python 代码的工具。
  * [pycallgraph](https://github.com/gak/pycallgraph) ⚠️ Archived：这个库可以把你的 Python 应用的流程(调用图)进行可视化。
  * [pysonar2](https://github.com/yinwang0/pysonar2) ⭐ 1,425 | 🐛 2 | 🌐 Java | 📅 2026-03-02：Python 类型推断和检索工具。
  * [coala](http://coala-analyzer.org/)：语言独立和易于扩展的代码分析应用程序。

* Lint 工具
  * [YAPF](https://github.com/google/yapf) ⭐ 13,980 | 🐛 419 | 🌐 Python | 📅 2026-08-14：Google 的 Python 代码格式化工具。

  * [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) ⭐ 2,889 | 🐛 23 | 🌐 Python | 📅 2026-08-14：有史以来最严格的 Python 代码审查工具。

  * [Flake8](https://pypi.python.org/pypi/flake8)：模块化源码检查工具，提供与 `pycodestyle`、`pyflakes` 、McCabe 相关的装饰器。
    * [awesome-flake8-extensions](https://github.com/DmytroLitvinov/awesome-flake8-extensions) ⭐ 1,279 | 🐛 1 | 📅 2026-07-21

  * [Pylint](https://www.pylint.org/)：一个完全可定制的源码分析器。

  * [pylama](https://pylama.readthedocs.org/en/latest/)：Python 和 JavaScript 的代码审查工具。

* 代码格式化
  * [black](https://github.com/ambv/black) ⭐ 41,806 | 🐛 305 | 🌐 Python | 📅 2026-08-10：一个坚定的 Python 代码格式化工具。
  * [isort](https://github.com/timothycrosley/isort) ⭐ 6,949 | 🐛 92 | 🌐 Python | 📅 2026-08-16：用于纠正包导入顺序的 Python 库。
  * [autopep8](https://github.com/hhatto/autopep8) ⭐ 4,660 | 🐛 136 | 🌐 Python | 📅 2026-07-20：自动格式化 Python 代码，以使其符合 PEP8 规范。

* 静态类型注释生成器

  * [pytype](https://github.com/google/pytype) ⭐ 5,029 | 🐛 5 | 🌐 Python | 📅 2026-03-16：检查和推断 Python 代码中的类型，无需添加注解。
  * [MonkeyType](https://github.com/Instagram/MonkeyType) ⭐ 5,000 | 🐛 78 | 🌐 Python | 📅 2026-02-11：通过收集运行时的类型来为 Python 生成静态类型注释的系统。
  * [pyannotate](https://github.com/dropbox/pyannotate) ⭐ 1,443 | 🐛 40 | 🌐 Python | 📅 2026-07-06：自动生成符合 PEP-484 的注解。

### 调试工具

用来进行代码调试的库。

* 调试器
  * [pyringe](https://github.com/google/pyringe) ⚠️ Archived：可以在 Python 进程中附加和注入代码的调试器。
  * [wdb](https://github.com/Kozea/wdb) ⭐ 1,593 | 🐛 40 | 🌐 Python | 📅 2022-12-06：一个奇异的 web 调试器，通过 WebSockets 工作。
  * [pdb++](https://github.com/antocuni/pdb) ⭐ 1,465 | 🐛 108 | 🌐 Python | 📅 2024-04-15：另一种 pdb 的替代。
  * [ipdb](https://pypi.python.org/pypi/ipdb)：IPython 启用的 [pdb](https://docs.python.org/2/library/pdb.html)。
  * [pudb](https://pypi.python.org/pypi/pudb)：全屏，基于控制台的 Python 调试器。
  * [winpdb](http://winpdb.org/)：一个具有图形用户界面的 Python 调试器，可以进行远程调试，基于 rpdb2。

* 追踪器
  * [pyringe](https://github.com/google/pyringe) ⚠️ Archived：能够附加到 Python 进程并将代码注入Python进程的调试器。
  * [python-hunter](https://github.com/ionelmc/python-hunter) ⭐ 872 | 🐛 49 | 🌐 Python | 📅 2025-08-22：一个灵活的代码追踪工具包。
  * [lptrace](https://github.com/khamidou/lptrace) ⭐ 700 | 🐛 7 | 🌐 Python | 📅 2018-10-26：为 Python 程序打造的 [strace](http://man7.org/linux/man-pages/man1/strace.1.html)。
  * [manhole](https://github.com/ionelmc/python-manhole) ⭐ 402 | 🐛 9 | 🌐 Python | 📅 2024-07-04：调试UNIX套接字连接，并显示所有线程的堆栈跟踪和交互式提示。

* 性能分析器
  * [py-spy](https://github.com/benfred/py-spy) ⭐ 15,435 | 🐛 236 | 🌐 Rust | 📅 2026-08-14：Python 程序采样分析器，使用 Rust 实现。
  * [vprof](https://github.com/nvdv/vprof) ⭐ 3,980 | 🐛 30 | 🌐 Python | 📅 2022-07-15：视觉 Python 分析器。
  * [pyflame](https://github.com/uber/pyflame) ⚠️ Archived：用于 Python 的跟踪分析器。
  * [profiling](https://github.com/what-studio/profiling) ⚠️ Archived：一个交互式 Python 性能分析工具。
  * [lineprofiler](https://github.com/rkern/lineprofiler)：逐行性能分析。
  * [Memory Profiler](http://pypi.python.org/pypi/memory_profiler)、[内存](https://github.com/fabianp/memoryprofiler)：监控 Python 代码的内存使用。

* 其他
  * [icecream](https://github.com/gruns/icecream) ⭐ 10,105 | 🐛 68 | 🌐 Python | 📅 2026-08-10：通过一个简单的函数调用检查变量、表达式和程序执行情况。
  * [django-debug-toolbar](https://github.com/django-debug-toolbar/django-debug-toolbar) ⭐ 8,378 | 🐛 82 | 🌐 Python | 📅 2026-08-16：为 Django 显示各种调试信息。
  * [pyelftools](https://github.com/eliben/pyelftools) ⭐ 2,271 | 🐛 56 | 🌐 Python | 📅 2026-07-30：解析和分析 ELF 文件以及 DWARF 调试信息。
  * [django-devserver](https://github.com/dcramer/django-devserver) ⭐ 1,266 | 🐛 59 | 🌐 Python | 📅 2020-02-26：一个 Django 运行服务器的替代品。
  * [flask-debugtoolbar](https://github.com/mgood/flask-debugtoolbar) ⭐ 978 | 🐛 43 | 🌐 JavaScript | 📅 2026-08-03：django-debug-toolbar 的 flask 版。
  * [python-statsd](https://github.com/WoLpH/python-statsd) ⭐ 110 | 🐛 1 | 🌐 Python | 📅 2019-02-15：[statsd](https://github.com/etsy/statsd/) ⭐ 18,070 | 🐛 90 | 🌐 JavaScript | 📅 2025-05-20 服务器的 Python 客户端。

### 科学计算和数据分析

用来进行科学计算和数据分析的库。

* [zipline](https://github.com/quantopian/zipline) ⭐ 20,042 | 🐛 370 | 🌐 Python | 📅 2024-02-13：一个 Python 算法交易库。
* [SymPy](https://github.com/sympy/sympy) ⭐ 14,873 | 🐛 5,955 | 🌐 Python | 📅 2026-08-16：一个用于符号数学的 Python 库。
* [statsmodels](https://github.com/statsmodels/statsmodels) ⭐ 11,580 | 🐛 2,829 | 🌐 Python | 📅 2026-08-16：统计建模和计量经济学。
* [PyMC](https://github.com/pymc-devs/pymc3) ⭐ 9,710 | 🐛 477 | 🌐 Python | 📅 2026-08-16：马尔科夫链蒙特卡洛采样工具。
* [AWS Data Wrangler](https://github.com/awslabs/aws-data-wrangler) ⭐ 4,115 | 🐛 58 | 🌐 Python | 📅 2026-08-15：AWS 平台上使用的 Pandas。
* [Karate Club](https://github.com/benedekrozemberczki/karateclub) ⭐ 2,285 | 🐛 12 | 🌐 Python | 📅 2024-07-17：用于图形结构化数据的无监督机器学习工具箱。
* [Optimus](https://github.com/ironmussa/Optimus) ⭐ 1,536 | 🐛 30 | 🌐 Python | 📅 2024-12-02：在使用 PySpark 时，让敏捷数据科学工作流程变得简单。
* [ObsPy](https://github.com/obspy/obspy/wiki/) ⭐ 1,326 | 🐛 311 | 🌐 Python | 📅 2026-08-10：地震学 Python 工具箱。
* [Open Mining](https://github.com/mining/mining) ⚠️ Archived：使用 Python 挖掘商业情报 (BI) (Pandas web 接口)。
* [Bayesian-belief-networks](https://github.com/eBay/bayesian-belief-networks) ⚠️ Archived：优雅的贝叶斯理念网络框架。
* [bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen) ⭐ 1,030 | 🐛 133 | 🌐 Python | 📅 2024-08-24：这个工具箱为全自动高通量测序分析提供符合最佳实践的处理流程。
* [bccb](https://github.com/chapmanb/bcbb) ⭐ 645 | 🐛 20 | 🌐 Python | 📅 2025-02-05：生物分析相关代码集合。
* [astropy](http://www.astropy.org/)：一个天文学 Python 库。
* [Biopython](http://biopython.org/wiki/MainPage)：Biopython 是一组可以免费使用的用来进行生物计算的工具。
* [blaze](http://blaze.readthedocs.org/en/latest/index.html)：NumPy 和 Pandas 的大数据接口。
* [cclib](http://cclib.github.io/)：一个用来解析和解释计算化学软件包输出结果的库。
* [NetworkX](https://networkx.github.io/)：一个为复杂网络设计的高性能软件。
* [Neupy](http://neupy.com/pages/home.html)：执行和测试各种不同的人工神经网络算法。
* [NumPy](http://www.numpy.org/)：使用 Python 进行科学计算的基础包。
* [Open Babel](http://openbabel.org/wiki/MainPage)：一个化学工具箱，用来描述多种化学数据。
* [orange](http://orange.biolab.si/)：通过可视化编程或 Python 脚本进行数据挖掘，数据可视化，分析和机器学习。
* [Pandas](http://pandas.pydata.org/)：提供高性能，易用的数据结构和数据分析工具。
* [PyDy](http://www.pydy.org/)：PyDy 是 Python Dynamics 的缩写，用来为动力学运动建模工作流程提供帮助， 基于 NumPy, SciPy, IPython 和 matplotlib。
* [RDKit](http://www.rdkit.org/)：化学信息学和机器学习软件。
* [SciPy](http://www.scipy.org/)：由一些基于 Python ，用于数学，科学和工程的开源软件构成的生态系统。
* [Colour](http://colour-science.org/)：大量色彩理论转换和算法的实现。
* [NIPY](http://nipy.org)：神经影响学工具箱集合。
* [QuTiP](http://qutip.org/)：Python 版 Quantum 工具箱。
* [SimPy](https://gitlab.com/team-simpy/simpy)：一个基于过程的离散事件模拟框架。

### 数据可视化

进行数据可视化的库。 参见：[awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization) ⭐ 35,018 | 🐛 29 | 📅 2026-07-31。

* [diagrams](https://github.com/mingrammer/diagrams) ⭐ 42,515 | 🐛 386 | 🌐 Python | 📅 2026-08-16：用图表作为代码。
* [bokeh](https://github.com/bokeh/bokeh) ⭐ 20,431 | 🐛 860 | 🌐 TypeScript | 📅 2026-08-16：用 Python 进行交互式 web 绘图。
* [pyecharts](https://github.com/chenjiandongx/pyecharts) ⭐ 15,775 | 🐛 4 | 🌐 Python | 📅 2026-08-04：基于百度 Echarts 的数据可视化库。
* [Seaborn](https://github.com/mwaskom/seaborn) ⭐ 14,004 | 🐛 228 | 🌐 Python | 📅 2026-07-06：使用 Matplotlib 进行统计数据可视化。
* [Altair](https://github.com/altair-viz/altair) ⭐ 10,453 | 🐛 143 | 🌐 Python | 📅 2026-08-16：用于 Python 的声明式统计可视化库。
* [plotnine](https://github.com/has2k1/plotnine) ⭐ 4,759 | 🐛 84 | 🌐 Python | 📅 2026-08-15：基于ggplot2的Python图形语法。
* [bqplot](https://github.com/bloomberg/bqplot) ⭐ 3,694 | 🐛 278 | 🌐 TypeScript | 📅 2026-05-07：Jupyter Notebook 的交互式绘图库。
* [ggplot](https://github.com/yhat/ggplot) ⚠️ Archived：ggplot2 给 R 提供的 API 的 Python 版本。
* [vincent](https://github.com/wrobstory/vincent) ⚠️ Archived：把 Python 转换为 Vega 语法的转换工具。
* [Cartopy](https://github.com/SciTools/cartopy) ⭐ 1,615 | 🐛 332 | 🌐 Python | 📅 2026-08-12：具有 matplotlib 支持的 Python 制图库。
* [matplotlib](http://matplotlib.org/)：一个 Python 2D 绘图库。
* [plotly](https://plot.ly/python/)：协同 Python 和 matplotlib 工作的 web 绘图库。
* [pygal](http://www.pygal.org/en/latest/)：一个 Python SVG 图表创建工具。
* [pygraphviz](https://pypi.python.org/pypi/pygraphviz)：Graphviz 的 Python 接口。
* [PyQtGraph](http://www.pyqtgraph.org/)：交互式实时 2D/3D/ 图像绘制及科学/工程学组件。
* [SnakeViz](http://jiffyclub.github.io/snakeviz/)：一个基于浏览器的 Python's cProfile 模块输出结果查看工具。
* [VisPy](http://vispy.org/)：基于 OpenGL 的高性能科学可视化工具。
* [Dash](https://plot.ly/products/dash/)：构建在 Flask、React 和 Plotly 之上，旨在用于分析 Web 应用程序。
  * [awesome-dash](https://github.com/Acrotrend/awesome-dash) ⭐ 2,267 | 🐛 1 | 🌐 Python | 📅 2024-12-30
* [PyGraphviz](https://pypi.org/project/pygraphviz/)： [Graphviz](http://www.graphviz.org/) 的 Python 接口。

### 计算机视觉

计算机视觉相关库。

* [Face Recognition](https://github.com/ageitgey/face_recognition) ⭐ 56,658 | 🐛 830 | 🌐 Python | 📅 2026-06-25：简单的面部识别库。
* [EasyOCR](https://github.com/JaidedAI/EasyOCR) ⭐ 29,911 | 🐛 530 | 🌐 Python | 📅 2025-12-05：支持40多种语言的即用型 OCR。
* [Kornia](https://github.com/kornia/kornia/) ⭐ 11,315 | 🐛 86 | 🌐 Python | 📅 2026-08-16：PyTorch 的开源差异化计算机视觉库。
* [pytesseract](https://github.com/madmaze/pytesseract) ⭐ 6,379 | 🐛 21 | 🌐 Python | 📅 2026-07-13：[Google Tesseract OCR](https://github.com/tesseract-ocr) 的另一包装库。
* [tesserocr](https://github.com/sirfz/tesserocr) ⭐ 2,171 | 🐛 46 | 🌐 Python | 📅 2026-08-04：另一个简单的，兼容 Pillow 的 `tesseract-ocr` API 装饰器，可用于 OCR。
* [pyocr](https://github.com/jflesch/pyocr) ⚠️ Archived：Tesseract 和 Cuneiform 的包装库。
* [OpenCV](http://opencv.org/)：开源计算机视觉库。
* [SimpleCV](http://simplecv.org/)：一个用来创建计算机视觉应用的开源框架。

### 深度学习

神经网络和深度学习相关框架。 也可以参考 [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning) ⭐ 28,766 | 🐛 84 | 📅 2025-05-26。

* [Caffe](http://caffe.berkeleyvision.org)：一个 [Caffe](https://github.com/BVLC/caffe) ⭐ 34,562 | 🐛 1,565 | 🌐 C++ | 📅 2024-07-31 的 python 接口。
* [Theano](https://github.com/Theano/Theano) ⭐ 9,999 | 🐛 699 | 🌐 Python | 📅 2024-01-15：一个快速数值计算库。
* [SerpentAI](https://github.com/SerpentAI/SerpentAI) ⚠️ Archived：游戏代理框架，可使用任意视频游戏作为深度学习沙箱。
* [skflow](https://github.com/tensorflow/skflow) ⚠️ Archived：一个 [TensorFlow](https://github.com/tensorflow/tensorflow) ⭐ 197,087 | 🐛 2,868 | 🌐 C++ | 📅 2026-08-16 的简化接口(模仿 scikit-learn)。
* [pydeep](https://github.com/andersbll/deeppy) ⭐ 1,370 | 🐛 22 | 🌐 Python | 📅 2020-12-28：Python 深度学习库。
* [hebel](https://github.com/hannes-brt/hebel) ⭐ 1,169 | 🐛 6 | 🌐 Python | 📅 2020-12-29：GPU 加速的深度学习库。
* [Caffe2](https://caffe2.ai/)：一个轻量级的，模块化的，可扩展的深度学习框架。
* [keras](https://keras.io/)：以 tensorflow/theano/CNTK 为后端的深度学习封装库，快速上手神经网络。
* [MXNet](http://mxnet.incubator.apache.org/)：一个高效和灵活的深度学习框架。
* [Pytorch](http://pytorch.org/)：一个具有张量和动态神经网络，并有强大 GPU 加速能力的深度学习框架。
* [TensorFlow](http://tensorflow.org/)：谷歌开源的最受欢迎的深度学习框架。

### 机器学习

机器学习相关库，也可以参考 [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python) ⭐ 74,036 | 🐛 24 | 🌐 Python | 📅 2026-08-11。

* [MindsDB](https://github.com/mindsdb/mindsdb) ⭐ 39,591 | 🐛 3 | 🌐 Makefile | 📅 2026-08-13：MindsDB 是现有数据库的开源 AI 层，可让使用标准查询轻松地进行开发，训练和部署最新的机器学习模型。
* [gym](https://github.com/openai/gym) ⚠️ Archived：开发和比较强化学习算法的工具包。
* [xgboost](https://github.com/dmlc/xgboost) ⭐ 28,659 | 🐛 419 | 🌐 C++ | 📅 2026-08-15：可扩展，便携式和分布式梯度提升库。
* [pattern](https://github.com/clips/pattern) ⭐ 8,859 | 🐛 179 | 🌐 Python | 📅 2026-08-05：Python 网络挖掘模块。
* [H2O](https://github.com/h2oai/h2o-3) ⭐ 7,495 | 🐛 2,880 | 🌐 Jupyter Notebook | 📅 2026-08-16：开源快速可扩展的机器学习平台。
* [NuPIC](https://github.com/numenta/nupic) ⭐ 6,351 | 🐛 465 | 🌐 Python | 📅 2024-12-03：智能计算 Numenta 平台。
* [PyBrain](https://github.com/pybrain/pybrain) ⭐ 2,857 | 🐛 156 | 🌐 Python | 📅 2024-06-27：另一个 Python 机器学习库。
* [Pylearn2](https://github.com/lisa-lab/pylearn2) ⭐ 2,769 | 🐛 201 | 🌐 Python | 📅 2021-08-20：一个基于 [Theano](https://github.com/Theano/Theano) ⭐ 9,999 | 🐛 699 | 🌐 Python | 📅 2024-01-15 的机器学习库。
* [Metrics](https://github.com/benhamner/Metrics) ⭐ 1,651 | 🐛 36 | 🌐 Python | 📅 2023-01-11：机器学习的评估指标。
* [python-recsys](https://github.com/ocelma/python-recsys) ⭐ 1,480 | 🐛 9 | 🌐 Python | 📅 2020-12-29：一个用来实现推荐系统的 Python 库。
* [Crab](https://github.com/muricoca/crab) ⭐ 1,175 | 🐛 46 | 🌐 Python | 📅 2020-12-30：灵活、快速的推荐引擎。
* [vowpal\_porpoise](https://github.com/josephreisinger/vowpal_porpoise) ⭐ 174 | 🐛 8 | 🌐 Python | 📅 2020-01-07：Python 版 [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/) ⭐ 8,702 | 🐛 3 | 🌐 C++ | 📅 2026-07-15 装饰器。
* [scikit-learn](http://scikit-learn.org/)：基于 SciPy 构建的机器学习 Python 模块。
* [vowpalporpoise](https://github.com/josephreisinger/vowpalporpoise)：轻量级 [Vowpal Wabbit](https://github.com/JohnLangford/vowpalwabbit/) 的 Python 封装。

### 推荐系统

用于构建推荐系统的相关库。

* [annoy](https://github.com/spotify/annoy) ⭐ 14,288 | 🐛 84 | 🌐 C++ | 📅 2025-10-29：对 C++/Python 实现的近似近邻算法进行了内存优化。
* [Surprise](https://github.com/NicolasHug/Surprise) ⭐ 6,805 | 🐛 80 | 🌐 Python | 📅 2026-05-30：用于构建和分析推荐系统的科学工具。
* [lightfm](https://github.com/lyst/lightfm) ⭐ 5,111 | 🐛 166 | 🌐 Python | 📅 2024-07-24：很多流行的推荐算法的 Python 实现。
* [implicit](https://github.com/benfred/implicit) ⭐ 3,814 | 🐛 97 | 🌐 Python | 📅 2026-05-08：对隐式数据集进行协作过滤的快速 Python 实现。
* [spotlight](https://github.com/maciejkula/spotlight) ⭐ 3,044 | 🐛 73 | 🌐 Python | 📅 2022-12-21：使用 PyTorch 实现的深度推荐模型。
* [libffm](https://github.com/guestwalk/libffm) ⚠️ Archived：Field-aware Factorization Machine (FFM) 相关库。
* [tensorrec](https://github.com/jfkirk/tensorrec) ⭐ 1,300 | 🐛 40 | 🌐 Python | 📅 2023-05-22：TensorFlow 的推荐引擎框架。
* [fastFM](https://github.com/ibayer/fastFM) ⭐ 1,086 | 🐛 51 | 🌐 Python | 📅 2022-07-17：Factorization Machine 相关库。

### 分布式计算

分布式计算相关的框架和库。

* [Ray](https://github.com/ray-project/ray/) ⭐ 43,534 | 🐛 3,485 | 🌐 Python | 📅 2026-08-16：一个用于并行和分布式 Python 的系统，它统一了机器学习生态系统。
* [luigi](https://github.com/spotify/luigi) ⭐ 18,764 | 🐛 166 | 🌐 Python | 📅 2026-07-18：这个模块帮你构建批处理作业的复杂流水线。
* [dask](https://github.com/dask/dask) ⭐ 13,890 | 🐛 1,310 | 🌐 Python | 📅 2026-08-10：用于分析计算的灵活的并行计算库。
* [faust](https://github.com/robinhood/faust) ⭐ 6,823 | 🐛 279 | 🌐 Python | 📅 2024-07-27：一个 Python 流处理库，核心思想来源 [Kafka Streams](https://kafka.apache.org/documentation/streams/)。
* [mars](https://github.com/mars-project/mars) ⭐ 2,741 | 🐛 215 | 🌐 Python | 📅 2024-01-02：是基于张量的，用于进行大规模数据计算的统一计算框架。
* [dpark](https://github.com/douban/dpark) ⚠️ Archived：Spark 的 Python 克隆版，一个类似 MapReduce 的框架。
* [mrjob](https://github.com/Yelp/mrjob) ⭐ 2,613 | 🐛 217 | 🌐 Python | 📅 2026-04-02：在 Hadoop 或 Amazon Web Services 上运行 MapReduce 任务。
* [streamparse](https://github.com/Parsely/streamparse) ⭐ 1,505 | 🐛 61 | 🌐 Python | 📅 2026-04-22：运行针对事实数据流的 Python 代码。集成了 [Apache Storm](http://storm.apache.org/)。
* [dumbo](https://github.com/klbostee/dumbo) ⭐ 1,030 | 🐛 28 | 🌐 Python | 📅 2018-01-09：这个 Python 模块可以让人轻松的编写和运行 Hadoop 程序。
* [PySpark](http://spark.apache.org/docs/latest/programming-guide.html)：Spark 的 Python API 。

### 函数式编程

使用 Python 进行函数式编程。

* [Toolz](https://github.com/pytoolz/toolz) ⭐ 5,151 | 🐛 135 | 🌐 Python | 📅 2026-01-01：一组用于迭代器，函数和字典的函数式编程工具。
* [Coconut](https://github.com/evhub/coconut) ⭐ 4,349 | 🐛 90 | 🌐 Python | 📅 2026-02-16：为了简单、优雅、更 Pythonic 的函数式编程而构建的 Python 变体。
* [returns](https://github.com/dry-python/returns) ⭐ 4,347 | 🐛 81 | 🌐 Python | 📅 2026-08-15：一个类型安全的单元、转换器与合成工具集合。
* [more-itertools](https://github.com/erikrose/more-itertools) ⭐ 4,087 | 🐛 7 | 🌐 Python | 📅 2026-08-12：比 `itertools` 拥有更多的可迭代对象的操作方式。
* [funcy](https://github.com/Suor/funcy) ⭐ 3,509 | 🐛 16 | 🌐 Python | 📅 2026-04-19：炫酷又实用的函数式工具。
* [fn.py](https://github.com/kachayev/fn.py) ⭐ 3,368 | 🐛 33 | 🌐 Python | 📅 2022-08-30：在 Python 中进行函数式编程：实现了一些享受函数式编程缺失的功能。
* [CyToolz](https://github.com/pytoolz/cytoolz/) ⭐ 1,111 | 🐛 34 | 🌐 Python | 📅 2025-12-01：Toolz 的 Cython 实现：高性能函数式工具。

### 第三方 API

用来访问第三方 API 的库。 参见： [List of Python API Wrappers and Libraries](https://github.com/realpython/list-of-python-api-wrappers) ⭐ 2,161 | 🐛 11 | 📅 2023-08-29。

* [boto3](https://github.com/boto/boto3) ⭐ 9,873 | 🐛 187 | 🌐 Python | 📅 2026-08-14：Amazon Web Services 的 Python 接口。
* [google-api-python-client](https://github.com/google/google-api-python-client) ⭐ 8,902 | 🐛 61 | 🌐 Python | 📅 2026-07-14：Python 用的 Google APIs 客户端库。
* [gspread](https://github.com/burnash/gspread) ⭐ 7,496 | 🐛 70 | 🌐 Python | 📅 2026-07-30：Google 电子表格的 Python API。
* [facebook-sdk](https://github.com/mobolic/facebook-sdk) ⭐ 2,793 | 🐛 38 | 🌐 Python | 📅 2024-08-02：Facebook 平台的 Python SDK。
* [twython](https://github.com/ryanmcgrath/twython) ⭐ 1,861 | 🐛 29 | 🌐 Python | 📅 2022-07-30：Twitter API 的封装。
* [gmail](https://github.com/charlierguo/gmail) ⭐ 1,802 | 🐛 64 | 🌐 Python | 📅 2023-07-09：Gmail 的 Python 接口。
* [facepy](https://github.com/jgorset/facepy) ⭐ 851 | 🐛 3 | 🌐 Python | 📅 2020-04-04：Facepy 让和 Facebook's Graph API 的交互变得更容易。
* [django-wordpress](https://github.com/sunlightlabs/django-wordpress/) ⭐ 361 | 🐛 5 | 🌐 Python | 📅 2021-06-07：Django 的 WordPress 模型与视图。
* [apache-libcloud](https://libcloud.apache.org/)：一个为各种云设计的 Python 库。

### DevOps 工具

用于 DevOps 的软件和库。

* [Ansible](https://github.com/ansible/ansible) ⭐ 70,336 | 🐛 830 | 🌐 Python | 📅 2026-08-11：一个非常简单的 IT 自动化平台。
* [SaltStack](https://github.com/saltstack/salt) ⭐ 15,615 | 🐛 1,925 | 🌐 Python | 📅 2026-08-16：基础设施自动化和管理系统。
* [psutil](https://github.com/giampaolo/psutil) ⭐ 11,265 | 🐛 255 | 🌐 Python | 📅 2026-08-16：一个跨平台进程和系统工具模块。
* [supervisor](https://github.com/Supervisor/supervisor) ⭐ 9,102 | 🐛 181 | 🌐 Python | 📅 2025-12-21：UNIX 的进程控制系统。
* [pyinfra](https://github.com/Fizzadar/pyinfra) ⭐ 5,953 | 🐛 191 | 🌐 Python | 📅 2026-07-27：一个通用的 CLI 工具包和 python 库，用于自动化的基础设施。
* [pexpect](https://github.com/pexpect/pexpect) ⭐ 2,847 | 🐛 170 | 🌐 Python | 📅 2025-04-11：在一个伪终端中控制交互程序，就像 GNU expect 一样。
* [honcho](https://github.com/nickstenning/honcho) ⭐ 1,713 | 🐛 26 | 🌐 Python | 📅 2025-06-03：[Foreman](https://github.com/ddollar/foreman) ⭐ 6,156 | 🐛 72 | 🌐 Ruby | 📅 2025-07-27 的 Python 克隆版，用来管理基于 [Procfile](https://devcenter.heroku.com/articles/procfile) 的应用。
* [honcho](https://github.com/nickstenning/honcho) ⭐ 1,713 | 🐛 26 | 🌐 Python | 📅 2025-06-03：[Foreman](https://github.com/ddollar/foreman) ⭐ 6,156 | 🐛 72 | 🌐 Ruby | 📅 2025-07-27 的 Python 克隆版，用于管理基于 Procfile 的应用。
* [cuisine](https://github.com/sebastien/cuisine) ⭐ 1,265 | 🐛 26 | 🌐 Python | 📅 2024-05-21：为 Fabric 提供一系列高级函数。
* [Fabtools](https://github.com/ronnix/fabtools) ⭐ 1,251 | 🐛 104 | 🌐 Python | 📅 2019-12-13：一个用来编写超赞的 Fabric 文件的工具。
* [OpenStack](http://www.openstack.org/)：用于构建私有和公有云的开源软件。
* [Docker Compose](https://docs.docker.com/compose/)：快速，分离的开发环境，使用 Docker。
* [Fabric](http://www.fabfile.org/)：一个简单的，Python 风格的工具，用来进行远程执行和部署。
* [gitapi](https://bitbucket.org/haard/gitapi)：Git 的纯 Python API。
* [hgapi](https://bitbucket.org/haard/hgapi)：Mercurial 的纯 Python API。
* [cloudinit](https://cloudinit.readthedocs.io/en/latest/)：一个多分发包，用于处理云实例的早期初始化。
* [BorgBackup](https://www.borgbackup.org/)：具有压缩和加密功能的重复数据删除存档器。
* [docker-compose](https://docs.docker.com/compose/)： 使用 [Docker](https://www.docker.com/) 的快速独立的开发环境。

### 任务调度

任务调度库。

* [Prefect](https://github.com/PrefectHQ/prefect) ⭐ 23,632 | 🐛 848 | 🌐 Python | 📅 2026-08-15：一个现代的工作流程编排框架，使构建、计划和监视健壮的数据管道变得容易。
* [schedule](https://github.com/dbader/schedule) ⭐ 12,259 | 🐛 178 | 🌐 Python | 📅 2024-05-25：人性化的 Python 任务调度库。
* [Spiff](https://github.com/knipknap/SpiffWorkflow) ⭐ 1,910 | 🐛 8 | 🌐 Python | 📅 2026-08-10：使用纯 Python 实现的强大的工作流引擎。
* [Plan](https://github.com/fengsp/plan) ⭐ 1,184 | 🐛 4 | 🌐 Python | 📅 2022-07-16：如有神助地编写 crontab 文件。
* [django-schedule](https://github.com/thauber/django-schedule) ⭐ 847 | 🐛 22 | 🌐 Python | 📅 2019-12-29：一个 Django 排程应用。
* [gunnery](https://github.com/gunnery/gunnery) ⭐ 770 | 🐛 16 | 🌐 Python | 📅 2022-03-29：分布式系统使用的多用途任务执行工具 ，具有 web 交互界面。
* [APScheduler](http://apscheduler.readthedocs.org/en/latest/)：轻巧但强大的进程内任务调度，使你可以调度函数。
* [doit](http://pydoit.org/)：一个任务执行和构建工具。
* [Joblib](http://pythonhosted.org/joblib/index.html)：一组为 Python 提供轻量级作业流水线的工具。
* [TaskFlow](http://docs.openstack.org/developer/taskflow/)：一个可以让你方便执行任务的 Python 库，一致并且可靠。
* [Airflow](https://airflow.apache.org/) ：是一个工作流分配管理系统，通过有向非循环图的方式管理任务流程，设置任务依赖关系和时间调度。

### 外来函数接口

使用外来函数接口的库。

* [cffi](https://pypi.python.org/pypi/cffi)：用来调用 C 代码的外来函数接口。
* [ctypes](https://docs.python.org/2/library/ctypes.html)：(Python 标准库) 用来调用 C 代码的外来函数接口。
* [PyCUDA](https://mathema.tician.de/software/pycuda/)：Nvidia CUDA API 的封装。
* [SWIG](http://www.swig.org/Doc1.3/Python.html)：简化的封装和接口生成器。

### 重构

Python 重构相关库和工具。

* [Bicycle Repair Man](http://bicyclerepair.sourceforge.net/)：Python 的重构工具。
* [Bowler](https://pybowler.io/)：适用于现代Python的安全代码重构。
* [Rope](https://github.com/python-rope/rope) ⭐ 2,232 | 🐛 140 | 🌐 Python | 📅 2026-08-16：一个 Python 的重构库。

### 高性能

让 Python 更快的库。

* [MicroPython](https://github.com/micropython/micropython) ⭐ 21,991 | 🐛 1,537 | 🌐 C | 📅 2026-08-16：精简高效的 Python 编程语言实现。
* [Grumpy](https://github.com/google/grumpy) ⚠️ Archived：编译器比解释器更强大的 cpython2.7 替代品（alpha）。
* [Pyston](https://github.com/dropbox/pyston) ⚠️ Archived：使用 LLVM 和现代 JIT 技术构建的 Python 实现，目标是为了获得很好的性能。
* [IronPython](https://github.com/IronLanguages/ironpython3) ⭐ 2,759 | 🐛 314 | 🌐 C# | 📅 2026-06-20：用 C＃ 编写的 Python 编程语言的实现。
* [PeachPy](https://github.com/Maratyszcza/PeachPy) ⭐ 2,060 | 🐛 28 | 🌐 Python | 📅 2023-09-25：嵌入 Python 的 x86-64 汇编器。可以被用作 Python 内联的汇编器或者是独立的汇编器，用于 Windows，Linux，OS X，Native Client 或者 Go 。
* [Pyjion](https://github.com/Microsoft/Pyjion) ⚠️ Archived：基于 CoreCLR 的 Python JIT。
* [CLPython](https://github.com/metawilm/cl-python) ⭐ 396 | 🐛 2 | 🌐 Common Lisp | 📅 2024-06-13：用 Common Lisp 编写的 Python 编程语言的实现。
* [Cython](http://cython.org/)：优化的 Python 静态编译器。使用类型混合使 Python 编译成 C 或 C++ 模块来获得性能的极大提升。
* [Jython](https://hg.python.org/jython)：为 JVM 用 Java 编写的 Python 编程语言的实现。
* [Numba](http://numba.pydata.org/)：Python JIT (just in time) 编译器，针对科学用的 Python ，由 Cython 和 NumPy 的开发者开发。
* [PyPy](http://pypy.org/)：使用 Python 实现的 Python。解释器使用黑魔法加快 Python 运行速度且不需要加入额外的类型信息。
* [Stackless Python](https://bitbucket.org/stackless-dev/stackless/overview)：一个强化版的 Python。

### 微软的 Windows 平台

在 Windows 平台上进行 Python 编程。

* [Python(x,y)](http://python-xy.github.io/)：面向科学应用的 Python 发行版，基于 Qt 和 Spyder。
* [pythonlibs](http://www.lfd.uci.edu/~gohlke/pythonlibs/)：非官方的 Windows 平台 Python 扩展二进制包。
* [PythonNet](https://github.com/pythonnet/pythonnet) ⭐ 5,509 | 🐛 165 | 🌐 C# | 📅 2026-08-16：Python 与 .NET 公共语言运行库 (CLR)的集成。
* [PyWin32](https://sourceforge.net/projects/pywin32/)：针对 Windows 的 Python 扩展。
* [WinPython](https://winpython.github.io/)：Windows 7/8 系统下便携式开发环境。

### 网络可视化和 SDN

用来进行网络可视化和 SDN(软件定义网络)的工具和库。

* [napalm](https://github.com/napalm-automation/napalm) ⭐ 2,486 | 🐛 172 | 🌐 Python | 📅 2026-08-12：可跨供应商 API 来操纵网络设备。
* [POX](https://github.com/noxrepo/pox) ⭐ 649 | 🐛 48 | 🌐 Python | 📅 2024-10-19：一个针对基于 Python 的软件定义网络应用（例如 OpenFlow SDN 控制器）的开源开发平台。
* [SDX Platform](https://github.com/sdn-ixp/internet2award) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2021-12-26：基于 SDN 的 IXP 实现，影响了 Mininet, POX 和 Pyretic。
* [Mininet](http://mininet.org/)：一款流行的网络模拟器以及用 Python 编写的 API。
* [Pyretic](http://frenetic-lang.org/pyretic/)：火热的 SDN 编程语言中的一员，为网络交换机和模拟器提供强大的抽象能力。
* [NRU](http://ryu.readthedocs.io/en/latest/)：一个基于组件的软件定义网络框架。

### 硬件

用来对硬件进行编程的库。

* [scapy](https://github.com/secdev/scapy) ⭐ 12,474 | 🐛 130 | 🌐 Python | 📅 2026-08-16：一个非常棒的操作数据包的库。
* [keyboard](https://github.com/boppreh/keyboard) ⭐ 3,961 | 🐛 416 | 🌐 Python | 📅 2026-07-10：在 Windows 和 Linux 上挂钩并模拟全局键盘事件。
* [PyUserInput](https://github.com/SavinaRoja/PyUserInput) ⭐ 1,065 | 🐛 76 | 🌐 Python | 📅 2021-09-08：跨平台的，控制鼠标和键盘的模块。
* [mouse](https://github.com/boppreh/mouse) ⚠️ Archived：在 Windows 和 Linux 上挂钩并模拟全局鼠标事件。
* [ino](http://inotool.org/)：操作 [Arduino](https://www.arduino.cc/) 的命令行工具。
* [Pyro](http://pyrorobotics.com/)：Python 机器人编程库。
* [wifi](https://wifi.readthedocs.org/en/latest/)：一个 Python 库和命令行工具用来在 Linux 平台上操作 WiFi。
* [Pingo](http://www.pingo.io/)：Pingo 为类似 Raspberry Pi，pcDuino， Intel Galileo 等设备提供统一的 API 用以编程。

### 兼容性

帮助从 Python 2 向 Python 3 迁移的库。

* [Python-Future](http://python-future.org/index.html)：这就是 Python 2 和 Python 3 之间丢失的那个兼容性层。
* [Six](https://pypi.python.org/pypi/six)：Python 2 和 3 的兼容性工具。
* [modernize](https://github.com/PyCQA/modernize) ⭐ 371 | 🐛 58 | 🌐 Python | 📅 2026-08-10：使 Python 代码更加现代化以便最终迁移到 Python 3。

### 算法和设计模式

数据结构、算法和设计模式的 Python 实现。也可以参考 [awesome-algorithms](https://github.com/tayllan/awesome-algorithms) ⭐ 25,454 | 🐛 0 | 📅 2026-04-18 。

* 算法
  * [TheAlgorithms](https://github.com/TheAlgorithms/Python) ⭐ 223,797 | 🐛 1,030 | 🌐 Python | 📅 2026-08-03：所有算法的 Python 实现。
  * [algorithms](https://github.com/keon/algorithms) ⭐ 25,534 | 🐛 5 | 🌐 Python | 📅 2026-08-01：数据结构和算法的简单示例。
  * [sortedcontainers](https://github.com/grantjenks/python-sortedcontainers) ⭐ 3,972 | 🐛 38 | 🌐 Python | 📅 2024-03-08：排序集合的快速的纯 Python 实现。
  * [python-ds](https://github.com/prabhupant/python-ds) ⭐ 3,091 | 🐛 34 | 🌐 Python | 📅 2024-04-06：用于面试的数据结构和算法的集合。
* 设计模式
  * [python-patterns](https://github.com/faif/python-patterns) ⭐ 42,926 | 🐛 15 | 🌐 Python | 📅 2026-08-13：一个 Python 设计模式集合。
  * [transitions](https://github.com/pytransitions/transitions) ⭐ 6,580 | 🐛 21 | 🌐 Python | 📅 2025-09-11：轻量级的，面向对象的有限状态机实现。
  * [PyPattyrn](https://github.com/tylerlaberge/PyPattyrn) ⚠️ Archived：一个简单而有效的库，用于实现常见的设计模式。

### 内置类的增强版实现

一些 Python 内置类的增强版实现库。

* [attrs](https://github.com/python-attrs/attrs) ⭐ 5,830 | 🐛 148 | 🌐 Python | 📅 2026-08-07：一个在类定义时可替换 `__init__`, `__eq__`, `__repr__`等方法的样板。
* [Box](https://github.com/cdgriffith/Box) ⭐ 2,831 | 🐛 45 | 🌐 Python | 📅 2026-02-21：具有高级点符号访问权限的 Python 字典。
* [bidict](https://github.com/jab/bidict) ⭐ 1,584 | 🐛 3 | 🌐 Python | 📅 2026-08-16：高效的 Pythonic 的双向映射数据结构和相关功能。
* [DottedDict](https://github.com/carlosescri/DottedDict) ⭐ 221 | 🐛 9 | 🌐 Python | 📅 2024-12-09：提供一种使用点路径符号访问列表和字典的方法的库。
* [dataclasses](https://docs.python.org/3/library/dataclasses.html)：(Python 标准库) 数据类。

### 机器人

机器人相关库。

* [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐ 30,308 | 🐛 50 | 🌐 Python | 📅 2026-08-10：各种具有可视化效果的机器人算法的汇总。
* [rospy](http://wiki.ros.org/rospy)：ROS (Robot Operating System) 库。

### 聊天工具

聊天机器人开发相关的库。

* [errbot](https://github.com/errbotio/errbot/) ⭐ 3,298 | 🐛 45 | 🌐 Python | 📅 2026-08-15：实现 ChatOps 的最简单最受欢迎的聊天机器人。

### 编辑器插件和 IDE

* Emacs
  * [elpy](https://github.com/jorgenschaefer/elpy) ⭐ 1,937 | 🐛 394 | 🌐 Emacs Lisp | 📅 2026-07-15：Emacs Python 开发环境。
* Sublime Text
  * [anaconda](https://github.com/DamnWidget/anaconda) ⭐ 2,239 | 🐛 185 | 🌐 Python | 📅 2022-08-12：Anaconda 可将功能齐全的 Python 开发 IDE 转换为 Sublime Text 3。
  * [SublimeJEDI](https://github.com/srusskih/SublimeJEDI) ⭐ 927 | 🐛 35 | 🌐 Python | 📅 2022-08-30：一个很棒的自动补全库 Jedi 的Sublime Text 插件。
* Vim
  * [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) ⭐ 25,892 | 🐛 36 | 🌐 Python | 📅 2026-08-15：包含 Jedi 补全的 Python 引擎。
  * [python-mode](https://github.com/python-mode/python-mode) ⭐ 5,464 | 🐛 39 | 🌐 Vim Script | 📅 2026-05-24：一个将 Vim 转换为 Python IDE 的多合一插件。
  * [jedi-vim](https://github.com/davidhalter/jedi-vim) ⭐ 5,308 | 🐛 31 | 🌐 Python | 📅 2026-06-16：用于 Python 的 Jedi 自动补全库的 Vim 绑定。
* Visual Studio
  * [PTVS](https://github.com/Microsoft/PTVS) ⭐ 2,565 | 🐛 155 | 🌐 C# | 📅 2026-08-13：Visual Studio Python 工具。
* Visual Studio Code
  * [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)：对 Python 有丰富支持的官方 VSCode 扩展。
* IDE
  * [spyder](https://github.com/spyder-ide/spyder) ⭐ 9,288 | 🐛 1,348 | 🌐 Python | 📅 2026-08-15： 开源 Python IDE。
  * [PyCharm](https://www.jetbrains.com/pycharm/)：JetBrains 提供的商业 Python IDE，也有免费的社区版。

### 企业级应用集成

企业级环境中用于集成的平台与工具。

* [Zato](https://zato.io)：ESB, SOA, REST, APIs 以及云的 Python 整合。

### GraphQL

GraphQL 相关库。

* [graphene](https://github.com/graphql-python/graphene/) ⭐ 8,232 | 🐛 114 | 🌐 Python | 📅 2025-09-04：Python GraphQL 框架。
* [tartiflette-asgi](https://github.com/tartiflette/tartiflette-asgi/) ⭐ 99 | 🐛 14 | 🌐 Python | 📅 2023-06-26：Tartiflette GraphQL 引擎的 ASGI 支持。
* [tartiflette-aiohttp](https://github.com/tartiflette/tartiflette-aiohttp/) ⭐ 62 | 🐛 16 | 🌐 Python | 📅 2023-11-12：Tartiflette 的基于 aiohttp 的装饰器，用于通过 HTTP 公开 GraphQL API。
* [tartiflette](https://tartiflette.io)：支持 Python 3.6+ 和 asyncio 的 SDL 优先的 GraphQL 引擎实现。

### 股票金融

* [vnpy](https://github.com/vnpy/vnpy) ⭐ 44,550 | 🐛 30 | 🌐 Python | 📅 2026-08-10：基于Python的开源量化交易系统开发框架，整合了多种交易接口，并针对具体策略算法和功能开发提供了简洁易用的API，用于快速构建交易员所需的量化交易应用
* [abu](https://github.com/bbfamily/abu) ⭐ 18,155 | 🐛 6 | 🌐 Python | 📅 2026-01-24: 基于python的开源量化交易，量化投资架构
* [QUANTAXIS](https://github.com/QUANTAXIS/QUANTAXIS) ⭐ 11,009 | 🐛 239 | 🌐 Python | 📅 2026-02-28：支持任务调度，分布式部署的股票/期货/期权/港股/虚拟货币的数据/回测/模拟/交易/可视化/多账户纯本地量化解决方案
* [Hikyuu Quant](https://github.com/fasiondog/hikyuu) ⭐ 3,441 | 🐛 5 | 🌐 C++ | 📅 2026-08-12：基于C++/Python的开源量化交易研究框架，用于策略分析及回测（仅受限于数据，如有数据也可用于期货等）

### 杂项

不属于上面任何一个类别，但是非常有用的库。

* [magenta](https://github.com/magenta/magenta) ⚠️ Archived：使用人工智能生成音乐与艺术的工具。
* [boltons](https://github.com/mahmoud/boltons) ⭐ 6,915 | 🐛 68 | 🌐 Python | 📅 2026-08-07：一组纯 Python 实用工具。
* [itsdangerous](https://github.com/pallets/itsdangerous) ⭐ 3,128 | 🐛 4 | 🌐 Python | 📅 2025-06-14：将受信任的数据传递到不受信任的环境的帮助工具。
* [blinker](https://github.com/jek/blinker) ⭐ 2,086 | 🐛 0 | 🌐 Python | 📅 2025-11-19：快速的 Python 运行时信号/事件分配系统。
* [pluginbase](https://github.com/mitsuhiko/pluginbase) ⭐ 1,139 | 🐛 5 | 🌐 Python | 📅 2021-05-16：一个简单但灵活的 Python 插件系统。
* [tryton](http://www.tryton.org/)：一个通用业务框架。

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-16._
