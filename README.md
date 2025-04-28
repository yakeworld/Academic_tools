# Academic_tools
## 缘由
快速获取领域知识并撰写学术论文，一致是研究热点。Poe搭建了一个工具，利用AI来帮助提取关键词，结合参考文献来润色论文，非常方便，其不足是国内访问不方便。https://poe.com/Academic_Search_mul
可以将功能分解：
### 1） 文献检索
可以用DeepSeek来推荐关键词
用[keywords_find](./Academic_tools/keywords_find.html)来缩小检索访问。
semantic scholar来找到一篇最相关论文，然后顺藤摸瓜根据参考文献以及被引文献来找到相关文献，也是非常方便。semantic scholar支持选择和保存文献，非常实用。也支持导出BIBTEX格式，其缺点是文献内容不全，可以通过[bibtex_enhance](./Academic_tools/bibtex_enhance.html)来补充和完善。
### 2） 全文下载
[学术文献搜索器](https://yakeworld.github.io/Academic_tools/Academic_Search_mul.html)所导出文献包括全文下载地址。
部分文献可以通过SCI-HUB来下载。
### 3）论文撰写
[notebooklm](https://notebooklm.google.com/)上传论文和参考文献，通过对话确定论文题目，可以快速完整论文撰写。
通过提示词构建，支持参考文献引用[@key]
### 4）论文修改和渲染
[Makrdown_academic](https://yakeworld.github.io/Academic_tools/Academic_bibtex.html)支持bibtex引用markdown格式渲染，支持参考文献格式设定，打开google 全文翻译可以支持左侧英文右侧中文显示，快速完成论文修改。可以在上传到notebooklm反复润色。

## 工具列表

1. [Makrdown_academic](https://yakeworld.github.io/Academic_tools/Academic_bibtex.html)
   这是一个使用 CodeMirror 和 Tailwind CSS 构建的 Markdown 编辑器，它具备 BibTeX 引用支持。用户可以实时预览 Markdown 内容，并能通过简单的操作插入和管理学术引用。编辑器支持多种参考文献格式（APA、MLA、Chicago、Harvard、IEEE），支持自定义参考文献格式，并提供暗黑模式切换功能，旨在为需要撰写学术文档的用户提供便捷的体验。 

3. [Literature_Search_mu](https://yakeworld.github.io/Academic_tools/Academic_Search_mul.html)
学术文献搜索器，专注学术文献快速检索，集成三大数据库，让科研人员更高效地找到所需资料。
主要特点：
多库集成： 同时搜索 PubMed, Semantic Scholar 和 arXiv，覆盖广泛的学术领域。
筛选精准： 支持关键词、作者、年份等多条件筛选，快速定位目标文献。
BibTeX导出： 一键导出 BibTeX 格式，方便论文写作和文献管理。
适用人群： 科研人员、研究生、学者等需要查阅学术文献的人群。

3. [keywords_find](https://yakeworld.github.io/Academic_tools/keywords_find.html)
关键词的组合是非常关键的，可以缩小检索范围，精准找到所需要的文献

4. [期刊信息检索查询](https://yakeworld.github.io/Academic_tools/zkyfqv2.html)
包括中科院2025期刊分区信息，SCI指数信息，支持筛选和排序。
数据来源于https://github.com/hitfyd/ShowJCR

5. [bibtex_enhance](https://yakeworld.github.io/Academic_tools/bibtex_enhance.html)
Semantic Scholar检索论文，快速找到目标文献并保存和导出参考文献是比较合适的文献检索方法，缺点是导出的bibtex文献内容不完整，缺乏全文下载地址，卷期页等信息。小工具用来补充和完善文献。


 
