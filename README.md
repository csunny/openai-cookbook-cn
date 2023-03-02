# OpenAI-Cookbook-cn

OpenAI CookBook 为完成[OpenAI API](https://openai.com/api/)的通用任务分享了一些示例代码。

运行这些示例代码, 你需要一个OpenAI的账号以及其关联的API 密钥([创建API密钥](https://beta.openai.com/signup))

绝大多数的样例代码是用Python编写的，这些概念也可以用于其他任何语言。


## 最近添加 【上新】
---
- [使用向量数据库对Redis进行嵌入搜索](https://github.com/openai/openai-cookbook/tree/main/examples/vector_databases/redis) [2023年2月15日]
- [使用嵌入的问答网站](https://github.com/openai/openai-cookbook/tree/main/apps/web-crawl-q-and-a) [2023年2月11日]
- [使用嵌入的文件问答](https://github.com/openai/openai-cookbook/tree/main/apps/file-q-and-a) [2023年2月11日] 
- [可视化嵌入中的权重与偏差](https://github.com/openai/openai-cookbook/blob/main/examples/Visualizing_embeddings_in_W%26B.ipynb) [2023年2月9日]
- [使用松散检索增强来生成问题答案](https://github.com/openai/openai-cookbook/blob/main/examples/vector_databases/pinecone/Gen_QA.ipynb) [2023年2月8日]


## 指南与样例
---
- 接口使用
    - [如何处理速率限制](https://github.com/openai/openai-cookbook/blob/main/examples/How_to_handle_rate_limits.ipynb)
        - [并行处理脚本样例来避免命中速率限制](https://github.com/openai/openai-cookbook/blob/main/examples/api_request_parallel_processor.py)
    - [如何用tiktoken来对语言符号进行计数](https://github.com/openai/openai-cookbook/blob/main/examples/How_to_count_tokens_with_tiktoken.ipynb)
    - [如何流式化输出](https://github.com/openai/openai-cookbook/blob/main/examples/How_to_stream_completions.ipynb)
- GPT
    - [如何格式化ChatGPT模型的输入](https://github.com/openai/openai-cookbook/blob/main/examples/How_to_format_inputs_to_ChatGPT_models.ipynb)
- GPT-3
    - [指南: 如何使用大语言模型](https://github.com/openai/openai-cookbook/blob/main/how_to_work_with_large_language_models.md)
    - [指南: 提升可靠性的技巧](https://github.com/openai/openai-cookbook/blob/main/techniques_to_improve_reliability.md)
    - [如何使用多步提示来写测试用例](https://github.com/openai/openai-cookbook/blob/main/examples/Unit_test_writing_using_a_multi-step_prompt.ipynb)
    - [文本编写样例](https://github.com/openai/openai-cookbook/blob/main/text_writing_examples.md)
    - [文本解释样例](https://github.com/openai/openai-cookbook/blob/main/text_explanation_examples.md)
    - [文本编辑样例](https://github.com/openai/openai-cookbook/blob/main/text_editing_examples.md)
    - [代码编写样例](https://github.com/openai/openai-cookbook/blob/main/code_writing_examples.md)
    - [代码解释样例](https://github.com/openai/openai-cookbook/blob/main/code_explanation_examples.md)
    - [代码编辑样例](https://github.com/openai/openai-cookbook/blob/main/code_editing_examples.md)
- 嵌入
    - [文本比对样例](https://github.com/openai/openai-cookbook/blob/main/text_comparison_examples.md)
    - [如何获取嵌入](https://github.com/openai/openai-cookbook/blob/main/examples/Get_embeddings.ipynb)
    - [使用嵌入回答问题](https://github.com/openai/openai-cookbook/blob/main/examples/Question_answering_using_embeddings.ipynb)
    - [使用嵌入的语义搜索](https://github.com/openai/openai-cookbook/blob/main/examples/Semantic_text_search_using_embeddings.ipynb)
    - [使用嵌入做推荐](https://github.com/openai/openai-cookbook/blob/main/examples/Recommendation_using_embeddings.ipynb)
    - [使用嵌入聚类](https://github.com/openai/openai-cookbook/blob/main/examples/Clustering.ipynb)
    - [嵌入可视化在2D或者3D场景](https://github.com/openai/openai-cookbook/blob/main/examples/Visualizing_embeddings_in_2D.ipynb)
    - [嵌入长文本](https://github.com/openai/openai-cookbook/blob/main/examples/Embedding_long_inputs.ipynb)
- 微调GPT-3
    - [指南: 微调GPT-3在文本分类场景下的最佳实践](https://docs.google.com/document/d/1rqj7dkuvl7Byd5KQPUJRxc19BJt8wo0yHNwK84KfU3Q/edit)
    - [微调分类](https://github.com/openai/openai-cookbook/blob/main/examples/Fine-tuned_classification.ipynb)
- DALL-E
    - [如何生成并编辑图片使用DALL-E](https://github.com/openai/openai-cookbook/blob/main/examples/dalle/Image_generations_edits_and_variations_with_DALL-E.ipynb)
- Azure OpenAI
    - [如何用Azure OpenAI获取结果](https://github.com/openai/openai-cookbook/blob/main/examples/azure/completions.ipynb)
    - [如何用Azure OpenAI获取嵌入](https://github.com/openai/openai-cookbook/blob/main/examples/azure/embeddings.ipynb)
    - [如何用Azure OpenAI微调GPT-3](https://github.com/openai/openai-cookbook/blob/main/examples/azure/finetuning.ipynb)
- 应用
    - [文件的问答](https://github.com/openai/openai-cookbook/blob/main/apps/file-q-and-a)
    - [网页抓取问答](https://github.com/openai/openai-cookbook/blob/main/apps/web-crawl-q-and-a)

## 相关资料
------
除了这里列出来的代码示例, 你也可以通过以下的资源学习OpenAI API:
- 使用API在[OpenAI Playgroud](https://beta.openai.com/playground)
- 阅读[OpenAI文档](https://beta.openai.com/docs/introduction)中相关API说明
- 在开源论坛里面进行讨论 [OpenAI社区论坛](https://community.openai.com/top?period=monthly)
- 在[帮助中心](https://help.openai.com/en/)寻求帮助
- 查看相关的提示在[OpenAI 样例](https://beta.openai.com/examples)中
- 进行一些免费的研究通过[ChatGPT](https://chat.openai.com/)
- 及时了解[OpenAI博客](https://openai.com/blog/)

## 贡献
-----
如果以上这些例子或者指南你不喜欢, 可以随时在[问题页面](https://github.com/openai/openai-cookbook/issues)提出建议



