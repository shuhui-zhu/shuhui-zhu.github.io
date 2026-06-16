---
permalink: /
# title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a Ph.D. candidate in Computer Science at the University of Waterloo and the Vector Institute, supervised by [Prof. Pascal Poupart](https://cs.uwaterloo.ca/~ppoupart/). My research focuses on cooperative and safe agentic AI, spanning reinforcement learning, large language models, mechanism design, information design, and game theory. I am particularly interested in designing mechanisms and algorithms that promote cooperation, alignment, and safety in mixed-motive multi-agent systems, including both RL-driven and generative agents.

---
You can reach me at [shuhui [dot] zhu [at] uwaterloo [dot] ca](mailto:shuhui.zhu@uwaterloo.ca). You can also find my work on [Google Scholar](https://scholar.google.ca/citations?user=mKti-YAAAAAJ&hl=en).

News
======

<div class="news-scroll" markdown="1">

* **August 2026**: I will present our paper [Talk, Judge, Cooperate: Gossip-Driven Indirect Reciprocity in Self-Interested LLM Agents](https://arxiv.org/abs/2602.07777) at the [*Cooperative AI Summer School 2026*](https://www.cooperativeai.com/summer-school/summer-school-2026) in Toronto.
* **July 2026**: I will present [Talk, Judge, Cooperate: Gossip-Driven Indirect Reciprocity in Self-Interested LLM Agents](https://arxiv.org/abs/2602.07777) at [*ICML 2026*](https://icml.cc/Conferences/2026) in Seoul.
* **June 2026**: Joined [Vijil](https://vijil.ai/) as an assistant applied scientist, supervised by [Prof. Tim G. J. Rudner](https://timrudner.com/), researching and developing methods to improve the safety and trustworthiness of AI agents.
* **May 2026**: Our paper [Talk, Judge, Cooperate: Gossip-Driven Indirect Reciprocity in Self-Interested LLM Agents](https://arxiv.org/abs/2602.07777) was accepted to *The 43rd International Conference on Machine Learning* ([*ICML 2026*](https://icml.cc/Conferences/2026)).
* **August 2025**: I will be at [*RLC 2025 Workshop on Coordination and Cooperation in Multi-Agent Reinforcement Learning*](https://sites.google.com/view/cocomarl2025) presenting our paper [Learning to Negotiate via Voluntary Commitment](https://arxiv.org/abs/2503.03866).
* **July 2025**: I will be at [*EC'25 Workshop on Swap Regret and Strategic Learning*](https://sites.google.com/view/strategic-learning-ec25) and [*Cooperative AI Summer School 2025*](https://www.cooperativeai.com/summer-school/summer-school-2025) presenting our paper [Learning to Negotiate via Voluntary Commitment](https://arxiv.org/abs/2503.03866).
* **January 2025**: Our paper [Learning to Negotiate via Voluntary Commitment](https://openreview.net/forum?id=DZwHPyPeZO) was accepted to *The 28th International Conference on Artificial Intelligence and Statistics* ([*AISTATS, 2025*](https://virtual.aistats.org/Conferences/2025)).
* **August 2024**: Joined the Normativity Lab as a research assistant at the University of Toronto and the Schwartz Reisman Institute, supervised by [Prof. Gillian Hadfield](https://engineering.jhu.edu/faculty/gillian-hadfield/).
* **July 2024**: Attended [CIFAR Deep Learning + Reinforcement Learning Summer School](https://dlrl.ca).
* **January 2022**: Started Ph.D. at the David R. Cheriton School of Computer Science, University of Waterloo and the Vector Institute, supervised by [Prof. Pascal Poupart](https://cs.uwaterloo.ca/~ppoupart/).
* **May 2021**: Started internship at [PerkinElmer](https://content.perkinelmer.com) as a Machine Learning Engineer.
* **September 2020**: Started MMath in Computational Mathematics at the University of Waterloo, supervised by [Prof. Hans De Sterck](https://uwaterloo.ca/applied-mathematics/profiles/hans-sterck) and [Prof. Jun Liu](https://uwaterloo.ca/hybrid-systems-lab/jun-liu).

</div>

Publications
======
<div class="pub-item">
  <div class="pub-figure">
    <img src="images/DecisionProcess.jpg" alt="Talk, Judge, Cooperate figure">
    <img src="images/AgentLLM_EG.jpg" alt="ALIGN framework example">
  </div>
  <div class="pub-body">
    <p class="pub-title">Talk, Judge, Cooperate: Gossip-Driven Indirect Reciprocity in Self-Interested LLM Agents</p>
    <p class="pub-meta">
      <b>Shuhui Zhu</b>, Yue Lin, Shriya Kaistha, Wenhao Li, Baoxiang Wang, Hongyuan Zha, Gillian K Hadfield, Pascal Poupart<br>
      <span class="pub-venue">ICML, 2026</span><br>
      <span class="pub-links">
        <a href="https://arxiv.org/abs/2602.07777">Paper</a> &middot;
        <a href="https://github.com/shuhui-zhu/ALIGN">Code</a> &middot;
        <a href="https://shuhui-zhu.github.io/files/ICML-ALIGN-slides.pdf">Talk</a>
      </span>
    </p>
    <p class="pub-abstract">
      We introduce public gossip as a decentralized reputation mechanism that enables self-interested LLM agents to cooperate in mixed-motive settings. Building on this idea, our ALIGN framework uses hierarchical gossip to assess trustworthiness, sustain reciprocity, and reliably exclude defectors.
    </p>
  </div>
</div>

<div class="pub-item">
  <div class="pub-figure">
    <img src="images/MCG.jpg" alt="Learning to Negotiate via Voluntary Commitment figure">
  </div>
  <div class="pub-body">
    <p class="pub-title">Learning to Negotiate via Voluntary Commitment</p>
    <p class="pub-meta">
      <b>Shuhui Zhu</b>, Baoxiang Wang, Sriram Ganapathi Subramanian, Pascal Poupart<br>
      <span class="pub-venue">AISTATS, 2025</span><br>
      <span class="pub-links">
        <a href="https://arxiv.org/abs/2503.03866">Paper</a> &middot;
        <a href="https://github.com/shuhui-zhu/DCL">Code</a> &middot;
        <a href="https://shuhui-zhu.github.io/files/seminar_talk_commitment.pdf">Talk</a> &middot;
        <a href="https://shuhui-zhu.github.io/files/AISTATS_poster.pdf">Poster</a>
      </span>
    </p>
    <p class="pub-abstract">
      We present a novel framework where RL agents can propose and voluntarily commit to actions in strategic interactions, improving cooperation among self-interested agents in challenging mixed-motive environments.
    </p>
  </div>
</div>

<div class="pub-item">
  <div class="pub-figure">
    <img src="images/reciprocity_grad.png" alt="The Reciprocity Gradient figure">
  </div>
  <div class="pub-body">
    <p class="pub-title">The Reciprocity Gradient</p>
    <p class="pub-meta">
      Yue Lin, Pascal Poupart, <b>Shuhui Zhu</b>, Dan Qiao, Wenhao Li, Yuan Liu, Hongyuan Zha, Baoxiang Wang<br>
      <span class="pub-venue">Working Paper</span><br>
      <span class="pub-links">
        <a href="https://arxiv.org/abs/2605.08323">Paper</a>
      </span>
    </p>
    <p class="pub-abstract">
      We introduce the reciprocity gradient, a novel method for learning cooperative policies in multi-agent environments by explicitly backpropagating reward gradients through private estimators of opponents' policies, enabling agents to account for the complex influence of their actions on others' reputations and future rewards without relying on intrinsic rewards or reward shaping.
    </p>
  </div>
</div>

<div class="pub-item">
  <div class="pub-figure">
    <img src="images/mpp.png" alt="Policy-Conditioned Policies figure">
  </div>
  <div class="pub-body">
    <p class="pub-title">Policy-Conditioned Policies for Multi-Agent Task Solving</p>
    <p class="pub-meta">
      Yue Lin, <b>Shuhui Zhu</b>, Wenhao Li, Ang Li, Dan Qiao, Pascal Poupart, Hongyuan Zha, Baoxiang Wang<br>
      <span class="pub-venue">Working Paper</span><br>
      <span class="pub-links">
        <a href="https://arxiv.org/abs/2512.21024">Paper</a>
      </span>
    </p>
    <p class="pub-abstract">
      We introduce Policy-Conditioned Policies, a paradigm that represents multi-agent strategies as human-interpretable code and leverages Large Language Models to iteratively synthesize and optimize these programmatic policies for adaptive task solving.
    </p>
  </div>
</div>

<div class="pub-item">
  <div class="pub-figure">
    <img src="images/BP_Flowchart.jpg" alt="Information Bargaining figure">
  </div>
  <div class="pub-body">
    <p class="pub-title">Information Bargaining: Bilateral Commitment in Bayesian Persuasion</p>
    <p class="pub-meta">
      Yue Lin, <b>Shuhui Zhu</b>, William A Cunningham, Wenhao Li, Pascal Poupart, Hongyuan Zha, Baoxiang Wang<br>
      <span class="pub-venue">Working Paper</span><br>
      <span class="pub-links">
        <a href="https://arxiv.org/abs/2506.05876">Paper</a>
      </span>
    </p>
    <p class="pub-abstract">
      This paper reframes Bayesian persuasion as an information bargaining problem to address its complexity in long-term interactions. Unlike one-sided commitment models, the proposed framework enables fairer and more efficient cooperation by balancing the sender's and receiver's roles. Empirical validation using LLMs confirms the framework’s predictions.
    </p>
  </div>
</div>

<div class="pub-item">
  <div class="pub-figure">
    <img src="images/altar.png" alt="Altared Environments figure">
  </div>
  <div class="pub-body">
    <p class="pub-title">Altared Environments: The Role of Normative Infrastructure in AI Alignment</p>
    <p class="pub-meta">
      Rakshit Trivedi, Nikhil Chandak, Andrei Ioan Muresanu, <b>Shuhui Zhu</b>, Atrisha Sarkar, Joel Z Leibo, Dylan Hadfield-Menell, Gillian K Hadfield<br>
      <span class="pub-venue">Under Review</span><br>
      <span class="pub-links">
        <a href="https://openreview.net/pdf?id=Gd6QrBLHBN">Paper</a>
      </span>
    </p>
    <p class="pub-abstract">
      We propose Altared Games, a novel Markov game framework integrating a classification institution to enable AI agents to adapt to dynamic norms, demonstrating its effectiveness in enhancing cooperation and social welfare in multi-agent reinforcement learning environments.
    </p>
  </div>
</div>

<!-- <div style="display: flex; align-items: center; margin-bottom: 20px; font-family: Garamond, serif;">
  <div style="flex: 0 0 420px; margin-right: 20px;">
    <img src="images/bpisbg.webp" alt="Paper Figure" width="420">
  </div>
  <div style="flex: 1;">
    <p style="font-size: 20px; font-weight: bold; color: #000; margin-bottom: 5px;">
      Bayesian Persuasion Is a Bargaining Game
    </p>
    <p style="margin-top: 0; margin-bottom: 5px;">
      Yue Lin, <b>Shuhui Zhu</b>, William A Cunningham, Wenhao Li, Pascal Poupart, Hongyuan Zha, Baoxiang Wang<br>
      <i>Submitted to ICLR, 2024</i> <br>
      <a href="https://openreview.net/forum?id=RWiqprM18N" style="color: #2E7F93;">Paper</a>
    </p>
    <p style="font-size: 16px; line-height: 1.5; margin-top: 0">
      We reformulate Bayesian persuasion as a bargaining game, demonstrating that the receiver can leverage strategic commitments to counteract the sender’s informational advantage, and validate this perspective through theoretical analysis and empirical experiments with large language models, which exhibit bargaining behaviors in persuasion tasks.
    </p>
  </div>
</div> -->

<div class="pub-item">
  <div class="pub-figure">
    <img src="images/dto.png" alt="Spline Parameterization for Continuous Normalizing Flows figure">
  </div>
  <div class="pub-body">
    <p class="pub-title">Spline Parameterization for Continuous Normalizing Flows</p>
    <p class="pub-meta">
      <b>Shuhui Zhu</b><br>
      <span class="pub-venue">Master's Thesis, 2021</span><br>
      <span class="pub-links">
        <a href="https://uwaterloo.ca/computational-mathematics/sites/default/files/uploads/documents/shuhui_zhu_research_paper.pdf">Thesis</a>
      </span>
    </p>
    <p class="pub-abstract">
      I develop a Spline-based parameterization method for Continuous Normalizing Flows using Neural ODEs, formulating the problem as an optimal control task to efficiently learn time-dependent patterns while reducing computational cost and maintaining accuracy.
    </p>
  </div>
</div>