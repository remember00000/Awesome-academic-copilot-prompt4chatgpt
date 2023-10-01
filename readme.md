# **ChatGPT Prompts for Academic Research**

**在chatgpt告诉发展的今天，科研也应该完全脱离原始的口口相传的低速进展的模式，利用这个超级工具，我们的科研应该是高速推进的。**数学家陶哲轩分享promp和谷歌科学家提到现在的科研就是工程实现的速度比拼，现有的科研范式已经发生改变，能掌握最新工作flow的才是能领跑的。人类和其他生物的区别就在于使用工具的能力，学会使用chatgpt实现高速科研过程就是新时代科研工作者和传统的区别。然而传统的科研模式下还是劳动力为基础的，更多的底层的科研工作者在论文发表之前的各个阶段可以说做了大量的劳动性工作。而现在其中对每一个阶段都能被chatgpt为代表的AI工具加速，能够让我们更加专注于思考更高维度的流程、应该做什么层面，人类科研应该更多的专注于高层面纬度。现在chatgpt的出现是能将原本一周的工作压缩到1天来进行，我们要做的就是知道每个阶段要做什么，怎么利用chatgpt加速实现这个过程。本文对如何加速进行梳理，主要侧重prompt模板，让实际使用不用思考prompt怎么设计，

**涵盖科研过程：**brainstorming research ideas（ idea评估）， conducting literature reviews， **paper** reading， 实验代码实现，实验代码调试，实验结果分析，paper writing，improving language and style。

Use directly in: [chat.openai.com](http://chat.openai.com)、bard

这个仓库存在的原因：能够极大解放生产力，更多的关注更高层面的创造，这是未来的趋势，我们科研工作者是位于科技前沿的从业人员，更应该首先使用这一套工具 首先进入到这一个新时代里，解放重复性耗时工作。对于初级工作者来说，又一个交流更多的导师甚至超过导师。

The list is regularly updated, so you can keep track of new prompts by following this repository. 也希望大家讲自己的工作好用的prompt**通过提出issue的形式来让整个仓库更加完善。**

**TIPS:** 本仓库的prompt形式采用了吴恩达的prompt课程上的技巧，包括使用‘’‘作为分隔符，原因是这种分隔符在模型训练时被单独分离能够对后面的文字信息起到强调对作用。

大牛学术科研prompt：

陶哲轩使用：https://chat.openai.com/share/53aab67e-6974-413c-9e60-6366e41d8414

**BRAINSTORMING**

- 我的研究题目是【研究题目】，帮我想一下更加细化的方向。
- 请为以下的研究题目写一个详细的提案。请确保它是原创的、没有抄袭。[段落]
- 关于[段落]，生成10个学术研究问题。
- 列出与[TOPIC SENTENCE]相关的研究假设。
- 在这[研究主题]的背景下，识别未来研究的潜在领域。
- 建议在[研究领域]中对[TOPIC SENTENCE]的新颖应用。
- 我的研究问题是【研究问题背景介绍】，针对某个问题【问题的详细细节】，我的解决方案是【提出你的解决方案】，你觉得怎么样？（你觉得还有哪些可以改进的地方/你觉得还有什么更好的解决方式/你觉得创新性怎么样？）

## ARTICLE SECTIONS

### Translate/Polish

- 帮我翻译以下这段内容，注意时态使用一般现在时，不要使用生僻词，不要使用缩写。
- 帮我润色一些这段句子，更符合英语表达习惯，更有逻辑，不改变原意，注意时态使用一般现在时，不要使用生僻词，不要使用缩写。
- 请使用学术语言重写此段落：[段落]
- 请纠正此段落的语法错误：[段落]
- 建议改进此段落的三个要点是什么？：[段落]
- 改进我文章的清晰度和连贯性：[段落]
- 改进我论文的组织和结构：[段落]
- 能否改进这一段落，使其更具连贯性？：[段落]
- 请将此段落重写为Introduction：[段落]
- 作为[研究领域]专家，请审查我关于[TOPIC ]的文章，并重点检查语法和标点。
- 作为【研究领域】专家，请审查我关于[TOPIC ]的文章，并重点检查语法和标点。

### Title/Topic Sentence

- 为以下摘要建议5个标题：[摘要段落]
- 为此段落写一个主题句：[段落]

### Keywords

- 给出关键词: [PARAGRAPHS]

### Abstract

- 将以下内容重写为摘要: [PARAGRAPHS]

### Outline

- 为[主题句]生成一个大纲
- 我想关于[主题句]写一篇期刊文章。给我一个文章的大纲

### Introduction

- Come up with an introduction for the following research topic: [TOPIC SENTENCE]

### Literature Review

- Conduct a literature review on [TOPIC SENTENCE] and provide review paper references
- Provide me with references and links to papers in [PARAPGRAPH]
- Write this in standart Harvard referencing [PARAGRAPH]
- Convert this [BIBLIOGRAPHY] from MLA to APA style.
- Compare and contrast [THEORY1] and [THEORY2] in the context of [RESEARCH DOMAIN]:

### Methodology

- Create objectives and methodology for [TOPIC SENTENCE]
- Write a detailed methodology for the topic: [TOPIC SENTENCE]
- Analyze the strengths and weaknesses of this methodology: [PARAGRAPHS]
- Write objectives for this study: [TOPIC SENTENCE]
- What are the limitations of using [TOPIC SENTENCE] in [RESEARCH DOMAIN]?
- Create a recipie for the methods used in this [PARAGRAPHS]
- Suggest interdisciplinary approaches to [TOPIC SENTENCE]
- Explain how qualitative/quantitative research methods can be used to address [RESEARCH QUESTIONS]
- Explain how qualitative/quantitative research methods can be used to address [RESEARCH QUESTIONS]
- Recommend best practices for data collection and analysis in [TOPIC SENTENCE]

### Experiments

- Design an experiment that [ACTION]

### Results

- Write a result section for the following paragraphs. Please write this in third person. [PARAGRAPHS]

### Discussion

- Discuss this results: [RESULT PARAGRAPHS]

### Conclusion

- Generate a conclusion for this: [PARAGRAPHS]
- Give recommendations and conclusion for: [PARAGRAPHS]

### Future Works

- Can you suggest 3 directions for future research on this topic: [PARAGRAPH]]?

## Experiment

#### 代码实现

- 我想实现【代码功能描述】，帮我用python实现

#### 代码报错处理

- 代码出现【代码报错复制粘贴】，怎么解决？

#### 代码优化加速

- 这段代码运行过慢，怎么加速？
- 现在batch只能限制在很小，有什么优化策略？【给出代码】
- 【给出自己的代码】针对这段代码有什么优化建议

#### 实验结果分析

- 直接将实验结果丢给chatgpt-advanced data analysis，告诉他【实验研究背景】，针对某些指标让chatgpt进行分析

## **paper** reading

> 大大缩短读论文的时间

- 使用bard上传pdf
- 告诉我这篇论文的核心点是什么，任何关于论文的问题和细节都能提问

## references

专注于用chatgpt提升写作的repo：https://github.com/ahmetbersoz/chatgpt-prompts-for-academic-writing

> 科研写作是科研的一环，但其实现有的AI工具能在科研的前几个环节都能极大帮助我们解放生产力，这是本仓库存在的原因--积累下每个过程加速的方法。以上记录了本人使用以及一些大佬分享的案例，但很多内容文字表示更多，写出来冗余故暂时没有添加，以后有更好的表示方法