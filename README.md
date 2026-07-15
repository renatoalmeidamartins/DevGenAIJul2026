# DevGenAIJul2026

## Class and course book links
- [Lab and coursebook access](https://us-east-1.student.classrooms.aws.training/class/ilt%23k2k2Hrr9PGJTdB2uWSpiRE)
- [Skill builder, with access to hundreds of courseware, free and subscription-based](https://skillbuilder.aws/)

## Day 1 links
- [Database migration service walkthroughs](https://docs.aws.amazon.com/dms/latest/sbs/dms-sbs-welcome.html)
- [Migrating genai workloads to bedrock through Transform](https://aws.amazon.com/blogs/migration-and-modernization/migrate-your-ai-workloads-to-amazon-bedrock-with-aws-transform/)
- [Agentic AI capabilities built into AWS Transform to improve migrations](https://aws.amazon.com/blogs/migration-and-modernization/accelerating-cloud-migration-with-aws-transform-and-generative-ai/)
- [Sagemaker built-in algorithms](https://docs.aws.amazon.com/sagemaker/latest/dg/algos.html)
- [Neural Network zoo](https://www.asimovinstitute.org/neural-network-zoo/)
- [Transformers in GenAI](https://aws.amazon.com/what-is/transformers-in-artificial-intelligence/)
- [Attention is all you need](https://arxiv.org/pdf/1706.03762)
- [Spatial Transformer Networks](https://arxiv.org/pdf/1506.02025)
- [Measuring GitHub Copilot’s Impact on Productivity](https://cacm.acm.org/research/measuring-github-copilots-impact-on-productivity/)
- [Influence response generation with inference parameters](https://docs.aws.amazon.com/bedrock/latest/userguide/inference-parameters.html)
- [Converse and ConverseStream](https://docs.aws.amazon.com/bedrock/latest/userguide/conversation-inference.html) are improvements over the InvokeModel and InvokeModelWithResponseStream, as they provide a consistent API. With the InvokeModel*, you need to format the model parameters in a way that is model-specific.
- [Bedrock-mantle endpoint](https://aws.amazon.com/blogs/aws/try-the-new-console-experience-in-amazon-bedrock-optimized-for-anthropic-and-openai-compatible-apis/), introduced to offer full compatibility with the "de facto" standards for LLM interactions (OpenAI's Chat completions and Responses APIs, as well as Anthropic's Messages API). 
- [Bedrock Data Automation](https://docs.aws.amazon.com/bedrock/latest/userguide/bda.html)
- [BDA sample notebooks](https://github.com/aws-samples/sample-document-processing-with-amazon-bedrock-data-automation)
- [LLM-as-a-Judge uses prompts to generate the metrics](https://docs.aws.amazon.com/bedrock/latest/userguide/model-evaluation-metrics.html). Bedrock has a lot of [built-in prompts](https://docs.aws.amazon.com/bedrock/latest/userguide/model-evaluation-type-judge-prompt.html)
- [Bedrock prompting best practices](https://docs.aws.amazon.com/bedrock/latest/userguide/design-a-prompt.html)
- [Prompt engineering defined by AWS](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-prompt-engineering.html)
- [Implementing advanced prompt engineering with Amazon Bedrock](https://aws.amazon.com/blogs/machine-learning/implementing-advanced-prompt-engineering-with-amazon-bedrock/)
- [Prompt engineering inside "generic" AWS doc](https://aws.amazon.com/what-is/prompt-engineering/)
- [Intelligent prompt routing](https://docs.aws.amazon.com/bedrock/latest/userguide/prompt-routing.html) allows you to expose a single endpoint and let Bedrock choose between two models from the same provider (one simpler, one more complex) based on the complexity of the task and the likelihood of similar answers in both models.
- [ReAct - reasoning and action on LLMs](https://arxiv.org/pdf/2210.03629)
- [ReWOO - reasoning without observation](https://arxiv.org/pdf/2305.18323)
- [Improve the relevance of query responses with a reranker model in Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/rerank.html)
- [Amazon Bedrock introduces new advanced prompt optimization and migration tool](https://aws.amazon.com/blogs/aws/amazon-bedrock-introduces-new-advanced-prompt-optimization-and-migration-tool/)
- [Provisioned throughput](https://docs.aws.amazon.com/bedrock/latest/userguide/prov-throughput.html)
- [Batch inference](https://docs.aws.amazon.com/bedrock/latest/userguide/batch-inference.html)
- [Application inference profiles](https://docs.aws.amazon.com/bedrock/latest/userguide/inference-profiles-create.html), useful for tracking usage and granting acces
- [Prompt caching in Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/prompt-caching.html#prompt-caching-models), supported by Anthropic's models and Amazon Nova series.
- [Blog covering prompt caching](https://aws.amazon.com/blogs/machine-learning/effectively-use-prompt-caching-on-amazon-bedrock/)
- [Announcement of 1-hour TTL support for caching in Anthropic's models](https://aws.amazon.com/about-aws/whats-new/2026/01/amazon-bedrock-one-hour-duration-prompt-caching/)
- [Lambda durable functions](https://aws.amazon.com/blogs/aws/build-multi-step-applications-and-ai-workflows-with-aws-lambda-durable-functions/)
- [Lambda durable functions vs Step Functions](https://docs.aws.amazon.com/lambda/latest/dg/durable-step-functions.html)
- [contents that can be used in the messages section: document, image, cachePoint](https://docs.aws.amazon.com/bedrock/latest/userguide/conversation-inference.html)
- [TTL in DynamoDB](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/TTL.html)
## Day 2 links
- [Dive deep into vector data stores using Amazon Bedrock Knowledge Bases](https://aws.amazon.com/blogs/machine-learning/dive-deep-into-vector-data-stores-using-amazon-bedrock-knowledge-bases/)
- [Amazon Nova Multimodal Embeddings: State-of-the-art embedding model for agentic RAG and semantic search](https://aws.amazon.com/blogs/aws/amazon-nova-multimodal-embeddings-now-available-in-amazon-bedrock/)
- [Introducing Amazon S3 Vectors: First cloud storage with native vector support at scale (preview)](https://aws.amazon.com/blogs/aws/introducing-amazon-s3-vectors-first-cloud-storage-with-native-vector-support-at-scale/)
- [Launching S3 Files, making S3 buckets accessible as file systems](https://aws.amazon.com/blogs/aws/launching-s3-files-making-s3-buckets-accessible-as-file-systems/)
- [Vector store integrations in Langchain](https://docs.langchain.com/oss/python/integrations/vectorstores), just to highlight that there are many options for storing your vectors. It is certainly not an exhaustive, only the ones natively integrated with Langchain
