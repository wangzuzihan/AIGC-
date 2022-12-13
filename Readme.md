#生成式AI行研


一、导语
---
人类擅长分析事物，而机器在这方面甚至做得就更好了。机器可以分析一组数据，并在其中找到许多用例（use case）的模式，无论是欺诈还是垃圾邮件检测，预测你的发货时间或预测该给你看哪个TikTok视频，它们在这些任务中变得越来越聪明。这被称为“分析型AI（Analytical AI）”，或传统AI。
但是人类不仅擅长分析事物，我们也擅长创造。我们写诗，设计产品，制作游戏，编写代码。直到最近，机器还没有机会在创造性工作上与人类竞争——它们被降格为只做分析和机械性的认知工作。但最近，机器开始尝试创造有意义和美丽的东西，这个新类别被称为“生成式AI（Generative AI）”，这意味着机器正在生成新的东西，而不是分析已经存在的东西。

生成式AI正在变得不仅更快、更便宜，而且在某些情况下比人类创造的更好。从社交媒体到游戏，从广告到建筑，从编程到平面设计，从产品设计到法律，从市场营销到销售，每一个原来需要人类创作的行业都等待着被机器重新创造。某些功能可能完全被生成式AI取代，而其他功能则更有可能在人与机器之间紧密迭代的创作周期中蓬勃发展。但生成式AI应该在广泛的终端市场上解锁更好、更快、更便宜的创作。人们期待的梦想是：生成式AI将创造和知识工作的边际成本降至零，产生巨大的劳动生产率和经济价值，以及相应的市值。

生成式AI可以处理的领域包括了知识工作和创造性工作，而这涉及到数十亿的人工劳动力。生成式AI可以使这些人工的效率和创造力至少提高10%，它们不仅变得更快和更高效，而且比以前更有能力。因此，生成式AI有潜力产生数万亿美元的经济价值。

二、Why Now
---
生成式AI与更广泛的AI有着相同的“为什么是现在（Why now）”的原因：更好的模型，更多的数据，更多的算力。这个类别的变化速度比我们所能捕捉到的要快，但我们有必要在大背景下回顾一下最近的历史。

<b>第1波浪潮：小模型（small models）占主导地位（2015年前），</b>小模型在理解语言方面被认为是“最先进的”。这些小模型擅长于分析任务，可以用于从交货时间预测到欺诈分类等工作。但是，对于通用生成任务，它们的表达能力不够。生成媲美人类的写作或代码仍然是一个白日梦。
<b>第2波浪潮：规模竞赛（2015年-至今），</b>Google Research的一篇里程碑式的论文 Attention is All You Need https://arxiv.org/abs/1706.03762 描述了一种用于自然语言理解的新的神经网络架构，称为transformer，它可以生成高质量的语言模型，同时具有更强的并行性，需要的训练时间更少，应用范围也更加广泛，可以相对容易地在各领域进行定制。

<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/204441856-b1ee2d36-e6c5-490f-b6eb-c208527ade45.PNG"/>
</div>

<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/204441993-dea0d467-e0f8-4a0c-851d-f014746c1a75.JPEG"/>
</div>


随着模型越来越大，它们开始可以输出达到人类水平的结果，然后是超人的结果。从2015年到2020年，用于训练这些模型的计算量增加了6个数量级，其结果在书写、语音、图像识别、阅读和语言理解方面超过了人类的表现水平。OpenAI的GPT-3表现尤其突出：该模型的性能比GPT-2有了巨大的飞跃，并且从代码生成到笑话编写的任务中都提供了出色的Twitter demo来证明。据我们了解，就在最近，Open AI已经迭代出了GPT-4，其在提升多轮长对话的表现方面有了更加出色的表现。

尽管所有的基础研究都取得了进展，但这些模型并不普遍。它们庞大且难以运行(需要特别的GPU配置)，不能被更多人广泛触达使用(不可用或只进行封闭测试)，而且作为云服务使用成本昂贵。尽管存在这些限制，最早的生成式AI应用程序也已经开始进入竞争。

![3](https://user-images.githubusercontent.com/118708553/204442080-e7fe54b5-7993-49fa-82bc-1f4c29e69c4f.PNG)


<b>第3波浪潮：更好、更快和更便宜（2022+），</b>算力变得更便宜，新技术，如扩散模型（diffusion models），降低了训练和运行所需的成本。研究人员继续开发更好的算法和更大的模型。开发人员的访问权限从封闭测试扩展到开放测试，或者在某些情况下扩展到开源。

![4](https://user-images.githubusercontent.com/118708553/204442399-fb58a127-73e2-40cb-a95c-f2072bcb0bf9.JPEG)

对于那些渴望接触LLMs（Large Language Model 大语言模型）的开发人员来说，探索和应用开发的闸门现在已经打开，应用开始大量涌现。

<b>第4波浪潮：杀手级应用出现（现在），</b>随着平台层的稳固，模型继续变得更好、更快和更便宜，模型的获取趋于免费和开源，应用层的创造力已经成熟。

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
<b>文本（Text）：</b>是目前技术最成熟的领域，以GPT-3为例，其文本生成能力已被直接应用于Writesonic、 Conversion.ai、 Snazzy AI、 Copysmith、 Copy.ai等文本写作/编辑工具中。另一方面，以transformer架构为重要代表，相关的底层架构仍在不断精进。如今，这些模型在一般的中短篇形式的写作中相当出色(但即便如此，它们通常用于迭代或初稿)。而对话则为文本的另一重要发展方向，基于RLHF+优化的模型架构的ChatGPT能力确实有些夸张。随着GPT-4的出现，新版的ChatGPT更加值得我们期待。

<b>代码生成（Code generation）：</b>可能会在短期内对开发人员的生产力产生很大的影响，正如GitHub CoPilot所表现的那样。此外，代码生成还将使非开发人员更容易创造性地使用代码。

<b>图片（Images）：</b>图片生成的竞争正变得愈演愈烈。以diffusion模型为基础的MidJourney、Stable Diffusion、Stable Diffusion2等应用和模型均可以快速产生质量足以达到商用的图片。图片生成将极大提升创作者的效率，成为解放生产力的重要工具。

<b>语音合成（Speech synthesis）：</b>已经出现一段时间了，但消费者和企业应用才刚刚起步。对于像电影和播客这样的高端应用程序来说，听起来不机械的，具有人类质量的语音是相当高的门槛。但就像图像一样，今天的模型为进一步优化或实现应用的最终输出提供了一个起点。

<b>视频：</b>其发展则远远落后，主要原因是视频和3D的数据不像图片那样容易获取，同时视频和3D模型对算力的要求极高。人们对这些模型的潜力感到兴奋，因为它们可以打开电影、游戏、虚拟现实、建筑和实物产品设计等大型创意市场。文字生成视频的浪潮在2022年4月兴起，在9月，Meta和Google的工作使得文字生成视频的质量得到了飞跃。其中Meta创造了基于Diffusion model的 Make-a-video，而Google发布了两个模型，一个是基于diffusion model的Imagen，另一个是基于其他foundation model的Phenanki，并且Phenanki可以根据额外的信息动态调整视频。


<b>3D：</b>其发展和视频一样处于较为落后的阶段，数据的收集、如何建模都是难题。3D生成领域一直以来的主流模型为NeRF，其利用深度学习完成了计算机图形学中的3D渲染任务。之后，Google的Dream Fusion和Nvidia的Magic 3D则以Diffusion模型为框架，优化了NeRF，使其从随机角度的二维渲染损失降低。而后者更是全面超越Dreamfusion，其生成3D模型的速度是Dream Fusion的2倍，3D效果也比Dream Fusion好，分辨率是后者的8倍。

<b>生物领域：</b>人们于近几年开始关注 AI 和计算机辅助药物设计（CADD）在制药领域的应用，并开始尝试将其应用于实际生产中，其中在小分子制药领域使用较为成熟。AI 和 CADD 相关技术的使用帮助研发者成功缩短研发周期、寻找新的突破方向和降低研发成本，但目前还面临着数据不足、软件/学习门槛高和相关人才缺乏等障碍。除此之外人们还希望能够在模型准确性、运算速度和算力调用的便捷性上有更多提升。

还有很多其他领域，比如从音频和音乐到化学等等，都在进行基础模型的研发。下面这张图是基本模型进展和相关应用程序成为可能的时间表，其中2025年及以后的部分只是一个猜测。

<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/204446980-4a6c8388-f539-4ee0-862a-fcd4a206abca.png"/>
</div>


### 3.2 应用程序
以下是一些让我们感到兴奋的应用，这仅仅只是一部分，实际上的应用要比我们所捕捉到的多得多，我们被创始人和开发人员所梦想的创造性应用程序所吸引。

<b> 文案（Copywriting）：</b>越来越多的人需要个性化的网页和电子邮件内容来推动销售和营销策略以及客户支持，这是语言模型的完美应用。这些文案往往形式简单，并且都有固定的模版，加上这些团队的时间和成本压力，应该会大大推动对自动化和增强解决方案的需求。

<b> 垂直行业的写作助手（Vertical specific writing assistants）：</b>现在大多数写作助手都是通用型的，我们相信为特定的终端市场构建更好的生成式应用程序有着巨大机会，比如从法律合同编写到剧本编写。这里的产品差异化体现在针对特定工作流的模型和UX交互的微调。

<b> 代码生成（Code generation）：</b>当前的应用程序推动了开发人员的发展，使他们的工作效率大大提高。在安装了Copilot的项目中，它生成了近40%的代码。但更大的机会可能是为C端消费者赋能编程开发能力，学习提示（learning to prompt）可能会成为最终的高级编程语言。

<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/204447045-4f7ed247-067d-473a-88b3-8b8975c13f56.png"/>
</div>


<b> 艺术生成（Art generation）：</b>整个艺术史和流行文化的世界现在都被编码进了这些大型模型中，这将允许任何人随意探索在以前可能需要花人一辈子的时间才能掌握的主题和风格。

（1） 文生图
AIGC极大降低了人们的创作门槛，没有经过技法训练的人现在仅凭自己的想法就能方便创造属于自己的作品，在未来这将重塑人们认知艺术的维度。就目前来看，文生图的市场前景广阔的，国内的盗梦师上线一周便有20万用户注册，国外的MidJourney及Dream Studio已经打造了很好的社区文化。经过我们的了解，目前文生图的壁垒是数据和算力，未来发展的方向是是如何生成多轮高质量的图片，而不仅仅是在某一次生成令人眼前一亮的作品。


<div align=center>
<img src="https://user-images.githubusercontent.com/118708553/204445879-58a2963c-57d3-4f41-a1d9-c7385f0a4fcb.png"/>
</div>

![11](https://user-images.githubusercontent.com/118708553/204445901-583052e8-a0e6-47c8-b324-4830642181bc.png)
![12](https://user-images.githubusercontent.com/118708553/204445939-1d59cf0b-b3df-4a71-b932-db63cb9bfefc.png)

 (2) 视频、3D领域
想要生成高质量的内容还有很长的路要走。我们采访过从事影视艺术的创作者，他们认为目前AI能做的是部分地代替人类去做重复性的工作，但对于视频和影视创作来说，一方面，数据和算力的制约使得AI目前无法生成连贯和谐的画面，另一方面，像电影和动画这种有很多定制性需求的东西其实很难应用generate AI，因为在画面里，有太多需要控制的，比如微表情、灯光等，很难应用AI生成满意的画面。

![13](https://user-images.githubusercontent.com/118708553/204446340-92b824b3-e22e-48a6-b9ba-bf27d23b4899.png)


<b>游戏（Gaming）：</b>在这方面的梦想是使用自然语言创建复杂的场景或可操纵的模型，这个最终状态可能还有很长一段路要走，但在短期内有更直接的选择，如生成纹理和天空盒艺术（skybox art）。不过生成游戏的前提还是画面和3D/4D的建模，在这方面的差距目前还是很大。而另一种思路是WEB3.0阶段利用社群，使得大家能够贡献自己的GPU、创意、玩法等。更详细的信息可以参考：https://a16z.com/2022/11/17/the-generative-ai-revolution-in-games

<b> 媒体/广告（Media/Advertising）：</b>想象一下自动化代理工作的潜力，为消费者实时优化广告文案和创意。多模态生成的绝佳机会是将销售信息与互补的视觉效果结合起来。

<b> 虚拟人生成（Virtual human generation）：</b>虚拟人生成代表着从文本/音频等低密度模态向图像/视频/实时交互等信息密度更高的模态 的转化。其中，视频是短期的发展重点，而长期来看，乃至在元宇宙阶段，通过实时交互成为社交节点，都将是虚拟人重要的应用场景。

<b> 设计（Design）：</b>设计数字和实物产品的原型是一个劳动密集型的迭代过程，AI根据粗略的草图和提示来制作高保真的效果图已经成为现实。随着3D模型的出现，生成设计的过程将从制造和生产延伸到实物，你的下一个iPhone APP或运动鞋可能是由机器设计的。

<b> 社交媒体和数字社区（Social media and digital communities）：</b>是否存在使用生成工具表达自我的新方式？随着Midjourney等新应用学会了像人类一样在社交网络上创作，这将创造新的社交体验。

一个不完全统计，从图像到语言、以及音乐和其他，市面上叫得出名号的产品已让人眼花缭乱。

![14](https://user-images.githubusercontent.com/118708553/204447184-93498c57-8d65-4644-af35-8ee0fc762b74.png)

接下来将对几个领域的代表性公司进行梳理：

<b>编程语言:</b>

<b>文本领域最成熟的应用暂时不在人类自然语言，而是在代码等机器语言的生成领域。</b>因为机器语言相对更结构化，易学习；比如鲜有长文本的上下文关系、基于语境的不同含义等情况。

（1）代码生成：Github Copilot

代表公司是微软出品的 Github Copilot，编程中的副驾驶。该产品基于 OpenAI 专门用 GPT-3 为编程场景定制的 AI 模型 Codex。使用者文字输入代码逻辑，它能快速理解，根据海量开源代码生成造好的轮子供开发者使用。提高一家科技公司 10% 的 coding 效率能带来很大收益，微软内部已进行推广使用。
相比低代码工具，Copilot 的目标群体是代码工作者。未来的低代码可能是两者结合：低代码 UI 界面实现代码框架搭建，代码子模块通过 Copilot 自动生成。
正如 Copilot 的 slogan：Don't fly solo，没有 Copilot 的帮助 coder 的工作会变得繁冗，没有 coder 的指引 Copilot 生成的内容可能会出现纰漏。也有用户报告了一些侵犯代码版权、或代码泄露的案例，当前技术进步快于版权法规产生了一定的空白。

（2）软件行为生成：Adept.ai

Adept.ai 是一家明星创业公司。创始团队中有两人是 Transformer 模型论文作者，CEO 是谷歌大脑中大模型的技术负责人，它目前的估值已经达到了15亿美元。他们的主要产品是大模型 ACT-1，让算法理解人类语言并使机器自动执行任务。目前产品形态是个 chrome 插件，用户输入一句话，能实现单击、输入、滚动屏幕行文。在展示 demo 中，一位客服让浏览器中自动记录下与某位顾客的电话，正在考虑买 100 个产品。这个任务需要点击 10 次以上，但通过 ACT-1 一句话就能完成。软件行为生成颠覆的是当下的人机交互形式，使用文字或语音的自然语言形式来代替当下人与机器的图形交互模式（GUI）。大模型成熟后，人们使用搜索引擎、生产力工具的方式都将变得截然不同。

<b>自然语言</b>

自然语言下还有多个应用型文本生成领域值得关注：新闻撰写、文案创作、对话机器人等。

（1）新闻撰写：Automated Inights

他们的结构化数据新闻撰写工具叫做 wordsmith，通过输入相应数据和优先级排序，能产出一篇基于数据的新闻报道。该工具已在为美联社每季度自动化产出 300 余篇财报相关报道，在雅虎体育新闻中也已经崭露头角。据分析师评价，由 AI 完成的新闻初稿已接近人类记者在 30 分钟内完成的报道水准。Narrative Science 是另一家新闻撰写生成公司，其创始人甚至曾预测，到 2030 年，90% 以上的新闻将由机器人完成。

（2）文案创作：copy.ai、Jasper、copysmith

该领域竞争较为激烈，有 copy.ai、Jasper、copysmith 等公司。他们基于 GPT-3 的能力加入了文案领域的人工模板与结构，为商家和个人创作者提供了快速为自己的商品、内容进行宣传的能力。

（3）对话机器人：Character.ai

Transformer的二作创办的 Character.ai 是当前对话机器人中使用效果最逼真的。该对话机器人可以自定义或使用模板来定义角色的家庭、职业、年龄等，在此基础上保持一贯的设定和符合设定的对话风格。经常能体现出一定的共情对话能力带给人惊喜，并且支持多语言互通。比如他们有已训练好的马斯克等名人和一些动漫角色，与他们对话会有很棒的代入感。而商业化的对话机器人，在客服、销售等行业有巨大的市场空间，但如今还为成熟。主要出现的问题有二：其一，客服、销售行业遇到的客户往往情绪状态不稳定，AI 难以对情绪进行适应并调整对话内容；其二，AI 的多轮对话能力较弱，无法保证持续有效的跟进问题。

（4） 创作性文本：Open.ai

AI 对于长文本创作有一定困难，难以保持 1000 字以上的文本创作后仍能进行上下文的联系。但基于短文本创作仍有一些有趣的应用，例如基于 GPT-3 的 AI Dungeon，可以引导 AI 创造一个虚拟游戏世界观。最近风靡全球的Open.ai的ChatGPT在创作型文本上的表现着实令人称叹，你可以让它写诗，写小说，写剧本！Open.ai在语言模型方面的工作令人赞叹，相信随着GPT4的发布，它还会给我们带来更多新奇的体验。

<b>图片生成</b>

（1）Disco Diffusion

最早出圈的 AI 绘图工具是开源模型Disco Diffusion。发布时间比 DALL·E 2 稍晚，同样也是 CLIP + Diffusion Model 的结构，生成效果让许多插画师担心起了失业。尽管很多插画师和 AI 工具爱好者的推荐都认可了该工具的易用性和生成效果的出众，但其生成时间略长有待优化，可以认为是大家对图片生成大模型的初体验。

（2）MidJourney

该模型发布后不久，Disco Diffusion 的开发者 Somnai 加入了 MidJourney，和团队一起打造了一款产品化的 Disco Diffusion。Midjourney 的创始人  David Holz 并不是以 CV（计算机视觉）研究为主，更关注人机交互。产品公测和主要交流平台都基于 Discord，使用 Discord Bot 进行交互，打造了相当良好的社区讨论环境。使用中印象深刻的有几个重要功能：MidJourney 画廊中可以看到每时每刻创作者们用 MJ 创作出的作品，用户可以对作品进行打分，每周排名靠前的作品将得到额外的 fast GPU 时间奖励。同时，MJ 官方还为用户贴心的提供了引导语 prompt 集合和 AI 擅长的风格指南，指导用户如何最高效的生成出他们想要的图片。
基于良好的产品和社区体验，MidJourney 的付费用户量也是目前最大的。目前收费模式采用了订阅制，个人用户有两个档位，每月最多 200 张图片（超额另收费）的 10 美元 / 月，以及“不限量”图片的 30 美元 / 月；对企业客户，单人一年收费仅有 600 美元，且生成的作品可以商用（当前法规尚不完善，仍可能存在一定版权问题）。

（3）Stability.ai

如果说 MidJourney 是一个勤勤恳恳的绩优生，那么 Stability.ai 则是天赋异禀技术力强、诞生之初就备受 VC 追捧的富二代，公司估值已达到十亿美元。产品 Stable Diffusion 首要目标是一个开源共创模型，与当年的 Hugging Face 神似。
创始人 Emad 之前是对冲基金经理，用自己充裕的资金联合 LMU 和 Runaway ML 开发了开源的 Stable Diffusion，在 Twitter 上使用扎克伯格在 Oculus 发布会上的照片作为背景，号召 SD 会成为“人类图像知识的基础设施”，通过开源让所有人都能够使用和改进它，并让所有人更好地合作。
Stable Diffusion 可以认为是一个开源版本的 DALL·E2，甚至不少使用者认为是当前生成模型可以使用的最佳选择。官方版本部署在官网 Dream Studio 上，开放给所有用户注册。相比其他模型，有很多可以定制化的点。就在不久前，Stable Diffusino2模型的诞生，使得文字生成图像的分辨率大幅提高，同时在图生图的质量上也有了长足进步。

下面，我们做了一个更加详细的mapping，梳理了生成式AI中各玩家的“武器库”。

<div align=center>


|代表公司|大模型|跨模态|文本|图像|视频和3D|代码|游戏|生物|语音|算力资源|资金投入|领军人物|
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|<div style="width: 100pt">Open AI|<div style="width: 100pt">GPT-3|<div style="width: 100pt">CLIP|<div style="width: 100pt">GPT1/GPT2/GPT3 均开源/ChatGPT（对话）/InstructGPT|<div style="width: 100pt">DALL-E/DALL-E2|<div style="width: 100pt">IDM/VPT|<div style="width: 100pt">Codex 未开源|<div style="width: 100pt">Gym Retro/Open AI five| <div style="width: 100pt">|<div style="width: 100pt">Whisper|<div style="width: 100pt"> |<div style="width: 100pt">3年投入超20亿美元|<div style="width: 100pt">Ilya Sutskever|
|Stability AI|Stable Diffusion|CLIP| |Stable Diffusion/Stable Diffusion2 均开源| | | |Diffusion Model| |公有云上4000张A100|（1）stable diffusion训练成本为600万美金 https://zhuanlan.zhihu.com/p/563159006 运营和云支出成本超过5000万美金https://new.qq.com/rain/a/20221020A03EAN00 （2）近期获得了1.01亿美元超额融资，估值达10亿美元 https://hub.baai.ac.cn/view/20386 这里有一个小问题，第一个链接里说训练成本是600万美金，第二个里面说是60万美金|Emad Mostaque/David Ha（ex-Google）|
|Google|BERT／T5/CANINE/Decision Transformer/ELECTRA/MT5/Pegasus/PEGASUS-X/REALM/Reformer/RemBERT/Transformer-XL/UL2/XLNet/Chinchilla/Gato/PerceiverIO|T5/T5v1.1/Flamingo/NFNets/Preceirver/Flamingo/NFNets/Preceirver|LaMDA/PALM/ALBERT/BERT/BigBird/OWL-ViT/Pythia/Ithaca/Sparrow/Flan-T5|Imagen/Parti/Dreambooth/Re-Imagen/ViT/NFNet-F3|Imagen Video/Phenaki/DreamFusion/MuZero|Alpha Code|PaLM/Alpha Star/DQN|Alpha Fold|WaveNet|（1）几十个TPU v4 pods，拥有全球最大机器学习中心（https://cloud.tencent.com/developer/article/200395） 谷歌推出基于XLA编译器的自动并行化系统GSPMD。即使硬件没有进步，也能做到在150种模型上性能全面提高5%-15%，甚至个别情况下提高了2.4倍。https://www.qbitai.com/2022/01/31905.html|数十亿美元 https://baijiahao.baidu.com/s?id=1737302643347647745&wfr=spider&for=pc|Li Feifei/Jeff Dean|
|Meta|AV-HuBERT/Data2vec/BART／OPT-175B/Decision Transformer/DETR/FLAVA/OPT/RoBERTa|RA-CM3/BART/CamemBERT/Data2Vec/SpeechToTextTransformer/SpeechToTextTransformer2|XLS-R/Sphere/RA-CM3/BlenderbotSmall/Blenderbot/CamemBERT/DPR/M2M100/NLLB/RAG/XGLM/XLM|RA-CM3/ConvNeXT/DeiT/LeViT/ViTMAE|Make-a-Video| |Cicero|Masked Language Model/ESM|Meta-StyleSpeech/Hubert/M-CTC-T/Wav2Vec2/Wav2Vec2-Conformer/Wav2Vec2Phoneme/WavLM|公有云上有5400张A100，私有云上有16000张A100|（1）4亿美元建造全球最强AI超算 https://ai.facebook.com/blog/ai-rsc/、https://view.inews.qq.com/k/20220125A09J5C00?web_channel=wap&openApp=false （2）到2026年，Meta将至少在Meatverse投资700亿美元 https://36kr.com/p/dp1948473529960834 |Yann LeCun|
|Nvidia|PoE GAN/Megatron-Turing|PoE GAN|BERT/DistillBERTG/GroupViT/Megatron-BERT/SegFormer/MegatronBERT2|GauGAN/GauGAN2|Omniverse/Magic 3D/NeRF/GET3D| |MineCLIP| |QODA|（1）私有云上4320张A100（2）打造下一代芯片H100，提升模型训练速度 https://baijiahao.baidu.com/s?id=1741572168951984095&wfr=spider&for=pc （3）过去十年（10-21），公司算力提升至原来的100万倍，预计2030年会再提升100万倍（何展）|累计投入超过600亿美元建立AI初创企业加速器 https://blogs.nvidia.cn/2021/08/20/inception-global-8k-plus-thought-leadership/|Bill Dally|
|Microsoft|Megatron-Turing/DeBERTa/MarkupLM/MPNet/ProphetNet/Swin Transformer/Swin Transformer V2/XLM-ProphetNet|Microsoft-Turing/DiT/LayoutLM/TrOCR|GPT-4/ApacheSpark/NÜWA/DialoGPT|CoModGAN/BEit/CvT/NÜWA/ResNet|NÜWA/X-CLIP| |Analyzer|Uni-TTSv4/UniSpeech/UniSpeechSat| | |百亿美元 https://view.inews.qq.com/k/20210416A05JBG00?web_channel=wap&openApp=false |EricHorvitz|
|BigScience workshop| | |BLOOM| | | | | | | |1000-2000万美金| |
|Amazon|bort|Polly/Transcribe/|Comprehend/Translate/Comprehend Medical/Kendra（搜索）| |Rekognition|CodeGuru| | |Lex|数千卡https://aws.amazon.com/hpc/ |20亿美金|Li Mu|


</div>

四、中国的AIGC
---

与美国相比，中国生成式AI行业还处于起步阶段，难以出现能够媲美Open.AI的公司。
下面列举了一些中国具有代表性的生成式AI公司或机构：
北京智源研究院：北京智源人工智能研究院（Beijing Academy of Artificial Intelligence，BAAI）是人工智能领域的新型研发机构。2018年11月14日在科技部和北京市支持下，依托北京大学、清华大学、中国科学院、百度、小米、字节跳动、美团点评、旷视科技等北京人工智能领域优势单位共建的新型研究机构。
 
智谱华章：简称智谱AI，成立于2019年，由清华大学计算机系知识工程实验室的技术成果转化而来，于9月获得数亿元人民币的B轮融资。
 
小冰公司：小冰公司作为微软全球首个以中国为总部的人工智能产品线，相关领先技术覆盖自然语言处理、计算机语音、计算机视觉和人工智能内容生成等人工智能领域，估值目前约20亿美元。
 
百度：目前是国内做大模型的领先者。文心大模型已大规模应用于搜索、信息流、智能音箱等互联网产品，并通过飞桨开源开放平台、百度智能云赋能制造、能源、金融、通信、媒体、城市、教育等各行各业。随着应用场景的进一步扩大，文心大模型已联合打造超过 10 个行业大模型，不断从行业及企业的特有数据和知识中融合学习，模型能力进一步增强，助力企业降本增效，加快行业转型升级。
 
对于国内公司，我们也梳理了mapping。
<div align=center>

|代表公司/机构|NLP|CV|语音|跨模态|代码|生物|行业大模型|算力资源|资金投入|领军人物|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|<div style="width: 100pt">华为|<div style="width: 100pt">盘古NLP大模型|<div style="width: 100pt">盘古CV大模型|<div style="width: 100pt"> |<div style="width: 100pt">盘古跨模态大模型|<div style="width: 100pt">CodeGeeX|<div style="width: 100pt">盘古分子大模型| <div style="width: 100pt">|<div style="width: 100pt">华为打造昇腾AI系统，建设中国算力一张网https://baijiahao.baidu.com/s?id=1743138180340584460&wfr=spider&for=pc |在生成式AI的预算看起来是10亿人民币以内,去年AI整体投入15亿美元 https://www.ngui.cc/el/1581331.html |田奇|
|百度|ERNIE-Health（医疗）/ERNIE-Finance（金融）/PLATO（对话）/ERNIE-Search（搜索）/ERNIE-UIE（信息搜取）/ERNIE-M（跨语言）/ERNIE-Sage（图网络）/ERNIE 3.0（百亿级）/鹏城-百度 文心（千亿级）/ERNIE 3.0 Zeus（任务知识增强）/ERNIE 3.0 Tiny（轻量级）/ERNIE-Code （代码）|VIMER-StrucTexT（OCR图像表征学习）/VIMER-UMS（商品图文搜索）/VIMER-UFO（多任务视觉表征学习）/VIMER-TCIR（视觉处理多任务学习）/VIMER-CAE（自监督视觉表征学习）| |ERNIE-VILG（图文生成）/ERNIE-Layout（文档分析）/ERNIE-ViL（视觉-语言）/ERNIE-SAT（语言-语言）/ERNIE-GeoL（地理-语言）| |HELIX-GEM（化合物表征/HELIX-Fold（蛋白质结构分析）|国网-百度-文心/浦发-百度-文心/航天-百度-文心/人民网-百度-文心/冰城-百度-文心/电影频道-百度-文心/深燃-百度-文心/吉利-百度-文心/泰康-百度-文心/TCL-百度-文心/辞海-百度-文心|百度智能云-昆仑芯（盐城）智算中心，算力规模达200P https://baijiahao.baidu.com/s?id=1742862623767555762&wfr=spider&for=pc 百度百舸提供了千卡规模|在生成式AI的预算看起来是10亿人民币以内，智能云十年累计投入超一千亿元|王海峰|
|网易|图文预训练/音乐预训练/行为序列预训练/文本预训练/AI音乐|骨骼捏脸/Mesh捏脸/挖机视角合成/手势迁移/三维场景&材质重建/头发重建/挖机双目重建| |虚拟人：表情迁移、手势&肢体编码、识别及迁移、表情基自动绑定、语音生成表情、表情动作单元检测、换脸| | | |自建千卡|NA 预测在一亿|赵增|
|美团|美团NLP大平台-搜索，推荐，广告-智能客服/助理-内容社区-企业办公-有与悟道合作-强调大模型+小样本联合训练方案|美团视频团队| |美团文生图大模型（暂未对外）| | | |CTR 预测服务成功的迁移到 GPU 平台上，在为业务提供更好的支撑的同时也获得了更好的性价比 https://www.elecfans.com/d/1767002.html | |夏华夏|
|智谱华章|GLM系列模型（共8个）GLM-130B/Transformer-XL（中文预训练模型，代替GPT中的中文Transformer）/CodeGeeX（代码）/Multilingual-GLM（多语言）| | |CogView（文生图）/CogVideo（文生视频）|CodeGeeX| | |GLM-130B，通过快速推理方法，已经将模型压缩到可以在一台 A100（40G*8）或 V100（32G*8）服务器上进行单机推理 http://www.myzaker.com/article/638db557b15ec0416303e817 |估值20亿人民币，华兴做FA，一线美金并没有注资|唐杰|
|西湖心辰|ALBERT|ALBERT| | | | | |背靠西湖，近千卡|上一轮投资人：蓝驰创投、凯泰资本、西湖大学。目前希望融资2000万美金|蓝振忠|
|澜舟科技|孟子大模型|孟子Mengzi-图文模型| |孟子Mengzi-图文模型| | |孟子Mengzi-金融模型|模型压缩和轻量化 https://baijiahao.baidu.com/s?id=1747836631598279154&wfr=spider&for=pc| pre-Al轮投资近千万，联想创投、斯道资本共同领投，创新工场跟投|周明|
|腾讯|混元HunYuan|混元HunYuan/GFP-GAN|TLC-BLSTM|混元HunYuan| |GROVER/GCN-MF| |(1)业内首推数字孪生云，算力消耗降50％，开发速度翻番https://new.qq.com/rain/a/20221205A029X700 （2）建设长三角人工智能先进计算中心，建成算力是目前世界排名第一的超算中心的10倍https://sghexport.shobserver.com/html/baijiahao/2022/09/08/848366.html| |张正友|
|字节|火山引擎大模型训练框架（veGiantModel）|iBOT| |X2-VLM| | | | | |李航|
|阿里|M6/PLUG/通义-AliceMind|M6/通义-CV|LC-BLSTM/DFSMN-CTC|通义-M6| | | |（1）张北超级智算中心，总建设规模为12 EFLOPS（每秒1200亿亿次浮点运算）AI算力，https://m.gmw.cn/baijia/2022-09/19/36034189.html （2）飞天智算平台，提升AI训练效率11倍 https://baijiahao.baidu.com/s?id=1742726416680420587&wfr=spider&for=pc| |程立|
|文澜大模型|MLMM|BriVL| |BriVL| | | | |目前有一线TS|卢志武|
|上海人工智能研究院| | | | | | | |（1）AIDC，其总算力达3740PetaFLOPS https://baijiahao.baidu.com/s?id=1722840044715688959&wfr=spider&for=pc （2）与华为签署全面合作协议共同构建昇腾AI产业生态，打造公共算力平台http://www.xinhuanet.com/info/20220812/4ee9d2eae3714c10aa630fcfa7626382/c.html| |毛军发|
|北京智源人工智能研究院|悟道 文渊/悟道 文汇|悟道 文澜/AltCLIP/EVA| |CogVideo| |悟道 文溯| |一千多张卡|每年经费5亿人民币左右|刘嘉|
|IDEA|二郎神/周文王/燃灯/比干/闻仲|二郎神/周文王/燃灯/比干/闻仲/太乙| | | | |余元|NLP和CV团队Share鹏城实验室下面2400张卡中的1200张A-100（AOHAN）|每年4亿人民币|沈向洋/张家兴/张磊|
|浙江之江实验室|NLP算法团队|CV算法团队| |混合增强智能研究中心| | | |1600张A-100（AOHAN）|（1）2018-2022年省财政拨款100亿https://baijiahao.baidu.com/s?id=1619452937154157900&wfr=spider&for=pc （2）5年社会累积投资28.6亿http://www.kjw.cc/guonei/2022/1020/61641.html |潘云鹤|

 </div>
 
以上是模型层面的梳理，而关于具体应用层面，我们按照模态，从文本、图像、视频和3D、游戏领域进行了梳理：
 
<div align=center>
 
|项目|方向|GO to market|
|:--:|:--:|:--:|
|秘塔|文本编辑|C端/B端|
|Xiaomingbot|文字生成|文字工作者|
|澜舟科技|文字生成|学生/文字工作者/2B品牌|
|FridayAI|文字生成|2B品牌+文字工作者|
|写作猫|文字生成|学生/媒体工作者|
|Gliso写作机器人|文字生成|学生/文字工作者|
|Get写作|文字生成|学生/文字工作者|
|写作狐|文字生成|学生/文字工作者|
|沃沃AI人工智能写作|文字生成|学生/媒体工作者/作家|
|聆心智能|AI陪伴/小说攥写|抑郁症患者/文案创作者|
|6 pen|文生图|创作者/大学生|
|ZMO|文生图|创作者/电商|
|万兴AI绘画|文生图|创作者+社区|
|中文在线|文生图|创作者|
|机画师|文生图|创作者|
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
|VidPress|文生音频|创作者|
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
|mixlab无界社区|AIGC社区|创作者|
</div>

为了直观比较中美生成式AI的差异，我们对比了国内外SOTA，具体情况如下：

<div align=center>

|模型|类型|架构|参数|数据|性能|
|:----:|:----:|:----:|:----:|:----:|:----:|
|<div style="width: 100pt">Google：PaLM|<div style="width: 200pt">语言模型|<div style="width: 100pt">基于Transformer的dense decoder-only模型|<div style="width: 50pt">540 B|<div style="width: 100pt">多语言和GitHub代码数据集|<div style="width: 100pt">语言理解和生成的合理性，代码相关任务相比LaMDA，GLaM都有很大提升|
|OpenAI：ChatGPT/GPT4|语言模型|ChatGPT：RLHF GPT4:MoE RLHF|ChatGPT: 暂时不知道（GPT4的一部分能力露出）GPT 4至少是5250billion（30x GPT3）也有说法是100 Trillion（https://towardsdatascience.com/gpt-4-will-have-100-trillion-parameters-500x-the-size-of-gpt-3-582b98d82253） |ChatGPT：多语言和GitHub代码数据集 GPT 4：多语言和GitHub代码数据集|ChatGPT：对话任务中alignment最好的模型 GPT4：多轮长对话表现很好，inference time对比GPT3不增加，推理时间不增加|
|智源/华章：GLM-130B|语言模型|通用语言双向稠密模型|130B|4000 亿个文本标识符（中文和英文各 2000 亿）|精度高（https://new.qq.com/rain/a/20220905A0651E00）|
|Google：DreamBooth|文生图模型|Diffusion模型| |开源数据包括：Leion以及谷歌自己的数据|弥补stable diffusion无法生成特定个人图像的缺陷（https://zh.wikipedia.org/wiki/DreamBooth|
|百度：ERNIE-ViILG|文生图模型|Transformer|10B|开源数据包括：Leion以及百度自己的数据|引入知识图谱，提升了学习效率及可解释性；更准确理解中文表达击败stable diffusion、DALL-E 2（https://m.thepaper.cn/baijiahao_20522594）|
|智源：文汇|图文跨模态模型|Transformer|11.3B|开源数据包括：Leion|可完成多种文图生成任务（https://baijiahao.baidu.com/s?id=1688859914374120633&wfr=spider&for=pc）|
|Meta：Make-a-Video|文生视频模型|Diffusion 模型| |带描述性的图片和无标签的视频|（1）加速了文字生成视频模型的训练速度；（2）训练时不需要文字和视频配对的数据；（3）继承了如今图片生成模型的美学性 在实验中，超过70%的被试愿意选择make a video|
|北京智源研究院：CogVideo|文生视频模型|Transformer|9.4B|5.4 million的带文字视频|复杂prompt下生成视频的准确率较高|
|Google：DreamFusion|文生3D视频|Diffusion 模型| |图片|仅需要2D数据即可训练模型|
|Nvida：Magic 3D|文生3D模型|Diffusion 模型| | |（1）生成3D模型的速度是Dream Fusion的2倍；（2）3D效果比Dream Fusion好，分辨率是后者的8倍|

 </div>
 
经过我们的了解，中美之间生成式AI之间的巨大差距主要来源于人才密度、算力投入、模型架构和资金的差异。

|Take away：|
|:---:|
|人才密度对比：中国缺少做生成式AI方向的顶级学者，同时人才交叉密度也和美国相比有较大差距。在美国，例如Deepmind.AI 研发团队超过800人，各个学科的PHD都有，OpenAI300人。国内一方面缺乏AI的领军人物，有知名度的学者较少hands-on带团队。另一中国的人才交叉密度目前仍不足，例如智源/华章研发团队200-300人（核心研发30）。|
|算力投入：微软给OpenAI万张GPU，谷歌模型动辄2000TPU，国内SOTA大多仅为1000GPU。造成了模型训练时间的显著差异，例如智源训练一次GLM的资源是Google PaLM的1/13|
|架构：ChatGPT是在GPT 3.5系列的基础上进行改进的，引入了RLHF训练方式，CharacterAI模型训练cost不到千万美元的量级，参数也只有千亿，但是效果非常好在架构上做了不少优化；国内虽然有参数很大的模型，例如百度文心，但是整体的表现和美国相比有很大距离，主要原因是中国的大模型较多采用已有的transformer架构，少有创新。|
|资金差异：美国生成式AI项目资金投入更多，例如OpenAI投入了20亿美金，Amazon20亿美金；对比国内大厂，由于内部资源竞争且大厂主要考虑降本增效，生成式AI行业资金投入通常是十亿之内。而像政府支持机构，例如北京智源研究院，每年投入仅为5亿人民币。|
|造成结果：中国的Foundation Model全面落后，应用同样落后，美国先进模型不开放给中国；国内对于未来的预期技术成熟速度产生了较为悲观的预判，如：在海外的华人，比如工业界的学者对比国内的学术界和工业界学者整体上对于文字语言模型或者视频模型，他们都更乐观一些。比如说当我们去问如果要做到一个像抖音一样输出质量 720p 5 到 10 分钟高逻辑性的视频能否在未来三年完成的时候，国内的学者大都相对保守，而来自谷歌或者meta等机构的学者则更加乐观。|
|中国需要：|
|比较强研发+engineer能力和经验的团队|
|足够的资金：中国的资本比较缺乏耐心，会要求被投企业很快有回报。但生成式AI需要投入很多研发成本，需要很多模型和算法的迭代与优化。|
|数据：中国的生成式AI生态没有搭建起来，很多API都没有开源出去，因此获得的数据相比已经开源的Stability会减少很多。|
|算力：更强大的算力才能训练出更好，功能更完备的模型，一个模型2000张GPU的集群应该是充分条件。|
 
</div>

五、未来会发生什么
---
立足当下，我们看到了生成式AI的现状，它足够令人兴奋；展望未来，我们看到了更多的可能正在诞生，它是那让人心潮澎湃。下面，我们就四个方面展开，谈谈生成式AI的未来。它们分别是：（1）GPT4和ChatGPT的展望；（2）中美学者对AIGC的不同态度；（3）AI的民主化；（4）游戏领域的新机遇

<b> (1) GPT4和ChatGPT的展望。</b>就在最近，我们获得的消息是，GPT4模型是一个基于MoE架构的超大模型，参数量是GPT3的30倍！目前可以预知的是其能超过图灵测试，在推理过程中消耗的资源和算力并不会比GPT3大多少，甚至很有可能是一样的。Open AI 一直看好通用语言模型的发展，从其过去发布的 GPT 系列模型就可看出这一趋势。而基于GPT3.5和RALF架构的ChatGPT更是在最近风靡全球。Open AI 的 CEO Sam Altman 在推特上说：”Language interfaces are going to be a big deal, I thik." OpenAI 只是一个先行者，相信很快大家就能用上真正智能的提供建议的 AI 助手了。


![SA](https://user-images.githubusercontent.com/118708553/205486319-23df3ef7-36c3-4229-83b1-899d72c501bd.jpg)

今年的一个明显感受就是，通用领域的玩家下场搞垂直赛道真的是降维打击。这也反映了以往对话领域的困境：令对话系统取得飞跃式进展的技术几乎都来自通用领域（大规模预训练、检索增强等），想搞真正有用的创新只能从数据层面入手。当数据的优势也失去后，便难有招架之力了。

由此我们也可以去推演偏通用性的语言会发生在什么样的场景里边，比如说AI教育、AI助理、AI陪伴这些垂直领域，这些方向都是非常值得关注的。我们相信在明年会有这一类型创业公司的一个新的机会，而壁垒可能就建立在如何把这样的通用的语言能力和用户交互的interface的门槛降低，比如像虚拟人技术。

<b> (2) 中美学者对AIGC不同的态度。</b>通过我们跟行业人士的交流，我们发现在海外的华人，比如工业界的学者对比国内的学术界和工业界学者整体上对于文字语言模型或者视频模型，他们都更乐观一些。比如说当我们去问如果要做到一个像抖音一样输出质量 720p 5 到 10 分钟高逻辑性的视频能否在未来三年完成的时候，国内的学者大都相对保守，而来自谷歌或者meta等机构的学者则更加乐观。所以我们也可以预判AIGC的创业者就值得去冒更大的风险，因为整个行业发展的势能是非常快的。

<b>（3）AI的民主化。</b>关于语言模型，我们能够猜想到，比如说在两三年之后，可以由任何一个端接入到像 gbt 4 这样的语言模型，并且由于有像联邦学习这样的隐私计算功能的存在，每个人都可以训练出属于自己的个人助手或者是 AI 模型，这样能够实现真正意义上的 AI 民主化。

<b>（4）游戏领域的新机遇。</b>今天在游戏领域，与 Generative AI 结合的，其实只有 unity 通过 huggingface 简单地这个支持了 stable diffusion 的功能，而我们相信这里有一个颠覆现有引擎的这个机会，因为如果有了 Generative AI 的帮助所有的创作管线都会发生改变，从对话、剧情、角色、3D场景，甚至未来是玩法，都会发生转变。

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
