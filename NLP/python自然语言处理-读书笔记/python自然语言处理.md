# 语言处理与python
1. 几种函数功能
   1. 查找 
      1. 词所在的位置`concordance`
      2. 含有相似上下文的词`similar`
      3. 查找两个或两个以上的词共同上下文`common_contexts`
      4. 绘制分布图`dispersion_plot`
      5. 频率分布`FreqDist`
      6. 双连词`collocations`（函数执行有error）
2. 对于一个文本语料库，你可以做什么？
    1. 文本有多少词符（单词、符号）
    2. 词汇丰富度（词符数目 / 总数目）
    3. 单词出现的次数、占比
    4. 词符频率分布
    5. 长词、高频长词
    6. 词语搭配、双连词
    7. 词的长度的频率分布
3. [ipynb笔记](ipynb/python自然语言处理-1.ipynb)

#获得文本语料和词汇资源
1. 获取文本语料库
   1. 古腾堡语料库
      1. 三种属性
         1. 统计平均词长（英语的一般属性，一般为3）
         2. 平均句子长度
         3. 本文中每个单词出现的平均次数（词汇多样性）
      2. 三个函数
         1. 原始资料（包括空格）`gutenberg.raw()`
         2. `gutenberg.words()`
         3. 划分为句子，每个句子是一个单词列表`gutenberg.sents()`
   2. 网络和聊天文本
   3. 布朗语料库
      1. 比较不同文本中的情态动词的用法
   4. 路透社语料库
   5. 就职演说语料库
      1. 观察america与citizen随时间推移的使用情况
   6. 标注文本语料库
      1. 通过udhr（包含超过300中语言的世界人权宣言）研究不同语言字长的差异
      2. 研究某语言字母频率分布