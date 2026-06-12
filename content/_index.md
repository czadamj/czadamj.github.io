---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2023-08-01
type: landing

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Call-to-action button under the biography
      button:
        text: Download CV
        url: uploads/ZhangA_CV.pdf
    design:
      # Gradient Mesh disabled for a clean, flat hero background
      background:
        gradient_mesh:
          enable: false
      # Avatar customization
      avatar:
        size: medium # small | medium | large | xl | xxl
        shape: circle # circle | square | rounded
  - block: markdown
    id: papers
    content:
      title: Working Papers
      text: |
        <div class="wp-list">
        <details class="wp-card">
        <summary class="wp-summary"><div class="wp-head"><h3>Lifecycle Financial Portfolios in General Equilibrium</h3><div class="wp-actions"><a class="wp-pdf" href="uploads/LifecycleFinPortGE.pdf" target="_blank" rel="noopener">PDF &rarr;</a><span class="wp-chevron" aria-hidden="true">&#9662;</span></div></div></summary>
        <p>This paper quantifies general equilibrium effects of financial innovations that increase access to equity markets. I study an overlapping-generations model with idiosyncratic and aggregate risk in which households face participation frictions and rebalancing frictions on saving flows. The model is disciplined by lifecycle moments for portfolio holdings and wealth, as well as aggregate asset-pricing moments and recent empirical evidence on stock demand elasticity and limited risk transfer. Counterfactual adoption of an age-based asset allocation rule decreases the equity premium, stabilizes equity return volatility, improves risk sharing, and lowers financial wealth inequality. These outcomes are similar to an economy without any participation costs or rebalancing frictions. Following the transition to an age-based asset allocation rule, rich young households lose in welfare by up to 3% consumption equivalents, while the rest of young households gain almost 6%; and retirees benefit by 0&ndash;3%.</p>
        </details>
        <details class="wp-card">
        <summary class="wp-summary"><div class="wp-head"><h3>The Effect of Inequality on Redistribution: An Econometric Analysis <span class="wp-authors">(with Michael Boskin and Kareem Elnahal)</span></h3><div class="wp-actions"><a class="wp-pdf" href="uploads/BEZ_draft.pdf" target="_blank" rel="noopener">PDF &rarr;</a><span class="wp-chevron" aria-hidden="true">&#9662;</span></div></div></summary>
        <p>Using data on U.S. state and federal taxes and transfers over a quarter century, we estimate a regression model that yields the marginal effect of any shift of market income share from one quintile to another on the entire post-tax, post-transfer income distribution. We identify exogenous income distribution changes and account for reverse causality using instruments based on exposure to international trade shocks, international commodity price shocks, and national industry demand shocks, as well as lagged endogenous variables, with controls for the level of income, the business cycle, and demographics. We find the degree of attenuation of market income shifts initially increases in quintile rank, peaks at the middle quintile, and then falls for higher income quintiles, consistent with median-voter political economy theory and what Stigler called Director's Law. We also provide evidence of considerable and systematic spillover effects on quintiles neither gaining nor losing in the experiments, also favoring the middle quintile, what we label the greedy median voter. We find a strong negative relationship between average real income and redistribution and a modest effect of two-year-led inequality.</p>
        </details>
        <details class="wp-card">
        <summary class="wp-summary"><div class="wp-head"><h3>A House for a Bride: Marriage and Homeownership in China <span class="wp-authors">(with Scarlet Chen)</span></h3><div class="wp-actions"><a class="wp-pdf" href="uploads/ChenZhang_MarriageHousingChina.pdf" target="_blank" rel="noopener">PDF &rarr;</a><span class="wp-chevron" aria-hidden="true">&#9662;</span></div></div></summary>
        <p>This paper studies the phenomenon of the marriage house in China and its effects on demographics and homeownership. We first show empirical evidence: single males with a marriage house (a house where the newlywed can move in) have 70% higher odds of getting married than counterparts who do not have one. The timing of home purchase exhibits a clear cut-off around marriage, with the probability of purchasing peaking 0&ndash;2 years before marriage and slumping immediately after. In the cross section, county house prices and average age at marriage are highly correlated in both level and growth rate. We then quantify the marriage-related incentives for homeownership using a lifecycle consumption-savings model with housing demand and ownership-dependent marriage shocks. Without the marriage-market premium, young households delay home purchases by about five years. Eliminating the convenience value of a marriage house reduces overall ownership by 35% for families with a male child between ages 15 and 45, and the marriage-house friction accounts for 40% of the rise in marriage age between 1995 and 2010. Our results suggest that policies directed at either housing affordability or demographics can have significant consequences for both marriage and housing markets.</p>
        </details>
        <details class="wp-card">
        <summary class="wp-summary"><div class="wp-head"><h3>The Political Economy of China's Housing Boom <span class="wp-authors">(with Xu Lu)</span></h3><div class="wp-actions"><a class="wp-pdf" href="uploads/LuZhang_PoliticalChinaHousing.pdf" target="_blank" rel="noopener">PDF &rarr;</a><span class="wp-chevron" aria-hidden="true">&#9662;</span></div></div></summary>
        <p>This paper provides causal evidence that the Chinese Communist Party's cadre promotion system contributed to China's real estate boom between 2003 and 2015. We first show that promotions of city-level leaders to higher ranks were largely based on city GDP performance. We then identify exogenous shocks to promotion chances, caused by new social-tie establishments between city-level officials and their superiors, using provincial party leader changes initiated by the central government. An incumbent city leader who shared a hometown with a newly appointed provincial leader was 50% more likely to be promoted than average, regardless of the city's GDP performance. Cities where leaders had hometown connections experienced 40% higher supplies of residential land, while industrial and commercial land supplies both dropped by 30% and total land supply was unaffected. House price growth rates were also 50% lower than average in such cities.</p>
        </details>
        </div>
        <script>document.querySelectorAll('.wp-card summary a.wp-pdf').forEach(function(a){a.addEventListener('click',function(e){e.stopPropagation();});});</script>
    design:
      columns: '1'
---
