# 欧盟轮胎查询与对比 · EPREL Tyre Explorer

[下载使用 / Download](https://github.com/Ciender/eprel-tyre-explorer/releases/download/v2026.10.12/eprel-tyre-explorer-2026-10-12.zip)

收录 **219,548 条轮胎数据**，来自[欧盟能效标签产品数据库（EPREL）](https://eprel.ec.europa.eu/screen/product/tyres)，涵盖轿车、轻型商用车、卡车和客车轮胎。可在电脑上离线查询、筛选和对比。

**数据采集日期：2026 年 10 月 10 日。**

## 怎么用

1. 下载上方压缩包并解压。
2. 用浏览器打开 `eprel_tyre_explorer.html`。
3. 在页面中选择或拖入 `eprel_tyres_open.sqlite3`，即可开始查询。

不需要安装软件或注册账号。两个主要文件分别是：

- **`eprel_tyre_explorer.html`：查询工具。** 用来搜索、筛选、查看详情和对比轮胎。
- **`eprel_tyres_open.sqlite3`：轮胎数据库。** 保存品牌、型号、尺寸、载重、速度级别、节能等级、湿地抓地等级和噪声等参数。

## 有哪些功能

- 按品牌、型号、尺寸和性能等级等条件搜索、筛选；支持常见品牌及部分型号的中文名称。
- 同时对比多款轮胎，以彩色等级显示主要指标；可展开已选列表，查看和移除轮胎。
- 查看详细参数、导出表格；通过「参数定义」了解湿地抓地、噪声、载重和速度代号等含义。

## 国内用户请注意

**这是欧盟市场的轮胎资料，不能直接当作国内同名轮胎的实测结果。** 同名轮胎不一定是相同规格或版本，[原厂配套版本也可能采用不同设计和配方](https://www.michelin.co.uk/why-michelin/partnership/aston-martin)。购买前请核对完整型号、尺寸、载重、速度级别和原厂配套标记，以实物及厂商说明为准。

参数由供应商按欧盟测试要求申报，监管部门进行抽查，**不是欧盟将所有轮胎统一送测后做出的横评**。同一型号的不同尺寸或版本也可能有不同等级。[欧盟轮胎标签说明](https://energy-efficient-products.ec.europa.eu/product-list/tyres_en)

## 数据来源与许可

轮胎数据来源于[欧盟委员会 EPREL 公开数据库](https://eprel.ec.europa.eu/screen/product/tyres)，本项目进行了数据整理，并补充中文名称及参数说明。工具和文档采用 MIT 许可；原始数据的再利用须遵守来源方适用条款。项目保留来源署名并说明整理改动，不主张原始数据、品牌名称或商标的所有权，也不通过软件许可授予第三方数据或商标权利。完整说明见压缩包内的 `LICENSES.txt`。

## 免责声明

本项目为**非营利项目**，免费提供，用于学习、研究和信息查询，不出售轮胎数据。项目为非官方整理，与欧盟委员会、EPREL 及轮胎厂商无隶属、合作或背书关系。

数据可能存在错误、遗漏或过时，仅供参考，不替代厂商说明或专业选型建议。在法律允许的范围内，软件和数据按现状提供，不提供担保，也不对因使用而产生的损失承担责任。

### 侵权投诉与下架处理

尊重欧盟委员会、EPREL、轮胎厂商及其他权利人的合法权益。如收到权利人或 GitHub 转达、并指明具体内容的侵权或数据再利用异议通知，维护者将**立即先行下架相关内容、停止提供相应下载**，并配合后续更正、删除等处理；在取得相应授权或争议解决前，不恢复分发。

---

## English

An offline tool for searching and comparing **219,548 tyre data entries** from the EU's [European Product Registry for Energy Labelling (EPREL)](https://eprel.ec.europa.eu/screen/product/tyres), covering passenger cars, light commercial vehicles, trucks and buses.

**Data collected: 10 October 2026.**

### How to use

1. Download and extract the ZIP linked above.
2. Open `eprel_tyre_explorer.html` in a desktop browser.
3. Select or drop `eprel_tyres_open.sqlite3` into the page.

The **HTML file is the search and comparison tool**. The **SQLite file is the tyre database**, containing brands, models, sizes, load/speed ratings, fuel-efficiency and wet-grip grades, noise and other specifications. No installation or account is required.

Features include detailed filters, Chinese aliases for common brands and selected models, multi-tyre comparison with coloured ratings, an expandable selection list, detailed specifications, table export and parameter explanations. The interface is in Chinese.

### Before comparing or buying

These are **EU-market specifications**. A tyre sold under the same name in China or another market may have a different specification or version; manufacturer-specific original-equipment versions can also differ. Check the exact model, size, load/speed ratings and original-equipment markings against the tyre and manufacturer information.

Suppliers declare parameters under EU testing requirements, with spot checks by authorities. This is not an EU-run head-to-head test of every tyre. Ratings can differ between sizes and versions. See the [EU tyre label guide](https://energy-efficient-products.ec.europa.eu/product-list/tyres_en).

### Data source and licence

Tyre data come from the [European Commission's EPREL public database](https://eprel.ec.europa.eu/screen/product/tyres). This project organises the data and adds Chinese names and parameter explanations. The tool and documentation are MIT-licensed; reuse of the original data is subject to applicable upstream terms. The project preserves source attribution, identifies its changes and claims no ownership of the original data, brand names or trademarks. Its software licence grants no third-party data or trademark rights. See `LICENSES.txt` in the ZIP for full notices.

### Disclaimer

This project is operated **on a not-for-profit basis**, is provided free of charge for learning, research and information lookup, and does not sell tyre data. It is unofficial and is not affiliated with, partnered with or endorsed by the European Commission, EPREL or tyre manufacturers.

Data may contain errors, omissions or outdated information and are provided for reference, not as a replacement for manufacturer instructions or professional advice. To the extent permitted by law, the software and data are provided as is, without warranty or liability for losses arising from their use.

### Rights complaints and takedown

The project respects the rights of the European Commission, EPREL, tyre manufacturers and other rights holders. On receiving an infringement or data-reuse objection from a rights holder or forwarded by GitHub that identifies the relevant content, the maintainer will **immediately take that content offline and suspend the corresponding downloads**, and cooperate with subsequent correction or removal. Distribution will not resume until the relevant permission is obtained or the dispute is resolved.

