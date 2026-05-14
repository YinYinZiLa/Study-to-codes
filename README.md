# Study-to-codes
# Python 学习路线

> 点击标题左侧的小三角展开 / 收起。

## 总览

- 第一关：Python 基础能跑起来
- 第二关：核心数据结构与函数
- 第三关：文件、异常、模块与查文档能力
- 第四关：Git 最小用法 + 第一个完整项目
- 第五关：测试、日志、规范
- 第六关：面向对象与项目重构
- 第七关：基础算法与复杂度意识
- 第八关：数据库
- 第九关：Web 后端开发
- 第十关：Git 协作、Linux 与部署
- 第十一关：Python 进阶与代码质量
- 主线完成标准
- 支线 A：办公自动化
- 支线 B：爬虫
- 支线 C：数据分析

---

<details>
<summary><strong>主线完成标准</strong></summary>

> **说明：** 完成到 416，不是看完就算完成。

**必须满足以下标准：**

- 有一个学生管理系统项目
- 有一个 FastAPI 后端项目
- 项目用 Git 管理
- 项目有 README
- 项目有测试
- 项目接入数据库
- 项目能 Docker 启动
- 你能解释每个模块为什么这样拆
- 你能改 bug
- 你能重构代码
- 你能根据报错查文档解决问题

</details>

<details>
<summary><strong>第一关：Python 基础能跑起来</strong></summary>

> **目标：** 能独立创建、运行、修改 Python 文件，能看懂基础报错。

<details>
<summary>01｜环境与运行</summary>

- 001｜安装 Python
- 002｜安装 VS Code 或 PyCharm
- 003｜配置 Python 解释器
- 004｜运行第一个 `.py` 文件
- 005｜认识终端 / 命令行
- 006｜理解代码从上到下执行
- 007｜能看懂报错的最后一行
- 008｜理解脚本、解释器、终端之间的关系

</details>

<details>
<summary>02｜基础语法</summary>

- 009｜变量
- 010｜变量命名规则
- 011｜整数 `int`
- 012｜浮点数 `float`
- 013｜字符串 `str`
- 014｜布尔值 `bool`
- 015｜空值 `None`
- 016｜`print()` 输出
- 017｜`input()` 输入
- 018｜类型转换：`int()` / `float()` / `str()`
- 019｜算术运算：`+ - * / // % **`
- 020｜比较运算：`> < >= <= == !=`
- 021｜逻辑运算：`and` / `or` / `not`
- 022｜括号控制优先级
- 023｜f-string 字符串格式化

</details>

<details>
<summary>03｜流程控制</summary>

- 024｜`if` 判断
- 025｜`elif` 多条件判断
- 026｜`else` 兜底逻辑
- 027｜嵌套判断
- 028｜三元表达式
- 029｜`for` 循环
- 030｜`while` 循环
- 031｜`range()`
- 032｜`break`
- 033｜`continue`
- 034｜循环嵌套

</details>

<details>
<summary>第一关验收</summary>

- 能写一个 BMI 计算器
- 能写一个猜数字游戏
- 能写一个简单菜单程序
- 能根据报错定位到代码行

</details>

</details>

<details>
<summary><strong>第二关：核心数据结构与函数</strong></summary>

> **目标：** 能处理列表、字典、嵌套数据，能用函数拆分代码。

<details>
<summary>04｜字符串</summary>

- 035｜字符串索引
- 036｜字符串切片
- 037｜`len()`
- 038｜`split()`
- 039｜`join()`
- 040｜`strip()`
- 041｜`replace()`
- 042｜`find()`
- 043｜`in`

</details>

<details>
<summary>05｜列表</summary>

- 044｜创建列表
- 045｜索引读取元素
- 046｜修改元素
- 047｜`append()`
- 048｜`insert()`
- 049｜`remove()`
- 050｜`pop()`
- 051｜`del`
- 052｜遍历列表
- 053｜`enumerate()`
- 054｜`sort()`
- 055｜`sorted()`
- 056｜列表切片
- 057｜列表推导式

</details>

<details>
<summary>06｜字典</summary>

- 058｜创建字典
- 059｜通过 key 读取 value
- 060｜修改字典值
- 061｜新增键值对
- 062｜删除键值对
- 063｜`get()` 安全读取
- 064｜`keys()`
- 065｜`values()`
- 066｜`items()`
- 067｜判断 key 是否存在
- 068｜字典推导式

</details>

<details>
<summary>07｜元组、集合、嵌套结构</summary>

- 069｜元组
- 070｜元组拆包
- 071｜集合
- 072｜集合去重
- 073｜交集
- 074｜并集
- 075｜差集
- 076｜嵌套列表
- 077｜字典嵌套字典
- 078｜列表嵌套字典
- 079｜遍历列表嵌套字典
- 080｜理解 JSON 风格数据
- 081｜可变类型与不可变类型
- 082｜浅拷贝与深拷贝基础

</details>

<details>
<summary>08｜函数</summary>

- 083｜定义函数
- 084｜调用函数
- 085｜位置参数
- 086｜关键字参数
- 087｜默认参数
- 088｜返回值 `return`
- 089｜区分 `print()` 和 `return`
- 090｜局部变量
- 091｜全局变量
- 092｜函数拆分思想
- 093｜一个函数只做一件事
- 094｜`*args`
- 095｜`**kwargs`
- 096｜`lambda` 初步了解
- 097｜`map()` 初步了解
- 098｜`filter()` 初步了解
- 099｜`zip()`

</details>

<details>
<summary>第二关验收</summary>

- 能用列表字典保存一组学生信息
- 能根据姓名查询学生
- 能统计平均分
- 能把重复代码拆成函数
- 能说清楚 `print()` 和 `return` 的区别

</details>

</details>

<details>
<summary><strong>第三关：文件、异常、模块与查文档能力</strong></summary>

> **目标：** 能做本地小工具，能处理文件，能拆分模块，能查文档解决问题。

<details>
<summary>09｜文件读写</summary>

- 100｜`open()`
- 101｜`with open()`
- 102｜读取 txt
- 103｜写入 txt
- 104｜追加写入 txt
- 105｜理解 `r` / `w` / `a`
- 106｜理解 `encoding="utf-8"`
- 107｜文件不存在时自动创建

</details>

<details>
<summary>10｜JSON、CSV、路径</summary>

- 108｜理解 JSON
- 109｜`json.load()`
- 110｜`json.dump()`
- 111｜`ensure_ascii=False`
- 112｜`indent=4`
- 113｜理解 CSV
- 114｜读取 CSV
- 115｜写入 CSV
- 116｜`os.getcwd()`
- 117｜`os.listdir()`
- 118｜`os.path.exists()`
- 119｜`os.path.join()`
- 120｜`pathlib.Path`
- 121｜相对路径与绝对路径

</details>

<details>
<summary>11｜异常处理</summary>

- 122｜理解异常是什么
- 123｜`try except`
- 124｜捕获 `ValueError`
- 125｜捕获 `FileNotFoundError`
- 126｜`else`
- 127｜`finally`
- 128｜不要裸写 `except:`
- 129｜打印异常信息
- 130｜自定义异常基础

</details>

<details>
<summary>12｜模块、包与环境</summary>

- 131｜`import`
- 132｜`from xxx import xxx`
- 133｜`as`
- 134｜自定义模块
- 135｜`__name__ == "__main__"`
- 136｜理解包
- 137｜`__init__.py`
- 138｜绝对导入
- 139｜相对导入
- 140｜`pip`
- 141｜安装第三方库
- 142｜创建虚拟环境
- 143｜激活虚拟环境
- 144｜退出虚拟环境
- 145｜`requirements.txt`

</details>

<details>
<summary>13｜查文档能力</summary>

- 146｜会看 Python 官方文档
- 147｜会看第三方库 README
- 148｜会看函数参数说明
- 149｜会看报错栈 traceback
- 150｜会根据报错关键词搜索
- 151｜会判断教程是否过时
- 152｜会看 GitHub issue
- 153｜会做最小复现代码

</details>

<details>
<summary>第三关验收</summary>

- 能写一个读取 JSON 的小程序
- 能写一个保存 JSON 的小程序
- 能处理文件不存在错误
- 能把代码拆成多个 `.py` 文件
- 能根据文档独立学会一个简单第三方库

</details>

</details>

<details>
<summary><strong>第四关：Git 最小用法 + 第一个完整项目</strong></summary>

> **目标：** 开始像开发者一样管理代码，而不是随手写脚本。

<details>
<summary>14｜Git 最小用法</summary>

- 154｜安装 Git
- 155｜`git init`
- 156｜`git status`
- 157｜`git add`
- 158｜`git commit`
- 159｜`.gitignore`
- 160｜查看提交记录 `git log`
- 161｜理解每完成一个小功能就提交一次

</details>

<details>
<summary>15｜项目一：学生管理系统函数版</summary>

- 162｜创建学生数据结构
- 163｜添加学生
- 164｜查看所有学生
- 165｜查询学生
- 166｜删除学生
- 167｜修改学生成绩
- 168｜统计平均分
- 169｜找最高分学生
- 170｜菜单循环
- 171｜输入退出功能
- 172｜输入错误时程序不崩溃
- 173｜每完成一个功能就 Git commit

</details>

<details>
<summary>16｜学生管理系统文件版</summary>

- 174｜保存学生数据到 JSON
- 175｜启动程序时读取 JSON
- 176｜文件不存在时自动创建空数据
- 177｜分数输入必须是数字
- 178｜删除学生后同步保存文件
- 179｜修改学生后同步保存文件
- 180｜程序退出前保存数据

</details>

<details>
<summary>17｜学生管理系统多文件版</summary>

- 181｜`main.py` 作为入口
- 182｜`student_service.py` 放业务函数
- 183｜`storage.py` 放文件读写
- 184｜`utils.py` 放通用工具
- 185｜`config.py` 放配置
- 186｜整理项目目录结构
- 187｜写项目 README

</details>

<details>
<summary>第四关验收</summary>

- 项目可以正常运行
- 数据可以保存到 JSON
- 代码拆成多个文件
- 至少有 10 次 Git commit
- README 写清楚项目怎么运行

</details>

</details>

<details>
<summary><strong>第五关：测试、日志、规范</strong></summary>

> **目标：** 代码不只是能跑，还要可验证、可维护。

<details>
<summary>18｜pytest 最小测试</summary>

- 188｜理解为什么要写测试
- 189｜安装 pytest
- 190｜写第一个测试函数
- 191｜使用 `assert`
- 192｜测试添加学生
- 193｜测试删除学生
- 194｜测试查询学生
- 195｜测试分数输入异常
- 196｜测试文件不存在情况
- 197｜测试边界值
- 198｜fixture 基础
- 199｜mock 初步了解
- 200｜coverage 测试覆盖率初步了解

</details>

<details>
<summary>19｜调试、日志、规范</summary>

- 201｜`print()` 调试
- 202｜断点调试
- 203｜单步执行
- 204｜查看变量值
- 205｜`assert`
- 206｜PEP8 基础规范
- 207｜类型提示基础
- 208｜docstring
- 209｜`logging`
- 210｜把关键 print 替换成 logging

</details>

<details>
<summary>20｜工程化工具入门</summary>

- 211｜理解项目目录结构
- 212｜理解配置文件
- 213｜理解 `.env`
- 214｜`requirements.txt`
- 215｜`pyproject.toml` 初步了解
- 216｜ruff 代码检查
- 217｜black 代码格式化
- 218｜pre-commit 初步了解
- 219｜mypy 初步了解，不深挖

</details>

<details>
<summary>第五关验收</summary>

- 学生管理系统有基础测试
- 运行 pytest 能通过
- 项目有日志
- 代码格式统一
- 能解释项目目录结构

</details>

</details>

<details>
<summary><strong>第六关：面向对象与项目重构</strong></summary>

> **目标：** 理解类不是语法装饰，而是组织复杂代码的方式。

<details>
<summary>21｜面向对象基础</summary>

- 220｜理解类是模板
- 221｜理解对象是实例
- 222｜定义类
- 223｜创建对象
- 224｜实例属性
- 225｜实例方法
- 226｜`self`
- 227｜`__init__`
- 228｜类属性
- 229｜实例属性 vs 类属性

</details>

<details>
<summary>22｜面向对象进阶</summary>

- 230｜封装
- 231｜私有属性 `_name` / `__name`
- 232｜`property`
- 233｜继承
- 234｜方法重写
- 235｜`super()`
- 236｜多态
- 237｜`dataclass`
- 238｜`@staticmethod` 初步了解
- 239｜`@classmethod` 初步了解

</details>

<details>
<summary>23｜常用魔法方法</summary>

- 240｜`__str__`
- 241｜`__repr__`
- 242｜`__len__`
- 243｜`__eq__`
- 244｜`__lt__` 了解即可
- 245｜`__iter__` 了解即可
- 246｜`__next__` 了解即可

</details>

<details>
<summary>24｜学生管理系统面向对象版</summary>

- 247｜创建 `Student` 类
- 248｜创建 `StudentManager` 类
- 249｜创建 `Storage` 类
- 250｜创建 `Menu` 类
- 251｜用类管理学生数据
- 252｜用类管理文件读写
- 253｜用类组织菜单逻辑
- 254｜重构后保持测试通过

</details>

<details>
<summary>第六关验收</summary>

- 同一个项目有函数版和面向对象版
- 能解释为什么要拆类
- 能解释每个类负责什么
- 重构后测试仍然通过

</details>

</details>

<details>
<summary><strong>第七关：基础算法与复杂度意识</strong></summary>

> **目标：** 不追求刷题，但要避免写出明显低效的代码。

<details>
<summary>25｜算法与复杂度基础</summary>

- 255｜理解时间复杂度
- 256｜理解空间复杂度
- 257｜理解 O(1)
- 258｜理解 O(n)
- 259｜理解 O(n²)
- 260｜列表查找为什么慢
- 261｜字典查找为什么快
- 262｜排序基础
- 263｜栈
- 264｜队列
- 265｜递归基础
- 266｜二分查找
- 267｜什么时候不需要过度优化

</details>

<details>
<summary>第七关验收</summary>

- 能解释列表查找和字典查找的区别
- 能写一个简单二分查找
- 能判断一段双重循环可能较慢
- 能在项目里避免明显低效写法

</details>

</details>

<details>
<summary><strong>第八关：数据库</strong></summary>

> **目标：** 从“文件保存数据”升级到“数据库保存业务数据”。

<details>
<summary>26｜SQL 基础</summary>

- 268｜理解数据库是什么
- 269｜理解表、字段、记录
- 270｜理解主键
- 271｜理解外键
- 272｜安装 SQLite 工具
- 273｜创建数据库
- 274｜创建表
- 275｜`SELECT`
- 276｜`INSERT`
- 277｜`UPDATE`
- 278｜`DELETE`
- 279｜`WHERE`
- 280｜`ORDER BY`
- 281｜`GROUP BY`
- 282｜`JOIN`
- 283｜索引基础
- 284｜事务基础

</details>

<details>
<summary>27｜Python 操作数据库</summary>

- 285｜`sqlite3`
- 286｜Python 连接 SQLite
- 287｜执行 SQL
- 288｜查询数据
- 289｜插入数据
- 290｜更新数据
- 291｜删除数据
- 292｜参数化查询
- 293｜理解 SQL 注入风险
- 294｜把学生管理系统从 JSON 改成 SQLite
- 295｜SQLAlchemy 基础
- 296｜ORM 思想
- 297｜Alembic 了解即可，先不深挖

</details>

<details>
<summary>第八关验收</summary>

- 学生管理系统可以用 SQLite 保存数据
- 能写基本 CRUD
- 能解释 SQL 注入风险
- 能用参数化查询
- 能理解 ORM 是什么

</details>

</details>

<details>
<summary><strong>第九关：Web 后端开发</strong></summary>

> **目标：** 能写正常后端接口。

<details>
<summary>28｜HTTP 与 API</summary>

- 298｜理解 HTTP
- 299｜请求 request
- 300｜响应 response
- 301｜GET
- 302｜POST
- 303｜PUT
- 304｜DELETE
- 305｜状态码
- 306｜Header
- 307｜Body
- 308｜JSON API
- 309｜RESTful API
- 310｜接口文档

</details>

<details>
<summary>29｜FastAPI 入门</summary>

- 311｜安装 FastAPI
- 312｜安装 Uvicorn
- 313｜启动第一个 FastAPI 服务
- 314｜写第一个路由
- 315｜路径参数
- 316｜查询参数
- 317｜请求体
- 318｜响应 JSON
- 319｜Pydantic 模型
- 320｜自动接口文档
- 321｜错误处理
- 322｜依赖注入基础
- 323｜FastAPI 项目目录结构

</details>

<details>
<summary>30｜后端项目：任务管理 API</summary>

- 324｜创建任务管理项目
- 325｜设计任务数据表
- 326｜创建任务
- 327｜查看任务列表
- 328｜查看任务详情
- 329｜修改任务
- 330｜删除任务
- 331｜任务状态管理
- 332｜任务分类
- 333｜分页查询
- 334｜搜索任务
- 335｜接入数据库
- 336｜接入 SQLAlchemy
- 337｜给接口写 pytest 测试

</details>

<details>
<summary>31｜用户系统与权限</summary>

- 338｜用户注册
- 339｜用户登录
- 340｜密码哈希
- 341｜Session 基础
- 342｜JWT 基础
- 343｜登录状态校验
- 344｜权限控制
- 345｜只允许用户操作自己的数据
- 346｜统一错误返回格式

</details>

<details>
<summary>第九关验收</summary>

- 能写 FastAPI CRUD 接口
- 能接数据库
- 能实现用户注册登录
- 能实现权限控制
- 能给接口写测试
- 能用接口文档调试 API

</details>

</details>

<details>
<summary><strong>第十关：Git 协作、Linux 与部署</strong></summary>

> **目标：** 项目不只是在本地能跑，还能部署、排查、维护。

<details>
<summary>32｜Git 进阶</summary>

- 347｜`git clone`
- 348｜分支 `branch`
- 349｜合并 `merge`
- 350｜解决冲突 conflict
- 351｜`git reset`
- 352｜`git revert`
- 353｜GitHub
- 354｜Pull Request
- 355｜Code Review 基础

</details>

<details>
<summary>33｜Linux 基础</summary>

- 356｜理解 Linux
- 357｜`pwd`
- 358｜`ls`
- 359｜`cd`
- 360｜`mkdir`
- 361｜`touch`
- 362｜`cp`
- 363｜`mv`
- 364｜`rm`
- 365｜`cat`
- 366｜`tail`
- 367｜`grep`
- 368｜文件权限
- 369｜进程查看
- 370｜端口查看
- 371｜ssh 登录服务器
- 372｜查看日志

</details>

<details>
<summary>34｜Docker 与部署</summary>

- 373｜理解 Docker
- 374｜镜像 image
- 375｜容器 container
- 376｜Dockerfile
- 377｜`docker build`
- 378｜`docker run`
- 379｜查看容器日志
- 380｜环境变量配置
- 381｜docker compose
- 382｜部署 FastAPI 项目
- 383｜Nginx 基础
- 384｜Uvicorn / Gunicorn
- 385｜项目上线后的日志排查

</details>

<details>
<summary>第十关验收</summary>

- 任务管理 API 可以 Docker 启动
- 能查看服务日志
- 能通过端口访问接口
- 能排查启动失败问题
- 能写部署说明

</details>

</details>

<details>
<summary><strong>第十一关：Python 进阶与代码质量</strong></summary>

> **目标：** 进入中级开发能力：更懂 Python，更会维护代码。

<details>
<summary>35｜Python 进阶语法</summary>

- 386｜迭代器
- 387｜生成器
- 388｜装饰器
- 389｜闭包进阶
- 390｜上下文管理器
- 391｜`with` 原理
- 392｜类型注解进阶
- 393｜泛型基础
- 394｜多线程 threading
- 395｜多进程 multiprocessing
- 396｜`async` / `await`
- 397｜`asyncio`

</details>

<details>
<summary>36｜性能、重构与架构</summary>

- 398｜识别重复代码
- 399｜识别过长函数
- 400｜识别复杂条件判断
- 401｜函数重构
- 402｜类重构
- 403｜cProfile 性能分析
- 404｜缓存基础
- 405｜数据库查询优化基础
- 406｜分层架构
- 407｜Controller / Service / Repository
- 408｜MVC / MTV 思想
- 409｜依赖注入
- 410｜配置管理
- 411｜错误处理规范
- 412｜日志规范
- 413｜接口设计规范
- 414｜常用设计模式基础
- 415｜代码可维护性
- 416｜项目复盘与重构

</details>

<details>
<summary>第十一关验收</summary>

- 能重构自己的 FastAPI 项目
- 能解释项目分层
- 能定位性能问题
- 能统一错误处理
- 能统一日志规范
- 能写出可维护的项目结构

</details>

</details>

<details>
<summary><strong>支线 A：办公自动化</strong></summary>

> **说明：** 适合结合工作需要学习，不是主线必学。

- A001｜Excel 自动化：`openpyxl`
- A002｜读取 Excel
- A003｜写入 Excel
- A004｜批量处理 Excel 文件
- A005｜Word 自动化：`python-docx`
- A006｜PDF 处理：`pypdf`
- A007｜文件夹批量整理
- A008｜做一个 Excel 批处理工具

</details>

<details>
<summary><strong>支线 B：爬虫</strong></summary>

> **说明：** 只学合法、正常的数据获取方式。

- B001｜理解 HTTP 基础
- B002｜安装 `requests`
- B003｜使用 `requests.get()`
- B004｜理解状态码
- B005｜设置 `headers`
- B006｜读取网页文本
- B007｜安装 BeautifulSoup
- B008｜用 BeautifulSoup 解析 HTML
- B009｜提取标题
- B010｜提取链接
- B011｜保存为 CSV / JSON
- B012｜多页爬取
- B013｜请求失败异常处理
- B014｜加请求间隔
- B015｜了解 robots.txt
- B016｜不学习验证码、绕限制、突破反爬

</details>

<details>
<summary><strong>支线 C：数据分析</strong></summary>

> **说明：** 不走数据方向的话，学到基础应用即可。

- C001｜安装 pandas
- C002｜读取 CSV
- C003｜读取 Excel
- C004｜查看数据前几行
- C005｜筛选数据
- C006｜分组统计
- C007｜保存结果
- C008｜matplotlib 基础画图
- C009｜做一个简单数据分析报告

</details>
