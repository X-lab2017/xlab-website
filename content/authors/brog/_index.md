---

# Username (this should match the folder name)
authors:
- brog

# Is this the primary user of the site?
superuser: true


# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
- admin
---

**书蛙（Brog）** 是一个专为学术成长者打造的**智能资料索引系统**。系统致力于帮助用户体验少检索、少筛选、易接受、更高效的学术之旅。在精简用户学习成本的同时，也尝试提供更精准的反馈，让不同知识背景的用户找到适合自己的学习路径，使得学习和科研过程更加流畅。

针对目标用户的痛点，我们的主要实现目标有:
- 针对初学者用户对于新知识的学习需求，针对性的为其提供相关知识点的快速索引
- 针对用户对于知识的回顾复习需求，提供相关知识点的快速索引助其形成完整的知识脉络
- 针对用户在阅读论文时的查阅需求，从数据库中查找相关知识点及定义，节省研究者时间成本

为了提供个性化的资料索引服务，**书蛙** 将为每一个用户自动创建合适的用户画像。这一画像会随着用户的使用，系统会自动学习用户的学习习惯和知识背景成长过程，从而进一步的提升用户体验。实现该项目所利用的主要技术点包括:**文档文字识别(OCR)**, **自然语言处理(NLP)**, **知识图谱(KG)** 和 **推荐算法(RA)** 等。