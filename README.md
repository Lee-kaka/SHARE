# Introduction
Recommender systems (RSs), as a data-driven way, have been widely applied in various domains such as e-commerce and social media. However, RSs face long-term threats that require high attention. Attackers manipulate recommendation outcomes by injecting malicious data to achieve financial gain. These endless attacks seriously affect the accuracy and fairness of recommendations. In this paper, we propose SHARE, a novel personalized adversarial training method driven by dynamic rewards to defend against these threats. First, we selectively eliminate low-value data to reduce the risk of poisoning samples contaminating the model by quantifying the contribution of samples to the robustness and fairness of the model. Second, we design a dynamic perturbation strategy based on user embedding norm to address the behavioral differences among different users. Finally, we introduce a multi-dimensional reward function to guide the model to dynamically balance defense effectiveness and recommendation quality in adversarial training. Extensive experiments with different basic recommendation models, different datasets, and different types of attacks, demonstrate the effectiveness of SHARE compared with existing competing baselines. Specifically, SHARE can improve the recommendation performance by an average of 17.30% in clean data scenarios and reduce the success rate of attacks by an average of 14.15%.
# Requirements
For our running environment see requirements.txt
# Usage
<!-- 嵌入 HTML -->
<div>
  <pre><code id="code-block" class="language-python">
python main.py
</code></pre>
</div>

