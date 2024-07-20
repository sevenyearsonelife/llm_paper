# paper
[[2404.16130] From Local to Global: A Graph RAG Approach to Query-Focused Summarization (arxiv.org)](https://arxiv.org/abs/2404.16130)
> 这篇文章主要讲了


[[2312.10997] Retrieval-Augmented Generation for Large Language Models: A Survey (arxiv.org)](https://arxiv.org/abs/2312.10997)

https://arxiv.org/abs/2312.06648
> 基于命题的检索

https://arxiv.org/abs/2401.05856
> 检索增强生成系统工程中的七个失败点

https://arxiv.org/abs/2210.07316
> MTEB: Massive Text Embedding Benchmark

[[2401.05856] Seven Failure Points When Engineering a Retrieval Augmented Generation System (arxiv.org)](https://arxiv.org/abs/2401.05856)


[[2407.02485] RankRAG: Unifying Context Ranking with Retrieval-Augmented Generation in LLMs (arxiv.org)](https://arxiv.org/abs/2407.02485)



[[2407.01219] Searching for Best Practices in Retrieval-Augmented Generation (arxiv.org)](https://arxiv.org/abs/2407.01219)
>论文主要研究了 RAG 技术的最佳实践方法，从 RAG 整体工作流、每个步骤的不同方法选择、实验对比方法，来论证 RAG 过程的影响因素，如何找到最佳实践。


https://arxiv.org/abs/2401.00368
> Improving Text Embeddings with Large Language Models
> 在本文中，我们介绍了一种新颖且简单的方法，仅使用合成数据和少于 1k 的训练步骤即可获得高质量的文本嵌入。 现有方法通常依赖于使用数十亿个弱监督文本对进行多阶段中间预训练，然后使用一些标记数据集进行微调，与此不同的是，我们的方法不需要构建复杂的训练管道或依赖于手动收集的数据集 通常受到任务多样性和语言覆盖范围的限制。 我们利用专有的法学硕士为 93 种语言的数十万个文本嵌入任务生成各种合成数据。 然后，我们使用标准对比损失对合成数据上的仅限开源解码器的 LLM 进行微调。 实验表明，我们的方法在不使用任何标记数据的情况下，在竞争激烈的文本嵌入基准上实现了强大的性能。 此外，当使用合成数据和标记数据的混合进行微调时，我们的模型在 BEIR 和 MTEB 基准上设置了新的最先进的结果。

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

https://osanseviero.github.io/hackerllama/blog/posts/sentence_embeddings/
> 值得深入研究！极好的文章
https://arxiv.org/abs/1908.10084 
> Sentence-BERT：使用 Siamese BERT 网络的句子嵌入 
https://www.sbert.net/examples/applications/semantic-search/README.html
> 对称与非对称语义搜索
https://cookbook.openai.com/examples/search_reranking_with_cross-encoders
https://docs.llamaindex.ai/en/stable/examples/finetuning/cross_encoder_finetuning/cross_encoder_finetuning/
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

https://neo4j.com/blog/graphrag-manifesto/
> 图RAG的宣言

https://microsoft.github.io/graphrag/posts/query/0-global_search/



# MTEB
https://huggingface.co/spaces/mteb/leaderboard