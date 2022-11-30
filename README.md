# AIGC行研
一、导语
---
人类擅长分析事物，而机器在这方面甚至做得就更好了。机器可以分析一组数据，并在其中找到许多用例（use case）的模式，无论是欺诈还是垃圾邮件检测，预测你的发货时间或预测该给你看哪个TikTok视频，它们在这些任务中变得越来越聪明。这被称为“分析型AI（Analytical AI）”，或传统AI。
但是人类不仅擅长分析事物，我们也擅长创造。我们写诗，设计产品，制作游戏，编写代码。直到最近，机器还没有机会在创造性工作上与人类竞争——它们被降格为只做分析和机械性的认知工作。但最近，机器开始尝试创造有意义和美丽的东西，这个新类别被称为“生成式AI（Generative AI）”，这意味着机器正在生成新的东西，而不是分析已经存在的东西。

生成式AI正在变得不仅更快、更便宜，而且在某些情况下比人类创造的更好。从社交媒体到游戏，从广告到建筑，从编程到平面设计，从产品设计到法律，从市场营销到销售，每一个原来需要人类创作的行业都等待着被机器重新创造。某些功能可能完全被生成式AI取代，而其他功能则更有可能在人与机器之间紧密迭代的创作周期中蓬勃发展。但生成式AI应该在广泛的终端市场上解锁更好、更快、更便宜的创作。人们期待的梦想是：生成式AI将创造和知识工作的边际成本降至零，产生巨大的劳动生产率和经济价值，以及相应的市值。

生成式AI可以处理的领域包括了知识工作和创造性工作，而这涉及到数十亿的人工劳动力。生成式AI可以使这些人工的效率和创造力至少提高10%，它们不仅变得更快和更高效，而且比以前更有能力。因此，生成式AI有潜力产生数万亿美元的经济价值。

二、Why Now
---
生成式AI与更广泛的AI有着相同的“为什么是现在（Why now）”的原因：更好的模型，更多的数据，更多的算力。这个类别的变化速度比我们所能捕捉到的要快，但我们有必要在大背景下回顾一下最近的历史。

第1波浪潮：小模型（small models）占主导地位（2015年前），小模型在理解语言方面被认为是“最先进的”。这些小模型擅长于分析任务，可以用于从交货时间预测到欺诈分类等工作。但是，对于通用生成任务，它们的表达能力不够。生成人类级别的写作或代码仍然是一个白日梦。
第2波浪潮：规模竞赛（2015年-至今），Google Research的一篇里程碑式的论文 Attention is All You Need https://arxiv.org/abs/1706.03762 描述了一种用于自然语言理解的新的神经网络架构，称为transformer，它可以生成高质量的语言模型，同时具有更强的并行性，需要的训练时间更少，同时transformer的应用范围也更加广泛，可以相对容易地在各领域进行定制。

<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/204441856-b1ee2d36-e6c5-490f-b6eb-c208527ade45.PNG"/>
</div>

<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/204441993-dea0d467-e0f8-4a0c-851d-f014746c1a75.JPEG"/>
</div>


果不其然，随着模型越来越大，它们开始可以输出达到人类水平的结果，然后是超人的结果。从2015年到2020年，用于训练这些模型的计算量增加了6个数量级，其结果在书写、语音、图像识别、阅读和语言理解方面超过了人类的表现水平。OpenAI的GPT-3表现尤其突出：该模型的性能比GPT-2有了巨大的飞跃，并且从代码生成到笑话编写的任务中都提供了出色的Twitter demo来证明。据我们了解，就在最近，Microsoft已经迭代出了GPT-4，其在提升多轮长对话的表现方面有了更加出色的表现。

尽管所有的基础研究都取得了进展，但这些模型并不普遍。它们庞大且难以运行(需要特别的GPU配置)，不能被更多人广泛触达使用(不可用或只进行封闭测试)，而且作为云服务使用成本昂贵。尽管存在这些限制，最早的生成式AI应用程序也已经开始进入竞争。

![3](https://user-images.githubusercontent.com/118708553/204442080-e7fe54b5-7993-49fa-82bc-1f4c29e69c4f.PNG)


第3波浪潮：更好、更快和更便宜（2022+），算力变得更便宜，新技术，如扩散模型（diffusion models），降低了训练和运行所需的成本。研究人员继续开发更好的算法和更大的模型。开发人员的访问权限从封闭测试扩展到开放测试，或者在某些情况下扩展到开源。

![4](https://user-images.githubusercontent.com/118708553/204442399-fb58a127-73e2-40cb-a95c-f2072bcb0bf9.JPEG)

对于那些渴望接触LLMs（Large Language Model 大语言模型）的开发人员来说，探索和应用开发的闸门现在已经打开，应用开始大量涌现。

第4波浪潮：杀手级应用出现（现在），随着平台层的稳固，模型继续变得更好、更快和更便宜，模型的获取趋于免费和开源，应用层的创造力已经成熟。

![5](https://user-images.githubusercontent.com/118708553/204442444-25bdbcaf-592b-43d1-a8ae-d83c719f0abd.JPEG)
![6](https://user-images.githubusercontent.com/118708553/204446889-15b4dc20-1b02-47b7-9464-ee7648a4605c.png)

正如移动设备通过GPS、摄像头和网络连接等新功能释放了新类型的应用程序一样，我们预计这些大型模型将激发生成式AI应用程序的新浪潮。就像十年前移动互联网的拐点被一些杀手级应用打开了市场一样，我们预计生成式AI的杀手级应用程序也会出现，比赛开始了。

三、市场格局
---
下面是一个示意图，说明了为每个类别提供动力的平台层，以及将在其上构建的潜在应用程序类型。
<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/204446620-0e9b08f4-38d6-4971-915d-eabc8f5f6ff2.png"/>
</div>

### 3.1 模型
`文本（Text）：`是目前最先进的领域，以GPT-3为例，其文本生成能力已被直接应用于Writesonic、 Conversion.ai、 Snazzy AI、 Copysmith、 Copy.ai等文本写作/编辑工具中。另一方面，以transformer架构为重要代表，相关的底层架构仍在不断精进。如今，这些模型在一般的中短篇形式的写作中相当出色(但即便如此，它们通常用于迭代或初稿)。而对话则为文本的另一重要发展方向，具有代表性的是Google的LaMDA、PaLM以及最新发布的GPT-4。

`代码生成（Code generation）：`可能会在短期内对开发人员的生产力产生很大的影响，正如GitHub CoPilot所表现的那样。此外，代码生成还将使非开发人员更容易创造性地使用代码。

`图片（Images）：`是最近才出现的现象，但它们已经像病毒一样传播开来。在Twitter上分享生成的图片比文本有趣得多！我们正在看到具有不同美学风格的图像模型和用于编辑和修改生成图像的不同技术在陆续出现。

`语音合成（Speech synthesis）：`已经出现一段时间了，但消费者和企业应用才刚刚起步。对于像电影和播客这样的高端应用程序来说，听起来不机械的，具有人类质量的语音是相当高的门槛。但就像图像一样，今天的模型为进一步优化或实现应用的最终输出提供了一个起点。

`视频和3D：`其发展则远远落后，主要原因是视频和3D的数据不像图片那样容易获取，同时视频和3D模型对于算力的要求极高。人们对这些模型的潜力感到兴奋，因为它们可以打开电影、游戏、虚拟现实、建筑和实物产品设计等大型创意市场。
文字生成视频的浪潮在2022年4月兴起，在9月，Meta和Google的工作使得文字生成视频的质量得到了飞跃。其中Meta创造了基于diffusion model的 Make-a-video，而Google发布了两个模型，一个是基于diffusion model的Imagen，另一个是基于其他foundation model的Phenanki，并且Phenanki可以根据额外的信息动态调整视频。
在文字生成3D领域的主要模型为NerF，其利用深度学习完成了计算机图形学中的3D渲染任务。但作为纯隐式神经网络的NeRF确定位置的速度较慢，计算量较大，会导致画质低、变形等问题。而英伟达与斯坦福大学推出的结合了显隐式神经网络特征的EG3D模型，在速度和内存消耗上都有明显改进。Google提出的Dreamfusion模型不需要3D数据，也不需要对图像扩散模型进行修改，证明了预训练的图像扩散模型作为先验的有效性。随着技术的不断迭代，3D建模的效率逐渐提升，可以遇见，在随着元宇宙等概念、深度相机等相关基础设施、VR眼镜等消费渠道的发展，3D内容生成将成为未来内容领域的必经之路。

`生物领域：`人们于近几年开始关注 AI 和计算机辅助药物设计（CADD）在制药领域的应用，并开始尝试将其应用于实际生产中，其中在小分子制药领域使用较为成熟。AI 和 CADD 相关技术的使用帮助研发者成功缩短研发周期、寻找新的突破方向和降低研发成本，但目前还面临着数据不足、软件/学习门槛高和相关人才缺乏等障碍。除 此之外人们还希望能够在模型准确性、运算速度和算力调用的便捷性上有更多提升。

还有很多其他领域，比如从音频和音乐到化学等等，都在进行基础模型的研发。下面这张图是基本模型进展和相关应用程序成为可能的时间表，其中2025年及以后的部分只是一个猜测。

<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/204446980-4a6c8388-f539-4ee0-862a-fcd4a206abca.png"/>
</div>


### 3.2 应用程序
以下是一些让我们感到兴奋的应用，这仅仅只是一部分，实际上的应用要比我们所捕捉到的多得多，我们被创始人和开发人员所梦想的创造性应用程序所吸引。
文案（Copywriting）：越来越多的人需要个性化的网页和电子邮件内容来推动销售和营销策略以及客户支持，这是语言模型的完美应用。这些文案往往形式简单，并且都有固定的模版，加上这些团队的时间和成本压力，应该会大大推动对自动化和增强解决方案的需求。

·`直行业的写作助手（Vertical specific writing assistants）：`现在大多数写作助手都是通用型的，我们相信为特定的终端市场构建更好的生成式应用程序有着巨大机会，比如从法律合同编写到剧本编写。这里的产品差异化体现在针对特定工作流的模型和UX交互的微调。

`代码生成（Code generation）：`当前的应用程序推动了开发人员的发展，使他们的工作效率大大提高。在安装了Copilot的项目中，它生成了近40%的代码。但更大的机会可能是为C端消费者赋能编程开发能力，学习提示（learning to prompt）可能会成为最终的高级编程语言。

<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/204447045-4f7ed247-067d-473a-88b3-8b8975c13f56.png"/>
</div>


艺术生成（Art generation）：整个艺术史和流行文化的世界现在都被编码进了这些大型模型中，这将允许任何人随意探索在以前可能需要花人一辈子的时间才能掌握的主题和风格。

（1）文生图
图片数据在互联网上容易获得，文字生成图片已经是AIGC较为成熟的技术，很多图片的质量比较高，已经达到了可以商用的程度。AIGC的确极大降低了人们的创作门槛，没有经过技法训练的人现在仅凭自己的想法就能方便创造属于自己的作品，在未来这将重塑人们认知艺术的维度。不过就目前来看，其取代一些初级的画家是有可能的，但要取代真正头部的艺术家还是很难的。经过我们的了解，目前文生图发展的趋势是如何生成多轮可持续的高质量的图片，而不仅仅是在某一次生成令人眼前一亮的图片。Open AI在2022年4月迭代出的DALL-E模型使得图片生成的质量有了很大的提升。此后不久，Google研制出了一个基于diffusion model的，几乎有相同生成质量的模型Imagen。
同时，Google的Parti模型也上线了，不过采用了另外一种底层架构。Stability AI的Stable Diffusion模型自2022年发布以来便受到了持续关注，其开源的特性使得许多用户纷纷采用了它。而与DALL-E和MidJourney相比，它可以在大部分用户的硬件上跑而不是仅仅能在云端跑。而就在最近，Stable Diffusion的新版本正式发布，与初代版本相比，它在生成图片的质量和分辨率有了很大提升。
类似的软件及公司包括Big Sleep、StarryAI、WOMBO Dream。国内相关软件则包括Timmat，以及百度文心ERNIE-ViLG、小冰框架、悟道文澜、阿里M6等跨模态生成模型。


<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/204445879-58a2963c-57d3-4f41-a1d9-c7385f0a4fcb.png"/>
</div>

![11](https://user-images.githubusercontent.com/118708553/204445901-583052e8-a0e6-47c8-b324-4830642181bc.png)
![12](https://user-images.githubusercontent.com/118708553/204445939-1d59cf0b-b3df-4a71-b932-db63cb9bfefc.png)

(2)视频、3D领域
想要生成高质量的内容还有很长的路要走。我们采访过从事影视艺术的创作者，他认为目前AI能做的是部分地代替人类去做重复性的工作，但对于视频和影视创作来说，一方面，数据和算力的制约使得AI目前无法生成连贯和谐的画面，另一方面，像电影和动画这种有很多定制性需求的东西其实很难应用generate AI，因为在画面里，有太多需要控制的，比如微表情、灯光等，很难应用AI生成满意的画面。代表公司/产品方面，2C的包括百度智能视频合成平台 VidPress、慧川智能、Gliacloud、Synths.video、lumen5，2B端代表公司为Pencil。

![13](https://user-images.githubusercontent.com/118708553/204446340-92b824b3-e22e-48a6-b9ba-bf27d23b4899.png)


`游戏（Gaming）：`在这方面的梦想是使用自然语言创建复杂的场景或可操纵的模型，这个最终状态可能还有很长一段路要走，但在短期内有更直接的选择，如生成纹理和天空盒艺术（skybox art）。不过生成游戏的前提还是画面和3D/4D的建模，在这方面的差距目前还是很大。而另一种思路是WEB3.0阶段利用社群，使得大家能够贡献自己的GPU、创意、玩法等。目前的代表机构是腾讯 AI Lab（腾讯”绝悟“），其AI通过强化学习的方法来模仿真实玩家，包括发育、运营、协作等指标类别，以及每分钟手速、技能释放频率、命中率、击杀数等具体参数，让AI更接近正式服玩家真实表现，将测试的总体准确性提升到95%。同时还有超参数这家公司，该公司估值已达独角兽，业内率先实现在3D FPS（游戏的帧数）领域的大规模商业化落地，服务对象包括数款千万级日活的游戏产品。rct AI也是杰出的代表，其属于业内较为少见的可以在逻辑侧进行AI生成开发的公司，其核心产品包括个性化且动态的剧情探索、智能NPC/ AI MetaBeings/ 智能环境 ，提供真人般的游戏对抗体验。

`媒体/广告（Media/Advertising）：`想象一下自动化代理工作的潜力，为消费者实时优化广告文案和创意。多模态生成的绝佳机会是将销售信息与互补的视觉效果结合起来。

`虚拟人生成（Virtual human generation）：`虚拟人生成代表着从文本/音频等低密度模态向图像/视频/实时交互等信息密度更高的模态 的转化。其中，视频是短期的发展重点，而长期来看，乃至在元宇宙阶段，通过实时交互成为社交节点，都将是虚拟人重要的应用场景。代表公司有HourOne.ai、Synthesia、Rephrase.ai、小冰公司、倒映有声、数字王国、影谱科技、科大讯飞、相芯科技、追一科技、网易伏羲、火山引擎、百度、搜狗等。

`设计（Design）：`设计数字和实物产品的原型是一个劳动密集型的迭代过程，AI根据粗略的草图和提示来制作高保真的效果图已经成为现实。随着3D模型的出现，生成设计的过程将从制造和生产延伸到实物，你的下一个iPhone APP或运动鞋可能是由机器设计的。

`社交媒体和数字社区（Social media and digital communities）：`是否存在使用生成工具表达自我的新方式？随着Midjourney等新应用学会了像人类一样在社交网络上创作，这将创造新的社交体验。

一个不完全统计，从图像到语言、以及音乐和其他，市面上叫得出名号的产品已让人眼花缭乱。

![14](https://user-images.githubusercontent.com/118708553/204447184-93498c57-8d65-4644-af35-8ee0fc762b74.png)


美国具有代表性的公司
（1）Open AI：是一个人工智能（AI）研究实验室，由营利组织 OpenAI LP 与母公司非营利组织 OpenAI Inc 所组成，目的是促进和发展友好的人工智能，使人类整体受益。Open AI目前估值超过200亿美金。

（2）Midjourney：7 月 12 日公测，8 月已经盈利，用户用 Discord 机器人命令通过 Midjourney 来创建艺术品，团队由 Leap Motion 的联合创始人 David Holz 领导，商业模式是使用免费增值业务模式。

（3）Jasper.AI：利用人工智能为博客文章、社交媒体帖子及网页等平台生成文字内容。估值超过15亿美元，由Rogenmoser与摩根大通和Chris Hull于去年年初共同创立。Rogenmoser和Chris此前曾是Y Combinator的校友。

（4）Stability.AI：英国公司，创始人是前对冲基金经理。与 OpenAI 不同，其利用开源 AI 技术，这也是他向客户和投资者推销的重点。8 月，该公司融种子轮时估值为 1 个亿，9 月跃升为 5 亿，10月17日，宣布公司估值为 10 个亿。两个月内估值从 1 亿跃升到了 10 亿美金。

（5）Google/Meta/Microsoft：纷纷推出了AIGC的相关模型，正在进行商业化。

<div align=center>

|代表公司|大模型|跨模态|文本|图像|视频和3D|代码|游戏|生物|语音|
|:-----:|:----:|:---:|:--:|:--:|:-----:|:--:|:--:|:--:|:--:|
|Open AI|     |  CLIP    |GPT1/GPT2/GPT3 均开源|DALL-E/DALL-E2||Codex 未开源|Gym Retro/Open AI five| | |
|Stability AI||CLIP||Stable Diffusion/Stable Diffusion2 均开源||||||
|DeepMind|Chinchilla/Gato|Flamingo/NFNets/Preceirver||||Alpha Code|Alpha Star|Alpha Fold|WaveNet|
|Google|BERT／T5||LaMDA/PALM|Imagen/Parti/Dreambooth|Imagen Video/Phenaki|||||
|Meta|AV-HuBERT/Data2vec／OPT-175B||XLS-R||Make-a-Video|||语言模型||
|Nvidia|PoE GAN/Megatron||||Omniverse/Magic 3D||||||
|Microsoft|||GPT-4/Apache Spark/NÜWA||NÜWA|NÜWA||||
|Jasper.AI|||GPT-3|DALL-E2||||||
|Midjourney||CLIP|Stble Diffusion||

</div>

四、生成式AI解析
---
生成式AI应用程序会是什么样子？以下是一些预测：

### 4.1 智能和模型微调
生成式AI应用是建立在GPT-3或Stable Diffusion等大型模型之上的，随着这些应用获得更多的用户数据，它们可以对模型进行微调，一方面针对特定的问题空间改进模型质量和性能，另外一方面减少模型的大小和成本。

我们可以把生成式AI应用看作`一个UI层和位于大型通用模型“大大脑（big brain）”之上的“小大脑（little brain）”。`

### 4.2 形成的因素
如今，生成式AI应用在很大程度上以插件的形式存在于现有的软件生态系统中。比如代码生成在你的IDE中，图像生成在Figma或Photoshop中，甚至Discord机器人也是将生成AI放在数字社交社区里的工具。
还有少量独立的生成式AI Web应用，如在文案方面有Jasper和Copy.ai，在视频剪辑方面有Runway，在做笔记方面有Mem。
`插件的形式可能是生成式AI应用在早期比较好的切入点`，它可以克服用户数据和模型质量方面面临的“先有鸡还是先有蛋”的问题(这里具体指的是：一方面需要分发来获得足够多的使用数据，从而来改进模型，另外一方面又需要好的模型来吸引用户)。我们已经看到这种策略在其他市场类别中取得了成功，如消费者和社交市场。

### 4.3 交互范式
如今，大多数生成式AI演示都是“一次性”的：你提供一个输入，机器吐出一个输出，你可以保留它或扔掉它，然后再试一次。未来，模型将会`支持迭代`，你可以使用输出来修改、调整、升级和生成变化。
如今，生成式AI输出被用作原型或初稿。应用程序非常擅长抛出多个不同的想法，以使创作过程继续(比如一个logo或建筑设计的不同选项)，它们也非常擅长给出初稿，但需要用户最终润色来定稿(比如博客帖子或代码自动完成)。随着模型变得越来越智能，同时部分借助于用户数据，我们应该期待这些草稿会变得越来越好，直到它们足够好，`可以用作最终产品。`

### 4.4 持续的行业领导力
最好的生成式AI公司可以通过在用户粘性、数据和模型性能之间形成的飞轮来产生可持续的竞争优势。为了取得胜利，团队必须通过以下方法来实现这个飞轮:

`拥有出色的用户粘性→将更多的用户粘性转化为更好的模型性能(及时改进、模型微调、把用户选择作为标记训练数据)→使用出色的模型性能来推动更多的用户增长和留存。`

他们可能会专注于特定的领域(如代码、设计和游戏)，而不是试图解决所有人的问题。他们可能首先将深度集成到现有的应用程序中，以便在此基础上利用和分发自己的程序，然后尝试用AI原生工作流替换现有的应用程序。用正确的方式构建这些应用来积累用户和数据是需要时间的，但我们相信最好的应用将会是持久的，并有机会变得庞大。

五、中国的AIGC
---
目前国内的AIGC企业没有一线的VC投，做不出能够媲美Open.AI的公司。通过我们和海内外从事AIGC业务的工作人员的访谈，总结出以下原因：
（1）中国厂商投入不够。企业层面做AIGC的主要是中国的大厂，例如百度、华为等，这些企业目前主要考虑的如何降本增效，AIGC业务需要各部门的协调，而各部门由于竞争关系导致内耗较多，因此在这块业务投入不多。而代表政府的机构，如北京智源研究院，其投入约为10亿元，而Open.AI的累计投入超过20亿美元。

（2）科学家和人才密度不够。中国缺少做AIGC方向的顶级学者，同时人才交叉密度也和美国相比有较大差距。在美国，例如Deepmind.AI 研发团队超过800人，各个学科的PHD都有。而国内缺乏AI的领军人物，有一定知名度的学者也大都不写论文不带人才了。同时中国的人才交叉密度目前仍不足。最后在创业领域，据我们了解，中国做Nerf和diffusion model的科学家有一波人出来创业了，但是他们普遍缺乏对产品的思考，而目前拥有产品管理经验的人缺少技术，因此如果能将二者结合到一起会是一个好的机会。
数据和算力。中国的AIGC生态没有搭建起来，很多API都没有开源出去，因此获得的数据相比已经开源的Open.AI和Stability等公司会减少很多。同时中国企业的算力与美国也有差距，像智源等公司用于训练大模型的芯片和显卡数量都很有限。

（3）资本的耐心。中国的资本比较缺乏耐心，会要求被投企业很快有回报。但AIGC需要投入很多研发成本，需要很多模型和算法的迭代与优化，发论文在资本眼里是不make sense的。

基于此，中国的AIGC有很大的发展潜力，值得资本的关注。

北京智源研究院：北京智源人工智能研究院（Beijing Academy of Artificial Intelligence，BAAI）是人工智能领域的新型研发机构。2018年11月14日在科技部和北京市支持下，依托北京大学、清华大学、中国科学院、百度、小米、字节跳动、美团点评、旷视科技等北京人工智能领域优势单位共建的新型研究机构。
智谱华章：简称智谱AI，成立于2019年，由清华大学计算机系知识工程实验室的技术成果转化而来，于9月获得数亿元人民币的B轮融资。

小冰公司：小冰公司作为微软全球首个以中国为总部的人工智能产品线，相关领先技术覆盖自然语言处理、计算机语音、计算机视觉和人工智能内容生成等人工智能领域，估值目前约20亿美元。

百度：目前是国内做大模型做的最好的。

<div align=center>

|代表公司|文本|图像|语音|视频和3D|代码|生物|
|:-----:|:---:|:--:|:--:|:-----:|:--:|:--:|
|华为|盘古|盘古||DNN|CodeGeeX|盘古|
|百度|ERNIE-M/ERNIE 3.0/PLATO/ERNIE-IE|VIMER-Image|ERNIE-ViLG/ERNIE-FAT|VIMER-Video||GEM|
|北京智源人工智能研究所|悟道 文渊/悟道 文汇 全部开源|悟道 文澜/AltDiffusion|悟道2.0 开源|||悟道 文溯 开源|
|智谱华章|GLM-130B|||||||
|小冰公司|第九代小冰|||||||
|阿里巴巴|M6／PLUG|M6|LC-BLSTM／DFSMN-CTC||||
|腾讯|混元|||混元|
|字节跳动|veGiantModel/X2-VLM|
|IDEA|二郎神/周文王/燃灯/闻仲|太乙 Stable Diffusion|||||
|西湖心辰|ALBERT|改进的Stable Diffusion|
|澜舟科技|孟子|孟子|

</div>
应用层面：

<div align=center>
  
|项目|方向|GO to market|
|:--:|:--:|:--:|
|秘塔|文本编辑|C端/B端|
|澜舟科技|文字生成|学生/文字工作者/2B品牌|
|FridayAI|文字生成|2B品牌+文字工作者|
|写作猫|文字生成|学生/媒体工作者|
|Gliso写作机器人|文字生成|学生/文字工作者|
|Get写作|文字生成|学生/文字工作者|
|写作狐|文字生成|学生/文字工作者|
|沃沃AI人工智能写作|文字生成|学生/媒体工作者/作家|
|6 pen|文生图|创作者/大学生|
|ZMO|文生图|创作者/电商|
|万兴AI绘画|文生图|创作者+社区|
|中文在线|文生图|创作者|
|机画师|文生图|创作者|
|聆心智能|AI陪伴/小说攥写|抑郁症患者/文案创作者|
|mixlab无界社区|AIGC社区|创作者|
|ERNIE-ViLG|文生图|创作者|
|ClueAI.art（配图师）|文生图|创作者|
|文心一格|文生图|创作者＋2B品牌|
|MuseArt|文生图|创作者＋社区|
|大画家Domo|文生图|创作者＋社区|
|意见AI绘画|文生图|创作者＋社区|
|洞天数藏|文生图|创作者+2B品牌|
|百度文心 ERNIE-ViLG|文生图|创作者|
|盗梦师|文生图|创作者+社区/2B品牌|
|Tiamat|文生图|2B品牌+社区|
|Enlight|文生图|2B品牌|
|猴子无限|文生图|2B品牌|
|郑文团队|文生图|创作者|
|Nolibox|文生图|创作者|
|无界版图|文生图|创作者|
|ZCool|文生图|创作者|
|VCG AILab|图生图|创作者|
|阿里鹿班|图生图|创作者＋电商＋2B品牌|
|诗云科技|图生图|创作者＋电商＋2B品牌|
|道子智能绘画系统|图生图|创作者|
|思必驰|文生音频|2B品牌|
|九锤配音|文生音频|创作者|
|加音|文生音频|创作者|
|剪映|文生音频|创作者|
|XAudioPro|文生视频|创作者|
|右脑科技|文生视频|创作者+2B品牌|
|百度智能视频合成平台VidPress|文生视频|创作者|
|慧川智能|文生视频|创作者/媒体工作者|
|Gliacloud|文生视频|创作者|
|Pencil|文生视频|2B品牌|
|彩云小梦|文字/对话|创作者/游戏开发|
|超参数|AI Bot|游戏玩家+2B品牌|
|腾讯AI Lab|AI Bot|游戏玩家+2B品牌|
|rct AI|NPC逻辑自动生成|游戏玩家+2B品牌|
|AI美甲生成器|AI美甲|C端|
|Laxis|会议助手|B端/C端|
|AIFashions|AI数字服装|创作者+2B品牌|
|Kua.ai|AIGC+DAM|2B品牌+C端|

  
</div>



六、困难和挑战
---
尽管生成式AI具有巨大的潜力，但在商业模式和技术方面仍有许多问题需要解决。比如`版权、信任、安全和成本`等重要问题还亟待解决。人工智能伦理：安全与自由.
2022 年出现的最大辩论是安全与自由之间的矛盾。人工智能应该交给大众随心所欲地使用，还是为了安全而需要一个监管方？像 OpenAI 这样的公司认为，必须有一个 gatekeeper 来保护社会免受人工智能的潜在不良影响,OpenAI 把自己的模型围起来，用户需要申请，才能使用，直到最近。OpenAI 被批评为有选择地确定访问权限，以及它的一些审查决定。OpenAI 认为，这些措施对于防止人工智能被滥用非常重要。
另一方面，像 Stability 这样的公司，把自己比作普罗米修斯给人类带来的火种。Stability 认为，虽然人工智能可能是危险的，但对社会来说，允许一个未经选
举的 gatekeeper 控制谁可以使用该技术以及如何使用，更危险。Stability 认为，技术被滥用是不可避免的，政府的适当角色是规范使用，而不是限制使用。对于人工智能领域的领军人物来说，AI 技术的伦理和社会影响是他们工作的驱动力。OpenAI 的明确自己的使命是为了人类而推进人工智能发展，OpenAI的首席执行官，兼联合创始人 Sam Altman，提到过，AI 的社会影响也是驱动他前行的主要动力。Stablility AI 的创始人 Emad Mostaque 在开始使用人工智能技术研究自闭症时，开始对人工智能感到兴奋，他坚信人工智能将成为贫困国家教育儿童阅读和写作的关键。
当然，鉴于人工智能的优势和弊端，基于这些的讨论才刚刚开始。

为了领先于这些 "和人类相关的伦理问题"，已经有人工智能公司正在雇用内部法律团队，开始思考道德层面的政策和考量。HuggingFace 聘请了 Margaret
Mitchell 作为其首席伦理科学家。哈佛大学的高级研究员 Joaquin Candela领导了 Facebook 的“负责任的 AI 人工智能”。为人工智能建立一个强大的法律
和监管框架对于长期应用人工智能至关重要，这需要公共和企业部门领袖之间的合作。

人工智能会抢走人类的工作吗？
在人工智能领域经常被问到的第二个 "大问题 "是 "人工智能会夺走我的工作吗？" 很长时间以来，人们相信人工智能会取代人类的手工劳动。令人惊讶的是，第一个发展起来的人工智能应用，针对的是艺术等创造性工作，而不是像呼叫中心自动化这样更普通的任务。但这些应用案例也引发了争议，包
括艺术家的反击，他们认为用人工智能生成艺术是 "作弊"。当涉及到知识工作时，我们希望人工智能成为一种补充技术，赋予现有工人权力，
而不是完全取代他们的工作。例如，Gong 使用人工智能为销售代表提供超强支持。据该公司称，Gong 帮助销售代表节省了 20%的时间，每个销售代表的收入增加了 27%。像 PhotoRoom 这样帮助电子商务商家快速编辑产品照片的公司，因为减少了繁琐的工作而获得了很多零售商的青睐。对于制造业、建筑业和呼叫中心等行业来说，人工智能可能是应对人口老龄化挑战的一个重要解决方案。美国今天严重的劳动力短缺，因 COVID-19 而加剧，是人工智能可以帮助解决的另一个紧迫问题。正如英伟达 CEO 在 2018 年Coatue 会议上指出的那样，人工智能的最大优势可能是将富裕世界的经济体从其人口命运中拯救出来。这种观点在今天很流行，因为美国在关键行业挣扎于劳
动力短缺，这可能是支持人工智能兴奋度回升的又一个因素。

人工智能已经在成为广泛应用的助手型工具，这也可能是它在推动广泛共享的生
产力改进方面的早期契机。如果 GitHub Copilot 通过编写 40%的代码加速了软件工程师的工作，那么它能为其他人做什么？我们每天遇到的许多新的公司都在研究如何将这种模式应用于各种不同场景的工作，从安装太阳能板（AuroraSolar）到维护能源网（Weavegrid）

互联网并没有提高人类的生产力，那么，人工智能呢？

七、未来会发生什么
---
随着深度学习和基础模型的兴起，我们已经跨越了人工智能旅程中的另一道鸿沟。 就在过去的几个月里，我们看到了人工智能应用的寒武纪爆炸，从它们在博客文章和艺术中的应用到电影等等。 随着人工智能离开研究实验室，进入现实世界，更多的东西正在到来。未来几年，人工智能将改变众多垂直行业的许多业务。我们将看到好莱坞、农业，以及两者之间的一切变化。人工智能的机会是巨大的。它有望实现实体经济的自动化，推动人类生产力的阶梯式提高。它还承诺了一个新的创造性的飞跃，人工智能艺术提供了一个探索人类经验本身的新途径。还有这么多工作要做。我们正处于人工智能革命的第一波。规模化运行的机器学习、个性化的模型、多元宇宙--还有很多事情要做。最聪明的人正在引领潮流，他们建立的新公司将定义未来十年及以后的发展。 



