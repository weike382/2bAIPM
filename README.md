
# 2bAIPM

学习如何成为人工智能产品经理（AIPM）并将其体系化总结成知识库：知识库(Knowledge Base)是指一个易操作、易利用、全面有组织的知识集群，针对某些领域问题求解的需要，采用某种知识表示方式在计算机中存储、组织、管理和使用的互相联系的知识片集合。这些知识可以包括与该领域相关的理论知识、事实数据以及常识性知识，或者是专家经验得到的启发式知识。简而言之，知识库就是储存某一领域的知识，可以理解为知识管理。
参考项目：https://stevenjokess.github.io/2bPM/

## Docker里d2lbook2生成书

利用项目：https://github.com/aieye-top/d2l-book2

```bash
docker run --rm --name 2bPM -e HTTP_PROXY=127.0.0.1:1080 -ditv /d/onedrive/Documents/read/2bPM:/d2lbook2/2bPM registry.cn-shanghai.aliyuncs.com/csq-dl/d2l-book2:latest   /bin/bash

docker exec -it 2bPM /bin/bash

cd 2bPM

d2lbook2 build html

d2lbook2 deploy html
```


## 声明

若有侵权，请联系删除。若制作相关衍生作品时，请务必留下原文的URL链接。

```
@misc{2bAIPM,
  author = {weike382},
  title = {2bAIPM},
  year = {2025},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/weike382/2bAIPM}},
  note         = {A knowledge base for becoming an AI Product Manager.}
}

@misc{2bPM,
  author = {Shuqi Cai},
  title = {2bPM},
  year = {2020},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/StevenJokess/2bPM}},
}

```
