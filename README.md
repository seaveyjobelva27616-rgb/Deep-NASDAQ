# Deep NASDAQ

麻烦试用的朋友们给我点个 Star，谢谢大家～ 🥺✨🌟💖

## 尝鲜邀请码

### 可用邀请码

2G3DJKDW8BJG | 3DRF6TA7J142 | 0NAFFY75W5C2 | NYD9VZMYETF9<br/>
9CS7BC5Y7B1D | S6JPFCYPXDNP | 5GS9TP9H760P | B2MWGA1MXJ7C<br/>
WE544229Q073 | E9R3BX9MG3ZX | MWZMB53MGTCC | 63YG3T5ERHFN<br/>
5QJDA7WB950R | 11H741V033C8 | DKKF6MYVAAVS | EV7JHQCM6XT7<br/>
PWZTHNCWM1X4 | CVGBNZWC8MME | T3TZ7R0AEWAA | Z2JWFSWM8JRK<br/>
GPWKMXGZ5SW0 | K8E6P2FCYRTD | ZPNP26BNVMW6 | PEGB2754Y2WB<br/>
5WBAZ7WDQ2XT | 8MX2F82C7QB4

### 旧码（已激活）

~~XBYW9FTVJF23~~ | ~~GRG6SNMTQ4TR~~ | ~~ZKN9A35B895V~~ | ~~SBT8A120HPSE~~<br/>
~~B5P1D5ATK6PN~~ | ~~K32SFNB5K1WW~~ | ~~C8J3D03BFXYE~~ | ~~X5QP8QCFSTN9~~<br/>
~~XVC15C09AYB2~~ | ~~H77W8PFXYRSK~~ | ~~M2M4BPRHA6SH~~ | ~~WJQ1W46WRQ79~~<br/>
~~YA5BNFCY4132~~ | ~~BR1EJ2GM5APQ~~

Deep NASDAQ 是一个面向 A 股市场结构观察的可视化看板，覆盖板块资金流、个股确认、热度与调研、题材生命周期、估值位置、相关性网络、板块传染和指数脱锚等界面。

网站地址：[https://deepnasdaq.com/](https://deepnasdaq.com/)

本仓库是公开展示包，只包含网站地址、主要界面的主体截图和各界面的参考文献。仓库不包含应用源码、数据库、凭据、部署脚本、原始数据文件或私有研究模块。

准备过程中已做外部成熟模组调研；公开仓库只列学术论文与安全标准文献，不列实现项目。

## 主体界面截图

### 登录入口

![登录入口](screenshots/01-login.png)

### 市场总览主体

![市场总览主体](screenshots/02-market-overview.png)

### 资金强弱分层主体

![资金强弱分层主体](screenshots/03-rotation.png)

### 热度排名主体

![热度排名主体](screenshots/04-attention.png)

### 股价新高确认主体

![股价新高确认主体](screenshots/05-confirmation.png)

### 全量明细主体

![全量明细主体](screenshots/06-universe.png)

### 题材生命周期主体

![题材生命周期主体](screenshots/07-lifecycle.png)

### PE/PB 估值主体

![PE/PB 估值主体](screenshots/08-valuation.png)

### 股东拥挤度主体

![股东拥挤度主体](screenshots/14-holder-crowding.png)

### 季节性热图主体

![季节性热图主体](screenshots/15-seasonality.png)

### 关联图谱主体

![关联图谱主体](screenshots/09-relationship-graph.png)

### 板块传染主体

![板块传染主体](screenshots/10-sector-contagion.png)

### 指数脱锚主体

![指数脱锚主体](screenshots/11-index-decoupling.png)

### 个股详情主体

![个股详情主体](screenshots/12-stock-detail.png)

### 概念净流入动画主体

![概念净流入动画主体](screenshots/13-concept-flow.png)

## 参考文献

下表按界面列出研究依据，用于说明每个主体界面的理论来源和可解释性边界。本仓库不展示实现细节，也不列实现项目。

| 界面 | 研究依据 | 参考文献 |
| --- | --- | --- |
| 登录入口 | 身份认证、会话管理、安全基线 | NIST, *Digital Identity Guidelines: Authentication and Lifecycle Management*, SP 800-63B, https://csrc.nist.gov/pubs/sp/800/63/b/4/final ; OWASP, *Application Security Verification Standard*, https://owasp.org/www-project-application-security-verification-standard/ |
| 市场总览主体 | 行业动量、基准相对观察、板块收益持续性 | Tobias J. Moskowitz and Mark Grinblatt, "Do Industries Explain Momentum?", *Journal of Finance*, 1999, https://ideas.repec.org/a/bla/jfinan/v54y1999i4p1249-1290.html ; Runjia Yang and Beining Shi, "Sector Rotation by Factor Model and Fundamental Analysis", arXiv:2401.00001, https://arxiv.org/abs/2401.00001 |
| 资金强弱分层主体 | 板块轮动、相对强弱、短期反转、因子与基本面轮动 | Moskowitz and Grinblatt, "Do Industries Explain Momentum?", https://ideas.repec.org/a/bla/jfinan/v54y1999i4p1249-1290.html ; Yang and Shi, "Sector Rotation by Factor Model and Fundamental Analysis", https://arxiv.org/abs/2401.00001 ; Sami Fakhouri, Michael E. Neubert and Robert A. E. Price, "Sector Rotation across the Business Cycle", SSRN, https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1467457 |
| 热度排名主体 | 投资者注意力、注意力代理变量、分析师覆盖与信息扩散速度 | Zhi Da, Joseph Engelberg and Pengjie Gao, "In Search of Attention", SSRN, https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1364209 ; Harrison G. Hong, Terence Lim and Jeremy C. Stein, "Bad News Travels Slowly: Size, Analyst Coverage and the Profitability of Momentum Strategies", SSRN, https://papers.ssrn.com/sol3/papers.cfm?abstract_id=226286 |
| 股价新高确认主体 | 动量确认、信息扩散、K 线与技术形态决策支持 | Hong, Lim and Stein, "Bad News Travels Slowly", https://papers.ssrn.com/sol3/papers.cfm?abstract_id=226286 ; Rosdyana Mangir Irawan Kusuma et al., "Using Deep Learning Neural Networks and Candlestick Chart Representation to Predict Stock Market", arXiv:1903.12258, https://arxiv.org/abs/1903.12258 |
| 全量明细主体 | 横截面比较、板块成分、个股动量与行业动量关系 | Moskowitz and Grinblatt, "Do Industries Explain Momentum?", https://ideas.repec.org/a/bla/jfinan/v54y1999i4p1249-1290.html ; Hong, Lim and Stein, "Bad News Travels Slowly", https://papers.ssrn.com/sol3/papers.cfm?abstract_id=226286 |
| 题材生命周期主体 | 相对强弱、动量生命周期、板块轮动、市场网络结构 | Yang and Shi, "Sector Rotation by Factor Model and Fundamental Analysis", https://arxiv.org/abs/2401.00001 ; Greg Leibon, Scott D. Pauls, Daniel N. Rockmore and Robert Savell, "Topological structures in the equities market network", arXiv:0805.3470, https://arxiv.org/abs/0805.3470 |
| PE/PB 估值主体 | 估值比率、价值与成长收益分解、板块基本面位置 | Eugene F. Fama and Kenneth R. French, "The Anatomy of Value and Growth Stock Returns", SSRN, https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1071124 ; Yang and Shi, "Sector Rotation by Factor Model and Fundamental Analysis", https://arxiv.org/abs/2401.00001 |
| 股东拥挤度主体 | 持有人广度、投资者基础集中度、筹码拥挤与预期收益压力 | Joseph Chen, Harrison G. Hong and Jeremy C. Stein, "Breadth of Ownership and Stock Returns", SSRN/NBER, https://papers.ssrn.com/sol3/papers.cfm?abstract_id=262106 ; NBER Working Paper 8151, https://www.nber.org/papers/w8151 |
| 季节性热图主体 | 日历季节性、信息周期、横截面季节性收益 | Haoyuan Li and Roger Loh, "The Information Cycle and Return Seasonality", SSRN, https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3746737 ; Steven L. Heston and Ronnie Sadka, "Seasonality in the Cross-Section of Stock Returns", *Journal of Financial Economics*, 2008, https://doi.org/10.1016/j.jfineco.2007.02.003 |
| 关联图谱主体 | 相关性网络、股票市场拓扑结构、聚类与最近邻关系 | Leibon et al., "Topological structures in the equities market network", https://arxiv.org/abs/0805.3470 ; Michele Tumminello, Tiziana Di Matteo, Tomaso Aste and Rosario N. Mantegna, "Correlation based networks of equity returns sampled at different time horizons", *European Physical Journal B*, 2007, https://doi.org/10.1140/epjb/e2006-00414-4 |
| 板块传染主体 | Hawkes 过程、多变量激励、金融传染与市场微观结构 | Emmanuel Bacry, Iacopo Mastromatteo and Jean-Francois Muzy, "Hawkes processes in finance", arXiv:1502.04592, https://arxiv.org/abs/1502.04592 ; "Analysis of Contagion in China's Stock Market: A Hawkes Process Approach", arXiv, https://arxiv.org/html/2512.08000 |
| 指数脱锚主体 | 基准相对离散、市场网络拓扑、宏观状态下的板块轮动 | Leibon et al., "Topological structures in the equities market network", https://arxiv.org/abs/0805.3470 ; Fakhouri, Neubert and Price, "Sector Rotation across the Business Cycle", https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1467457 |
| 个股详情主体 | K 线表示、技术分析、个股级别确认 | Kusuma et al., "Using Deep Learning Neural Networks and Candlestick Chart Representation to Predict Stock Market", https://arxiv.org/abs/1903.12258 ; Andrew W. Lo, Harry Mamaysky and Jiang Wang, "Foundations of Technical Analysis: Computational Algorithms, Statistical Inference, and Empirical Implementation", *Journal of Finance*, 2000, https://doi.org/10.1111/0022-1082.00265 |
| 概念净流入动画主体 | 资金轮动、行业动量、注意力与资金确认 | Moskowitz and Grinblatt, "Do Industries Explain Momentum?", https://ideas.repec.org/a/bla/jfinan/v54y1999i4p1249-1290.html ; Da, Engelberg and Gao, "In Search of Attention", https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1364209 |

以上内容仅用于展示系统界面和研究依据，不构成任何投资建议。
