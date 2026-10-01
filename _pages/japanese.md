---
layout: single
permalink: /japanese/
classes: wide
author_profile: true
share: false
---

<style>
  body {
    font-size: 16px;
  }
</style>

## 大石凌平のウェブページへようこそ！

* **所属:** <a href="https://www.boj.or.jp/" target="_blank">日本銀行</a>、エコノミスト
* **勤務経験:** 金融市場局市場調節課、福島支店、企画局政策調査課等
* **最終学歴:** PhD in Economics [博士 (経済学)], <a href="https://www.ucl.ac.uk/" target="_blank">ユニバーシティ・カレッジ・ロンドン (UCL)</a>
* **研究分野:** マクロ計量経済学、マクロ経済学、機械学習・AI
* <a href="/cv/" target="_blank">履歴書（英文)</a>

{% if paginator %}
  {% assign posts = paginator.posts %}
{% else %}
  {% assign posts = site.posts %}
{% endif %}

{% assign entries_layout = page.entries_layout | default: 'list' %}
<div class="entries-{{ entries_layout }}">
  {% include documents-collection.html entries=posts type=entries_layout %}
</div>

---

## ワーキングペーパー

* **<a href="/pdf/RobustInference.pdf" target="_blank">Robust Inference on Macro Equations with Shock Proxies</a>**
  * Money Macro and Finance Society <a href="https://www.mmf.ac.uk/" target="_blank">(MMF)</a> より <a href="https://www.mmf.ac.uk/phd/2026-phd-conference/" target="_blank">Peter Sinclair Prize</a> を受賞
  * リンク: [<a href="/pdf/RobustInference.pdf" target="_blank">Paper</a>] [<a href="/pdf/RobustInference_slide.pdf" target="_blank">Slide</a>] [<a href="https://github.com/ryohei-oishi/Robust-Inference-Shock-Proxy-Example-Public" target="_blank">Example</a>] [<a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6248298" target="_blank">SSRN</a>]

* **<a href="/pdf/Text_DSGE.pdf" target="_blank">Structural Estimation with Unstructured Data</a>**
  * 共著者: <a href="https://www.saracasella.com/" target="_blank">Sara Casella</a>, <a href="https://www.sas.upenn.edu/~jesusfv/" target="_blank">Jesús Fernández-Villaverde</a>, <a href="https://sekhansen.github.io/" target="_blank">Stephen Hansen</a>, <a href="https://mcmcs.github.io/" target="_blank">Minchul Shin</a>
  * リンク: [<a href="/pdf/Text_DSGE.pdf" target="_blank">Paper</a>] [<a href="https://www.nber.org/papers/w35487" target="_blank">NBER</a>] [<a href="https://cepr.org/publications/dp21746" target="_blank">CEPR</a>] [<a href="https://www.philadelphiafed.org/the-economy/monetary-policy/structural-estimation-with-unstructured-data" target="_blank">Philly Fed</a>]

* **<a href="/pdf/ML_MHME.pdf" target="_blank">On Simulation Pseudo-Bias and Truncation in the Modified Harmonic Mean Estimator</a>**
  * リンク: [<a href="/pdf/ML_MHME.pdf" target="_blank">Paper</a>] [<a href="/pdf/ML_MHME_slide.pdf" target="_blank">Slide</a>] [<a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6502721" target="_blank">SSRN</a>] [<a href="/pdf/semiparametric_MHME.pdf" target="_blank">Companion Paper</a>]

---

## 日本銀行でのワーキングペーパー

* **<a href="https://www.clevelandfed.org/publications/working-paper/2022/wp-2234-sticky-information-versus-sticky-prices-revisited" target="_blank">Sticky Information Versus Sticky Prices Revisited: A Bayesian VAR-GMM Approach</a>**
  * 共著者: <a href="https://ideas.repec.org/e/pku88.html" target="_blank">黒住 卓司</a>, <a href="https://www.clevelandfed.org/people/profiles/v/van-zandweghe-willem" target="_blank">Willem Van Zandweghe</a>

* **<a href="https://www.boj.or.jp/en/research/wps_rev/wps_2022/wp22e03.htm" target="_blank">A Comparison of Japanese and US New Keynesian Phillips Curves with Bayesian VAR-GMM</a>**
  * 共著者: <a href="https://ideas.repec.org/e/pku88.html" target="_blank">黒住 卓司</a>

---
## 学歴

* **経済学 博士 (PhD)** <br> ユニバーシティ・カレッジ・ロンドン (2023 - 2026)
* **経済学 修士 (MRes)** Distinction および Dean's List <br> ユニバーシティ・カレッジ・ロンドン (2022 - 2023)
* **経済学 修士 (M.A.)** <br> 一橋大学 (2017 - 2018)
* **経済学 学士 (B.A.)** Honor's degree (優等学位) <br>一橋大学 (2013 - 2017)



---

## その他の記事・論文
* <a href="" target="_blank">Essays on Macroeconometrics and Applied Macroeconomics</a> （UCLでの博士論文）
* <a href="https://www.boj.or.jp/research/brp/mor/mor190530.htm" target="_blank">2018年度の金融市場調節</a> （日本銀行調査論文）
* <a href="https://www3.boj.or.jp/fukushima/kouhyo/120report.pdf" target="_blank">福島県の経済・産業の推移と今後の課題：日本銀行福島支店開設 120 周年特別レポート</a> （日本銀行調査論文、川口 圭太氏との共著）
* <a href="https://www3.boj.or.jp/fukushima/kouhyo/yellreport.pdf" target="_blank">ＮＨＫ連続テレビ小説「エール」の放映に伴う福島県経済への波及効果</a> （日本銀行調査論文）

---

## 連絡先 (Email)
* ryohei.oishi.61 (at) gmail.com
* ryohei.oishi.22 (at) ucl.ac.uk

<small style="color: #666;">注意事項：本ウェブサイトにおける見解はすべて私個人のものであり、私が現在所属する、もしくは過去に所属していた、いかなる機関や組織の見解や政策を代表するものではありません。</small>