# ComputerGraphicsBooks

# 参考资料
* [计算机图形学必读的10本书](https://www.msra.cn/zh-cn/news/features/book-recommendation-computer-graphics)

计算机图形学诞生于二十世纪六十年代，主要的研究内容是研究如何使用数学算法在计算机中有效地表达、生成、处理以及显示相关图像和图形。作为一门计算机应用科学，计算机图形学近年来的快速发展极大地促进了计算机辅助设计、虚拟现实、游戏、动画、影视特效等行业的发展。

为了帮助同学们更好地学习计算机图形学，我们邀请微软亚洲研究院网络图形组主管研究员董悦为大家推荐了该领域相关的经典书籍，内容涵盖图形学基础原理、渲染基础与算法、计算几何与几何处理、表观建模等。

计算机图形学基础
Computer Graphics: Principles and Practice

作者：John F. Hughes, Andries van Dam, Morgan McGuire, David F. Sklar, James D. Foley, Steven K. Feiner , Kurt Akeley

中文版：计算机图形学原理及实践



推荐理由：本书为四位图形学界大师的经典著作。作为计算机图形学入门基础最佳教程，该书内容涵盖非常广泛，从最基础的rasterization algorithm到现代GPU设计及并行计算应有尽有。这本书之所以有名一方面是因为其全面地介绍了计算机图形学的基本概念和经典算法，另一方面也来自于这本书的历史地位。该书第一版出版于1982年，可以说这本教材见证了计算机图形学界的发展，当然，本书也多次改版增添了大量内容以适应计算机图形学的飞速发展。从任何一个角度看，本书都是值得学习的经典入门书目。

渲染技术入门
Physically Based Rendering: From Theory to Implementation

作者：Matt Pharr, Wenzel Jakob, Greg Humphreys

中文版：物理渲染从理论到实现（第2版）



推荐理由：基于光线追踪的渲染算法最佳教材，该教材在渲染领域如雷贯耳，同时与该书配套的渲染系统PBRT也在计算机图形学领域被广泛应用，是学界最常用的渲染引擎之一。该书的作者也是渲染领域的几位大师级专家，该书涉及了光线追踪渲染的各个方向，同时该书的最新版也及时引入了大量新近的光线追踪渲染算法。光线追踪已经是现代电影特效工业的基础模块，同时随着基于GPU的光线追踪的发展，光线追踪在游戏中也会逐渐发挥自己的特长。该书是学习渲染的入门必读书目。

Real-Time Rendering, 4th Edition

作者：Tomas Akenine-Möller, Eric Haines, Naty Hoffman

中文版：实时计算机图形学（第二版）



推荐理由：前面那本书讲的是完全基于物理的光线追踪渲染系统，然而对于绝大多数游戏和实时交互场景，光线追踪的效率相对低下，无法满足实时计算的要求，因此在游戏引擎等实时性要求较高的应用中，人们设计了很多用于实时渲染的算法。本书出自三位具有丰富游戏引擎设计经验的大师之手，该书也是实时渲染领域的经典著作，几经再版，更新最新的实时渲染技术。当前最新的第四版也引入了很多最新游戏中使用的最新技术，值得每一位对实时渲染和游戏渲染系统感兴趣的同学学习。

渲染算法进阶
下面这两本更偏向于学术著述，需要有一定的渲染基础知识才可以阅读，然而由于出自先进渲染算法的几位经典导师之手，这两本书对于想深入研究渲染系统，或者希望在渲染领域进行学术研究的同学也是必读的书目，在阅读过程中也能学习到技术之外的一些关于如何设计这些算法的深刻思考。

Advanced Global Illumination, 2nd Edition

作者：Philip Dutre, Philippe Bekaert, Kavita Bala



推荐理由：本书基本围绕光线追踪这一分支下基于蒙特卡罗的光线追踪体系，根据概率计算有效提高渲染效率，同时始终对渲染结果做出无偏估计。是学习蒙特卡罗光线追踪的重要教材。

Realistic Image Synthesis Using Photon Mapping, 1st Edition

作者：Henrik Wann Jensen



推荐理由：本书主要介绍利用Photon Mapping进行有效计算全局光照和半透明渲染的方法，Photon Mapping虽然是一种有偏估计算法，但是该算法在一些特殊的渲染过程中具有非常高的计算效率优势，因此，Photon Mapping依然是电影工业中进行渲染计算不可或缺的重要部分。该书对Photon Mapping进行了深入浅出的介绍，是学习该方法的最佳读物。

计算几何与几何处理
Computational Geometry: Algorithms and Applications, 3rd Edition

作者：Mark de Berg, Otfried Cheong, Marc van Kreveld, Mark Overmars



推荐理由：计算几何是图形学的一个重要数学基础，本书围绕计算机图形学应用总结了计算几何的经典算法，是计算几何的经典入门书目。

Polygon Mesh Processing, 1st Edition

作者：Mario Botsch, Leif Kobbelt, Mark Pauly, Pierre Alliez, Bruno Levy



推荐理由：几何处理是计算机图形学的一个重要研究方向，本书出自几位当今活跃在科研一线的几何处理大师之手，基本涵盖了几何处理的各个重要研究方向，每个章节还为想深入研究该方向的同学列出了扩展阅读的材料，适合想深入学习研究几何处理的同学研读。

表观建模
Digital Modeling of Material Appearance (The Morgan Kaufmann Series in Computer Graphics), 1st Edition

作者：Julie Dorsey, Holly Rushmeier, François Sillion



推荐理由：表观建模研究物体与光线的交互作用，体现了物体的材质属性。本书出自表观建模的几位先驱者，全面系统地介绍了表观建模的概念和领域的多个重要方向。虽然此书出版时间相对较早，但本书作为表观建模领域的入门教材依然值得每个想在这个领域进行深入研究的同学阅读。同时，由于渲染与表观密不可分，因此也建议对表观建模感兴趣的同学结合前面介绍的渲染相关的书籍进行学习。

高动态范围图像
High Dynamic Range Imaging: Acquisition, Display, and Image-Based Lighting 2nd Edition, Kindle Edition

作者：Erik Reinhard, Wolfgang Heidrich, Paul Debevec, Sumanta Pattanaik, Greg Ward, Karol Myszkowski



推荐理由：高动态范围图像已经在当前图形学产业界有了非常广泛的应用，现在的手机相机也大多带有HDR拍照的功能。本书由HDR领域的多位先驱者共同编写，全面深入地介绍了HDR图像相关的方方面面，从理论基础到产业应用应有尽有。相信每一位对HDR技术感兴趣的同学都能在本书中找到自己需要的内容。

One more thing
Jim Blinn's Corner Series

作者：Jim Blinn



推荐理由：Jim Blinn是计算机图形学领域的泰斗级人物，在NASA和JPL制作的宇宙系列动画影响了一代人对宇宙和计算机图形学）探索的向往。同时大名鼎鼎的Blinn-Phong模型在今天依然有所大量的应用。这套系列丛书一共出版了三本，分别是

Jim Blinn's Corner: Dirty Pixels
Jim Blinn's Corner: A Trip Down The Graphics Pipeline
Jim Blinn's Corner: Notation, Notation, Notation
该系列丛书收集了Jim Blinn在IEEE Computer Graphics & Applications写的一系列专栏文章。由于文章发表时间相对久远，很多文中涉及到领域已经有了长足的发展，因此这套书相对而言更适合学术考古、溯本追源之用。
