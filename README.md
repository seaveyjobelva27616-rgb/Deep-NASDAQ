# Deep NASDAQ

Deep NASDAQ is a market-structure dashboard for A-share sector flow, stock-level confirmation, attention signals, lifecycle views, valuation context, network relationships, and contagion monitoring.

Website: [https://deepnasdaq.com/](https://deepnasdaq.com/)

This repository is intentionally a public presentation package only. It contains the website address, interface screenshots, and bibliography. It does not contain application source code, databases, credentials, deployment scripts, data files, or private research modules.

External module research was performed during preparation; this public package lists only academic and standards references.

## Interface Screenshots

### Login

![Login](screenshots/01-login.png)

### Market Overview

![Market overview](screenshots/02-market-overview.png)

### Capital Strength Rotation

![Capital strength rotation](screenshots/03-rotation.png)

### Attention Ranking

![Attention ranking](screenshots/04-attention.png)

### New-High Confirmation

![New-high confirmation](screenshots/05-confirmation.png)

### Full Universe Detail

![Full universe detail](screenshots/06-universe.png)

### Theme Lifecycle

![Theme lifecycle](screenshots/07-lifecycle.png)

### PE/PB Valuation

![PE/PB valuation](screenshots/08-valuation.png)

### Holder Crowding

![Holder crowding](screenshots/14-holder-crowding.png)

### Seasonality Heatmap

![Seasonality heatmap](screenshots/15-seasonality.png)

### Relationship Graph

![Relationship graph](screenshots/09-relationship-graph.png)

### Sector Contagion

![Sector contagion](screenshots/10-sector-contagion.png)

### Index Decoupling

![Index decoupling](screenshots/11-index-decoupling.png)

### Stock Detail

![Stock detail](screenshots/12-stock-detail.png)

### Concept Flow Animation

![Concept flow animation](screenshots/13-concept-flow.png)

## References

The bibliography below is grouped by interface so the public presentation remains traceable without exposing implementation code or implementation references.

| Interface | Research basis | References |
| --- | --- | --- |
| Login | Authentication and session-management baseline | NIST, *Digital Identity Guidelines: Authentication and Lifecycle Management*, SP 800-63B, https://csrc.nist.gov/pubs/sp/800/63/b/4/final ; OWASP, *Application Security Verification Standard*, https://owasp.org/www-project-application-security-verification-standard/ |
| Market Overview | Industry momentum, benchmark-relative observation, sector-level return persistence | Tobias J. Moskowitz and Mark Grinblatt, "Do Industries Explain Momentum?", *Journal of Finance*, 1999, https://ideas.repec.org/a/bla/jfinan/v54y1999i4p1249-1290.html ; Runjia Yang and Beining Shi, "Sector Rotation by Factor Model and Fundamental Analysis", arXiv:2401.00001, https://arxiv.org/abs/2401.00001 |
| Capital Strength Rotation | Sector rotation, relative strength, short-term reversal, factor/fundamental rotation | Moskowitz and Grinblatt, "Do Industries Explain Momentum?", https://ideas.repec.org/a/bla/jfinan/v54y1999i4p1249-1290.html ; Yang and Shi, "Sector Rotation by Factor Model and Fundamental Analysis", https://arxiv.org/abs/2401.00001 ; Sami Fakhouri, Michael E. Neubert and Robert A. E. Price, "Sector Rotation across the Business Cycle", SSRN, https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1467457 |
| Attention Ranking | Investor attention, attention proxies, analyst/research coverage and slow information diffusion | Zhi Da, Joseph Engelberg and Pengjie Gao, "In Search of Attention", SSRN, https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1364209 ; Harrison G. Hong, Terence Lim and Jeremy C. Stein, "Bad News Travels Slowly: Size, Analyst Coverage and the Profitability of Momentum Strategies", SSRN, https://papers.ssrn.com/sol3/papers.cfm?abstract_id=226286 |
| New-High Confirmation | Momentum confirmation, information diffusion, chart-based decision support | Hong, Lim and Stein, "Bad News Travels Slowly", https://papers.ssrn.com/sol3/papers.cfm?abstract_id=226286 ; Rosdyana Mangir Irawan Kusuma et al., "Using Deep Learning Neural Networks and Candlestick Chart Representation to Predict Stock Market", arXiv:1903.12258, https://arxiv.org/abs/1903.12258 |
| Full Universe Detail | Cross-section, sector membership, individual stock momentum versus industry momentum | Moskowitz and Grinblatt, "Do Industries Explain Momentum?", https://ideas.repec.org/a/bla/jfinan/v54y1999i4p1249-1290.html ; Hong, Lim and Stein, "Bad News Travels Slowly", https://papers.ssrn.com/sol3/papers.cfm?abstract_id=226286 |
| Theme Lifecycle | Relative strength, momentum lifecycle, sector rotation, market-network structure | Yang and Shi, "Sector Rotation by Factor Model and Fundamental Analysis", https://arxiv.org/abs/2401.00001 ; Greg Leibon, Scott D. Pauls, Daniel N. Rockmore and Robert Savell, "Topological structures in the equities market network", arXiv:0805.3470, https://arxiv.org/abs/0805.3470 |
| PE/PB Valuation | Valuation ratios, value/growth return decomposition, sector fundamentals | Eugene F. Fama and Kenneth R. French, "The Anatomy of Value and Growth Stock Returns", SSRN, https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1071124 ; Yang and Shi, "Sector Rotation by Factor Model and Fundamental Analysis", https://arxiv.org/abs/2401.00001 |
| Holder Crowding | Ownership breadth, investor-base concentration, crowding and expected-return pressure | Joseph Chen, Harrison G. Hong and Jeremy C. Stein, "Breadth of Ownership and Stock Returns", SSRN/NBER, https://papers.ssrn.com/sol3/papers.cfm?abstract_id=262106 ; NBER Working Paper 8151, https://www.nber.org/papers/w8151 |
| Seasonality Heatmap | Calendar seasonality and information-cycle interpretation | Haoyuan Li and Roger Loh, "The Information Cycle and Return Seasonality", SSRN, https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3746737 ; Steven L. Heston and Ronnie Sadka, "Seasonality in the Cross-Section of Stock Returns", *Journal of Financial Economics*, 2008, https://doi.org/10.1016/j.jfineco.2007.02.003 |
| Relationship Graph | Correlation networks, equity-market topology, clustered market structure | Leibon et al., "Topological structures in the equities market network", https://arxiv.org/abs/0805.3470 ; Michele Tumminello, Tiziana Di Matteo, Tomaso Aste and Rosario N. Mantegna, "Correlation based networks of equity returns sampled at different time horizons", *European Physical Journal B*, 2007, https://doi.org/10.1140/epjb/e2006-00414-4 |
| Sector Contagion | Hawkes processes, multivariate excitation, financial contagion and microstructure | Emmanuel Bacry, Iacopo Mastromatteo and Jean-Francois Muzy, "Hawkes processes in finance", arXiv:1502.04592, https://arxiv.org/abs/1502.04592 ; "Analysis of Contagion in China's Stock Market: A Hawkes Process Approach", arXiv, https://arxiv.org/html/2512.08000 |
| Index Decoupling | Benchmark-relative dispersion, market-network topology, sector rotation under macro regimes | Leibon et al., "Topological structures in the equities market network", https://arxiv.org/abs/0805.3470 ; Fakhouri, Neubert and Price, "Sector Rotation across the Business Cycle", https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1467457 |
| Stock Detail | Candlestick representation, technical-analysis decision support, stock-level confirmation | Kusuma et al., "Using Deep Learning Neural Networks and Candlestick Chart Representation to Predict Stock Market", https://arxiv.org/abs/1903.12258 ; Andrew W. Lo, Harry Mamaysky and Jiang Wang, "Foundations of Technical Analysis: Computational Algorithms, Statistical Inference, and Empirical Implementation", *Journal of Finance*, 2000, https://doi.org/10.1111/0022-1082.00265 |
| Concept Flow Animation | Flow rotation, industry momentum, attention and fund-flow confirmation | Moskowitz and Grinblatt, "Do Industries Explain Momentum?", https://ideas.repec.org/a/bla/jfinan/v54y1999i4p1249-1290.html ; Da, Engelberg and Gao, "In Search of Attention", https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1364209 |
