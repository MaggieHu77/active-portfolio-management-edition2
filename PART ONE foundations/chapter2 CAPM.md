Chapter 2: Consensus Expected Returns: The Capital Asset Pricing Model
======================================================================
---
+ This is the first chapter of part one: Foundation.

+ where are we now?

```mermaid
graph LR
A[APM Foundation] -->|One| B(expected returns)
subgraph
B --> |chapter two| E(CAPM, consensus, benchmark)
  subgraph major points
  E --> e1[r_i=r_mkt+r_res]
  E --> e2[expected r_res=0]
  E --> e3[logic: market efficiency]
  end
end

A -->|Two| C(risk)
A -.->|to be cont.| D(...)
style E fill:#f96
```

+ our attitude to CAPM: humility, `it turns out that much of the analysis originally developed in support of the CAPM can be turned out to the task of quantitative active management.`

### Introduction
+ **topic1**: why CAPM is better than historical average returns as estimate of consensus expected return?
> 1. average return contain sample errors. If volatility of hisorical return is $\sigma$, and the length of historical period is $\gamma$, then the stdandard deviation of average historical return is about $\frac{\sigma}{\sqrt{\gamma}}$.
> 2. true stock market changes over time. Not only the universe of stocks change(new stock listed and old stock expire or merge), but also the single stock's intrinsic attributes(such as its capital structure, earnings) can be quite different over time. Historical data is somehow inconsistent and regime-shifted.

+ **topic2**: why is CAPM is better than APT([arbitrage pricing theory](../PART TWO expected returns and valuation/chapter7 APT.md)) as estimate of consensus expected return?
> would like to treat APT as a tool for active manager instead a source of consensus expected return.

+ **topic3**: what does `consensus` mean in the framework of CAPM?
> + portfolio selection rule: **mean/variance  preferences <font color=red>+</font>**
> + expected return forecast model: **CAPM <font color=red>+</font>**
> + assume: **risk-free asset exists <font color=red>-></font>**
> + optimal portfolio: combination of ``market portfolio`` and ``risk-free asset``(with proportions depending on risk tolerence), ``market portfolio`` is the `consensus` portfolio.

### Separation of return
+ notation reminder:
  - $M$: market portfolio, generaly all traded assets; narrowlly, some broad value-weighted index, such as NYSE Composite.
  - $P$: any portfolio.
  - $\beta$: links any stock or $P$ to the $M$.
  - $r_P, r_M$: excess return of portfolio $P$ and market portfolio $M$
