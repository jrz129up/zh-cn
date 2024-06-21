---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<span style="font-size:17px;">我现在就读于中国人民大学农业与农村发展学院农村发展专业，师从[马九杰](http://www.sard.ruc.edu.cn/szll/zzjs/qzjs/299c34878e4d4d5d8b5878fdd743df0d.htm)教授</span>   
<br>
<br>
 <!-- 我已经发表 20+ 篇学术论文<a href='https://scholar.google.com/citations?user=WMkMTb4AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>。 -->

我的研究兴趣是**中国特色社会主义政治背景下基层制度与社会发展的关系**，这包括：
- 探究基层制度的有效性，即是否能实现福利的最大化，或至少能实现福利改进
  - 基层组织与社会福利目标
  - 福利的测度
  - 基层制度影响福利的因果机制
- 制度失效背景下的外生激励与制度变迁
  - 外生激励的异质性与最优激励组合
  - 如何变外生为内生，以实现可持续发展

<br>
现阶段，我主要在思考**“如何可持续地帮助社区形成有助于福利改善（相对有效）的非正式制度”**。
<br>
<br>
<span class='anchor' id='-xl'></span>

# 🎓 学历
- *2022.09 - 2025.06(expected)*, <a href="https://www.ruc.edu.cn/"><img class="svg" src="/zh-cn/images/Renmin_University_of_China_logo.svg" width="21pt"></a> 中国人民大学 农业与农村发展学院, 农林经济管理, 硕士 
- *2018.09 - 2022.06*, <a href="https://www.bjtu.edu.cn/"><img class="svg" src="/zh-cn/images/BJTU_emblem.svg" width="21pt"></a> 北京交通大学 经济管理学院, 经济学, 本科
<br>
<br>
<span class='anchor' id='-lw'></span>

# 📝 论文

### 已发表

- 	焦敬娟,张齐林,吴宇勇,**江润泽**,王姣娥.中国异地投资网络结构演化及影响因素研究.地理科学进展,2021 [[网页]](https://kns.cnki.net/kcms2/article/abstract?v=f1ZyUc11mdpYllT2xqHJRoxXcKTqVmXr4DtD6ltlH0CYLHwYvyjgm5ybiN0I3myBH_17MYu1KmSN1ftxJqErAFzasLI2IVRl5E5TScazfT91ACYsGHIvu6mYIRAMLyZ1H1MBs-DnPZzWetM5qrWazQ==&uniplatform=NZKPT&language=CHS)
<br>
- 	王超,**江润泽**,梁景玉,等.北京地铁票制票价调整空间及方式研究.综合运输,2020 [[网页]](https://kns.cnki.net/kcms2/article/abstract?v=f1ZyUc11mdrdk-T8GIsXuASAVU4iqRt6ZFgldxcDvkNnq-P4MpAAvTu-ilkeUUBW9tyJwd7-F03_h2QJeyfI7w57IX-5-dedSRwFEZknT9S4DpWXoLVtM6JNqpCfcCpEg3hhInWU56GEOwAOXae-1A==&uniplatform=NZKPT&language=CHS)

<br>

### 工作论文

- QL Zhang, **Runze Jiang**, JJ Jiao. Agglomeration and Dispersion Effects of High-speed Rail: A New Perspective of Intercity Labour Migration from China
  - **研究结论**
    - 高铁既产生聚集效应也产生分散效应，其中聚集效应占主导地位
    - 分散效应先发生，随后出现聚集效应
    - 就业机会、工资和环境的差异对这些效应具有调节作用
  - **数据来源与研究方法**：人口流动数据来源于2017年中国流动人口动态监测调查数据（CMDS），包括了迁移空间和时间信息（每一年记录调查对象以往流动的数据）；构建由288个地级市和4个直辖市为节点的855,560（293×292）个城市对的平衡面板数据，覆盖了2007年至2016年的10年；使用高维固定效应模型进行回归
  - **研究贡献**：基于城际劳动力流动的视角，明确评估了高铁产生的聚集效应和分散效应

<br>
- **江润泽**,马九杰.物质激励能促进规范违背吗？——来自全国治理积分制的证据
  - **研究结论**：物质激励并不利于人们违背无效规范，基层的组织能力才是主要因素
  - **数据来源与研究方法**：实地调研58个村庄收集质性资料，形成对积分制运行的基本了解，构建理论模型；利用Python与JS爬取为村平台数据，获取公共行为、基层组织等数据，并形成月度面板，进行回归分析
  - **研究贡献**
    - 从客体的角度说，当社会规范失效时采取物质激励促使人们违背无效规范的举措并不一定是有效的，补充了法律经济学中有关改变无效社会规范的研究
    - 从方法的角度说，在中国基层语境中证明了物质激励对动机挤出
    - 从主体的角度说，探讨了自治背景下基层组织，特别是拥有实权的党派组织，在公共产品生产中的重要作用
  - 未来拓展
    - 下一步研究将采用RCT，共分为四组，第一组是科斯组（市场化交易组），第二组是布鲁诺组（以公易公组），第三组是混合组，第四组是控制组
    - 第一组与第二组的差在本质上是在论证，公共领域内，到底是市场更优，还是确权前提下的集体主义制度更优；第三组是中国特色社会主义的一个写照
    - 通过对比不仅能证明公共行为领域内，到底是哪一种资源分配方式更优；往更宏观说，这是在论证不同制度的优劣之处
   
<br>
- **江润泽**.浅尝辄止: 社会科学研究的数据处理手册
  - 写作本手册的初衷是陈述对计算机的简约理解，记录在社科研究中进行数据处理的过程，总结运用计算机处理数据的经验，在此基础上形成一般化的经验并成书推广；就算最终无法出版成书，本书也能成为小范围内（例如一个师门）数据处理的指导手册
  - 涉及领域包括基本的计算机科学（计算机组成原理，操作系统，数据结构与算法及计算机网络）；网络爬虫；数据清洗；计量经济学；机器学习。目前主要在撰写前两部分
  - 运用Python与JavaScript实现上述不同场景需求的具体代码

<span class='anchor' id='-ryjx'></span>

# 🏅 荣誉奖项
- *2023.06-2024.06*  &nbsp;&nbsp;中国人民大学农业与农村发展学院研究生会及学术部主席
- *2023.10*    &nbsp;&nbsp;中国人民大学农业与农村发展学院 二等学业奖学金
- *2022.10*    &nbsp;&nbsp;中国人民大学农业与农村发展学院 二等学业奖学金
- *2021.04*    &nbsp;&nbsp;第七届“中国外运杯”全国大学生物流设计大赛 全国二等奖
- *2021.04*    &nbsp;&nbsp;“正大杯”第十一届全国大学生市场调查与分析大赛 全国三等奖

<span class='anchor' id='-grjl'></span>

# 📄 个人简历

这是我的简历：[CV](/runze_jiang_cv.pdf)


