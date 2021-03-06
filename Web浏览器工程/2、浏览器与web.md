# 浏览器与Web

为什么要学习浏览器？从我的角度来看，浏览器对于网络、现代计算乃至整个世界来说都是至关重要的，因此值得了解它们的工作方式。事实上，很酷的算法，复杂的数据结构和基本概念也在浏览器中活跃起来。本书从头开始带你构建浏览器。我希望当你阅读这本书的时候，会像我一样爱上浏览器。

***

**目录** 

* 浏览器与我
* web历史
* 真实的浏览器代码库
* 浏览器编程概念
* 浏览器中的角色
* 浏览器与你

***

### 浏览器与我

我-这是Chris所说的-我一生都知道浏览器。自从90年代我第一次接触web和其前身以来，我被浏览器和网络用户接口概念深深吸引。当我上网的时候，即使是最早期的形式，我也感觉看到了计算机的未来。从某种意义上来说，网络和我共同成长了。例如，在1994年，网络开始商业化的那一年，和我上大学是同一年。在大学我花了很多时间上网冲浪，直到1999年毕业，这段时间浏览器助长了著名的网络淘金热。我现在供职的谷歌公司，就是网络时代的产物，并且成立在那个时期。对我而言，网络是技术上的伴侣，而且在我工作和学习过程中从未离开过。

在我上大一的时候，曾经参加过红帽（RedHat）公司销售人员的演讲。这场演讲的目的当然是推销它们公司的Linux系统（RedHat Linux），他称其为未来的操作系统并预测是属于Linux台式机的一年。但是当问到红帽公司面临的挑战时，销售人员提到的不是Linux，而是Web，他说：需要有人为Linux开发出一款好用的浏览器。甚至在那时，在网络兴起的第一年，浏览器就已经成为每个计算机的必备组件。他甚至提出了一个挑战，“构建一个更好的浏览器有多难？”。确实，有多难呢？是什么让它如此之难？这些问题困扰了我很久。

真是太难了！在Chrome上工作了七年之后，我得到了他的问题的答案：构建一个浏览器即简单又非常困难，即有意又无意。在你能看到的任何地方，你都能在一个封装的代码库里看到web的发展和历史。最重要的是，这非常的有趣，而且是无穷无尽的有趣。

因此我爱上了浏览器。现在让我告诉你，你也会和我一样爱上它。



### Web历史

Web是一个疯狂的实验。现在，通过网络看视频、浏览新闻、社交都是很自然的事情。这使得网络看起来好像简单明了，理所当然的构建完成。但是web既不简单也不显而易见。```它是实验和研究的结果，可以追溯到计算机的开始，关于如何帮助人们彼此建立连接和相互学习。It is the result of experiments and research reaching back to nearly the beginning of computing about how to help people connect and learn from each other.```

在早期，互联网是一种位于大学、实验室以及政府机构之间的全世界范围内的网络，通过物理电缆和特定的应用程序连接。早期的网络基于这些基础构建。Web页面是以特定格式存储在服务端的文件，浏览器以自定义的应用协议来传输。Web网页的URL以计算机和文件命名，并且早期的服务器也只是完成从硬盘上读取文件的功能。此时网络的逻辑结构反应了它的物理结构。

现在已经大不一样了。HTML是动态组装的，并且是按需发送到你的浏览器上，包括了新闻、收件箱内容、根据你的特定口味调整的广告。甚至URL不再识别特定的计算机，内容分发网络将URL路由到全世界成千上万台计算机的任意一个。在更高的层次上，大多数网页不是某个人家里的电脑提供的，而是社交媒体平台或云计算服务提供的。

所有这些都发上了变化，但是有些东西是不变的，那就是组成网络本质的核心构成：

* web是被超链接关联的信息网络；
* 信息是用HTTP协议请求来的，并且被HTML文档结构化；
* 网页可以链接到不同格式的辅助资源，包括图像、音视频、CSS以及JavaScript；
* 用户通过浏览器（一种用户代理）可以访问Web；
* 所有这些构建块都是开放的、标准的，并且可以免费使用或重复使用。

作为一个哲学问题，这些原则中的一个或者另一个是次要的。















































