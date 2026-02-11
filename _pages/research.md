---
layout: single
classes: wide
author_profile: true
permalink: /research/
title: "Research"
---

<style>
/* The container for each paper */
.paper-box {
  cursor: pointer;
  margin-bottom: 2px;
  border-bottom: 2px solid #eee;
  padding-bottom: 1px;
}

/* Style for coauthors */
.coauthor-line {
  display: block;       
  font-size: 0.85em;    
  color: #777;          
  margin-top: 4px;      
}

.hover-comment {
  overflow: hidden;
  max-height: 0;
  opacity: 0;
  visibility: hidden;
  
  /* Initial margin is 0 so it takes no space when hidden */
  margin-top: 0; 

  /* Add margin-top to the transition list for smooth animation */
  transition: 
    max-height 0.4s cubic-bezier(0.4, 0, 0.2, 1), 
    opacity 0.4s ease,
    margin-top 0.4s ease;
  
  background-color: #fcfcfc;
  border-left: 2px solid #fcfcfc;
  max-width: 800px; line-height: 1.3; text-align: justify;
  color: black;
  font-size: 0.85em;

  
}

/* This element adds internal padding to the text */
.comment-content {
  padding: 12px 15px; 
}

/* When active (hovered) */
.paper-box.active .hover-comment {
  visibility: visible;
  opacity: 1;
  /* This creates the margin/gap before the summary box starts */
  margin-top: 15px; 
}
</style>

## Working Papers

<div class="paper-box">
  <span class="title-text">Robust Inference on Macro Equations with Shock Proxies</span>
  
  <div class="hover-comment">
    I propose weak-instrument-robust inference methods on macroeconomic equations using shock proxies as instruments. Empirical applications include the Phillips curve and fiscal multipliers.
  </div>

  <details style="margin-top: 5px; margin-bottom: 15px;">
  <summary style="cursor: pointer; color: inherit; font-size: 0.9em;">
  Abstract
  <span style="margin-left: 10px;">
    <a href="" target="_blank" style="text-decoration: none; color: #e53935; border: 1px solid currentColor; border-radius: 3px; padding: 0 4px; font-size: 0.8em; margin-left: 3px;">Paper</a>
    <a href="" target="_blank" style="text-decoration: none; color: #1e88e5; border: 1px solid currentColor; border-radius: 3px; padding: 0 4px; font-size: 0.8em; margin-left: 3px;">Slide</a>
    <a href="" target="_blank" style="text-decoration: none; color: #1e88e5; border: 1px solid currentColor; border-radius: 3px; padding: 0 4px; font-size: 0.8em; margin-left: 3px;">Example Code</a>
    <a href="" target="_blank" style="text-decoration: none; color: #1e88e5; border: 1px solid currentColor; border-radius: 3px; padding: 0 4px; font-size: 0.8em;">SSRN</a>
  </span>
  </summary>
  <div style="font-size: 0.8em; margin-top: 0.5em; margin-left: 1em; max-width: 600px; line-height: 1.3; text-align: justify; color: black;">
  This paper proposes weak-instrument-robust inference methods that achieve accurate size in finite samples for macroeconomic equations identified by structural shock proxies. The methods ensure size control for Anderson–Rubin and Kleibergen’s LM test statistics with Almon-parameterized instruments by imposing the null hypothesis when computing the heteroskedasticity- and autocorrelation-robust long-run variance. Applying these methods to the Phillips curve highlights the empirical importance of size accuracy: unlike existing methods that may introduce size distortion, the proposed methods do not reject either a completely flat or a very steep Phillips curve. Turning to fiscal policy rules, I find that the tax multiplier is statistically significantly positive, and approximately one.
  </div>
  </details>
</div>

<div class="paper-box">
  <span class="title-text">Structural Estimation of Dynamic Equilibrium Models with Unstructured Data</span>
  <div class="coauthor-line">
    with <a href="https://www.saracasella.com/" target="blank" style="color: inherit; text-decoration: none;">Sara Casella</a>,
    <a href="https://www.sas.upenn.edu/~jesusfv/" target="blank" style="color: inherit; text-decoration: none;">Jesús Fernández-Villaverde</a>,
    <a href="https://sekhansen.github.io/" target="blank" style="color: inherit; text-decoration: none;">Stephen Hansen</a>, and
    <a href="https://mcmcs.github.io/" target="blank" style="color: inherit; text-decoration: none;">Minchul Shin</a>
  </div>

  <div class="hover-comment">
  We develop a framework that integrates unstructured data, such as text, into DSGE model estimation. The method is applied to a medium-scale DSGE model with FOMC transcripts.
  </div>

  <details style="margin-top: 5px; margin-bottom: 15px;">
  <summary style="cursor: pointer; color: inherit; font-size: 0.9em;">
  Abstract
  <span style="margin-left: 10px;">
    <a href="" target="_blank" style="text-decoration: none; color: #e53935; border: 1px solid currentColor; border-radius: 3px; padding: 0 4px; font-size: 0.8em;">Paper</a>
    <a href="" target="_blank" style="text-decoration: none; color: #1e88e5; border: 1px solid currentColor; border-radius: 3px; padding: 0 4px; font-size: 0.8em;">NBER</a>
    <a href="" target="_blank" style="text-decoration: none; color: #1e88e5; border: 1px solid currentColor; border-radius: 3px; padding: 0 4px; font-size: 0.8em;">CEPR</a>
    <a href="" target="_blank" style="text-decoration: none; color: #1e88e5; border: 1px solid currentColor; border-radius: 3px; padding: 0 4px; font-size: 0.8em;">Philly Fed</a>
  </span>
  </summary>
  <div style="font-size: 0.8em; margin-top: 0.5em; margin-left: 1em; max-width: 600px; line-height: 1.3; text-align: justify; color: black;">
  We develop a general econometric framework that integrates unstructured data into the structural estimation of dynamic equilibrium models. The framework augments a standard state-space dynamic equilibrium models with a non-core measurement block that links latent structural shocks to a large collection of time series derived from unstructured sources. Because only a subset of these series is informative, we impose a sparse spike-and-slab prior on the measurement loadings, allowing the data to select relevant signals while preserving structural discipline. We apply the approach to a medium-scale New Keynesian DSGE model for the U.S. using topic measures extracted from FOMC transcripts. Incorporating text improves joint forecasting performance and materially alters structural inference, lowering the estimated responsiveness of monetary policy to inflation and output and implying a steeper Phillips curve. These results show how unstructured data can sharpen the identification of structural parameters with direct policy implications.
  </div>
  </details>
</div>

<div class="paper-box">
  <span class="title-text">Simulation Pseudo-Bias in Modified Harmonic Mean Estimators of Marginal Likelihoods: Robustness and Bias Correction (Draft available upon request)</span>

  <div class="hover-comment">
    
  </div>

  <details style="margin-top: 5px; margin-bottom: 15px;">
  <summary style="cursor: pointer; color: inherit; font-size: 0.9em;">
  Abstract
  </summary>
  <div style="font-size: 0.8em; margin-top: 0.5em; margin-left: 1em; max-width: 600px; line-height: 1.3; text-align: justify; color: black;">
  </div>
  </details>
</div>

<div class="paper-box">
  <span class="title-text">Sticky Information Versus Sticky Prices Revisited: A Bayesian VAR-GMM Approach</span>

  <div class="coauthor-line">
    with <a href = "https://ideas.repec.org/e/pku88.html" target = "blank" style="color: inherit; text-decoration: none;">Takushi Kurozumi</a> and <a href = "https://www.clevelandfed.org/people/profiles/v/van-zandweghe-willem" target="blank" style="color: inherit; text-decoration: none;">Willem Van Zandweghe</a>
  </div>

  <div class="hover-comment">
  We compare Phillips curves with sticky information, sticky prices, and unchanged prices in each period by using Bayesian VAR-GMM and find that all are essential to describe US inflation.
  </div>

  <details style="margin-top: 5px; margin-bottom: 15px;">
  <summary style="cursor: pointer; color: inherit; font-size: 0.9em;">
  Abstract
  <span style="margin-left: 10px;">
    <a href="https://www.clevelandfed.org/publications/working-paper/2022/wp-2234-sticky-information-versus-sticky-prices-revisited" target="_blank" style="text-decoration: none; color: #e53935; border: 1px solid currentColor; border-radius: 3px; padding: 0 4px; font-size: 0.8em;">Paper</a>
  </span>

  </summary>
  <div style="font-size: 0.8em; margin-top: 0.5em; margin-left: 1em; max-width: 600px; line-height: 1.3; text-align: justify; color: black;">
  Several Phillips curves based on sticky information and sticky prices are estimated and compared using Bayesian VAR-GMM. This method derives expectations in each Phillips curve from a VAR and estimates the Phillips curve parameters and the VAR coefficients simultaneously. Quasi-marginal likelihood-based model comparison selects a dual stickiness Phillips curve in which, each period, some prices remain unchanged, consistent with micro evidence. Moreover, sticky information is a more plausible source of inflation inertia in the Phillips curve than other sources proposed in previous studies. Sticky information, sticky prices, and unchanged prices in each period are all needed to better describe inflation dynamics.
  </div>
  </details>
</div>

<div class="paper-box">
  <span class="title-text">A Comparison of Japanese and US New Keynesian Phillips Curves with Bayesian VAR-GMM</span>

  <div class="coauthor-line">
    with <a href = "https://ideas.repec.org/e/pku88.html" target = "blank" style="color: inherit; text-decoration: none;">Takushi Kurozumi</a>
  </div>

  <div class="hover-comment">
    We find that Japan's inflation dynamics are best described by variable demand elasticity with higher persistence in inflation expectations and lower trend inflation than in the US.
  </div>

  <details style="margin-top: 5px; margin-bottom: 15px;">
  <summary style="cursor: pointer; color: inherit; font-size: 0.9em;">
  Abstract
  <span style="margin-left: 10px;">
    <a href="https://www.boj.or.jp/en/research/wps_rev/wps_2022/wp22e03.htm" target="_blank" style="text-decoration: none; color: #e53935; border: 1px solid currentColor; border-radius: 3px; padding: 0 4px; font-size: 0.8em;">Paper</a>
  </span>

  </summary>
  <div style="font-size: 0.8em; margin-top: 0.5em; margin-left: 1em; max-width: 600px; line-height: 1.3; text-align: justify; color: black;">
  We compare Japanese and US inflation dynamics during the post-Global Financial Crisis period by utilizing Bayesian VAR-GMM to estimate several specifications of the New Keynesian Phillips curve. With the estimation method, we derive expectations in the Phillips curve from a VAR and analyze the formation of inflation expectations explicitly. We select the specification with variable elasticity of demand for Japan and that with sticky information for the US, using quasi-marginal likelihood. The selected specifications show that the persistence of inflation expectations formation is higher and trend inflation is lower in Japan than in the US. These findings account for persistently weak inflation developments in Japan: in the presence of firms' cautious price-setting behavior that reflects the purchasing attitude of consumers who are sensitive to price increases, inflation remains low and induces, through the highly persistent formation of inflation expectations, low expected future inflation and hence low trend inflation, which in turn put downward pressure on present inflation through the Phillips curve.
  </div>
  </details>
</div>
<br/>


## Some Work in Progress

Fiscal adjustments and optimal monetary policy in HANK

<br/>

## Other articles
<a href="https://www.boj.or.jp/en/research/brp/mor/data/mor190719.pdf" target = "blank">"Market Operations in Fiscal 2018,"</a> BOJ Reports & Research papers

<a href="https://www3.boj.or.jp/fukushima/kouhyo/120report.pdf" target="_blank">"Economy and Industry in Fukushima - Bank of Japan Fukushima Branch 120th Anniversary Memorial Paper,"</a> BOJ Reports & Research Papers, with Keita Kawaguchi (in Japanese)

<a href="https://www3.boj.or.jp/fukushima/kouhyo/yellreport.pdf" target="_blank">"An Estimation of the Economic Effect of NHK Morning Drama (Asadora) Series 'Yell' on Fukushima Prefecture,"</a> BOJ Reports & Research Papers (in Japanese)


<script>
  const papers = document.querySelectorAll(".paper-box");
  let currentlyOpen = null;

  papers.forEach(paper => {
    const summary = paper.querySelector(".hover-comment");

    paper.addEventListener("mouseenter", () => {
      // If another paper is closing, this ensures a seamless handoff
      paper.classList.add("active");
      summary.style.maxHeight = summary.scrollHeight + "px";
      currentlyOpen = paper;
    });

    paper.addEventListener("mouseleave", () => {
      paper.classList.remove("active");
      summary.style.maxHeight = "0";
      currentlyOpen = null;
    });
  });
</script>