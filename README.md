<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!-- [![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Unlicense License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url] -->



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/ADAPT_icon.png" alt="Logo" width="200" height="200">
  </a>

  <h3 align="center">ADAPT: Benchmarking Commonsense Planning under Unspecified Affordance Constraints</h3>
</h3>

  <p align="center">
    A benchmark for evaluating whether embodied agents can reason about <b>implicit affordance constraints</b> and adapt to dynamic object states.
    <br />
    <a href="https://arxiv.org/abs/2604.14902"><strong>Explore the docs »</strong></a>
    <br />
    &middot;
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Paper</a>
    </li>
    <li>
      <a href="#getting-started">Key Contributions</a>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## 📌 About The Paper

DynAfford is a benchmark designed to evaluate whether embodied agents can handle **real-world commonsense scenarios** where:

- Instructions may be **incomplete or misleading**
- Object usability depends on **latent states** (e.g., dirty, occupied)
- Agents must **adapt actions instead of blindly executing plans**

Unlike prior benchmarks, DynAfford introduces:

- 🧠 **Implicit affordance reasoning**
- 🔄 **Dynamic object state transitions**
- 🎯 **Goal consistency under temporary infeasibility**

## 🚀 Key Contributions

- **Benchmark**: A new evaluation suite for dynamic affordance reasoning
- **ADAPT (Affordance-Aware Selection)**:
  - Detects infeasible actions
  - Defers execution instead of skipping goals
- **MICL + LoRA**:
  - Multimodal in-context learning
  - Fine-tuned LLaVA for affordance detection
<!-- 
## ⚙️ Installation
```bash
git clone https://github.com/your_username/ADAPT.git
cd ADAPT
``` -->


<!-- CONTACT -->
## 📬Contact

Pei-An Chen (Charlotte)
📧 charlottechen@cmlab.csie.ntu.edu.tw

Project Link:
https://charlotteannchen.github.io/ADAPT/

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## 🙏 Acknowledgments
We gratefully acknowledge the foundational contributions of prior work and open-source resources that made this project possible.

In particular, we thank the developers of the ALFRED benchmark and the AI2-THOR environment for providing essential platforms for embodied AI research. We also acknowledge the LLaVA project, whose codebase and models served as an important foundation for our affordance reasoning module.

Utilizing these resources implies agreement with their respective licenses. We deeply appreciate their contributions to the research community.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📖 Citations
If you use our work or our implementation in this repo or find them helpful, please consider giving a citation.
```bibtex
@misc{chen2026adaptbenchmarkingcommonsenseplanning,
      title={ADAPT: Benchmarking Commonsense Planning under Unspecified Affordance Constraints}, 
      author={Pei-An Chen and Yong-Ching Liang and Jia-Fong Yeh and Hung-Ting Su and Yi-Ting Chen and Min Sun and Winston Hsu},
      year={2026},
      eprint={2604.14902},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      url={https://arxiv.org/abs/2604.14902}, 
}
```
