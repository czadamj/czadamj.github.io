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
        <summary class="wp-summary"><div class="wp-head"><h3>Lifecycle Financial Portfolios in General Equilibrium</h3><div class="wp-actions"><a class="wp-pdf" href="/uploads/LifecycleFinPortGE.pdf" target="_blank" rel="noopener">PDF &rarr;</a><span class="wp-chevron" aria-hidden="true">&#9662;</span></div></div></summary>
        <p>This paper quantifies general equilibrium effects of financial innovations that increase access to equity markets. I study an overlapping-generations model with idiosyncratic and aggregate risk in which households face participation frictions and rebalancing frictions on saving flows. The model is disciplined by lifecycle moments for portfolio holdings and wealth, as well as aggregate asset-pricing moments and recent empirical evidence on stock demand elasticity and limited risk transfer. Counterfactual adoption of an age-based asset allocation rule decreases the equity premium, stabilizes equity return volatility, improves risk sharing, and lowers financial wealth inequality. These outcomes are similar to an economy without any participation costs or rebalancing frictions. Following the transition to an age-based asset allocation rule, rich young households lose in welfare by up to 3% consumption equivalents, while the rest of young households gain almost 6%; and retirees benefit by 0&ndash;3%.</p>
        </details>
        <details class="wp-card">
        <summary class="wp-summary"><div class="wp-head"><h3>The Effect of Inequality on Redistribution: An Econometric Analysis <span class="wp-authors">(with Michael Boskin and Kareem Elnahal)</span></h3><div class="wp-actions"><a class="wp-pdf" href="/uploads/BEZ_draft.pdf" target="_blank" rel="noopener">PDF &rarr;</a><span class="wp-chevron" aria-hidden="true">&#9662;</span></div></div></summary>
        <p>Using a quarter century of U.S. state and federal tax and transfer data, we estimate how shifts in the market income distribution pass through to the distribution of post-tax, post-transfer disposable income. A system of equations yields the marginal effect of moving market income share from any quintile to any other on the entire disposable distribution, and we address reverse causality by instrumenting with state-level exposure to international trade, commodity-price, and national industry-demand shocks. The system's attenuation of market income shifts is hump-shaped in quintile rank, peaking sharply at the middle quintile, consistent with the median voter theorem and Stigler's Director's Law. This works largely through large, systematic spillovers onto quintiles that neither gain nor lose, also favoring the middle, which we term the greedy median voter. The shape of this pass-through shifts with economic conditions. Where market inequality has run higher, the middle-favoring peak flattens and the bottom quintile is left more exposed, and as average real disposable income per capita rises the protection of the bottom likewise recedes, even as the middle peak holds firm. We complement these results with an insurance-coalition analysis.</p>
        </details>
        <details class="wp-card">
        <summary class="wp-summary"><div class="wp-head"><h3>A House for a Bride: Marriage and Homeownership in China <span class="wp-authors">(with Scarlet Chen)</span></h3><div class="wp-actions"><a class="wp-pdf" href="/uploads/ChenZhang_MarriageHousingChina.pdf" target="_blank" rel="noopener">PDF &rarr;</a><span class="wp-chevron" aria-hidden="true">&#9662;</span></div></div></summary>
        <p>This paper studies the phenomenon of the marriage house in China and its effects on demographics and homeownership. We first show empirical evidence: single males with a marriage house (a house where the newlywed can move in) have 70% higher odds of getting married than counterparts who do not have one. The timing of home purchase exhibits a clear cut-off around marriage, with the probability of purchasing peaking 0&ndash;2 years before marriage and slumping immediately after. In the cross section, county house prices and average age at marriage are highly correlated in both level and growth rate. We then quantify the marriage-related incentives for homeownership using a lifecycle consumption-savings model with housing demand and ownership-dependent marriage shocks. Without the marriage-market premium, young households delay home purchases by about five years. Eliminating the convenience value of a marriage house reduces overall ownership by 35% for families with a male child between ages 15 and 45, and the marriage-house friction accounts for 40% of the rise in marriage age between 1995 and 2010. Our results suggest that policies directed at either housing affordability or demographics can have significant consequences for both marriage and housing markets.</p>
        </details>
        <details class="wp-card">
        <summary class="wp-summary"><div class="wp-head"><h3>Career Incentives, Land Allocation, and Local Government Debt in China's Mandarin Growth Model <span class="wp-authors">(with Xu Lu)</span></h3><div class="wp-actions"><a class="wp-pdf" href="/uploads/LuZhang_ChinaPolitHousing.pdf" target="_blank" rel="noopener">PDF &rarr;</a><span class="wp-chevron" aria-hidden="true">&#9662;</span></div></div></summary>
        <p>A Chinese city leader's promotion rewards local GDP growth. The exception is a hometown tie. When a newly appointed provincial superior shares the leader's birthplace, promotion no longer depends on growth at all. Exploiting the timing of these appointments as a plausibly exogenous relaxation of career incentives, we show that tied leaders shift land supply from industrial to residential use by six to seven percentage points, lower residential land prices by roughly a fifth, and curtail local government debt accumulation, on the order of a year of forgone borrowing. These estimates lie outside the distribution of a 500-draw randomization placebo, and they are not explained by preferential treatment from above or by anticipated promotions. The response is compositional rather than expansionary, because investment, infrastructure, and the total quantity of land supplied do not move. Tracing the reallocation into the real economy, the visible industrial engine the tournament rewards winds down, as foreign investment and industrial employment fall, while housing delivered to households appears to expand and output holds up, a recomposition toward construction rather than broad productive growth. These patterns are the leader-level footprint of China's Mandarin model of growth, in which career incentives steer local development toward the visible activity a promotion tournament can credit. Relaxing those incentives changes the composition of local growth, not its level.</p>
        </details>
        </div>
        <script>document.querySelectorAll('.wp-card summary a.wp-pdf').forEach(function(a){a.addEventListener('click',function(e){e.stopPropagation();});});</script>
    design:
      columns: '1'
---
