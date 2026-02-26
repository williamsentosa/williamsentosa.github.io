---
permalink: /
title: "William Sentosa"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About me
======

I am a PhD candidate in Computer Science at the University of Illinois Urbana-Champaign (UIUC), advised by [Prof. Brighten Godfrey](https://pbg.cs.illinois.edu). Before joining UIUC, I worked with [Prof. Shan Lu](http://people.cs.uchicago.edu/~shanlu/) and [Prof. Henry Hoffmann](http://people.cs.uchicago.edu/~hankhoffmann/) from UChicago to build an auto-configuration framework for systems software. I earned a BS degree in Computer Science from Bandung Institute of Technology, Indonesia, in 2017.  

My research interests span broadly in the area of **networked systems**, including (but not limited to) low-latency networking, cellular networks, wide-area networks, ML Sys, Sys for ML, and VR/AR systems.

<span style="color:red">**Note:** I am on the job market for 2026, looking for an engineering or research position.</span>

I enjoy building systems, and these are three topics that I have been working on:
- Low latency networking
	- [DChannel](https://www.usenix.org/system/files/nsdi23-sentosa.pdf) provides a network-layer multipath solution that utilizes network slices in 5G (eMBB and URLLC) to achieve low latency and high bandwidth (**NSDI'23**, **HotMobile'21**) 
	- [HVC](https://pbg.cs.illinois.edu/papers/touseef23hvc.pdf) explores the challenges and opportunities of using emerging differentiated services across multiple networking layers. (**HotNets'23**)
	- [WTSN](files/wtsn-hotmobile25.pdf) achieves low latency in WiFi by using TSN through a multipath design (**HotMobile'25**)
	- [cISP](https://www.usenix.org/system/files/nsdi22-paper-bhattacherjee.pdf) proposes a design of wide-area networks that move data at near light speed in a vacuum (**NSDI'22**)
- Network emulation for network protocol evaluation
	- [CellReplay](https://www.usenix.org/system/files/nsdi25-sentosa.pdf) is an accurate record-and-replay emulator for cellular networks (**NSDI'25** 🏆) 
- Offloading VR/AR components to the cloud ([Project Agora](https://nsf-breaking-low-agora.illinois.edu))
	- [RemoteVIO](https://dl.acm.org/doi/10.1145/3712676.3714442) offloads head tracking to a remote server (**MMSys'25**)
	- [OpenWarp](https://dl.acm.org/doi/abs/10.1145/3712676.3714444) improves the cloud rendering experience through a mesh-based reprojection technique  (**MMSys'25**)  

Publications
======  

[CellReplay: Towards accurate record-and-replay for cellular networks](https://www.usenix.org/system/files/nsdi25-sentosa.pdf)  
**William Sentosa**, Balakrishnan Chandrasekaran, P. Brighten Godfrey, and Haitham Hassanieh.  
*In 22nd USENIX Symposium on Networked Systems Design and Implementation (USENIX NSDI'25)*   
🏆 <span style="color:red">**NSDI Community Award Winner** (best paper with open code and/or datasets)</span>  
[Code and datasets](https://github.com/williamsentosa95/cellreplay)

[DChannel: Accelerating Mobile Applications With Parallel High-bandwidth and Low-latency Channels](https://www.usenix.org/system/files/nsdi23-sentosa.pdf)  
**William Sentosa**, Balakrishnan Chandrasekaran, P. Brighten Godfrey, Haitham Hassanieh, and Bruce Maggs.  
*In 20th USENIX Symposium on Networked Systems Design and Implementation (USENIX NSDI'23)*

[Accelerating Mobile Applications With Parallel High-bandwidth and Low-latency Channels](https://dl.acm.org/doi/10.1145/3446382.3448357)  
**William Sentosa**, Balakrishnan Chandrasekaran, P. Brighten Godfrey, Haitham Hassanieh, Bruce Maggs, and Ankit Singla.  
*In 22nd International Workshop on Mobile Computing Systems and Applications (ACM HotMobile'21)*

[RemoteVIO: Offloading Head Tracking in an End-to-End XR System](https://dl.acm.org/doi/10.1145/3712676.3714442)  
Qinjun Jiang, Yihan Pang, **William Sentosa**, Steven Gao, Muhammad Huzaifa, Jeffrey Zhang, Javier Perez-Ramirez, Dibakar Das, Dave Cavalcanti, P. Brighten Godfrey, and Sarita Adve.  
*In 16th ACM Multimedia Systems Conference (ACM MMsys'25)*

[XRgo: Design and Evaluation of Rendering Offload for Low-Power Extended Reality Devices](https://dl.acm.org/doi/abs/10.1145/3712676.3714444)  
Steven Gao, Jeffrey Liu, Qinjun Jiang, Finn Sinclair, **William Sentosa**, P. Brighten Godfrey, and Sarita Adve.  
*In 16th ACM Multimedia Systems Conference (ACM MMsys'25)*

[Is WTSN the missing piece for low latency in general-purpose Wi-Fi?](files/wtsn-hotmobile25.pdf)  
Milind Kumar Vaddiraju, **William Sentosa**, Qinjun Jiang, Sarita Adve, Dave Cavalcanti, Dibakar Das, P. Brighten Godfrey, Javier Perez-Ramirez, and Deepak Vasisht.  
*In 26th International Workshop on Mobile Computing Systems and Applications (ACM HotMobile'25)*
  
[Boosting Application Performance using Heterogeneous Virtual Channels: Challenges and Opportunities](https://pbg.cs.illinois.edu/papers/touseef23hvc.pdf)  
Talal Touseef, **William Sentosa**, Milind Kumar Vaddiraju, Debopam Bhattacherjee, Bala Chandrasekaran, P. Brighten Godfrey, and Shubham Tiwari.  
*In Twenty-second ACM Workshop on Hot Topics in Networks (ACM HotNets'23)*

[cISP: A Speed-of-Light Internet Service Provider](https://www.usenix.org/system/files/nsdi22-paper-bhattacherjee.pdf)   
Debopam Bhattacherjee, Waqar Aqeel, Sangeetha Abdu Jyothi, Ilker Nadi Bozkurt, **William Sentosa**, Muhammad Tirmazi, Anthony Aguirre, Balakrishnan Chandrasekaran, P. Brighten Godfrey, Gregory Laughlin, Bruce Maggs, and Ankit Singla.  
*In 19th USENIX Symposium on Networked Systems Design and Implementation (USENIX NSDI'22)*
  
[Understanding and Auto-Adjusting Performance-Sensitive Configurations](https://dl.acm.org/doi/10.1145/3173162.3173206)  
Shu Wang, Chi Li, Henry Hoffmann, Shan Lu, **William Sentosa**, and Achmad Imam Kistijantoro.  
*In 23rd International Conference on Architectural Support for Programming Languages and Operating Systems (ACM ASPLOS'18)*