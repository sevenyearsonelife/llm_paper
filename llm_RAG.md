# paper
[[2404.16130] From Local to Global: A Graph RAG Approach to Query-Focused Summarization (arxiv.org)](https://arxiv.org/abs/2404.16130)
> 这篇文章主要讲了


[[2312.10997] Retrieval-Augmented Generation for Large Language Models: A Survey (arxiv.org)](https://arxiv.org/abs/2312.10997)

https://arxiv.org/abs/2312.06648
> 基于命题的检索

https://arxiv.org/abs/2401.05856
> 检索增强生成系统工程中的七个失败点


[[2401.05856] Seven Failure Points When Engineering a Retrieval Augmented Generation System (arxiv.org)](https://arxiv.org/abs/2401.05856)


[[2407.02485] RankRAG: Unifying Context Ranking with Retrieval-Augmented Generation in LLMs (arxiv.org)](https://arxiv.org/abs/2407.02485)



[[2407.01219] Searching for Best Practices in Retrieval-Augmented Generation (arxiv.org)](https://arxiv.org/abs/2407.01219)
>论文主要研究了 RAG 技术的最佳实践方法，从 RAG 整体工作流、每个步骤的不同方法选择、实验对比方法，来论证 RAG 过程的影响因素，如何找到最佳实践。


https://arxiv.org/abs/2401.05856


# video
[好贵！GraphRAG好确实好，就是有点费Token_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1hi421h7Vp/?spm_id_from=333.1007.tianma.9-4-34.click&vd_source=1781cc4e540cf27bcf0ed040e7626434)


[2024首发！斯坦福吴恩达《使用LlamaIndex构建主动式RAG#Building Agentic RAG with LlamaIndex》最新项目中英字幕_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1tw4m1q7PC/?spm_id_from=333.788.recommend_more_video.0&vd_source=1781cc4e540cf27bcf0ed040e7626434)


https://www.youtube.com/watch?v=8OJC21T2SL4
> 文本分割的5个级别





https://www.youtube.com/watch?v=1a8bdIjjO1A
> Haystack US 2023 - Roie Schwaber Cohen: Better Semantic Search with Hybrid (Sparse-Dense) Search



# blog
https://docs.llamaindex.ai/en/stable/examples/node_parsers/semantic_chunking/
> 语义分割

https://python.langchain.com/v0.1/docs/modules/data_connection/document_transformers/semantic-chunker/
> 语义分割

https://templates.langchain.com/new?integration_name=propositional-retrieval
> 命题检索

https://www.53ai.com/news/qianyanjishu/2024062131746.html
> 介绍了多种文本块切割方法

https://aibard123.com/digest/2024/0326/RAG%E7%B3%BB%E5%88%9705%E5%9F%BA%E4%BA%8E%E8%AF%AD%E4%B9%89%E7%9A%84Chunk%E5%88%86%E5%89%B2/
> 介绍了基于语义的文本块切割方法

https://www.sbert.net/examples/applications/cross-encoder/README.html
https://sbert.net/examples/applications/retrieve_rerank/README.html
https://osanseviero.github.io/hackerllama/blog/posts/sentence_embeddings2/
> 极好的文章【从推荐的角度理解rag中的检索模块】
> rag中的检索模块可以使用推荐系统中的【召回+排序】去做
> 原子命题是一个非常好的idea，可以将其理解为淘宝上的一个个商品
> 仅仅通过向量召回，这仅仅能保证弱相关性。通过query召回原子命题，然后通过精排模型排序，这才能保证强相关性
> 在原子命题上添加metadata、summary和question，本质上在考虑更多的特征（精排模型需要更多的特征）
> metadata和向量可以算作是两个召回通路
> 最终我们需要微调一个精排模型，来计算query和chunk的相关性

# MTEB
https://huggingface.co/spaces/mteb/leaderboard