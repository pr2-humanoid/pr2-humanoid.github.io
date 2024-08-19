<h2 align="center">
  <b><tt>PR2</tt>: A Physics- and Photo-realistic Humanoid Testbed with Pilot Study in Competition</b>
</h2>

<div align="center" margin-bottom="6em"> 
</div>

<div align="center" margin-bottom="6em">
Hangxin Liu, Qi Xie, Zeyu Zhang, Tao Yuan, Xiaokun Leng, Lining Sun <br/> Song-Chun Zhu, Jingwen Zhang<sup>✉️</sup>, Zhicheng He</a><sup>✉️</sup>,Yao Su</a><sup>✉️ </sup>
</div>
&nbsp;

<div align="center">
    <a href=" " target="_blank">
    <img src="https://img.shields.io/badge/Paper-arXiv-green" alt="Paper arXiv"></a>
    <a href="https://github.com/pr2-humanoid.github.io" target="_blank">
    <img src="https://img.shields.io/badge/Page-PR2-9cf" alt="Project Page"/></a> 
    <a href="" target="_blank">
    <img src="https://img.shields.io/badge/Data-Demos-9966ff" alt="Demos"/></a>
    
</div>
&nbsp;

![teaser](assets/teaser.png)

        

We present PR2, a humanoid robot testbed that evaluates a humanoid robot testbed designed for entry-level students with supports in

* **<span style="color: #EC407A;">bipedal locomotion</span>**  

* **<span style="color: #03A9F4;">multi-modal manipulation</span>** 

* **<span style="color: #FF7043;">interaction with vision and language foundation models</span>**
 
PR2</b> is built on <a target="_blank" href="https://developer.nvidia.com/isaac-sim">Isaac Sim</a>, which leverages
advanced GPU-enabled graphics and physics simulation with
Nvidia PhysX 5, enabling users to investigate and test robotic
skills in a physics-realistic and photo-realistic simulation environment. Designed to be modular, PR2 simplifies workflows
in interacting with humanoid robots with an easy-to-use interface for users. In addition to inheriting the capabilities of
Omniverse, PR2 consists of four main components: (i) the rendering module and (ii) the simulation
module, both built on Nvidia’s Omniverse and PhysX, respectively.
These modules support the import of various digital assets to create
diverse task environments and simulate physical effects such as forces
and system dynamics. Additionally, (iii) built-in model predictive and
whole-body controllers and (iv) high-level planners are provided for
beginners but can be replaced by more advanced users as needed.