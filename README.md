<div style="text-align: center;">
    <h1><img src="assets/logo.png" height="28px" /> Tool Learning Papers </h1>
</div>

Must-read papers on [tool learning](https://arxiv.org/abs/2304.08354) with foundation models. We also made some [slides](https://github.com/thunlp/ToolLearningPapers/tree/master/assets/tool_learning_ppt.pdf) about tool learning.

## Content

- [Content](#content)
- [Why Tool Learning?](#why-tool-learning)
- [Keywords Convention](#keywords-convention)
- [Papers](#papers)
  - [Survey](#survey)
  - [Tool-augmented Learning](#tool-augmented-learning)
  - [Tool-oriented Learning](#tool-oriented-learning)
  - [Applications and Toolkit](#applications-and-toolkit)
  - [Contributors](#contributors)
  - [Contributing to this paper list](#contributing-to-this-paper-list)

## Why Tool Learning?

Humans possess an extraordinary ability to create and utilize tools, allowing them to overcome physical limitations and explore new frontiers. With the advent of foundation models, AI systems have the potential to be equally adept in tool use as humans. This paradigm, i.e., tool learning with foundation models, combines the strengths of specialized tools and foundation models to achieve enhanced accuracy, efficiency, and automation in problem-solving. Despite its immense potential, there is still a lack of a comprehensive understanding of key challenges, opportunities, and future endeavors in this field. The field of tool learning is developing fast with many works being proposed lately. To make these works more accessible, we have created this repository with a list of resources related to tool learning, hoping to facilitate the development of this area.

## Keywords Convention

![](https://img.shields.io/badge/T5-blue) The abbreviation of the work.

![](https://img.shields.io/badge/Search_Engine-orange) The utilized tool in the work.

![](https://img.shields.io/badge/Other-green) Other important information of the work.

## Papers

### Survey

- **Tool Learning with Foundation Models**, Preprint 2023. ![](https://img.shields.io/badge/Tool_Augmented_Learning-green) ![](https://img.shields.io/badge/Tool_Oriented_Learning-green)

  *Yujia Qin, Shengding Hu, Yankai Lin, Weize Chen, Ning Ding, Ganqu Cui, Zheni Zeng, Yufei Huang, Chaojun Xiao, Chi Han, Yi Ren Fung, Yusheng Su, Huadong Wang, Cheng Qian, Runchu Tian, Kunlun Zhu, Shihao Liang, Xingyu Shen, Bokai Xu, Zhen Zhang, Yining Ye, Bowen Li, Ziwei Tang, Jing Yi, Yuzhang Zhu, Zhenning Dai, Lan Yan, Xin Cong, Yaxi Lu, Weilin Zhao, Yuxiang Huang, Junxi Yan, Xu Han, Xian Sun, Dahai Li, Jason Phang, Cheng Yang, Tongshuang Wu, Heng Ji, Zhiyuan Liu, Maosong Sun*. [[pdf](https://arxiv.org/abs/2304.08354)], [[Project](https://github.com/OpenBMB/BMTools)]

- **Augmented Language Models: a Survey**, Preprint 2023. ![](https://img.shields.io/badge/Tool_Augmented_Learning-green)

  *Grégoire Mialon, Roberto Dessì, Maria Lomeli, Christoforos Nalmpantis, Ram Pasunuru, Roberta Raileanu, Baptiste Rozière, Timo Schick, Jane Dwivedi-Yu, Asli Celikyilmaz, Edouard Grave, Yann LeCun, Thomas Scialom*. [[pdf](https://arxiv.org/abs/2302.07842)]

- **Foundation Models for Decision Making: Problems, Methods, and Opportunities**, Preprint 2023. ![](https://img.shields.io/badge/Tool_Oriented_Learning-green)

  *Sherry Yang, Ofir Nachum, Yilun Du, Jason Wei, Pieter Abbeel, Dale Schuurmans*. [[pdf](https://arxiv.org/abs/2303.04129)]

- **Interactive Natural Language Processing**, Preprint 2023. ![](https://img.shields.io/badge/Interactive_Learning-green)

  *Zekun Wang, Ge Zhang, Kexin Yang, Ning Shi, Wangchunshu Zhou, Shaochun Hao, Guangzheng Xiong, Yizhi Li, Mong Yuan Sim, Xiuying Chen, Qingqing Zhu, Zhenzhu Yang, Adam Nik, Qi Liu, Chenghua Lin, Shi Wang, Ruibo Liu, Wenhu Chen, Ke Xu, Dayiheng Liu, Yike Guo, Jie Fu*. [[pdf](https://arxiv.org/pdf/2305.13246.pdf)]

### Tool-augmented Learning

- **Tool Documentation Enables Zero-Shot Tool-Usage with Large Language Models** Preprint 2023.

  *Cheng-Yu Hsieh, Si-An Chen, Chun-Liang Li, Yasuhisa Fujii, Alexander Ratner, Chen-Yu Lee, Ranjay Krishna, Tomas Pfister* [[pdf](https://arxiv.org/pdf/2308.00675.pdf)]

- **ToolQA: A Dataset for LLM Question Answering with External Tools** Preprint 2023. ![](https://img.shields.io/badge/Database-orange)

  *Yuchen Zhuang, Yue Yu, Kuan Wang, Haotian Sun, Chao Zhang* [[pdf](https://arxiv.org/pdf/2306.13304.pdf)] [[Code](https://github.com/night-chen/ToolQA)]

- **Toolformer: Language Models Can Teach Themselves to Use Tools** Preprint 2023. ![](https://img.shields.io/badge/Search_Engine-orange) ![](https://img.shields.io/badge/Calculator-orange) ![](https://img.shields.io/badge/Calendar-orange) ![](https://img.shields.io/badge/Wikipedia-orange)

  *Timo Schick, Jane Dwivedi-Yu, Roberto Dessì, Roberta Raileanu, Maria Lomeli, Luke Zettlemoyer, Nicola Cancedda, Thomas Scialom* [[pdf](https://arxiv.org/abs/2302.04761)], [[Code](https://github.com/lucidrains/toolformer-pytorch)]
  
- **Generalization through Memorization: Nearest Neighbor Language Models** ICLR 2020. ![](https://img.shields.io/badge/Text_Retriever-orange)

  *Urvashi Khandelwal, Omer Levy, Dan Jurafsky, Luke Zettlemoyer, Mike Lewis* [[pdf](https://openreview.net/pdf?id=HklBjCEKvH)] [[Code](https://github.com/urvashik/knnlm)]

- **Improving Language Models by Retrieving from Trillions of Tokens** PMLR 2022. ![](https://img.shields.io/badge/Text_Retriever-orange)

  *Sebastian Borgeaud, Arthur Mensch, Jordan Hoffmann, Trevor Cai, Eliza Rutherford, Katie Millican, George Bm Van Den Driessche, Jean-Baptiste Lespiau, Bogdan Damoc, Aidan Clark, Diego De Las Casas, Aurelia Guy, Jacob Menick, Roman Ring, Tom Hennigan, Saffron Huang, Loren Maggiore, Chris Jones, Albin Cassirer, Andy Brock, Michela Paganini, Geoffrey Irving, Oriol Vinyals, Simon Osindero, Karen Simonyan, Jack Rae, Erich Elsen, Laurent Sifre* [[pdf](https://proceedings.mlr.press/v162/borgeaud22a/borgeaud22a.pdf)], [[blog](https://www.deepmind.com/blog/improving-language-models-by-retrieving-from-trillions-of-tokens)]
  
- **Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models** Preprint 2023. ![](https://img.shields.io/badge/Composition-orange) ![](https://img.shields.io/badge/Python_Interpreter-orange) ![](https://img.shields.io/badge/Search_Engine-orange) ![](https://img.shields.io/badge/Multi_Model-orange)

  *Pan Lu, Baolin Peng, Hao Cheng, Michel Galley, Kai-Wei Chang, Ying Nian Wu, Song-Chun Zhu, Jianfeng Gao* [[pdf](https://arxiv.org/pdf/2304.09842)], [[Blog](https://chameleon-llm.github.io/)], [[Code](https://github.com/lupantech/chameleon-llm)]

- **RestGPT: Connecting Large Language Models with Real-World Applications via RESTful APIs** Preprint 2023. ![](https://img.shields.io/badge/RESTAPI-orange)

  *Yifan Song, Weimin Xiong, Dawei Zhu, Cheng Li, Ke Wang, Ye Tian, Sujian Li* [[pdf](https://arxiv.org/abs/2306.06624)]

- **ToolAlpaca: Generalized Tool Learning for Language Models with 3000 Simulated Cases** Preprint 2023.

  *Qiaoyu Tang, Ziliang Deng, Hongyu Lin, Xianpei Han, Qiao Liang, Le Sun* [[pdf](https://arxiv.org/abs/2306.05301)]


- **Large Language Models are Versatile Decomposers: Decompose Evidence and Questions for Table-based Reasoning** SIGIR 2023. ![](https://img.shields.io/badge/SQL_Interpreter-orange)

  *Yunhu Ye, Binyuan Hui, Min Yang, Binhua Li, Fei Huang, Yongbin Li* [[pdf](https://arxiv.org/abs/2301.13808)] [[Code](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/dater)]

- **Extracting training data from large language models** USENIX 2021. ![](https://img.shields.io/badge/Search_Engine-orange)

  *Nicholas Carlini, Florian Tramèr, Eric Wallace, Matthew Jagielski, Ariel Herbert-Voss, Katherine Lee, Adam Roberts, Tom Brown, Dawn Song, Úlfar Erlingsson, Alina Oprea, Colin Raffel* [[pdf](https://www.usenix.org/system/files/sec21-carlini-extracting.pdf)], [[code](https://github.com/ftramer/LM_Memorization)]

- **Lamda: Language models for dialog applications** Preprint 2022. ![](https://img.shields.io/badge/Search_Engine-orange)

  *Aaron Daniel Cohen, Adam Roberts, Aleandra Molina, Alena Butryna, Alicia Jin, Apoorv Kulshreshtha, Ben Hutchinson, Ben Zevenbergen,Blaise Hilary Aguera Arcas, Chung-ching Chang, Claire Cui, Cosmo Du, Daniel De Freitas Adiwardana, Dehao Chen, Dmitry (Dima) Lepikhin, Ed H. Chi-rin Hoffman-ohn. Heno-1ze Chend. Honarae ee. cor krivokon. James 0in. amie Ha. oe Fenton. ohnny Soraker. athy Meier-HelstemKristen 0lson, Lora Mois Aroyo, Maarten Paul Bosma, Marc Joseph Pickett, Marcelo Amorim Menegali, Marian Croak, Mark Diaz, Matthew Lamm,Maxim Krikun, Meredith RingelMoris,Noam Shazeer, Quoc V Le, Rachel Berstein, Ravi Rajakumar, Ray kurzwei, Roma Thoppilan, Steven ZhengTaylor Bos,Toju Duke, Tulse Doshi, Vincent . Zhao, Vinodkumar Prabhakaran, Wil Rusch, YaGuang Li, Yanping Huang, Yangi Zhou, Yuanzhong XuZhifeng Chen* [[pdf](https://arxiv.org/abs/2201.08239.pdf)]

- **Recitation-Augmented Language Models** Preprint 2022. ![](https://img.shields.io/badge/Model_Knowledge-orange)

  *Zhiqing Sun, Xuezhi Wang, Yi Tay, Yiming Yang, Denny Zhou* [[pdf](https://arxiv.org/abs/2210.01296.pdf)], [[code](https://github.com/Edward-Sun/RECITE)]

* **Re-imagen: Retrieval-augmented text-to-image generator** Preprint 2022. ![](https://img.shields.io/badge/Multi_Model-orange)

  *Wenhu Chen, Hexiang Hu, Chitwan Saharia, William W. Cohen* [[pdf](https://arxiv.org/abs/2209.14491.pdf)]

* **Knn-diffusion: Image generation via large-scale retrieval** Preprint 2022. ![](https://img.shields.io/badge/Image_Retriever-orange)

  *Shelly Sheynin, Oron Ashual, Adam Polyak, Uriel Singer, Oran Gafni, Eliya Nachmani, Yaniv Taigman* [[pdf](https://arxiv.org/abs/2204.02849)]

* **Training verifiers to solve math word problems** Preprint 2021. ![](https://img.shields.io/badge/Calculator-orange)

  *Karl Cobbe, Vineet Kosaraju, Mohammad Bavarian, Mark Chen, Heewoo Jun, Lukasz Kaiser, Matthias Plappert, Jerry Tworek, Jacob Hilton, Reiichiro Nakano, Christopher Hesse, John Schulman* [[pdf](https://arxiv.org/abs/2110.14168)]

* **Talm: Tool augmented language models** Preprint 2022. ![](https://img.shields.io/badge/Calculator-orange) ![](https://img.shields.io/badge/QA_System-orange)  

  *Aaron Parisi, Yao Zhao, Noah Fiedel* [[pdf](https://arxiv.org/abs/2205.12255)]

* **Mind's Eye: Grounded Language Model Reasoning through Simulation** Preprint 2022. ![](https://img.shields.io/badge/Physics_Stimulation_Engine-orange)

  *Ruibo Liu, Jason Wei, Shixiang Shane Gu, Te-Yen Wu, Soroush Vosoughi, Claire Cui, Denny Zhou, Andrew M. Dai* [[pdf](https://arxiv.org/abs/2210.05359.pdf)]
  
* **Program of thoughts prompting: Disentangling computation from reasoning for numerical reasoning tasks** Preprint 2022. ![](https://img.shields.io/badge/Python_Interpreter-orange)

  *Wenhu Chen, Xueguang Ma, Xinyi Wang, William W. Cohen* [[pdf](https://arxiv.org/abs/2211.12588)]
  
* **PAL: Program-aided Language Models** Preprint 2022. ![](https://img.shields.io/badge/Python_Interpreter-orange)

  *Luyu Gao, Aman Madaan, Shuyan Zhou, Uri Alon, Pengfei Liu, Yiming Yang, Jamie Callan, Graham Neubig* [[pdf](https://arxiv.org/abs/2211.10435)]
  
* **Behavior Cloned Transformers are Neurosymbolic Reasoners** Preprint 2022. ![](https://img.shields.io/badge/Symbolic_Modules-orange)

  *Ruoyao Wang, Peter Jansen, Marc-Alexandre Côté, Prithviraj Ammanabrolu* [[pdf](https://arxiv.org/abs/2210.07382)]
  
* **Show your work: Scratchpads for intermediate computation with language models** Preprint 2021. ![](https://img.shields.io/badge/Scratch_Pad-orange)

  *Maxwell Nye, Anders Johan Andreassen, Guy Gur-Ari, Henryk Michalewski, Jacob Austin, David Bieber, David Dohan, Aitor Lewkowycz, Maarten Bosma, David Luan, Charles Sutton, Augustus Odena* [[pdf](https://arxiv.org/abs/2112.00114)]

* **Making Language Models Better Tool Learners with Execution Feedback** Preprint 2023. ![](https://img.shields.io/badge/Calculator-orange)

  *Shuofei Qiao, Honghao Gui, Huajun Chen, Ningyu Zhang* [[pdf](https://arxiv.org/pdf/2305.13068.pdf)]
  
* **GeneGPT: Augmenting Large Language Models with Domain Tools for Improved Access to Biomedical Information** Preprint 2023. ![](https://img.shields.io/badge/GeneGPT-blue) ![](https://img.shields.io/badge/NCBI_Web_API-orange) ![](https://img.shields.io/badge/Biomedicine-green)

  *Qiao Jin, Yifan Yang, Qingyu Chen, Zhiyong Lu* [[pdf](https://arxiv.org/pdf/2304.09667.pdf)]

* **Adaptive Chameleon or Stubborn Sloth: Unraveling the Behavior of Large Language Models in Knowledge Conflicts** Preprint 2023.

  *Jian Xie, Kai Zhang, Jiangjie Chen, Renze Lou, Yu Su* [[pdf](https://arxiv.org/pdf/2305.13300.pdf)]

### Tool-oriented Learning

- **ShortcutsBench: A Large-Scale Real-world Benchmark for API-based Agents** Preprint 2024. ![](https://img.shields.io/badge/Computer-orange) ![](https://img.shields.io/badge/iPhone-orange) ![](https://img.shields.io/badge/iPad-orange)

  *Haiyang Shen, Yue Li, Desong Meng, Dongqi Cai, Sheng Qi, Li Zhang, Mengwei Xu, Yun Ma* [[pdf](https://arxiv.org/abs/2407.00132)] [[Code](https://github.com/eachsheep/shortcutsbench)]

- **ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs** Preprint 2023. ![](https://img.shields.io/badge/RapidAPI-orange)

  *Yujia Qin, Shihao Liang, Yining Ye, Kunlun Zhu, Lan Yan, Yaxi Lu, Yankai Lin, Xin Cong, Xiangru Tang, Bill Qian, Sihan Zhao, Runchu Tian, Ruobing Xie, Jie Zhou, Mark Gerstein, Dahai Li, Zhiyuan Liu, Maosong Sun* [[pdf](https://arxiv.org/pdf/2307.16789.pdf)] [[Code](https://github.com/OpenBMB/ToolBench)]

- **TPTU: Task Planning and Tool Usage of Large Language Model-based AI Agents** Preprint 2023.

  *Jingqing Ruan, Yihong Chen, Bin Zhang, Zhiwei Xu, Tianpeng Bao, Guoqing Du, Shiwei Shi, Hangyu Mao, Xingyu Zeng, Rui Zhao* [[pdf](https://arxiv.org/pdf/2308.03427.pdf)]

- **WebCPM: Interactive Web Search for Chinese Long-form Question Answering** Preprint 2023. ![](https://img.shields.io/badge/Search_Engine-orange)

  *Yujia Qin, Zihan Cai, Dian Jin, Lan Yan, Shihao Liang, Kunlun Zhu, Yankai Lin, Xu Han, Ning Ding, Huadong Wang, Ruobing Xie, Fanchao Qi, Zhiyuan Liu, Maosong Sun and Jie Zhou* [[pdf](https://arxiv.org/abs/2305.06849)], [[Code](https://github.com/thunlp/WebCPM)]

- **CREATOR: Disentangling Abstract and Concrete Reasonings of Large Language Models through Tool Creation** Preprint 2023. ![](https://img.shields.io/badge/Math_Solver-orange)

  *Cheng Qian, Chi Han, Yi R. Fung, Yujia Qin, Zhiyuan Liu, Heng Ji* [[pdf](https://arxiv.org/abs/2305.14318)], [[Code](https://github.com/thunlp/WebCPM)]

- **Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents** Preprint 2023. ![](https://img.shields.io/badge/Robots-orange)

  *Zihao Wang, Shaofei Cai, Anji Liu, Xiaojian Ma, Yitao Liang* [[Project](http://www.craftjarvis.org)], [[pdf](https://arxiv.org/abs/2302.01560)], [[Code](https://github.com/CraftJarvis/MC-Planner)]

- **On the Tool Manipulation Capability of Open-source Large Language Models** Preprint 2023.

  *Qiantong Xu, Fenglu Hong, Bo Li, Changran Hu, Zhengyu Chen, Jian Zhang* [[pdf](https://arxiv.org/pdf/2305.16504.pdf)], [[Code](https://github.com/sambanova/toolbench)]

- **WebGPT: Browser-assisted question-answering with human feedback** Preprint 2023. ![](https://img.shields.io/badge/Search_Engine-orange)

  *Reiichiro Nakano, Jacob Hilton, Suchir Balaji, Jeff Wu, Long Ouyang, Christina Kim, Christopher Hesse, Shantanu Jain, Vineet Kosaraju, William Saunders, Xu Jiang, Karl Cobbe, Tyna Eloundou, Gretchen Krueger, Kevin Button, Matthew Knight, Benjamin Chess, John Schulman* [[pdf](https://arxiv.org/abs/2112.09332)], [[Blog](https://openai.com/research/webgpt)]

- **ReAct: Synergizing Reasoning and Acting in Language Models** ICLR 2023. ![](https://img.shields.io/badge/Shopping-orange) ![](https://img.shields.io/badge/Search_Engine-orange)

  *Shunyu Yao, Jeffrey Zhao, Dian Yu, Nan Du, Izhak Shafran, Karthik Narasimhan, Yuan Cao* [[pdf](https://arxiv.org/abs/2210.03629)], [[Blog](https://react-lm.github.io/)], [[Code](https://github.com/ysymyth/ReAct)]

- **Language Models as Zero-Shot Planners: Extracting Actionable Knowledge for Embodied Agents** PMLR, 2022. ![](https://img.shields.io/badge/Robots-orange)

  *Wenlong Huang, Pieter Abbeel, Deepak Pathak, Igor Mordatch* [[pdf](https://proceedings.mlr.press/v162/huang22a/huang22a.pdf)], [[Blog](https://wenlong.page/language-planner/)], [[Code](https://github.com/huangwl18/language-planner)]

- **Do As I Can, Not As I Say: Grounding Language in Robotic Affordances** Preprint 2022. ![](https://img.shields.io/badge/Robots-orange)

  *Michael Ahn, Anthony Brohan, Noah Brown, Yevgen Chebotar, Omar Cortes, Byron David, Chelsea Finn, Chuyuan Fu, Keerthana Gopalakrishnan, Karol Hausman, Alex Herzog, Daniel Ho, Jasmine Hsu, Julian Ibarz, Brian Ichter, Alex Irpan, Eric Jang, Rosario Jauregui Ruano, Kyle Jeffrey, Sally Jesmonth, Nikhil J Joshi, Ryan Julian, Dmitry Kalashnikov, Yuheng Kuang, Kuang-Huei Lee, Sergey Levine, Yao Lu, Linda Luu, Carolina Parada, Peter Pastor, Jornell Quiambao, Kanishka Rao, Jarek Rettinghouse, Diego Reyes, Pierre Sermanet, Nicolas Sievers, Clayton Tan, Alexander Toshev, Vincent Vanhoucke, Fei Xia, Ted Xiao, Peng Xu, Sichun Xu, Mengyuan Yan, Andy Zeng* [[pdf](https://arxiv.org/pdf/2204.01691.pdf)], [[Blog](https://say-can.github.io/)], [[Code](https://github.com/google-research/google-research/tree/master/saycan)]

- **Inner Monologue: Embodied Reasoning through Planning with Language Models** Preprint 2022. ![](https://img.shields.io/badge/Robots-orange)

  *Wenlong Huang, Fei Xia, Ted Xiao, Harris Chan, Jacky Liang, Pete Florence, Andy Zeng, Jonathan Tompson, Igor Mordatch, Yevgen Chebotar, Pierre Sermanet, Noah Brown, Tomas Jackson, Linda Luu, Sergey Levine, Karol Hausman, Brian Ichter* [[pdf](https://arxiv.org/pdf/2207.05608.pdf)], [[Blog](https://innermonologue.github.io/)]

- **Code as Policies: Language Model Programs for Embodied Control** Preprint 2022. ![](https://img.shields.io/badge/Robots-orange)

  *Jacky Liang, Wenlong Huang, Fei Xia, Peng Xu, Karol Hausman, Brian Ichter, Pete Florence, Andy Zeng* [[pdf](https://arxiv.org/pdf/2209.07753.pdf)], [[Blog](https://code-as-policies.github.io/)], [[Code](https://github.com/google-research/google-research/tree/master/code_as_policies)]

- **ProgPrompt: Generating Situated Robot Task Plans using Large Language Models** Preprint 2022. ![](https://img.shields.io/badge/Physics_Stimulation_Engine-orange)

  *Ishika Singh, Valts Blukis, Arsalan Mousavian, Ankit Goyal, Danfei Xu, Jonathan Tremblay, Dieter Fox, Jesse Thomason, Animesh Garg* [[pdf](https://arxiv.org/pdf/2209.11302.pdf)]

- **Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language** Preprint 2022. ![](https://img.shields.io/badge/Neural_Model-orange)

  *Andy Zeng, Maria Attarian, Brian Ichter, Krzysztof Choromanski, Adrian Wong, Stefan Welker, Federico Tombari, Aveek Purohit, Michael Ryoo, Vikas Sindhwani, Johnny Lee, Vincent Vanhoucke, Pete Florence* [[pdf](https://arxiv.org/pdf/2204.00598.pdf)]

- **A Generalist Agent** Preprint 2022.

  *Scott Reed, Konrad Zolna, Emilio Parisotto, Sergio Gomez Colmenarejo, Alexander Novikov, Gabriel Barth-Maron, Mai Gimenez, Yury Sulsky, Jackie Kay, Jost Tobias Springenberg, Tom Eccles, Jake Bruce, Ali Razavi, Ashley Edwards, Nicolas Heess, Yutian Chen, Raia Hadsell, Oriol Vinyals, Mahyar Bordbar, Nando de Freitas* [[pdf](https://arxiv.org/pdf/2205.06175.pdf)]

- **PaLM-E: An Embodied Multimodal Language Model** Preprint 2023.

  *Danny Driess, Fei Xia, Mehdi S. M. Sajjadi, Corey Lynch, Aakanksha Chowdhery, Brian Ichter, Ayzaan Wahid, Jonathan Tompson, Quan Vuong, Tianhe Yu, Wenlong Huang, Yevgen Chebotar, Pierre Sermanet, Daniel Duckworth, Sergey Levine, Vincent Vanhoucke, Karol Hausman, Marc Toussaint, Klaus Greff, Andy Zeng, Igor Mordatch, Pete Florence* [[pdf](https://arxiv.org/pdf/2303.03378.pdf)], [[Blog](https://palm-e.github.io/)]

- **WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents** Preprint 2022. ![](https://img.shields.io/badge/Shopping-orange)

  *Shunyu Yao, Howard Chen, John Yang, Karthik Narasimhan* [[pdf](https://arxiv.org/pdf/2207.01206.pdf)], [[Blog](https://webshop-pnlp.github.io/)], [[Code](https://github.com/princeton-nlp/WebShop)]

- **Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models** Preprint 2023. ![](https://img.shields.io/badge/Neural_Model-orange)

  *Chenfei Wu, Shengming Yin, Weizhen Qi, Xiaodong Wang, Zecheng Tang, Nan Duan* [[pdf](https://arxiv.org/pdf/2303.04671.pdf)], [[Code](https://github.com/microsoft/TaskMatrix)]

- **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in HuggingFace** Preprint 2023. ![](https://img.shields.io/badge/Neural_Model-orange)

  *Yongliang Shen, Kaitao Song, Xu Tan, Dongsheng Li, Weiming Lu, Yueting Zhuang* [[pdf](https://arxiv.org/pdf/2303.17580.pdf)], [[Code](https://github.com/microsoft/JARVIS)]

- **Language Models can Solve Computer Tasks** Preprint 2023. ![](https://img.shields.io/badge/Computer-orange)

  *Geunwoo Kim, Pierre Baldi, Stephen McAleer* [[pdf](https://arxiv.org/pdf/2303.17491.pdf)]

- **ToolkenGPT: Augmenting Frozen Language Models with Massive Tools via Tool Embeddings** Preprint 2023.

  *Shibo Hao, Tianyang Liu, Zhen Wang, Zhiting Hu* [[pdf](https://arxiv.org/abs/2305.11554)]

- **Large Language Models as Tool Makers** Preprint 2023.![](https://img.shields.io/badge/Python_Interpreter-orange)

  *Tianle Cai, Xuezhi Wang, Tengyu Ma, Xinyun Chen, Denny Zhou* [[pdf](https://arxiv.org/abs/2305.17126)],[[Code](https://github.com/ctlllll/LLM-ToolMaker)] 

- **Data-Copilot: Bridging Billions of Data and Humans with Autonomous Workflow** Preprint 2023.![](https://img.shields.io/badge/Python_Interpreter-orange)

  *Wenqi Zhang, Yongliang Shen, Weiming Lu, Yueting Zhuang*  [[pdf](https://arxiv.org/abs/2306.07209)],[[Code](https://github.com/zwq2018/Data-Copilot)]

- **GEAR: Augmenting Language Models with Generalizable and Efficient Tool Resolution** Preprint 2023.![](https://img.shields.io/badge/Tool%20Grounding-blue)

  *Yining Lu, Haoping Yu, Daniel Khashabi* [[pdf](https://arxiv.org/abs/2307.08775)],[[Code](https://github.com/yining610/GEAR)]

  

  

### Applications and Toolkit

- **BMTools**. [[Project](https://github.com/OpenBMB/BMTools)]

- **ToolBench**. [[Project](https://github.com/OpenBMB/ToolBench)]

- **WebCPM**. [[Project](https://github.com/thunlp/WebCPM)]

- **AgentVerse**. [[Project](https://github.com/OpenBMB/AgentVerse)]

- **ChatGPT Plugins**. [[Project](https://platform.openai.com/docs/plugins/)]

- **LangChain**. [[Project](https://github.com/hwchase17/langchain)]

- **Auto-GPT**. [[Project](https://github.com/Significant-Gravitas/Auto-GPT)]

- **BabyAGI**. [[Project](https://github.com/yoheinakajima/babyagi)]

### Contributors

<a href="https://github.com/thunlp/ToolLearningPapers/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=thunlp/ToolLearningPapers" />
</a>

### Contributing to this paper list

-  There are cases where we miss important works in this field, please contribute to this repo! Thanks for the efforts in advance.
