<h1 align="center">Awesome LLM Reasoning Failures</h1>

<p align="center">
    <b> Welcome! This repository is a curated collection of research works on LLM reasoning failures.</b>
</p>

🚩**News**: Our paper is accepted to the Transactions on Machine Learning Research (TMLR), 2026, with a **Survey Certificate**.

<details>
  <summary>🗂️ <b>Table of Contents</b></summary>
  <ol>
    <li><a href="#surveys">Surveys</a></li>
    <li><a href="#informal-reasoning---intuitive-cognition-and-social-behavior">Informal Reasoning - Intuitive Cognition and Social Behavior</a></li>
      <ul>
        <li><a href="#individual-cognitive-skills-and-biases">Individual Cognitive Skills and Biases</a></li>
        <li><a href="#implicit-social-reasoning">Implicit Social Reasoning</a></li>
        <li><a href="#explicit-social-reasoning">Explicit Social Reasoning</a></li>
      </ul>
    <li><a href="#formal-reasoning----logic-and-arithmetic">Formal Reasoning - Logic and Arithmetic</a></li>
      <ul>
        <li><a href="#logic-in-natural-languages">Logic in Natural Languages</a></li>
        <li><a href="#logic-in-benchmarks">Logic in Benchmarks</a></li>
        <li><a href="#arithmetic-and-mathematics">Arithmetic and Mathematics</a></li>
      </ul>
    <li><a href="#reasoning-in-embodied-environments">Reasoning in Embodied Environments</a></li>
      <ul>
        <li><a href="#1d---text-based">1D - Text Based</a></li>
        <li><a href="#2d---perception-based">2D - Perception Based</a></li>
        <li><a href="#3d---real-world">3D - Real-World</a></li>
      </ul>
    <li><a href="#generalcase-by-case-reasoning-failure-studies">General/Case-by-Case Reasoning Failure Studies</a></li>
  </ol>
</details>

![Image](https://github.com/user-attachments/assets/0ed3892b-462a-483d-bec2-1ada7c4bf463)

We welcome contributions - please feel free to open an issue or start a pull request if you would like to add new works to this collection!

## Surveys

1. **Large Language Model Reasoning Failures** `TMLR 2026` [[paper]](https://openreview.net/attachment?id=vnX1WHMNmz&name=pdf)

   *Song, Peiyang and Han, Pengrui and Goodman, Noah*

2. [Related] **Why Do Multi-Agent LLM Systems Fail?** `NeurIPS 2025` [[paper]](https://arxiv.org/abs/2503.13657)

   *Cemri, Mert and Pan, Melissa Z. and Yang, Shuyi and Agrawal, Lakshya A. and Chopra, Bhavya and Tiwari, Rishabh and Keutzer, Kurt and Parameswaran, Aditya and Klein, Dan and Ramchandran, Kannan and Zaharia, Matei and Gonzalez, Joseph E. and Stoica, Ion*

## Informal Reasoning - Intuitive Cognition and Social Behavior

### Individual Cognitive Skills and Biases

1. **Working memory capacity of ChatGPT: An empirical study** `AAAI 2024` [[paper]](https://arxiv.org/abs/2305.03731)

   *Gong, Dongyu and Wan, Xingchen and Wang, Dingmin*

1. **Working memory identifies reasoning limits in language models** `EMNLP 2024` [[paper]](https://aclanthology.org/2024.emnlp-main.938/)

   *Zhang, Chunhui and Jian, Yiren and Ouyang, Zhongyu and Vosoughi, Soroush*

1. **Self-Attention Limits Working Memory Capacity of Transformer-Based Modelss** `NeurIPS 2024 Workshop on Behavioral ML` [[paper]](https://openreview.net/forum?id=dXjQgm9kAr)

   *Dongyu Gong and Hantao Zhang*

1. **Unable to Forget: Proactive lnterference Reveals Working Memory Limits in LLMs Beyond Context Length** `ICML 2025 LCFM Workshop` [[paper]](https://openreview.net/forum?id=YUHksmL8aw)

   *Chupei Wang and Jiaqiu Vince Sun*

1. **LLMs Do Not Have Human-Like Working Memory** `arXiv preprint` [[paper]](https://arxiv.org/abs/2505.10571)

   *Huang, Jen-tse and Sun, Kaiser and Wang, Wenxuan and Dredze, Mark*

1. **Working memory attack on LLMs** `ICLR 2025 Workshop on BuildingTrust` [[paper]](https://openreview.net/forum?id=II0NVPLBcI)

   *Upadhayay, Bibek and Behzadan, Vahid and Karbasi, Amin*

1. **In-Context Learning May Not Elicit Trustworthy Reasoning: A-Not-B Errors in Pretrained Language Models** `EMNLP 2024` [[paper]](https://arxiv.org/abs/2409.15454)

   *Han, Pengrui and Song, Peiyang and Yu, Haofei and You, Jiaxuan*

1. **Deficient Executive Control in Transformer Attention** `bioRxiv preprint` [[paper]](https://www.biorxiv.org/content/10.1101/2025.01.22.634394v1)

   *Patel, Suketu and Wang, Hongbin and Fan, Jin*

1. **Cognitive flexibility of large language models** `ICML 2024 Workshop on LLMs and Cognition` [[paper]](https://openreview.net/forum?id=58yThpzlth)

   *Kennedy, Sean M and Nowak, Robert D*

1. **LLMs and the Abstraction and Reasoning Corpus: Successes, Failures, and the Importance of Object-based Representations** `TMLR 2024` [[paper]](https://openreview.net/forum?id=E8m8oySvPJ)

   *Xu, Yudong and Li, Wenhao and Vaezipoor, Pashootan and Sanner, Scott and Khalil, Elias B*

1. **Large language models are not strong abstract reasoners** `arXiv preprint` [[paper]](https://arxiv.org/abs/2305.19555)

   *Gendron, Ga{\"e}l and Bao, Qiming and Witbrock, Michael and Dobbie, Gillian*
 
1. **Evidence of Cognitive Deficits and Developmental Advances in Generative AI: A Clock Drawing Test Analysis** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.11756)

   *Galatzer-Levy, Isaac R and McGiffin, Jed and Munday, David and Liu, Xin and Karmon, Danny and Labzovsky, Ilia and Moroshko, Rivka and Zait, Amir and McDuff, Daniel*

1. **Lost in Time: Clock and Calendar Understanding Challenges in Multimodal LLMs** `arXiv preprint` [[paper]](https://arxiv.org/abs/2502.05092)

   *Rohit Saxena and Aryo Pradipta Gema and Pasquale Minervini*

1. **Language models, like humans, show content effects on reasoning tasks** `PNAS Nexus 2024` [[paper]](https://academic.oup.com/pnasnexus/article/3/7/pgae233/7712372)

   *Lampinen, Andrew K and Dasgupta, Ishita and Chan, Stephanie CY and Sheahan, Hannah R and Creswell, Antonia and Kumaran, Dharshan and McClelland, James L and Hill, Felix*

1. **Confirmation and Specificity Biases in Large Language Models: An Explorative Study** `IEEE Intelligent Systems` [[paper]](https://ieeexplore.ieee.org/document/10897252)

   *O’Leary, Daniel E*

1. **Unveiling Confirmation Bias in Chain-of-Thought Reasoning** `ACL 2025` [[paper]](https://aclanthology.org/2025.findings-acl.195/)

   *Yue Wan and Xiaowei Jia and Xiang Lorraine Li*

1. **Conformity in Large Language Models** `ACL 2025` [[paper]](https://aclanthology.org/2025.acl-long.195/)

   *Zhu, Xiaochen and Zhang, Caiqi and Stafford, Tom and Collier, Nigel and Vlachos, Andreas*

1. **Argumentative Experience: Reducing Confirmation Bias on Controversial Issues through LLM-Generated Multi-Persona Debates** `arXiv preprint` [[paper]](https://arxiv.org/abs/2412.04629)

   *Shi, Li and Liu, Houjiang and Wong, Yian and Mujumdar, Utkarsh and Zhang, Dan and Gwizdka, Jacek and Lease, Matthew*
   
1. **A Comprehensive Evaluation of Cognitive Biases in LLMs** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.15413)

   *Malberg, Simon and Poletukhin, Roman and Schuster, Carolin M and Groh, Georg*
   
1. **Cognitive bias in high-stakes decision-making with llms** `EMNLP 2024` [[paper]](https://arxiv.org/abs/2403.00811)

   *Echterhoff, Jessica and Liu, Yao and Alessa, Abeer and McAuley, Julian and He, Zexue*

1. **Correcting negative bias in large language models through negative attention score alignment** `arXiv preprint` [[paper]](https://arxiv.org/abs/2408.00137)

   *Koo, Ryan and Lee, Minhwa and Raheja, Vipul and Park, Jong Inn and Kim, Zae Myung and Kang, Dongyeop*

1. **Capturing failures of large language models via human cognitive biases** `NeurIPS 2022` [[paper]](https://arxiv.org/abs/2202.12299)

   *Jones, Erik and Steinhardt, Jacob*

1. **Do large language models show decision heuristics similar to humans? A case study using GPT-3.5.** `Journal of Experimental Psychology: General 2024` [[paper]](https://arxiv.org/abs/2305.04400)

   *Suri, Gaurav and Slater, Lily R and Ziaee, Ali and Nguyen, Morgan*

1. **Human bias in AI models? Anchoring effects and mitigation strategies in large language models** `Journal of Behavioral and Experimental Finance` [[paper]](https://www.sciencedirect.com/science/article/pii/S2214635024000868)

   *Nguyen, Jeremy K*

1. **An Anchoring Effect in Large Language Models** `IEEE Intelligent Systems 2025` [[paper]](https://ieeexplore.ieee.org/document/10962248)

   *O’Leary, Daniel E*

1. **An Empirical Study of the Anchoring Effect in LLMs: Existence, Mechanism, and Potential Mitigations** `arXiv preprint` [[paper]](https://arxiv.org/abs/2505.15392)

   *Huang, Yiming and Bie, Biquan and Na, Zuqiu and Ruan, Weilin and Lei, Songxin and Yue, Yutao and He, Xinlei*

1. **Assessing Judging Bias in Large Reasoning Models: An Empirical Study** `arXiv preprint` [[paper]](https://arxiv.org/abs/2504.09946)

   *Wang, Qian and Lou, Zhanzhi and Tang, Zhenheng and Chen, Nuo and Zhao, Xuandong and Zhang, Wenxuan and Song, Dawn and He, Bingsheng*

1. **WildFrame: Comparing Framing in Humans and LLMs on Naturally Occurring Texts** `arXiv preprint` [[paper]](https://arxiv.org/abs/2502.17091)

   *Lior, Gili and Nacchace, Liron and Stanovsky, Gabriel*

1. **Framing the Game: How Context Shapes LLM Decision-Making** `arXiv preprint` [[paper]](https://arxiv.org/abs/2503.04840)

   *Robinson, Isaac and Burden, John*

1. **Investigating bias in llm-based bias detection: Disparities between llms and human perception** `COLING 2025` [[paper]](https://arxiv.org/abs/2503.04840)

   *Lin, Luyang and Wang, Lingzhi and Guo, Jinsong and Wong, Kam-Fai*

1. **More or Less Wrong: A Benchmark for Directional Bias in LLM Comparative Reasoning** `arXiv preprint` [[paper]](https://arxiv.org/pdf/2506.03923)

   *Shafiei, Mohammadamin and Saffari, Hamidreza and Moosavi, Nafise Sadat*

1. **Verbosity bias in preference labeling by large language models** `arXiv preprint` [[paper]](https://arxiv.org/abs/2310.10076)

   *Saito, Keita and Wachi, Akifumi and Wataoka, Koki and Akimoto, Youhei*

1. **Talent or Luck? Evaluating Attribution Bias in Large Language Models** `arXiv preprint` [[paper]](https://arxiv.org/abs/2505.22910)

   *Raj, Chahat and Banerjee, Mahika and Caliskan, Aylin and Anastasopoulos, Antonios and Zhu, Ziwei*

1. **Large language models as recommender systems: A study of popularity bias** `arXiv preprint` [[paper]](https://arxiv.org/abs/2406.01285)

   *Lichtenberg, Jan Malte and Buchholz, Alexander and Schw{\"o}bel, Pola*

1. **Beyond Utility: Evaluating LLM as Recommender** `WWW 2025` [[paper]](https://openreview.net/forum?id=YiIdHqqoCd#discussion)

   *Jiang, Chumeng and Wang, Jiayin and Ma, Weizhi and Clarke, Charles LA and Wang, Shuai and Wu, Chuhan and Zhang, Min*

1. **Where to show Demos in Your Prompt: A Positional Bias of In-Context Learning** `arXiv preprint` [[paper]](https://arxiv.org/pdf/2507.22887)

   *Cobbina, Kwesi and Zhou, Tianyi*

1. **Large language models sensitivity to the order of options in multiple-choice questions** `NAACL 2024` [[paper]](https://arxiv.org/abs/2308.11483)

   *Pezeshkpour, Pouya and Hruschka, Estevam*

1. **Mitigating order sensitivity in large language models for multiple-choice question tasks** `IJAIRD 2024` [[paper]](https://iaeme.com/Home/article_id/IJAIRD_02_02_010)

   *Jayaram, Vivekananda and Ramineni, Vishnu and Krishnappa, Manjunatha Sughaturu*

1. **The Order Effect: Investigating Prompt Sensitivity to Input Order in LLMs** `KDD 2025 Workshop on Prompt Optimization` [[paper]](https://arxiv.org/abs/2502.04134)

   *Guan, Bryan and Roosta, Tanya and Passban, Peyman and Rezagholizadeh, Mehdi*

1. **Anchoring Bias in Large Language Models: An Experimental Study** `arXiv preprint` [[paper]](https://arxiv.org/abs/2412.06593)

   *Lou, Jiaxu and Sun, Yifan*

1. **Believing Anthropomorphism: Examining the Role of Anthropomorphic Cues on Trust in Large Language Models** `CHI 2024` [[paper]](https://dl.acm.org/doi/10.1145/3613905.3650818)

   *Cohn, Michelle and Pushkarna, Mahima and Olanubi, Gbolahan O and Moran, Joseph M and Padgett, Daniel and Mengesha, Zion and Heldreth, Courtney*   
   
1. **Benchmarking cognitive biases in large language models as evaluators** `ACL 2024` [[paper]](https://arxiv.org/abs/2309.17012)

   *Koo, Ryan and Lee, Minhwa and Raheja, Vipul and Park, Jong Inn and Kim, Zae Myung and Kang, Dongyeop*

1. **Large Language Models Can Be Easily Distracted by Irrelevant Context** `ICML 2023` [[paper]](https://arxiv.org/abs/2302.00093)

   *Shi, Freda and Chen, Xinyun and Misra, Kanishka and Scales, Nathan and Dohan, David and Chi, Ed and Schärli, Nathanael and Zhou, Denny*

1. **Instructed to bias: instruction-tuned language models exhibit emergent cognitive bias** `TACL 2024` [[paper]](https://arxiv.org/pdf/2308.00225)

   *Itzhak, Itay and Stanovsky, Gabriel and Rosenfeld, Nir and Belinkov, Yonatan*
   
1. **Machine psychology: Investigating emergent capabilities and behavior in large language models using psychological methods** `arXiv preprint` [[paper]](https://arxiv.org/abs/2303.13988)

   *Thilo Hagendorff and Ishita Dasgupta and Marcel Binz and Stephanie C. Y. Chan and Andrew Lampinen and Jane X. Wang and Zeynep Akata and Eric Schulz*

1. **Cognitive LLMs: Toward Human-Like Artificial Intelligence by Integrating Cognitive Architectures and Large Language Models for Manufacturing Decision-making** `Neurosymbolic Artificial Intelligence 2024` [[paper]](https://neurosymbolic-ai-journal.com/system/files/nai-paper-819.pdf)

   *Wu, Siyu and Oltramari, Alessandro and Francis, Jonathan and Giles, C Lee and Ritter, Frank E*

1. **Argumentative Experience: Reducing Confirmation Bias on Controversial Issues through LLM-Generated Multi-Persona Debates** `arXiv preprint` [[paper]](https://arxiv.org/abs/2412.04629)

   *Shi, Li and Liu, Houjiang and Wong, Yian and Mujumdar, Utkarsh and Zhang, Dan and Gwizdka, Jacek and Lease, Matthew*

### Implicit Social Reasoning

1. **Theory of mind in large language models: Examining performance of 11 state-of-the-art models vs. children aged 7-10 on advanced tests** `CoNLL 2023` [[paper]](https://aclanthology.org/2023.conll-1.25/)

   *van Duijn, Max J and van Dijk, Bram and Kouwenhoven, Tom and de Valk, Werner and Spruit, Marco R and van der Putten, Peter*

1. **FANToM: A benchmark for stress-testing machine theory of mind in interactions** `EMNLP 2023` [[paper]](https://aclanthology.org/2023.emnlp-main.890.pdf)

   *Kim, Hyunwoo and Sclar, Melanie and Zhou, Xuhui and Bras, Ronan Le and Kim, Gunhee and Choi, Yejin and Sap, Maarten*

1. **Neural theory-of-mind? on the limits of social intelligence in large lms** `EMNLP 2022` [[paper]](https://aclanthology.org/2022.emnlp-main.248/)

   *Sap, Maarten and LeBras, Ronan and Fried, Daniel and Choi, Yejin*
 
1. **Dissecting the Ullman Variations with a SCALPEL: Why do LLMs fail at Trivial Alterations to the False Belief Task?** `arXiv preprint` [[paper]](https://arxiv.org/abs/2406.14737)

   *Pi, Zhiqiang and Vadaparty, Annapurna and Bergen, Benjamin K and Jones, Cameron R*

1. **Large language models fail on trivial alterations to theory-of-mind tasks** `arXiv preprint` [[paper]](https://arxiv.org/abs/2302.08399)

   *Ullman, Tomer*

1. **Evaluating large language models in theory of mind tasks** `PNAS 2024` [[paper]](https://www.pnas.org/doi/10.1073/pnas.2405460121)

   *Kosinski, Michal*

1. **Clever hans or neural theory of mind? stress testing social reasoning in large language models** `EACL 2024` [[paper]](https://aclanthology.org/2024.eacl-long.138/)

   *Shapira, Natalie and Levy, Mosh and Alavi, Seyed Hossein and Zhou, Xuhui and Choi, Yejin and Goldberg, Yoav and Sap, Maarten and Shwartz, Vered*

1. **SimpleToM: Exposing the Gap between Explicit ToM Inference and Implicit ToM Application in LLMs** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.13648)

   *Gu, Yuling and Tafjord, Oyvind and Kim, Hyunwoo and Moore, Jared and Bras, Ronan Le and Clark, Peter and Choi, Yejin*

1. **Hi-tom: A benchmark for evaluating higher-order theory of mind reasoning in large language models** `EMNLP 2023` [[paper]](https://aclanthology.org/2023.findings-emnlp.717/)

   *He, Yinghui and Wu, Yufan and Jia, Yilin and Mihalcea, Rada and Chen, Yulong and Deng, Naihao*

1. **How FaR Are Large Language Models From Agents with Theory-of-Mind?** `arXiv preprint` [[paper]](https://arxiv.org/abs/2310.03051)

   *Zhou, Pei and Madaan, Aman and Potharaju, Srividya Pranavi and Gupta, Aditya and McKee, Kevin R and Holtzman, Ari and Pujara, Jay and Ren, Xiang and Mishra, Swaroop and Nematzadeh, Aida and others*  

1. **Testing theory of mind in large language models and humans** `Nature Human Behaviour 2024` [[paper]](https://www.nature.com/articles/s41562-024-01882-z)

   *Strachan, James WA and Albergo, Dalila and Borghini, Giulia and Pansardi, Oriana and Scaliti, Eugenio and Gupta, Saurabh and Saxena, Krati and Rufo, Alessandro and Panzeri, Stefano and Manzi, Guido and others*

1. **Minding Language Models’ (Lack of) Theory of Mind: A Plug-and-Play Multi-Character Belief Tracker** `ACL 2023` [[paper]](https://aclanthology.org/2023.acl-long.780.pdf)

   *Sclar, Melanie and Kumar, Sachin and West, Peter and Suhr, Alane and Choi, Yejin and Tsvetkov, Yulia*

1. **Artificial Intelligence and the Illusion of Understanding: A Systematic Review of Theory of Mind and Large Language Models** `Cyberpsychology, Behavior, and Social Networking 2025` [[paper]](https://pubmed.ncbi.nlm.nih.gov/40333375/)

   *Marchetti, Antonella and Manzi, Federico and Riva, Giuseppe and Gaggioli, Andrea and Massaro, Davide*

1. **Towards Dynamic Theory of Mind: Evaluating LLM Adaptation to Temporal Evolution of Human States** `ACL 2025` [[paper]](https://aclanthology.org/2025.acl-long.1171/)

   *Xiao, Yang and Wang, Jiashuo and Xu, Qiancheng and Song, Changhe and Xu, Chunpu and Cheng, Yi and Li, Wenjie and Liu, Pengfei*

1. **EmoBench: Evaluating the Emotional Intelligence of Large Language Models** `ACL 2024` [[paper]](https://aclanthology.org/2024.acl-long.326/)

   *Sabour, Sahand and Liu, Siyang and Zhang, Zheyuan and Liu, June M and Zhou, Jinfeng and Sunaryo, Alvionna S and Li, Juanzi and Lee, Tatia and Mihalcea, Rada and Huang, Minlie*

1. **EmoBench-M: Benchmarking Emotional Intelligence for Multimodal Large Language Models** `arXiv preprint` [[paper]](https://arxiv.org/abs/2502.04424)

   *Hu, He and Zhou, Yucheng and You, Lianzhong and Xu, Hongbo and Wang, Qianning and Lian, Zheng and Yu, Fei Richard and Ma, Fei and Cui, Laizhong*

1. **Can LLMs Reason Like Humans? Assessing Theory of Mind Reasoning in LLMs for Open-Ended Questions** `CIKM 2024` [[paper]](https://dl.acm.org/doi/10.1145/3627673.3679832)

   *Amirizaniani, Maryam and Martin, Elias and Sivachenko, Maryna and Mashhadi, Afra and Shah, Chirag*

1. **The Emotional Intelligence of the GPT-4 Large Language Model** `Psychol Russ 2024` [[paper]](https://pubmed.ncbi.nlm.nih.gov/39552777/)

   *Vzorinab, Gleb D and Bukinichac, Alexey M and Sedykha, Anna V and Vetrovab, Irina I and Sergienkob, Elena A*

1. **Multilingual Language Models are not Multicultural: A Case Study in Emotion** `ACL 2023` [[paper]](https://aclanthology.org/2023.wassa-1.19/)

   *Havaldar, Shreya and Rai, Sunny and Singhal, Bhumika and Liu, Langchen and Guntuku, Sharath Chandra and Ungar, Lyle*

1. **MoralBench: Moral Evaluation of LLMs** `arXiv preprint` [[paper]](https://arxiv.org/abs/2406.04428)

   *Ji, Jianchao and Chen, Yutong and Jin, Mingyu and Xu, Wujiang and Hua, Wenyue and Zhang, Yongfeng*

1. **As an AI Language Model," Yes I Would Recommend Calling the Police": Norm Inconsistency in LLM Decision-Making** `AIES 2024` [[paper]](https://dl.acm.org/doi/10.5555/3716662.3716716)

   *Jain, Shomik and Calacci, D and Wilson, Ashia*

1. **Measuring Moral Inconsistencies in Large Language Models** `arXiv preprint` [[paper]](https://arxiv.org/abs/2402.01719)

   *Bonagiri, Vamshi Krishna and Vennam, Sreeram and Gaur, Manas and Kumaraguru, Ponnurangam*

1. **Probing the moral development of large language models through defining issues test** `arXiv preprint` [[paper]](https://arxiv.org/abs/2309.13356)

   *Tanmay, Kumar and Khandelwal, Aditi and Agarwal, Utkarsh and Choudhury, Monojit*

1. **Correcting negative bias in large language models through negative attention score alignment** `arXiv preprint` [[paper]](https://arxiv.org/abs/2408.00137)

   *Yu, Sangwon and Song, Jongyoon and Hwang, Bongkyu and Kang, Hoyoung and Cho, Sooah and Choi, Junhwa and Joe, Seongho and Lee, Taehee and Gwon, Youngjune L and Yoon, Sungroh*

1. **Ethical reasoning and moral value alignment of LLMs depend on the language we prompt them in** `ACL 2024` [[paper]](https://aclanthology.org/2024.lrec-main.560/)

   *Agarwal, Utkarsh and Tanmay, Kumar and Khandelwal, Aditi and Choudhury, Monojit*

1. **GreedLlama: Performance of financial value-aligned large language models in moral reasoning** `arXiv preprint` [[paper]](https://arxiv.org/abs/2404.02934)

   *Yu, Jeffy and Huber, Maximilian and Tang, Kevin*
   
1. **EgoNormia: Benchmarking Physical Social Norm Understanding** `arXiv preprint` [[paper]](https://arxiv.org/abs/2502.20490)

   *Rezaei, MohammadHossein and Fu, Yicheng and Cuvin, Phil and Ziems, Caleb and Zhang, Yanzhe and Zhu, Hao and Yang, Diyi*

1. **The Moral Turing Test: Evaluating Human-LLM Alignment in Moral Decision-Making** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.07304)

   *Garcia, Basile and Qian, Crystal and Palminteri, Stefano*

1. **The moral machine experiment on large language models** `Royal Society` [[paper]](https://royalsocietypublishing.org/doi/10.1098/rsos.231393)

   *Takemoto, Kazuhiro*

1. **Investigating machine moral judgement through the Delphi experiment** `Nature Machine Intelligence 2025` [[paper]](https://www.nature.com/articles/s42256-024-00969-6)

   *Jiang, Liwei and Hwang, Jena D and Bhagavatula, Chandra and Bras, Ronan Le and Liang, Jenny T and Levine, Sydney and Dodge, Jesse and Sakaguchi, Keisuke and Forbes, Maxwell and Hessel, Jack and others*
   

### Explicit Social Reasoning

1. **Theory of mind for multi-agent collaboration via large language models** `EMNLP 2023` [[paper]](https://aclanthology.org/2023.emnlp-main.13/)

   *Li, Huao and Chong, Yu Quan and Stepputtis, Simon and Campbell, Joseph and Hughes, Dana and Lewis, Michael and Sycara, Katia*

1. **Socialeval: Evaluating social intelligence of large language models** `ACL 2025` [[paper]](https://aclanthology.org/2025.acl-long.1496.pdf)

   *Zhou, Jinfeng and Chen, Yuxuan and Shi, Yihan and Zhang, Xuanming and Lei, Leqi and Feng, Yi and Xiong, Zexuan and Yan, Miao and Wang, Xunzhi and Cao, Yaru and others*

1. **Hypothetical minds: Scaffolding theory of mind for multi-agent tasks with large language models** `ICLR 2025` [[paper]](https://openreview.net/forum?id=otW0TJOUYF)

   *Cross, Logan and Xiang, Violet and Bhatia, Agam and Yamins, Daniel LK and Haber, Nick*

1. **Large language model based multi-agents: A survey of progress and challenges** `IJCAI 2024` [[paper]](https://www.ijcai.org/proceedings/2024/890)

   *Guo, Taicheng and Chen, Xiuying and Wang, Yaqi and Chang, Ruidi and Pei, Shichao and Chawla, Nitesh V and Wiest, Olaf and Zhang, Xiangliang*

1. **LLM multi-agent systems: Challenges and open problems** `arXiv preprint` [[paper]](https://arxiv.org/abs/2402.03578)

   *Han, Shanshan and Zhang, Qifan and Yao, Yuhang and Jin, Weizhao and Xu, Zhaozhuo and He, Chaoyang*

1. **Cooperate or collapse: Emergence of sustainable cooperation in a society of llm agents** `NeurIPS 2024` [[paper]](https://arxiv.org/abs/2404.16698)

   *Piatti, Giorgio and Jin, Zhijing and Kleiman-Weiner, Max and Sch{\"o}lkopf, Bernhard and Sachan, Mrinmaya and Mihalcea, Rada*

1. **Building cooperative embodied agents modularly with large language models** `ICLR 2024` [[paper]](https://openreview.net/forum?id=EnXJfQqy0K)

   *Zhang, Hongxin and Du, Weihua and Shan, Jiaming and Zhou, Qinhong and Du, Yilun and Tenenbaum, Joshua B and Shu, Tianmin and Gan, Chuang*

1. **LLM-Coordination: Evaluating and Analyzing Multi-agent Coordination Abilities in Large Language Models** `arXiv preprint` [[paper]](https://arxiv.org/abs/2310.03903)

   *Saaket Agashe and Yue Fan and Anthony Reyna and Xin Eric Wang*

1. **Why Do Multiagent Systems Fail?** `ICLR 2025 Workshop` [[paper]](https://openreview.net/forum?id=wM521FqPvI&referrer=%5Bthe%20profile%20of%20Ion%20Stoica%5D(%2Fprofile%3Fid%3D~Ion_Stoica1))

   *Pan, Melissa Z and Cemri, Mert and Agrawal, Lakshya A and Yang, Shuyi and Chopra, Bhavya and Tiwari, Rishabh and Keutzer, Kurt and Parameswaran, Aditya and Ramchandran, Kannan and Klein, Dan and others*

1. **On the resilience of multi-agent systems with malicious agents** `CoRR 2024` [[paper]](https://openreview.net/forum?id=vgDdq5Tej8)

   *Huang, Jen-tse and Zhou, Jiaxu and Jin, Tailin and Zhou, Xuhui and Chen, Zixi and Wang, Wenxuan and Yuan, Youliang and Sap, Maarten and Lyu, Michael R*

1. **Monitoring Reasoning Models for Misbehavior and the Risks of Promoting Obfuscation** `arXiv preprint` [[paper]](https://arxiv.org/abs/2503.11926)

   *Baker, Bowen and Huizinga, Joost and Gao, Leo and Dou, Zehao and Guan, Melody Y and Madry, Aleksander and Zaremba, Wojciech and Pachocki, Jakub and Farhi, David*

1. **Magic: Investigation of large language model powered multi-agent in cognition, adaptability, rationality and collaboration** `EMNLP 2024` [[paper]](https://arxiv.org/abs/2311.08562)

   *Xu, Lin and Hu, Zhiyuan and Zhou, Daquan and Ren, Hongyu and Dong, Zhen and Keutzer, Kurt and Ng, See Kiong and Feng, Jiashi*

## Formal Reasoning -- Logic and Arithmetic

### Logic in Natural Languages

1. **The Reversal Curse: LLMs trained on "A is B" fail to learn "B is A"** `ICLR 2024` [[paper]](https://arxiv.org/abs/2309.12288)

   *Berglund, Lukas and Tong, Meg and Kaufmann, Max and Balesni, Mikita and Stickland, Asa Cooper and Korbak, Tomasz and Evans, Owain*

1. **Exploring the Reversal Curse and Other Deductive Logical Reasoning in BERT and GPT-Based Large Language Models** `Patterns 2024` [[paper]](https://arxiv.org/abs/2312.03633)

   *Wu, Da and Yang, Jingye and Wang, Kai*

1. **Reverse Training to Nurse the Reversal Curse** `COLM 2024` [[paper]](https://arxiv.org/abs/2403.13799)

   *Golovneva, Olga and Allen-Zhu, Zeyuan and Weston, Jason and Sukhbaatar, Sainbayar*

1. **The Queen of England is not England's Queen: On the Lack of Factual Coherency in PLMs** `EACL 2024` [[paper]](https://arxiv.org/abs/2402.01453)

   *Youssef, Paul and Schlötterer, Jörg and Seifert, Christin*

1. **Exploring Reversal Mathematical Reasoning Ability for Large Language Models** `ACL 2024` [[paper]](https://aclanthology.org/2024.findings-acl.811/)

   *Guo, Pei and You, WangJie and Li, Juntao and Bowen, Yan and Zhang, Min*

1. **Mitigating Reversal Curse in Large Language Models via Semantic-aware Permutation Training** `ACL 2024` [[paper]](https://arxiv.org/abs/2403.00758)

   *Guo, Qingyan and Wang, Rui and Guo, Junliang and Tan, Xu and Bian, Jiang and Yang, Yujiu*

1. **An Analysis and Mitigation of the Reversal Curse** `EMNLP 2024` [[paper]](https://arxiv.org/abs/2311.07468)

   *Lv, Ang and Zhang, Kaiyi and Xie, Shufang and Tu, Quan and Chen, Yuhan and Wen, Ji-Rong and Yan, Rui*

1. **Untying the Reversal Curse via Bidirectional Language Model Editing** `arXiv preprint` [[paper]](https://arxiv.org/abs/2310.10322)

   *Ma, Jun-Yu and Gu, Jia-Chen and Ling, Zhen-Hua and Liu, Quan and Liu, Cong*

1. **Rethinking the Reversal Curse of LLMs: a Prescription from Human Knowledge Reversal** `EMNLP 2024` [[paper]](https://aclanthology.org/2024.emnlp-main.428/)

   *Lu, Zhicong and Jin, Li and Li, Peiguang and Tian, Yu and Zhang, Linhao and Wang, Sirui and Xu, Guangluan and Tian, Changyuan and Cai, Xunliang*

1. **Delving into the Reversal Curse: How Far Can Large Language Models Generalize?** `NeurIPS 2024` [[paper]](https://arxiv.org/abs/2410.18808)

   *Lin, Zhengkai and Fu, Zhihang and Liu, Kai and Xie, Liang and Lin, Binbin and Wang, Wenxiao and Cai, Deng and Wu, Yue and Ye, Jieping*

1. **Towards a Theoretical Understanding of the 'Reversal Curse' via Training Dynamics** `NeurIPS 2024` [[paper]](https://arxiv.org/abs/2405.04669)

   *Zhu, Hanlin and Huang, Baihe and Zhang, Shaolun and Jordan, Michael and Jiao, Jiantao and Tian, Yuandong and Russell, Stuart* 

1. **The Two-Hop Curse: LLMs trained on A->B, B->C fail to learn A-->C** `arXiv preprint` [[paper]](https://arxiv.org/abs/2411.16353)

   *Balesni, Mikita and Korbak, Tomek and Evans, Owain*

1. **How Do LLMs Perform Two-Hop Reasoning in Context?** `arXiv preprint` [[paper]](https://arxiv.org/abs/2502.13913)

   *Guo, Tianyu and Zhu, Hanlin and Zhang, Ruiqi and Jiao, Jiantao and Mei, Song and Jordan, Michael I. and Russell, Stuart*

1. **Exploring the Limitations of Large Language Models in Compositional Relation Reasoning** `COLM 2024` [[paper]](https://arxiv.org/abs/2403.02615)

   *Zhao, Jinman and Zhang, Xueyan*

1. **Faith and Fate: Limits of Transformers on Compositionality** `NeurIPS 2023` [[paper]](https://arxiv.org/abs/2305.18654)

   *Dziri, Nouha and Lu, Ximing and Sclar, Melanie and Li, Xiang Lorraine and Jiang, Liwei and Lin, Bill Yuchen and West, Peter and Bhagavatula, Chandra and Bras, Ronan Le and Hwang, Jena D. and Sanyal, Soumya and Welleck, Sean and Ren, Xiang and Ettinger, Allyson and Harchaoui, Zaid and Choi, Yejin*

1. **Exploring the Compositional Deficiency of Large Language Models in Mathematical Reasoning** `EMNLP 2024` [[paper]](https://arxiv.org/abs/2405.06680)

   *Zhao, Jun and Tong, Jingqi and Mou, Yurong and Zhang, Ming and Zhang, Qi and Huang, Xuanjing*

1. **BoolQ: Exploring the Surprising Difficulty of Natural Yes/No Questions** `NAACL 2019` [[paper]](https://arxiv.org/abs/1905.10044)

   *Clark, Christopher and Lee, Kenton and Chang, Ming-Wei and Kwiatkowski, Tom and Collins, Michael and Toutanova, Kristina*

1. **LogicAsker: Evaluating and Improving the Logical Reasoning Ability of Large Language Models** `EMNLP 2024` [[paper]](https://arxiv.org/abs/2401.00757)

   *Wan, Yuxuan and Wang, Wenxuan and Yang, Yiliu and Yuan, Youliang and Huang, Jen-tse and He, Pinjia and Jiao, Wenxiang and Lyu, Michael R.*

1. **Evaluating Large Language Models with NeuBAROCO: Syllogistic Reasoning Ability and Human-like Biases** `NALOMA IV` [[paper]](https://arxiv.org/abs/2306.12567)

   *Ando, Risako and Morishita, Takanobu and Abe, Hirohiko and Mineshima, Koji and Okada, Mitsuhiro*
   
1. **An Investigation of LLMs' Inefficacy in Understanding Converse Relations** `EMNLP 2023` [[paper]](https://arxiv.org/abs/2310.05163)

   *Qi, Chengwen and Li, Bowen and Hui, Binyuan and Wang, Bailin and Li, Jinyang and Wu, Jinwang and Laili, Yuanjun*

1. **Assessing the Reasoning Abilities of ChatGPT in the Context of Claim Verification** `arXiv preprint` [[paper]](https://arxiv.org/abs/2402.10735)

   *Dougrez-Lewis, John and Akhter, Mahmud Elahi and He, Yulan and Liakata, Maria*

1. **LLMs Are Prone to Fallacies in Causal Inference** `EMNLP 2024` [[paper]](https://arxiv.org/abs/2406.12158)

   *Joshi, Nitish and Saparov, Abulhair and Wang, Yixin and He, He*

1. **Rulebreakers Challenge: Revealing a Blind Spot in Large Language Models' Reasoning with Formal Logic** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.16502)

   *Chan, Jason and Gaizauskas, Robert and Zhao, Zhixue*

1. **Large Language Models Fall Short: Understanding Complex Relationships in Detective Narratives** `ACL 2024` [[paper]](https://www.arxiv.org/abs/2402.11051)

   *Zhao, Runcong and Zhu, Qinglin and Xu, Hainiu and Li, Jiazheng and Zhou, Yuxiang and He, Yulan and Gui, Lin*

1. **Not All LLM Reasoners Are Created Equal** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.01748)

   *Hosseini, Arian and Sordoni, Alessandro and Toyama, Daniel and Courville, Aaron and Agarwal, Rishabh*

1. **Do Large Language Models Have Compositional Ability? An Investigation into Limitations and Scalability** `COLM 2024` [[paper]](https://arxiv.org/abs/2407.15720)

   *Xu, Zhuoyan and Shi, Zhenmei and Liang, Yingyu*

1. **Understanding and Patching Compositional Reasoning in LLMs** `ACL 2024` [[paper]](https://arxiv.org/abs/2402.14328)

   *Li, Zhaoyi and Jiang, Gangwei and Xie, Hong and Song, Linqi and Lian, Defu and Wei, Ying*

1. **Do Large Language Models Perform Latent Multi-Hop Reasoning without Exploiting Shortcuts?** `ACL 2024` [[paper]](https://arxiv.org/abs/2411.16679)

   *Yang, Sohee and Kassner, Nora and Gribovskaya, Elena and Riedel, Sebastian and Geva, Mor*

1. **Enhancing Logical Reasoning in Large Language Models through Graph-based Synthetic Data** `arXiv preprint` [[paper]](https://arxiv.org/abs/2402.01805v1)

   *Zhou, Jiaming and Ghaddar, Abbas and Zhang, Ge and Ma, Liheng and Hu, Yaochen and Pal, Soumyasundar and Coates, Mark and Wang, Bin and Zhang, Yingxue and Hao, Jianye*

1. **LogicGame: Benchmarking Rule-Based Reasoning Abilities of Large Language Models** `ACL 2024` [[paper]](https://arxiv.org/abs/2408.15778)

   *Gui, Jiayi and Liu, Yiming and Cheng, Jiale and Gu, Xiaotao and Liu, Xiao and Wang, Hongning and Dong, Yuxiao and Tang, Jie and Huang, Minlie*

1. **Can LLMs Reason with Rules? Logic Scaffolding for Stress-Testing and Improving LLMs** `ACL 2024` [[paper]](https://arxiv.org/abs/2402.11442)

   *Wang, Siyuan and Wei, Zhongyu and Choi, Yejin and Ren, Xiang*

1. **See What LLMs Cannot Answer: A Self-Challenge Framework for Uncovering LLM Weaknesses** `COLM 2024` [[paper]](https://arxiv.org/abs/2408.08978)

   *Chen, Yulong and Liu, Yang and Yan, Jianhao and Bai, Xuefeng and Zhong, Ming and Yang, Yinghao and Yang, Ziyi and Zhu, Chenguang and Zhang, Yue*

### Logic in Benchmarks

1. **Large Language Models Are Not Robust Multiple Choice Selectors** `ICLR 2024` [[paper]](https://arxiv.org/abs/2309.03882)

   *Zheng, Chujie and Zhou, Hao and Meng, Fandong and Zhou, Jie and Huang, Minlie*

1. **Large language models sensitivity to the order of options in multiple-choice questions** `NAACL 2024` [[paper]](https://arxiv.org/abs/2308.11483)

   *Pezeshkpour, Pouya and Hruschka, Estevam*

1. **When benchmarks are targets: Revealing the sensitivity of large language model leaderboards** `ACL 2024` [[paper]](https://arxiv.org/abs/2402.01781)

   *Alzahrani, Norah and Alyahya, Hisham Abdullah and Alnumay, Yazeed and Alrashed, Sultan and Alsubaie, Shaykhah and Almushaykeh, Yusef and Mirza, Faisal and Alotaibi, Nouf and Altwairesh, Nora and Alowisheq, Areeb and Bari, M Saiful and Khan, Haidar*

1. **In-Context Learning May Not Elicit Trustworthy Reasoning: A-Not-B Errors in Pretrained Language Models"** `EMNLP 2024` [[paper]](https://arxiv.org/abs/2409.15454)

   *Han, Pengrui and Song, Peiyang and Yu, Haofei and You, Jiaxuan*

1. **Changing Answer Order Can Decrease MMLU Accuracy** `arXiv preprint` [[paper]](https://arxiv.org/abs/2406.19470)

   *Gupta, Vipul and Pantoja, David and Ross, Candace and Williams, Adina and Ung, Megan*

1. **Premise Order Matters in Reasoning with Large Language Models** `ICML 2024` [[paper]](https://arxiv.org/abs/2402.08939)

   *Chen, Xinyun and Chi, Ryan A. and Wang, Xuezhi and Zhou, Denny*

1. **Failure Modes of LLMs for Causal Reasoning on Narratives** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.23884v1)

   *Yamin, Khurram and Gupta, Shantanu and Gaurav R. Ghosal, Gaurav R. and Lipton, Zachary C. and Wilder, Bryan*

1. **A Peek into Token Bias: Large Language Models Are Not Yet Genuine Reasoners** `EMNLP 2024` [[paper]](https://arxiv.org/abs/2406.11050)

   *Jiang, Bowen and Xie, Yangxinyu and Hao, Zhuoqun and Wang, Xiaomeng and Mallick, Tanwi and Su, Weijie J. and Taylor, Camillo J. and Roth, Dan*

1. **GSM-Symbolic: Understanding the Limitations of Mathematical Reasoning in Large Language Models** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.05229)

   *Mirzadeh, Iman and Alizadeh, Keivan and Shahrokhim, Hooman and Tuzel, Oncel and Bengio, Samy and Farajtabar, Mehrdad*

1. **Reasoning or Reciting? Exploring the Capabilities and Limitations of Language Models Through Counterfactual Tasks** `NAACL 2024` [[paper]](https://arxiv.org/abs/2307.02477)

    *Wu, Zhaofeng and Qiu, Linlu and Ross, Alexis and Akyürek, Ekin and Chen, Boyuan and Wang, Bailin and Kim, Najoung and Andreas, Jacob and Kim, Yoon*

1. **GSM-Plus: A Comprehensive Benchmark for Evaluating the Robustness of LLMs as Mathematical Problem Solvers** `ACL 2024` [[paper]](https://arxiv.org/abs/2402.19255)

   *Li, Qintong and Cui, Leyang and Zhao, Xueliang and Kong, Lingpeng and Bi, Wei*

1. **Are NLP Models really able to Solve Simple Math Word Problems?** `NAACL 2021` [[paper]](https://arxiv.org/abs/2103.07191)

   *Patel, Arkil and Bhattamishra, Satwik and Goyal, Navin*

1. **Large Language Models Can Be Easily Distracted by Irrelevant Context** `ICML 2023` [[paper]](https://arxiv.org/abs/2302.00093)

   *Shi, Freda and Chen, Xinyun and Misra, Kanishka and Scales, Nathan and Dohan, David and Chi, Ed and Schärli, Nathanael and Zhou, Denny*

1. **ReCode: Robustness Evaluation of Code Generation Models** `ACL 2023` [[[paper]](https://arxiv.org/abs/2212.10264)

   *Wang, Shiqi and Li, Zheng and Qian, Haifeng and Yang, Chenghao and Wang, Zijian and Shang, Mingyue and Kumar, Varun and Tan, Samson and Ray, Baishakhi and Bhatia, Parminder and Nallapati, Ramesh and Ramanathan, Murali Krishna and Roth, Dan and Xiang, Bing*

1. **Do Large Code Models Understand Programming Concepts? A Black-box Approach** `ICML 2024` [[paper]](https://arxiv.org/abs/2402.05980)

   *Hooda, Ashish and Christodorescu, Mihai and Allamanis, Miltiadis and Wilson, Aaron and Fawaz, Kassem and Jha, Somesh*

1. **Top Leaderboard Ranking = Top Coding Proficiency, Always? EvoEval: Evolving Coding Benchmarks via LLM** `COLM 2024` [[paper]](https://arxiv.org/abs/2403.19114)

   *Xia, Chunqiu Steven and Deng, Yinlin and Zhang, Lingming*

1. **Large Language Models of Code Fail at Completing Code with Potential Bugs** `NeurIPS 2023` [[paper]](https://arxiv.org/abs/2306.03438)

   *Dinh, Tuan and Zhao, Jinman and Tan, Samson and Negrinho, Renato and Lausen, Leonard and Zha, Sheng and Karypis, George*

1. **The Larger They Are, the Harder They Fail: Language Models do not Recognize Identifier Swaps in Python** `ACL 2023` [[paper]](https://arxiv.org/abs/2305.15507)

   *Miceli-Barone, Antonio Valerio and Barez, Fazl and Konstas, Ioannis and Cohen, Shay B.*

1. **Syntactic Robustness for LLM-based Code Generation** `arXiv preprint` [[paper]](https://arxiv.org/abs/2404.01535)

   *Sarker, Laboni and Downing, Mara and Desai, Achintya and Bultan, Tevfik*

1. **RUPBench: Benchmarking Reasoning Under Perturbations for Robustness Evaluation in Large Language Models** `arXiv preprint` [[paper]](https://arxiv.org/abs/2406.11020)

   *Wang, Yuqing and Zhao, Yun*

1. **Evaluating LLMs' Mathematical and Coding Competency through Ontology-guided Interventions** `arXiv preprint` [[paper]](https://arxiv.org/abs/2401.09395)

   *Hong, Pengfei and Majumder, Navonil and Ghosal, Deepanway and Aditya, Somak and Mihalcea, Rada and Poria, Soujanya*

1. **Fill in the Blank: Exploring and Enhancing LLM Capabilities for Backward Reasoning in Math Word Problems** `arXiv preprint` [[paper]](https://arxiv.org/abs/2310.01991)

   *Deb, Aniruddha and Oza, Neeva and Singla, Sarthak and Khandelwal, Dinesh and Garg, Dinesh and Singla, Parag*

1. **MATH-Perturb: Benchmarking LLMs' Math Reasoning Abilities against Hard Perturbations** `arXiv preprint` [[paper]](https://arxiv.org/abs/2502.06453)

   *Huang, Kaixuan and Guo, Jiacheng and Li, Zihao and Ji, Xiang and Ge, Jiawei and Li, Wenzhe and Guo, Yingqing and Cai, Tianle and Yuan, Hui and Wang, Runzhe and Wu, Yue and Yin, Ming and Tang, Shange and Huang, Yangsibo and Jin, Chi and Chen, Xinyun and Zhang, Chiyuan and Wang, Mengdi*

1. **The Illusion of Thinking: Understanding the Strengths and Limitations of Reasoning Models via the Lens of Problem Complexity** `arXiv preprint` [[paper]](https://arxiv.org/abs/2506.06941)

   *Shojaee, Parshin and Mirzadeh, Iman and Alizadeh, Keivan and Horton, Maxwell and Bengio, Samy and Farajtabar, Mehrdad*

1. **Comment on The Illusion of Thinking: Understanding the Strengths and Limitations of Reasoning Models via the Lens of Problem Complexity** `arXiv preprint` [[paper]](https://arxiv.org/abs/2506.09250)

   *Lawsen, Alex*

1. **OMEGA: Can LLMs Reason Outside the Box in Math? Evaluating Exploratory, Compositional, and Transformative Generalization** `arXiv preprint` [[paper]](https://arxiv.org/abs/2506.18880)

   *Sun, Yiyou and Hu, Shawn and Zhou, Georgia and Zheng, Ken and Hajishirzi, Hannaneh and Dziri, Nouha and Song, Dawn*

1. **FormulaOne: Measuring the Depth of Algorithmic Reasoning Beyond Competitive Programming** `arXiv preprint` [[paper]](https://arxiv.org/abs/2507.13337)

   *Beniamini, Gal and Dor, Yuval and Vinnikov, Alon and Peled, Shir Granot and Weinstein, Or and Sharir, Or and Wies, Noam and Nussbaum, Tomer and Shaul, Ido Ben and Zekharya, Tomer and Levine, Yoav and Shalev-Shwartz, Shai and Shashua, Amnon*
   
### Arithmetic and Mathematics

1. **Why Do Large Language Models (LLMs) Struggle to Count Letters?** `arXiv preprint` [[paper]](https://arxiv.org/abs/2412.18626)

   *Fu, Tairan and Ferrando, Raquel and Conde, Javier and Arriaga, Carlos and Reviriego, Pedro*

1. **Frontier LLMs Still Struggle with Simple Reasoning Tasks** `arXiv preprint` [[paper]](https://arxiv.org/abs/2507.07313)

   *Malek, Alan and Ge, Jiawei and Lazic, Nevena and Jin, Chi and György, András and Szepesvári, Csaba*

1. **Counting Ability of Large Language Models and Impact of Tokenization** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.19730)

   *Zhang, Xiang and Cao, Juntai and You, Chenyu*

1. **Language Models Need Inductive Biases to Count Inductively** `ICLR 2025` [[paper]](https://arxiv.org/abs/2405.20131)

   *Chang, Yingshan and Bisk, Yonatan*

1. **LLM The Genius Paradox: A Linguistic and Math Expert's Struggle with Simple Word-based Counting Problems** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.14166)

   *Xu, Nan and Ma, Xuezhe*

1. **When Can Transformers Count to n?** `arXiv preprint` [[paper]](https://arxiv.org/abs/2407.15160)

   *Yehudai, Gilad and Kaplan, Haim and Ghandeharioun, Asma and Geva, Mor and Globerson, Amir*

1. **Large Language Models Lack Understanding of Character Composition of Words** `arXiv preprint` [[paper]](https://arxiv.org/abs/2405.11357)

   *Shin, Andrew and Kaneko, Kunitake*

1. **Large Language Models Can Not Perform Well in Understanding and Manipulating Natural Language at Both Character and Word Levels?** `EMNLP 2024` [[paper]](https://aclanthology.org/2024.findings-emnlp.691/)

   *Zhang, Yidan and He, Zhenan*

1. **Can Neural Networks Do Arithmetic? A Survey on the Elementary Numerical Skills of State-of-the-Art Deep Learning Models** `Applied Sciences Vol. 14` [[paper]](https://www.mdpi.com/2076-3417/14/2/744)

   *Testolin, Alberto*

1. **Large Language Models Are Unconscious of Unreasonability in Math Problems** `arXiv preprint` [[paper]](https://arxiv.org/abs/2403.19346v1)

   *Ma, Jingyuan and Dai, Damai and Sha, Lei and Sui, Zhifang*

1. **Putnam-AXIOM: A Functional and Static Benchmark for Measuring Higher Level Mathematical Reasoning** `arXiv preprint` [[paper]](https://openreview.net/forum?id=WrBqgoseGL)

   *Gulati, Aryan and Miranda, Brando and Chen, Eric and Xia, Emily and Fronsdal, Kai and Dumont, Bruno de Moraes and Koyejo, Sanmi*

1. **GSM-Symbolic: Understanding the Limitations of Mathematical Reasoning in Large Language Models** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.05229)

   *Mirzadeh, Iman and Alizadeh, Keivan and Shahrokhim, Hooman and Tuzel, Oncel and Bengio, Samy and Farajtabar, Mehrdad*

1. **GSM-Plus: A Comprehensive Benchmark for Evaluating the Robustness of LLMs as Mathematical Problem Solvers** `ACL 2024` [[paper]](https://arxiv.org/abs/2402.19255)

   *Li, Qintong and Cui, Leyang and Zhao, Xueliang and Kong, Lingpeng and Bi, Wei*

1. **Large Language Models Can Be Easily Distracted by Irrelevant Context** `ICML 2023` [[paper]](https://arxiv.org/abs/2302.00093)

   *Shi, Freda and Chen, Xinyun and Misra, Kanishka and Scales, Nathan and Dohan, David and Chi, Ed and Schärli, Nathanael and Zhou, Denny*

1. **VarBench: Robust Language Model Benchmarking Through Dynamic Variable Perturbation** `EMNLP 2024` [[paper]](https://arxiv.org/abs/2406.17681)

   *Qian, Kun and Wan, Shunji and Tang, Claudia and Wang, Youzhi and Zhang, Xuanming and Chen, Maximillian and Yu, Zhou*

1. **Alice in Wonderland: Simple Tasks Showing Complete Reasoning Breakdown in State-Of-the-Art Large Language Models** `arXiv preprint` [[paper]](https://arxiv.org/abs/2406.02061)

   *Nezhurina, Marianna and Cipolina-Kun, Lucia and Cherti, Mehdi and Jitsev, Jenia*

1. **Rationales for Answers to Simple Math Word Problems Confuse Large Language Models** `ACL 2024` [[paper]](https://aclanthology.org/2024.findings-acl.524/)

   *Zhang, Yidan and Xue, Mingfeng and Liu, Dayiheng and He, Zhenan*

1. **Living in the Moment: Can Large Language Models Grasp Co-Temporal Reasoning?** `ACL 2024` [[paper]](https://arxiv.org/abs/2406.09072)

   *Su, Zhaochen and Li, Juntao and Zhang, Jun and Zhu, Tong and Qu, Xiaoye and Zhou, Pan and Bowen, Yan and Cheng, Yu and zhang, Min*

1. **Randomly Sampled Language Reasoning Problems Reveal Limits of LLMs** `arXiv preprint` [[paper]](https://arxiv.org/abs/2501.02825)

   *Gupta, Kavi and Sanders, Kate and Solar-Lezama, Armando*

1. **From Blind Solvers to Logical Thinkers: Benchmarking LLMs' Logical Integrity on Faulty Mathematical Problems** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.18921)

   *Rahman, A M Muntasir and Ye, Junyi and Yao, Wei and Yin, Wenpeng and Wang, Guiling*

1. **How well do Large Language Models perform in Arithmetic tasks?** `arXiv preprint` [[paper]](https://arxiv.org/abs/2304.02015)

   *Yuan, Zheng and Yuan, Hongyi and Tan, Chuanqi and Wang, Wei and Huang, Songfang*

1. **How Numerical Precision Affects Mathematical Reasoning Capabilities of LLMs** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.13857)

   *Feng, Guhao and Yang, Kai and Gu, Yuntian and Ai, Xinyue and Luo, Shengjie and Sun, Jiacheng and He, Di and Li, Zhenguo and Wang, Liwei*

1. **Language Models Do Hard Arithmetic Tasks Easily and Hardly Do Easy Arithmetic Tasks** `ACL 2024` [[paper]](https://arxiv.org/abs/2406.02356)

   *Gambardella, Andrew and Iwasawa, Yusuke and Matsuo, Yutaka*

1. **Language Models are Symbolic Learners in Arithmetic** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.15580)

   *Deng, Chunyuan and Li, Zhiqi and Xie, Roy and Chang, Ruidi and Chen, Hanjie*

1. **OccamLLM: Fast and Exact Language Model Arithmetic in a Single Step** `NeurIPS 2024` [[paper]](https://arxiv.org/abs/2406.06576v4)

   *Dugan, Owen and Beneto, Donato Manuel Jimenez and Loh, Charlotte and Chen, Zhuo and Dangovski, Rumen and Soljačić, Marin*

1. **GPT Can Solve Mathematical Problems Without a Calculator** `arXiv preprint` [[paper]](https://arxiv.org/abs/2309.03241)

   *Yang, Zhen and Ding, Ming and Lv, Qingsong and Jiang, Zhihuan and He, Zehai and Guo, Yuyi and Bai, Jinfeng and Tang, Jie*

1. **Fill in the Blank: Exploring and Enhancing LLM Capabilities for Backward Reasoning in Math Word Problems** `arXiv preprint` [[paper]](https://arxiv.org/abs/2310.01991)

   *Deb, Aniruddha and Oza, Neeva and Singla, Sarthak and Khandelwal, Dinesh and Garg, Dinesh and Singla, Parag*

1. **Robustness Assessment of Mathematical Reasoning in the Presence of Missing and Contradictory Conditions** `arXiv preprint` [[paper]](https://arxiv.org/abs/2406.05055)

   *Tian, Shi-Yu and Zhou, Zhi and Jia, Lin-Han and Guo, Lan-Zhe and Li, Yu-Feng*

1. **Reverse That Number! Decoding Order Matters in Arithmetic Learning** `arXiv preprint` [[paper]](https://arxiv.org/abs/2403.05845)

   *Zhang-Li, Daniel and Lin, Nianyi and Yu, Jifan and Zhang, Zheyuan and Yao, Zijun and Zhang, Xiaokang and Hou, Lei and Zhang, Jing and Li, Juanzi*

1. **RevOrder: A Novel Method for Enhanced Arithmetic in Language Models** `arXiv preprint` [[paper]](https://arxiv.org/abs/2402.03822)

   *Shen, Si and Shen, Peijun and Zhu, Danhao*

1. **Arithmetic Without Algorithms: Language Models Solve Math With a Bag of Heuristics** `ICLR 2025` [[paper]](https://arxiv.org/abs/2410.21272)

   *Nikankin, Yaniv and Reusch, Anja and Mueller, Aaron and Belinkov, Yonatan*

1. **CMATH: Can Your Language Model Pass Chinese Elementary School Math Test?** `arXiv preprint` [[paper]](https://arxiv.org/abs/2306.16636)

   *Wei, Tianwen and Luan, Jian and Liu, Wei and Dong, Shuang and Wang, Bin*
   
1. **Large Language Models and Mathematical Reasoning Failures** `arXiv preprint` [[paper]](https://arxiv.org/abs/2502.11574)

   *Boye, Johan and Moell, Birger*

1. **HARDMath: A Benchmark Dataset for Challenging Problems in Applied Mathematics** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.09988)

   *Fan, Jingxuan and Martinson, Sarah and Wang, Erik Y. and Hausknecht, Kaylie and Brenner, Jonah and Liu, Danxian and Peng, Nianli and Wang, Corey and Brenner, Michael P.*

1. **MATH-Perturb: Benchmarking LLMs' Math Reasoning Abilities against Hard Perturbations** `arXiv preprint` [[paper]](https://arxiv.org/abs/2502.06453)

   *Huang, Kaixuan and Guo, Jiacheng and Li, Zihao and Ji, Xiang and Ge, Jiawei and Li, Wenzhe and Guo, Yingqing and Cai, Tianle and Yuan, Hui and Wang, Runzhe and Wu, Yue and Yin, Ming and Tang, Shange and Huang, Yangsibo and Jin, Chi and Chen, Xinyun and Zhang, Chiyuan and Wang, Mengdi*

1. **Self-Improving Transformers Overcome Easy-to-Hard and Length Generalization Challenges** `arXiv preprint` [[paper]](https://arxiv.org/abs/2502.01612)

   *Lee, Nayoung and Cai, Ziyang and Schwarzschild, Avi and Lee, Kangwook and Papailiopoulos, Dimitris*

1. **OMEGA: Can LLMs Reason Outside the Box in Math? Evaluating Exploratory, Compositional, and Transformative Generalization** `arXiv preprint` [[paper]](https://arxiv.org/abs/2506.18880)

   *Sun, Yiyou and Hu, Shawn and Zhou, Georgia and Zheng, Ken and Hajishirzi, Hannaneh and Dziri, Nouha and Song, Dawn*

## Reasoning in Embodied Environments

### 1D - Text Based

1. **Prost: Physical reasoning about objects through space and time** `ACL 2021` [[paper]](https://aclanthology.org/2021.findings-acl.404/)

   *Aroca-Ouellette, Stéphane and Paik, Cory and Roncone, Alessandro and Kann, Katharina*

1. **TEXT2AFFORD: Probing Object Affordance Prediction abilities of Language Models solely from Text** `CoNLL 2024` [[paper]](https://aclanthology.org/2024.conll-1.27.pdf)

   *Adak, Sayantan and Agrawal, Daivik and Mukherjee, Animesh and Aditya, Somak*

1. **A Multi-layered Approach to Physical Commonsense Understanding: Creation and Evaluation of an Italian Dataset** `COLING 2024` [[paper]](https://aclanthology.org/2024.lrec-main.74/)

   *Pensa, Giulia and Altuna, Bego{\~n}a and Gonzalez-Dios, Itziar*

1. **ChatGPT and the frustrated socrates** `Physics Education 2023` [[paper]](https://iopscience.iop.org/article/10.1088/1361-6552/acc299)

   *Gregorcic, Bor and Pendrill, Ann-Marie*

1. **Things not written in text: Exploring spatial commonsense from visual signals** `ACL 2022` [[paper]](https://aclanthology.org/2022.acl-long.168/)

   *Liu, Xiao and Yin, Da and Feng, Yansong and Zhao, Dongyan*

1. **POSQA: Probe the World Models of LLMs with Size Comparisons** `EMNLP 2023` [[paper]](https://aclanthology.org/2023.findings-emnlp.504/)

   *Shu, Chang and Han, Jiuzhou and Liu, Fangyu and Shareghi, Ehsan and Collier, Nigel*

1. **Probing physical reasoning with Counter-Commonsense context** `ACL 2023` [[paper]](https://aclanthology.org/2023.acl-short.53/)

   *Kondo, Kazushi and Sugawara, Saku and Aizawa, Akiko*

1. **NEWTON: Are Large Language Models Capable of Physical Reasoning?** `EMNLP 2023` [[paper]](https://aclanthology.org/2023.findings-emnlp.652/)

   *Yi Ru Wang and Jiafei Duan and Dieter Fox and Siddhartha Srinivasa*

1. **PhysReason: A Comprehensive Benchmark towards Physics-Based Reasoning** `arXiv preprint` [[paper]](https://arxiv.org/abs/2502.12054)

   *Zhang, Xinyu and Dong, Yuxuan and Wu, Yanrui and Huang, Jiaxing and Jia, Chengyou and Fernando, Basura and Shou, Mike Zheng and Zhang, Lingling and Liu, Jun*

1. **UGPhysics: A Comprehensive Benchmark for Undergraduate Physics Reasoning with Large Language Models** `arXiv preprint` [[paper]](https://arxiv.org/abs/2502.00334)

   *Xu, Xin and Xu, Qiyun and Xiao, Tong and Chen, Tianhao and Yan, Yuchen and Zhang, Jiaxin and Diao, Shizhe and Yang, Can and Wang, Yang*

1. **Testing LLM performance on the Physics GRE: some observations** `arXiv preprint` [[paper]](https://arxiv.org/abs/2312.04613)

   *Gupta, Pranav*

1. **PHYBench: Holistic Evaluation of Physical Perception and Reasoning in Large Language Models** `arXiv preprint` [[paper]](https://arxiv.org/abs/2504.16074)

   *Qiu, Shi and Guo, Shaoyang and Song, Zhuo-Yang and Sun, Yunbo and Cai, Zeyu and Wei, Jiashen and Luo, Tianyu and Yin, Yixuan and Zhang, Haoxu and Hu, Yi and Wang, Chenyang and Tang, Chencheng and Chang, Haoling and Liu, Qi and Zhou, Ziheng and Zhang, Tianyu and Zhang, Jingtian and Liu, Zhangyi and Li, Minghao and Zhang, Yuku and Jing, Boxuan and Yin, Xianqi and Ren, Yutong and Fu, Zizhuo and Ji, Jiaming and Wang, Weike and Tian, Xudong and Lv, Anqi and Man, Laifu and Li, Jianxiang and Tao, Feiyu and Sun, Qihua and Liang, Zhou and Mu, Yushu and Li, Zhongxuan and Zhang, Jing-Jun and Zhang, Shutao and Li, Xiaotian and Xia, Xingqi and Lin, Jiawei and Shen, Zheyu and Chen, Jiahang and Xiong, Qiuhao and Wang, Binran and Wang, Fengyuan and Ni, Ziyang and Zhang, Bohan and Cui, Fan and Shao, Changkun and Cao, Qing-Hong and Luo, Ming-xing and Yang, Yaodong and Zhang, Muhan and Zhu, Hua Xing*

1. **ABench-Physics: Benchmarking Physical Reasoning in LLMs via High-Difficulty and Dynamic Physics Problems** `arXiv preprint` [[paper]](https://arxiv.org/abs/2507.04766)

   *Zhang, Yiming and Ma, Yingfan and Gu, Yanmei and Yang, Zhengkai and Zhuang, Yihong and Wang, Feng and Huang, Zenan and Wang, Yuanyuan and Huang, Chao and Song, Bowen and others*

1. **Theoretical Physics Benchmark (TPBench)--a Dataset and Study of AI Reasoning Capabilities in Theoretical Physics** `arXiv preprint` [[paper]](https://arxiv.org/abs/2502.15815)

   *Chung, Daniel JH and Gao, Zhiqi and Kvasiuk, Yurii and Li, Tianyi and M{\"u}nchmeyer, Moritz and Rudolph, Maja and Sala, Frederic and Tadepalli, Sai Chaitanya*

1. **Improving Physics Reasoning in Large Language Models Using Mixture of Refinement Agents** `arXiv preprint` [[paper]](https://arxiv.org/abs/2412.00821)

   *Jaiswal, Raj and Jain, Dhruv and Popat, Harsh Parimal and Anand, Avinash and Dharmadhikari, Abhishek and Marathe, Atharva and Shah, Rajiv Ratn*

1. **Structured chemistry reasoning with large language models** `ICML 2024` [[paper]](https://dl.acm.org/doi/10.5555/3692070.3693649)

   *Ouyang, Siru and Zhang, Zhuosheng and Yan, Bing and Liu, Xuan and Choi, Yejin and Han, Jiawei and Qin, Lianhui*

1. **Auto-Bench: An Automated Benchmark for Scientific Discovery in LLMs** `arXiv preprint` [[paper]](https://arxiv.org/abs/2502.15224)

   *Chen, Tingting and Anumasa, Srinivas and Lin, Beibei and Shah, Vedant and Goyal, Anirudh and Liu, Dianbo*
   
### 2D - Perception Based

1. **Core knowledge deficits in multi-modal language models** `ICML 2025` [[paper]](https://openreview.net/forum?id=EIK6xxIoCB)

   *Li, Yijiang and Gao, Qingying and Zhao, Tianwei and Wang, Bingyang and Sun, Haoran and Lyu, Haiyun and Hawkins, Robert D and Vasconcelos, Nuno and Golan, Tal and Luo, Dezhi and others*

1. **Breaking common sense: Whoops! a vision-and-language benchmark of synthetic and compositional images** `ICCV 2023` [[paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Bitton-Guetta_Breaking_Common_Sense_WHOOPS_A_Vision-and-Language_Benchmark_of_Synthetic_and_ICCV_2023_paper.pdf)

   *Bitton-Guetta, Nitzan and Bitton, Yonatan and Hessel, Jack and Schmidt, Ludwig and Elovici, Yuval and Stanovsky, Gabriel and Schwartz, Roy*

1. **Rome: Evaluating pre-trained vision-language models on reasoning beyond visual common sense** `EMNLP 2023` [[paper]](https://aclanthology.org/2023.findings-emnlp.683.pdf)

   *Zhou, Kankan and Lai, Eason and Yeong, Wei Bin Au and Mouratidis, Kyriakos and Jiang, Jing*

1. **Vision language models are blind** `ACCV 2024` [[paper]](https://openaccess.thecvf.com/content/ACCV2024/papers/Rahmanzadehgervi_Vision_language_models_are_blind_ACCV_2024_paper.pdf)

   *Rahmanzadehgervi, Pooyan and Bolton, Logan and Taesiri, Mohammad Reza and Nguyen, Anh Totti*

1. **Visual spatial reasoning** `TACL 2023` [[paper]](https://aclanthology.org/2023.tacl-1.37/)

   *Liu, Fangyu and Emerson, Guy and Collier, Nigel*

1. **Can Vision Language Models Learn from Visual Demonstrations of Ambiguous Spatial Reasoning?** `NeurIPS 2024` [[paper]](https://openreview.net/pdf/0e4134b9f62c6533e1e91fcbd5ba785cbe5e077c.pdf)

   *Zhao, Bowen and Dirac, Leo Parker and Varshavskaya, Paulina*

1. **Understanding the limits of vision language models through the lens of the binding problem** `NeurIPS 2024` [[paper]](https://openreview.net/forum?id=Q5RYn6jagC)

   *Campbell, Declan and Rane, Sunayana and Giallanza, Tyler and De Sabbata, Camillo Nicol{\`o} and Ghods, Kia and Joshi, Amogh and Ku, Alexander and Frankland, Steven and Griffiths, Tom and Cohen, Jonathan D and others*

1. **Words or Vision: Do Vision-Language Models Have Blind Faith in Text?** `arXiv preprint` [[paper]](https://arxiv.org/abs/2503.02199)

   *Deng, Ailin and Cao, Tri and Chen, Zhirui and Hooi, Bryan*
   
1. **Large Language Models Are Challenged by Habitat-Centered Reasoning** `EMNLP 2024` [[paper]](https://aclanthology.org/2024.findings-emnlp.763/)

   *Ghaffari, Sadaf  and Krishnaswamy, Nikhil*

1. **Visual cognition in multimodal large language models** `Nature Machine Intelligence 2025` [[paper]](https://www.nature.com/articles/s42256-024-00963-y)

   *Schulze Buschoff, Luca M and Akata, Elif and Bethge, Matthias and Schulz, Eric*

1. **Learning the effects of physical actions in a multi-modal environment** `EACL 2023` [[paper]](https://aclanthology.org/2023.findings-eacl.10.pdf)

   *Dagan, Gautier and Keller, Frank and Lascarides, Alex*

1. **Synthetic Vision: Training Vision-Language Models to Understand Physics** `arXiv preprint` [[paper]](https://arxiv.org/html/2412.08619v1)

   *Balazadeh, Vahid and Ataei, Mohammadmehdi and Cheong, Hyunmin and Khasahmadi, Amir Hosein and Krishnan, Rahul G*

1. **PhysBench: Benchmarking and Enhancing Vision-Language Models for Physical World Understanding** `ICLR 2025` [[paper]](https://openreview.net/forum?id=Q6a9W6kzv5)

   *Chow, Wei and Mao, Jiageng and Li, Boyi and Seita, Daniel and Guizilini, Vitor and Wang, Yue*

1. **Physion: Evaluating physical prediction from vision in humans and machines** `NeurIPS 2021` [[paper]](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/file/d09bf41544a3365a46c9077ebb5e35c3-Paper-round1.pdf)

   *Bear, Daniel M and Wang, Elias and Mrowca, Damian and Binder, Felix J and Tung, Hsiao-Yu Fish and Pramod, RT and Holdaway, Cameron and Tao, Sirui and Smith, Kevin and Sun, Fan-Yun and others*

1. **Craft: A benchmark for causal reasoning about forces and interactions** `ACL 2022` [[paper]](https://aclanthology.org/2022.findings-acl.205/)

   *Ates, Tayfun and Atesoglu, M Samil and Yigit, Cagatay and Kesen, Ilker and Kobas, Mert and Erdem, Erkut and Erdem, Aykut and Goksun, Tilbe and Yuret, Deniz*

1. **Mm-phyqa: Multimodal physics question-answering with multi-image cot prompting** `PAKDD 2024` [[paper]](https://dl.acm.org/doi/10.1007/978-981-97-2262-4_5)

   *Anand, Avinash and Kapuriya, Janak and Singh, Apoorv and Saraf, Jay and Lal, Naman and Verma, Astha and Gupta, Rushali and Shah, Rajiv*

1. **PhyX: Does Your Model Have the "Wits" for Physical Reasoning?** `arXiv preprint` [[paper]](https://arxiv.org/abs/2505.15929)

   *Hui Shen and Taiqiang Wu and Qi Han and Yunta Hsieh and Jizhou Wang and Yuyue Zhang and Yuxin Cheng and Zijian Hao and Yuansheng Ni and Xin Wang and Zhongwei Wan and Kai Zhang and Wendong Xu and Jing Xiong and Ping Luo and Wenhu Chen and Chaofan Tao and Zhuoqing Mao and Ngai Wong*

1. **Llmphy: Complex physical reasoning using large language models and world models** `arXiv preprint` [[paper]](https://arxiv.org/abs/2411.08027)

   *Cherian, Anoop and Corcodel, Radu and Jain, Siddarth and Romeres, Diego*

1. **Exploring Failure Cases in Multimodal Reasoning About Physical Dynamics** `AAAI 2024` [[paper]](https://ojs.aaai.org/index.php/AAAI-SS/article/download/31189/33349)

   *Sadaf Ghaffari and Nikhil Krishnaswamy*

1. **On Inherent 3D Reasoning of VLMs in Indoor Scene Layout Design** `preprint` [[paper]](https://openreview.net/forum?id=uBhqll8pw1)

   *Kar, Amlan and Acuna, David and Fidler, Sanja*

1. **Can-Do! A Dataset and Neuro-Symbolic Grounded Framework for Embodied Planning with Large Multimodal Models** `arXiv preprint` [[paper]](https://arxiv.org/abs/2409.14277)

   *Chia, Yew Ken and Sun, Qi and Bing, Lidong and Poria, Soujanya*

1. **Balrog: Benchmarking agentic llm and vlm reasoning on games** `ICLR 2025` [[paper]](https://openreview.net/forum?id=fp6t3F669F)

   *Paglieri, Davide and Cupia{\l}, Bart{\l}omiej and Coward, Samuel and Piterbarg, Ulyana and Wolczyk, Maciej and Khan, Akbir and Pignatelli, Eduardo and Kuci{\'n}ski, {\L}ukasz and Pinto, Lerrel and Fergus, Rob and others*

1. **DeepPHY: Benchmarking Agentic VLMs on Physical Reasoning** `arXiv 2025` [[paper]](https://www.arxiv.org/abs/2508.05405)

   *Xu, Xinrun and Bu, Pi and Wang, Ye and Karlsson, B{\"o}rje F and Wang, Ziming and Song, Tengtao and Zhu, Qi and Song, Jun and Ding, Zhiming and Zheng, Bo*

### 3D - Real-World

1. **Do as i can, not as i say: Grounding language in robotic affordances** `CoRL 2022` [[paper]](https://openreview.net/forum?id=bdHkMjBJG_w)

   *Ahn, Michael and Brohan, Anthony and Brown, Noah and Chebotar, Yevgen and Cortes, Omar and David, Byron and Finn, Chelsea and Fu, Chuyuan and Gopalakrishnan, Keerthana and Hausman, Karol and others*

1. **Embodied agent interface: Benchmarking llms for embodied decision making** `NeurIPS 2024` [[paper]](https://openreview.net/forum?id=iSwK1YqO7v#discussion)

   *Li, Manling and Zhao, Shiyu and Wang, Qineng and Wang, Kangrui and Zhou, Yu and Srivastava, Sanjana and Gokmen, Cem and Lee, Tony and Li, Erran Li and Zhang, Ruohan and others*

1. **Deploying and evaluating llms to program service mobile robots** `IEEE 2024` [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10416558)

   *Hu, Zichao and Lucchetti, Francesca and Schlesinger, Claire and Saxena, Yash and Freeman, Anders and Modak, Sadanand and Guha, Arjun and Biswas, Joydeep*

1. **Language models as zero-shot planners: Extracting actionable knowledge for embodied agents** `ICML 2022` [[paper]](https://proceedings.mlr.press/v162/huang22a/huang22a.pdf)

   *Huang, Wenlong and Abbeel, Pieter and Pathak, Deepak and Mordatch, Igor*

1. **Robotgpt: Robot manipulation learning from chatgpt** `IEEE 2024` [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10412086)

   *Jin, Yixiang and Li, Dingzhe and Yong, A and Shi, Jun and Hao, Peng and Sun, Fuchun and Zhang, Jianwei and Fang, Bin*

1. **AlphaMaze: Enhancing Large Language Models' Spatial Intelligence via GRPO** `arXiv preprint` [[paper]](https://arxiv.org/abs/2502.14669)

   *Dao, Alan and Vu, Dinh Bach*

1. **A little less conversation, a little more action, please: Investigating the physical common-sense of LLMs in a 3D embodied environment** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.23242)

   *Mecattaf, Matteo G and Slater, Ben and Te{\v{s}}i{\'c}, Marko and Prunty, Jonathan and Voudouris, Konstantinos and Cheke, Lucy G*

1. **Creative robot tool use with large language models** `arXiv preprint` [[paper]](https://arxiv.org/pdf/2310.13065)

   *Xu, Mengdi and Huang, Peide and Yu, Wenhao and Liu, Shiqi and Zhang, Xilun and Niu, Yaru and Zhang, Tingnan and Xia, Fei and Tan, Jie and Zhao, Ding*

1. **Spatialvlm: Endowing vision-language models with spatial reasoning capabilities** `CVPR 2024` [[paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_SpatialVLM_Endowing_Vision-Language_Models_with_Spatial_Reasoning_Capabilities_CVPR_2024_paper.pdf)

   *Chen, Boyuan and Xu, Zhuo and Kirmani, Sean and Ichter, Brain and Sadigh, Dorsa and Guibas, Leonidas and Xia, Fei*

1. **Task-oriented robotic manipulation with vision language models** `arXiv preprint` [[paper]](https://arxiv.org/abs/2410.15863)

   *Guran, Nurhan Bulus and Ren, Hanchi and Deng, Jingjing and Xie, Xianghua*
   
1. **Code as policies: Language model programs for embodied control** `ICRA 2023` [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10160591)

   *Liang, Jacky and Huang, Wenlong and Xia, Fei and Xu, Peng and Hausman, Karol and Ichter, Brian and Florence, Pete and Zeng, Andy*

1. **Badrobot: Manipulating embodied LLMs in the physical world** `ICLR 2025` [[paper]](https://openreview.net/forum?id=ei3qCntB66)

   *Zhang, Hangtao and Zhu, Chenyu and Wang, Xianlong and Zhou, Ziqi and Yin, Changgan and Li, Minghui and Xue, Lulu and Wang, Yichen and Hu, Shengshan and Liu, Aishan and others*

1. **EgoNormia: Benchmarking Physical Social Norm Understanding** `arXiv preprint` [[paper]](https://arxiv.org/abs/2502.20490)

   *Rezaei, MohammadHossein and Fu, Yicheng and Cuvin, Phil and Ziems, Caleb and Zhang, Yanzhe and Zhu, Hao and Yang, Diyi*

## General/Case-by-Case Reasoning Failure Studies

1. **Easy Problems That LLMs Get Wrong** `arXiv preprint` [[paper]](https://arxiv.org/abs/2405.19616)

   *Williams, Sean and Huckle, James*

1. **Reasoning with Transformer-based Models: Deep Learning, but Shallow Reasoning** `AKBC 2022` [[paper]](https://www.semanticscholar.org/paper/Reasoning-with-Transformer-based-Models%3A-Deep-but-Helwe-Clavel/8424082e3bf4792462eb112d7ebcecf5b0dc3613)

   *Helwe, Chadi and Clavel, Chloé and Suchanek, Fabian M.*

1. **A Categorical Archive of ChatGPT Failures** `arXiv preprint` [[paper]](https://arxiv.org/abs/2302.03494)

   *Borji, Ali*

## Citation

If you find our work useful, please consider citing our paper: **[Add link to our survey paper.]**

```BibTeX

```
