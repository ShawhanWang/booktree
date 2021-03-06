#[Developer](https://github.com/phodal/developer)进阶书单

> 这是一份关于如何[Re-Practise](https://github.com/phodal/repractise)的技术书籍推荐书单。

一直画/写一个推荐书单来供大家参考，无奈找不到一本合适的形式。有一天，想到了之前的技术树 [https://github.com/phodal/sherlock](https://github.com/phodal/sherlock)，便开始落地了。

我深知自己的知识有限，所以写下本文以便和大家切磋交流。欢迎通过 GitHub 的Issues或者直接Pull Requests方式来分享你的经验。期待你的反馈。

基本阅读路线图:

![BookTree](app/booktree.png)

**说明**: 完成工作是一件很容易的事，如何更好地完成工作就需要更多地学习。并且我坚信每一个有技术热情的人，都希望可以看到自己写的框架可以无处不在。

###《技术的本质》 - W. Brain Arthur早已看穿了一切

这是一本关于『技术是什么，它是如何进化』的书。新的技术是根据于我们当前的目的、一个可实现的原理、一种新现象而发明的。并且，新的技术都是基于之前的技术发展出来的。

So，通过研究现有技术的一些发展，我们可以预料到一些新的技术的出现。尽管新的技术并没有解决一些根本性问题，如业务，但是它是为了业务而简化现有的技术。

##Contribute

书的数据代码位于``app/data``目录:
 
 - arch.json 架构
 - cd.json   持续交付
 - code.json 更好的代码
 - frontend.json 前端 
 - lang.json  语言
 - ml.json   机器学习
 
基本格式如下:

```javascript
{
  "id": 1,
  "description": "尽管在国内，我们很少听到开发人员写测试，就更少听人们谈论TDD。虽然我不是TDD的死忠，但是我觉得TDD还是很有好处的。特别是当你的函数特别长的时候，它可以驱使你写出更短的函数——更多的函数。红->绿->重构，就是这么简单。",
  "title": "《测试驱动开发》",
  "depends": [
    2, 3
  ]
}
```

字段说明:

 - ``id``用于寻找依赖用的
 - ``description`` 书籍的简单书评
 - ``title`` 书名
 - ``depends`` 依赖,数组,可多个

###License

© 2015 [Phodal Huang](http://www.phodal.com). See `LICENSE.txt` in this directory.

[待我代码编成，娶你为妻可好](http://www.xuntayizhan.com/person/ji-ke-ai-qing-zhi-er-shi-dai-wo-dai-ma-bian-cheng-qu-ni-wei-qi-ke-hao-wan/)
