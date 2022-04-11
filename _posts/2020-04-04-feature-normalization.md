---
layout: article
title: 特征工程-特征归一化
tags: Machine learning
---

<!-- If you see this page, that means you have setup your site. enjoy! :ghost: :ghost: :ghost:

You may want to [config the site](https://tianqi.name/jekyll-TeXt-theme/docs/en/configuration) or [writing a post](https://tianqi.name/jekyll-TeXt-theme/docs/en/writing-posts) next. Please feel free to [create an issue](https://github.com/kitian616/jekyll-TeXt-theme/issues) or [send me email](mailto:kitian616@outlook.com) if you have any questions. -->

<!--more-->

<!-- ---

If you like TeXt, don't forget to give me a star. :star2:

[![Star This Project](https://img.shields.io/github/stars/kitian616/jekyll-TeXt-theme.svg?label=Stars&style=social)](https://github.com/kitian616/jekyll-TeXt-theme/) -->

---

# 特征归一化

为了消除数据特征之间的量纲影响，我们需要对特征进行归一化处理，使得
不同指标之间具有可比性。例如，分析一个人的身高和体重对健康的影响，如果
使用米（m）和千克（kg）作为单位，那么身高特征会在1.6～1.8m的数值范围
内，体重特征会在50～100kg的范围内，分析出来的结果显然会倾向于数值差别比
较大的体重特征。想要得到更为准确的结果，就需要进行特征归一化
（Normalization）处理，使各指标处于同一数值量级，以便进行分析。




