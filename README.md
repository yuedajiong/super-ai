# Me, Super-AI
  Independent-Researcher
  
  Never work for any country, any orgnization, any company, any individual.
  
  Never be used for 'Beijing China'.

  Just for my dream: approach to the demiurge, through super-intelligence. 
  
# 2023-07-01

  I have resigned from my last company, financial independence, and full-time for super-ai researching and implementation.
  
  I will record my key insights in the process of researching and implementation to super intelligence in Chinese.
  (If you need to read, please translate them into your own language.)

# 2024-03-15 (dynamaic-stereo-vision-direction)

  The first version of the ultimate visual model is completed.
  
  input: single-image, camera-free/train&infer, mask-support, incremental-hash-priori (so-far: single-object)
  
  output: explicit-stereo-representation (only: stereo; todo: dynamic and interactive.)

# 2024-11-21 / 2024-12-14 (<brain-like> ultimate-learning-and-thinking-direction)

  With accompanying features: incremental/online learning.
  
  2024-11-21: The 1st version of the non-BP learning (block-independent-leaning, w/ or w/o target). Effitive! Tested on: MLP, dimension-reduction, classification.
  
  2024-12-14: The 2nd version of the non-BP learning (block-independent-leaning, w/ or w/o target). Effitive! Tested on: MLP, regression (difficult-task-type, a little different with classification), generation should be easy. Not implement on larget attention/transformer network and  cifar10/100 or other big dataset task.
  
# 2025-09-22 / 2025-10-31 (ASI)
  2025-03-01 to 2025-08-31: In the summer of 2025, collaborated with Justin(https://github.com/yuenuting) to develop the Neural Octree Mesh representation algorithm, addressing highly detailed very large scale 3D representations and enabling neural network learnable.   
  
  2025-09-01 to 2025-09-21: Completed the first version of the 'ASI' program, capable of confidently handling tasks such as ARC-AGI, Math Solver Tasks (SAT/IP/MIP/...), Sudoku, and more.  (https://github.com/arcprize/hierarchical-reasoning-model-analysis/issues/2)
  
  Conclusion: "There is NO such thing as so-called AGI/ASI" -- what truly matters is diligent, systematic task-solving. However, problems can be abstracted into common solution frameworks and prepared system; yet, both learning and searching remain indispensable. The common components include but not limited:
  
    Problem representation
    
    Transformation of problem solution space (compression/abstraction, decomposition)
    
    General representation of solutions (one-shot function) and structured representation (directed graph)
    
    Automatic construction of atomic solution functions
    
    Brute-force search based on atomic solution functions, and
    
    Heuristic search guided by prior learning as state-action mappings (generalized reasoning: DG{A|S}, ...)

    ...

  2025-10-31，complete the ARC-AGI task solving, including algorithm and code.  detail pls refer to : https://github.com/arcprize/hierarchical-reasoning-model-analysis/issues/2

# 2025-12-20 Rethink AI
  浪费了人生数年，得到的痛苦的教训，关于人工智能的误解。
  2010特别是2012深度学习爆发以来，作为一个洞察事物本质缺乏深度的人，很容易受到行业里面辉煌的东西（比如DL@Vision#CNN/Transoformer/xNN@ImageNet, DL@Symbol#LLM/GPT, ...的蓬勃发展)的东西影响。
  在灿烂的烟花下，往往忽略了对事物本质的持续洞察，记录下2025年末，我得到的几个苦涩的教训：
  1. AI任务不是“函数拟合问题”，而是“算子在受约束范畴中的构造问题”。傻逼的不是我一个，我估计99.99%的AI研究人员今天还在这么认为。AI就是函数拟合，拟合个头。拜托上帝，请让我从骨子里清除这个理解。
     AI Task: T=(X,Y,S,L,C),  S是Latent Space，好的S的构造有助于“智能”的解决问题，我们应该弱化L/Loss，Loss可能是难以完美构造；我们应该强化C约束的构造（含学习）。
  3. 约束很重要，约束很重要，对于本身是强约束的任务，如果只是一味的面向Y/target的优化，得到的东西终究只是奇葩。比如LLM本身对应的任务本身应该是强约束的，所谓幻觉只是约束不够。 行业里面喧嚣的World Model，其实是不可能完美构造的，最终的Validator也很重要。世界模型被提及但缺乏有深度的理解。 面向优化拟合而设计的损失（广义的评估）是受限的。关于如何系统的表示和构造约束是空白。
  4. 目前为止的几乎所有的AI算法，更多的强调了学习Learn/Train（先验），忽略了搜索/Search（除了MuZero类是有比较强搜索的）。 
  5. 个人的一个理解，ASI面对的是可计算性的墙，而AGI的墙，可能需要一种“Language++的表征与操作体系”才能完成。现在还是空白。自然语言不够，纯数学的表达也不够，程序语言只有具体实例一层缺乏层次化的抽象。
  6. 当前人工智能领域，其实缺乏真正的大师了，像图灵那样的人。 能够一眼洞穿这些问题的本质，能够高瞻远瞩，在50年100年后，见解还足够深刻和正确的。 工程和算法上的繁荣是不够的。


# to be continued, in diary ...

# long-term: (super-ai) 
(not generative direction; Fig.2 strcuture/algorithm is still on developing ...)

2022-08-28 My thoughts, under LeCun's Paper on OpenReview:  https://openreview.net/forum?id=BZ5a1r-kVsf&noteId=8g5X9wi4HX

(Chinese)
![image](https://github.com/yuedajiong/super-ai/assets/52232153/a43fb2c3-963c-40be-a3fa-0f1134151419)

(English)
![image](https://github.com/yuedajiong/super-ai/assets/52232153/7099d885-4fc6-41a4-954a-c3f5b9fe9af8)


# current: (super-ai)
/physical/vision/interactive-dynamic-stereo  (https://github.com/yuedajiong/super-ai-vision)
![image](https://github.com/yuedajiong/super-ai/assets/52232153/176fe1cd-5328-49e7-a896-a50747b261df)


/symbol/thinker/unified-thinker(mathink & math-solver & arc-agi)  (https://github.com/yuedajiong/super-ai-symbol)
<img width="1326" height="906" alt="image" src="https://github.com/user-attachments/assets/e0c9b04b-52b7-4229-8eca-bf58bf415717" />

