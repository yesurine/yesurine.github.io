---
published: false
---

Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.


## HBase

요구에 의해 HBase 공식 사이트나 책을 통해 구조나 운영 방법을 배워 왔는데 기술적으로 좀 더 자세히 알고 싶어 이 곳에 기록을 남길 예정이다.


## HBase의 구성

HBase가 기본적으로 어떻게 구성되어 있는지 살펴보자.

HBase는 크게 HMaster(HBase Master), RegionServer 2가지 Daemon으로 구성되어 있다.
이름에서 보면 알 수 있듯이 Master-Worker 구조이며 분산 저장소의 기능을 수행하는 것이 목표이다.


