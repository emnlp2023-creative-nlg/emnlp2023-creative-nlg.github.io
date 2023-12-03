---
title: EMNLP 23 Tutorial on Creative Natural Language Generation
layout: page
permalink: /
---

# Speakers

<div style="width:100%">
<div class="col-md-4" style="width:25%">
    <div class="profile height150">
        <div><a href="https://vnpeng.net/"><img class="avatar-img" width=110 src="images/violet-profile.png"></a></div>
        <div style="margin-bottom:40px"><center><b>Nanyun (Violet) Peng</b><br>UCLA</center></div>
    </div>
</div>
<div class="col-md-4" style="width:25%">
    <div class="profile height150">
        <div><a href="https://hhexiy.github.io"><img class="avatar-img" width=110 src="images/hehe-profile.png"> </a></div>
        <div style="margin-bottom:40px"><center><b>He He</b><br>NYU</center></div>
    </div>
</div>
<div class="col-md-4" style="width:25%">
    <div class="profile height150">
        <div><a href="https://tuhinjubcse.github.io/"><img class="avatar-img" width=110 src="images/tuhin-profile.png"></a></div>
        <div style="margin-bottom:40px"><center><b>Tuhin Chakrabarty</b><br>Columbia</center></div>
    </div>
</div>
<div class="col-md-4" style="width:25%">
    <div class="profile height150">
        <div><a href="http://vishakhpk.github.io"><img class="avatar-img" width=110 src="images/vishakh-profile.jpeg"></a></div>
        <div style="margin-bottom:40px"><center><b>Vishakh Padmakumar</b><br>NYU</center></div>
    </div>
</div>
</div>
<br/><br/>

# Overview

- **Date**: December 6, 2023
- **Duration**: 2pm - 5pm (3 hrs)
- **Location**: Pisces 2&3
- **EMNLP Page**: [Miniconf](https://virtual2023.emnlp.org/tutorial_t6.html)

Large language models such as GPT-3, GPT-4, Claude etc., have advanced the state-of-the-art in several natural language generation tasks such as text summarization and machine translation. However, when it comes to open-ended tasks with a focus on creativity such as generating stories, poetry, or various forms of figurative language, these state-of-the-art language models are often found to be inadequate.This tutorial aims to bring awareness of the important and emerging research area of open-domain creative generation, with a focus on language generation while also touching on multi-modal generation (e.g., image captioning, visual metaphors). It targets natural language processing (NLP) and artificial intelligence (AI) researchers as well as creative writing practitioners who are interested in building systems that are capable of emulating as well as augmenting human creativity. In particular, we will review recent studies on creative language generation both at the sentence level as well as longer forms of text. We will provide the audiences with a holistic view of 1) the importance and challenges of building creative language generation systems; 2) how we incorporate content planning, domain knowledge, and creativity-specific heuristics for different forms of creative language generation such as story, poetry, humor, metaphors, etc. 3) how can we build better evaluation methods for creative text generation in standalone as well as interactive settings? In particular, how could the recent advancement of AI shape the future workforce for creativity? We will conclude the tutorial by outlining future research directions in this area.

<div><img class="avatar-img" width=400 src="images/map.png"></div>

**Click on each chapter to view the reading lists:** 
<details>
<summary>Overview and Historical Perspective of Creativity in NLP</summary>
<b>TALESPIN</b>
    <br>
    <a target="_blank" href="https://www.ijcai.org/Proceedings/77-1/Papers/013.pdf">TALE-SPIN, AN INTERACTIVE PROGRAM THAT WRITES STORIES </a>Meehan et al (1977)</li>
    <br>
    <a target="_blank" href="https://www.ijcai.org/Proceedings/81-1/Papers/004.pdf">STORY GENERATION AFTER TALE-SPIN </a>Dehn et al (1981)</li>
    <br>
<b>POETICS</b>
    <br>
    <a target="_blank" href="https://www.sciencedirect.com/science/article/abs/pii/0304422X84900019">Creating characters in a story-telling universe </a>Lebowitz et al (1984)</li><br>
    <a target="_blank" href="https://era.ed.ac.uk/bitstream/handle/1842/3461/0016.pdf?sequence=1&isAllowed=y">A Flexible Integrated Architecture For Generating Poetic Texts </a>Manurung et al (2000)</li><br>
<b>PRAGMATICS</b>
    <br>
    <a target="_blank" href="https://www.sciencedirect.com/science/article/abs/pii/0378216687901093">Generating natural language under pragmatic constraints 
    </a>Hovy et al (1987)</li><br>
    <a target="_blank" href="https://aclanthology.org/P05-3029.pdf">HAHAcronym: A Computational Humor System </a>Stock et al (2005)</li><br>
</details>
<details>
<summary>Content Planning</summary>
<br>
<b>PLAN AND WRITE</b>
<br>
    <a target="_blank" href="https://vnpeng.net/bibliography/yao2019plan/">Plan-And-Write: Towards Better Automatic Storytelling
    </a>Yao et al (2019)</li>
    <br>
    <a target="_blank" href="https://aclanthology.org/P19-1254/">Strategies for Structuring Story Generation </a>Fan et al (2019)</li>
    <br>
    <a target="_blank" href="https://ojs.aaai.org/index.php/AAAI/article/view/11430">Event Representations for Automated Story Generation with Deep Neural Nets 
    </a>Martin et al (2018)</li><br>
<b>IMPROVE PLAN AND THEN WRITE</b>
    <br>
    <a target="_blank" href="https://aclanthology.org/2020.emnlp-main.351.pdf">Content Planning for Neural Story Generation with Aristotelian Rescoring</a>Goldfarb-Tarrant et al (2020)</li><br>
<b>PLAN AND WRITE BY PROMPTING LLMS</b>
    <br>
    <a target="_blank" href="https://aclanthology.org/2022.naacl-main.262/">Zero-shot Sonnet Generation with Discourse-level Planning and Aesthetics Features
 </a>Tian et al (2022)</li><br>
    <a target="_blank" href="https://aclanthology.org/2022.emnlp-main.296/">Re3: Generating Longer Stories With Recursive Reprompting and Revision </a>Yang et al (2022)</li><br>
    <a target="_blank" href="https://aclanthology.org/2023.acl-long.190/">DOC: Improving Long Story Coherence With Detailed Outline Control </a>Yang et al (2023)</li>
    <br>
</details>
<details>
<summary>Incorporating Domain Knowledge</summary>
<br>
<b>DOMAIN KNOWLEDGE FROM WEB</b>
<br>
    <a target="_blank" href="https://cdn.aaai.org/AAAI/2007/AAAI07-233.pdf">Comprehending and Generating Apt Metaphors: A Web-driven, Case-based Approach to Figurative Language 
    </a>Veale et al (2007)</li>
    <br>
<b>DOMAIN KNOWLEDGE FROM EXTERNAL KNOWLEDGE MODELS</b>
    <br>
    <a target="_blank" href="https://aclanthology.org/2020.emnlp-main.524.pdf">Generating similes effortlessly like a Pro : A Style Transfer Approach for Simile Generation </a>Chakrabarty et al (2020)</li><br>
    <a target="_blank" href="https://aclanthology.org/2021.naacl-main.336.pdf">MERMAID: Metaphor Generation with Symbolism and Discriminative Decoding
     </a>Chakrabarty et al (2021)</li>
    <br>
<b>DOMAIN KNOWLEDGE FROM PROMPTING LLMS</b>
    <br>
    <a target="_blank" href="https://aclanthology.org/2023.findings-acl.465.pdf">I Spy a Metaphor: Large Language Models and Diffusion Models Co-Create Visual Metaphors </a>Chakrabarty et al (2023)</li><br>
</details>
<details>
<summary>Distilling Creativity to an Algorithm</summary>
<br>
<b>FORMULATE PRIOR, DEVISE ALGORITHM</b>
<br>
    <a target="_blank" href="https://aclanthology.org/N19-1172/">Pun Generation with Surprise </a>He et al (2019)</li>
    <br>
<b>FORMULATE PRIOR, LEARN STRUCTURE, DEVISE ALGORITHM</b>
    <br>
    <a target="_blank" href="https://aclanthology.org/2022.findings-emnlp.237/">A Unified Framework for Pun Generation with Humor Principles </a>Tian et al (2022)</li><br>
</details>
<details>
<summary>Human Centered Evaluation of Creative Writing</summary>
<br>
    <a target="_blank" href="https://arxiv.org/pdf/2309.14556.pdf">Art or Artifice? Large Language Models and the False Promise of Creativity </a>Chakrabarty et al (2023)</li>
    <br>
</details>
<details>
<summary>Human AI collaboration for Creativity</summary>
<br>
    <a target="_blank" href="https://dl.acm.org/doi/10.1145/3172944.3172983">Creative writing with a machine in the loop: Case studies on slogans and stories </a>Clark et al (2018)</li>
    <br>
    <a target="_blank" href="https://aclanthology.org/2020.emnlp-main.525/">STORIUM: A Dataset and Evaluation Platform for Machine-in-the-Loop Story Generation </a>Akoury et al (2019)</li>
    <br>
    <a target="_blank" href="https://aclanthology.org/2022.naacl-main.42/">Machine-in-the-Loop Rewriting for Creative Image Captioning </a>Padmakumar et al (2022)</li>
    <br>
    <a target="_blank" href="https://arxiv.org/pdf/2210.13669.pdf">Help me write a poem: Instruction Tuning as a Vehicle for Collaborative Poetry Writing </a> Chakrabarty al (2022)</li><br>
    <a target="_blank" href="https://arxiv.org/pdf/2309.12570.pdf">Creativity Support in the Age of Large Language Models: An Empirical Study Involving Emerging Writers </a>Chakrabarty et al (2023)</li>
    <br>
</details>



