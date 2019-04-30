## 什么是Docker
&ensp;&ensp;&ensp;&ensp;Docker是一种Linux容器技术，一种高效、敏捷、和轻量级的容器解决方案，并且支持在多种主流平台（PaaS)和本地部署。Docker是基于Go语言实现的云开源项目，诞生于2013年，最初发起者是DotCloud公司，后来改名为Docker Inc，之后专注于Docker相关技术和产品的开发。Docker项目目前已经加入了Linux基金会，遵循Apache 2.0 开源协议，全部开源代码均在[https://github.com/docker](https://github.com/docker)上进行相关维护，官网地址为：[https://www.docker.com/](https://www.docker.com),有相关文档可以参考，现在docker与openstack同为最受欢迎的云计算开源项目。</br>
  &ensp;&ensp;&ensp;&ensp;docker的Logo设计为蓝色鲸鱼，拖着许多集装箱。docker的构想思想是要实现“Build, Ship and Run Any App, Anywhere”，即通过对应用的封装（Packaging）、分发（Distribution）、部署（Deployment）、运行（Runtime）生命周期进行管理，达到应用组件“一次封装，到处运行”的目的。这里的应用组件，既可以是一个Web应用、一个编译环境，也可以是一套数据库平台服务，甚至是一个操作系统或集群。</br>
  &ensp;&ensp;&ensp;&ensp;基于Linux平台上的多项开源技术，Docker提供了高效、敏捷和轻量级的容器方案，并支持部署到本地环境和多种主流云平台。可以说，Docker首次为应用的开发、运行和部署提供了“一站式”的实用解决方案。</br>
  <img src=https://ws3.sinaimg.cn/large/005BYqpggy1g2kstw9f3tj309k064747.jpg>
  &ensp;&ensp;&ensp;&ensp;跟大部分新兴技术的诞生一样，Docker也并非“从石头缝里蹦出来的”，而是站在前人的肩膀上，其中最重要的就是Linux容器（Linux Containers，LXC）技术。操作系统级虚拟化的历史：
  + 1982年：你一定会很惊讶，第一个操作系统级的虚拟化技术是什么。答案就是chroot，直到现在我们依然在使用的一个系统调用。这个系统调用会改变运行进程的工作目录，并且只能在这个目录里面工作。这种操作其实就是一种文件系统层的隔离。
  + 2000年：FreeBSD jail，真正意义上的第一个功能完整的操作系统级虚拟化技术。所以，真正的容器化技术出现到现在已经过去了16年，并不是几年的时间。
  + 2005年：OpenVZ，这是linux平台上的容器化技术实现，同时也是LXC，即docker最初使用的容器技术核心实现。
  + 2008年：LXC发布，这是docker最初使用的具体内核功能实现。
  + 2013年：Docker发布，可以看出，docker最初是使用了LXC，同时封装了其他的一些功能。Docker的成功，与其说是技术的创新，还不如说是一次组合式的创新。
  

