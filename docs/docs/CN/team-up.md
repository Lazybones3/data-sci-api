# 欢迎加入我们！

`GlacierData`是开放数据网站，目前主要致力于COVID-19相关的数据和研究，提倡研究共享。欢迎优秀的开发者和科学家们加入和合作。

## 关于我们

我们来自开源社区，主要是各个专业的数据科学家和工程师。在过去一个月里，针对当下新冠状病毒我们已经做了一些研究，未来这些研究也可能在其他的公共卫生和公共安全事件上起到作用，我们致力于产生即时和长期的影响。
团队成员有着丰富的专业背景，包括物理学、经济学、数学和统计学，计算生物学和计算机科学等。因此我们能够理解跨学科协作的必要性和难点。

## 我们的目标

在疫情来临的关头，数据共享，开放讨论，共同研究。这是我们的目标

希望通过我们的项目，让任何拥有数据的人，或者数据分析相关技能的人都能迅速了解最新情况，做出自己力所能及的贡献。
根据我们的经验，做些什么事情比一个人呆着感觉好多了，所以参与项目对健康说不定也是有帮助的。

现代社会里传染病的复杂度主要是随着全球化的城市化的增加而增加的。举例来说，从2003年SARS以来，中国的火车流量增加了4倍，国际间的交流也成倍增长。因而，传染病这样的公共事件，可能不仅仅影响到公共卫生和人们的健康，也会影响到商业，交通，物流，民生，方方面面。顶级学术期刊如《柳叶刀》和[Nature](https://www.nature.com/articles/s41586-019-1717-y)都呼吁各方面开展合作，我们看到最近WHO也这样做了。我们此刻需要的合作，不仅需要世界各地的传染病学者同心协力，还需要诸多不同技能和领域的人士参与其中。数据科学也在里面扮演重要的角色，[这篇论文](https://royalsocietypublishing.org/doi/pdf/10.1098/rstb.2018.0276)列出了数据科学在传染病爆发中的一些应用。

但是，合作的理想和现实之间还是有着障碍。最大的障碍就是，学者需要时间来消化流行病学知识，理解疾病爆发的复杂影响因素。要进行分析，也需要获得和自己专业相关的数据。这些都需要时间，因此很多研究都是在疾病爆发后很久才完成的，在问题频出的紧迫当下，这样的研究强度无疑是不够的。

我们认为，一个能够致力于数据开放，研究者之间彼此相互帮助的平台，对于增加研究成果能够起到积极的作用。同时，也可以彼此帮助，完成专业知识的初期积累。一个月前，我们的团队成员就编写了流行病学建模相关的初级课程，也提供了流行病模型的代码示例。接下来我们会考虑借助全世界开源社区的力量来完善这个项目。我们也会提供数据API服务，主要提供用于研究和分析的数据集合。大家可以在项目中自由讨论，以拓展自己的研究视界。

在为社区做出贡献的同时，你自己的研究也能获得进展进展。数据科学里面有很多社区就是这样成功的，比如Kaggle。

我们的成员里也有实际做出自己研究的例子在，举例来说，其中一个成员所在的项目组，就推出了一个用于城市间疫情流动模拟的[平台](https://newshub.sustech.edu.cn/zh/html/202002/34047.html?from=timeline&isappinstalled=0)，这个平台是南方科技大学和东京大学的合作项目。它利用公开的数据集合，覆盖了目前在微观防控效果上的研究空缺。

你是不是也有很多事情想做?比如想要做出漂亮的可视化，想要知道疫情接下来的发展。

一个人可能是无法完成的，但是借由分享和开放，你可能可以完成自己的目标。

## 我们的缘起

我们的成员主要来自于Wuhan2020开源志愿者社区。Wuhan2020社区是COVID-19爆发期间成立的最大的开源社区，成立前三天就吸引了3，000多人。

国内的报道将Wuhan2020主要报道为一个防疫信息平台，提供医院和物流服务的捐赠列表，类似Craiglist，同时也和斯坦福和多家机构一起举办了武汉主题的黑客松。不过，我们来自于里面的数据科学组，由独立的研究和开发人员构成，我们拥有着自己的使命，目前和社区项目的财务，技术等多个方面都是独立的。

新冠状病毒的传播在过去的一个月里一日千里，已经成为全球卫生紧急情况。因此，我们决定继续发挥我们在合作研究方面的经验，我们想要启动这样一个开放数据和开放研究的项目。我们不仅想有助于流行病学和医学开发领域的研究(这方面研究已经有很多了)，还想推动社会科学和其他领域的相关研究。

## 项目的技术进展

**数据API服务:**目前后台API使用`PostgreSQL`+`Python`+`OpenAPI(Swagger)`，API的公开地址为https://www.sturgeons.app/
该代码库已经开源。

**基础数据:**我们拥有中国公共领域能找到的大部分数据，也在建立患者信息数据库。我们的下一步是国际数据。目前数据这块是我们的工作重点。

**模型:**我们在Github上的数据建模[项目Repo](https://github.com/wuhan2020/Covid-19-data-science)在Github上收获了100多星。这在没有任何公开曝光或宣传的情况下实现的。我们已经把它移到独立的REPO中，但在Wuhan2020社区里依然可以看到我们的一个分支。

**网站:**当前我们的所有用户都来自GitHub。为了扩大受众范围，我们会自己搭一个网站，目前已经有了一个demo。我们也需要数据可视化方面的协助。

**用户:**目前已经有人从Github上找到我们，发邮件问是否可以使用我们的数据。我们的核心用户是项目的积极贡献者们，潜在用户是所有数据科学家和定量研究人员。这个群体人数众多。根据我们组里的统计，有1/10的潜在用户会加入讨论，其中又有1/5可能会成为积极的贡献者。


## 联系我们

请发送电子邮件到**stockard[DOT]h[AT]gmail[DOT]com**与我联系。
由于大家都是志愿者，希望交流可以做到高效。推荐您仔细读完上面这些内容后，和我们开门见山地交流彼此能带来的帮助。
这是一个技术和数据驱动型的项目，再次真诚期待您的加入。

