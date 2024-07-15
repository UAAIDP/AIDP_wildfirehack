## Main Event Page
[Join the University of Alberta and Amazon Web Services to Innovate Solutions for Wildfire Evacuations](https://www.ualberta.ca/events/research-innovation/aidp-hackathon.html)

## Sample Datasets
- [Sample Datasets form Natural Resources Canada](https://cwfis.cfs.nrcan.gc.ca/datamart)
- [Canada Wildfire 2023 - Hotspot Data from Kaggle](https://tinyurl.com/245elc84)
- [Another Dataset provide by Natural Resources Canada](https://tinyurl.com/277qk4em)

## Learning Resources
- [Introduction to Generative AI - Art of the Possible](https://tinyurl.com/26xznw7z)
- [Planning a Generative AI Project](https://tinyurl.com/2boebu95)
- [Foundations of Prompt Engineering](https://tinyurl.com/ywsfbtth)
- [Generative AI with Large Language Models](https://tinyurl.com/287ubg2x)
- [Introduction to LangChain](https://tinyurl.com/2zgnq8sy)
- [Serverless LLM apps with Amazon Bedrock](https://tinyurl.com/2nj2e4ga)
- [Prompt Engineering Best Practices for LLMs](https://tinyurl.com/2ry23xrs)
- [General Prompt Engineering using Party Rock](https://partyrock.aws/u/js2222/zEj353AmT/Prompt-Engineering-Guide-Introduction) - Learn General Prompt Engineering using Party Rock (free to use).
- [Anthropic Claude on Party Rock](https://partyrock.aws/u/schuylr/proiDgYx9/Claude-Prompt-Engineering-Interactive-Tutorial-Chapter-1) - Learn Anthropic Claude Interactive Prompt Engineering tutorial on Party Rock (free to use).
- [Anthropic’s Official Documentation](https://docs.anthropic.com/claude/docs/guide-to-anthropics-prompt-engineering-resources) - Anthropic’s Official Prompting Documentation

## Getting Started with AWS Workshop Studio 🎧
The link to the AWS Workshop will be provided closer to the Hackathon

---
## Data (extending the LLM)

### Retrieval-augmented generation (RAG)

Retrieval-augmented generation (RAG) for large language models (LLMs) aims to improve prediction quality by using an external datastore at inference time to build a richer prompt that includes some combination of context, history, and recent/relevant knowledge

- [What Is Retrieval Augmented Generation (RAG)](https://aws.amazon.com/what-is/retrieval-augmented-generation/)
- More in-depth intro [Retrieval Augmented Generation (RAG) for LLMs](https://www.promptingguide.ai/research/rag)


### Implementing RAG applications on AWS

#### RDS / pgVector:

- [Building AI-powered search in PostgreSQL using Amazon SageMaker and pgvector (Blog post)](https://aws.amazon.com/blogs/database/building-ai-powered-search-in-postgresql-using-amazon-sagemaker-and-pgvector/)
- AWS Samples (GitHub) - [RAG with Amazon Bedrock and PGVector on Amazon RDS](https://github.com/aws-samples/rag-with-amazon-bedrock-and-pgvector)

#### Knowledge Base:

- [Knowledge Bases now delivers fully managed RAG experience in Amazon Bedrock](https://aws.amazon.com/blogs/aws/knowledge-bases-now-delivers-fully-managed-rag-experience-in-amazon-bedrock/)
- [Knowledge Base for Amazon Bedrock](https://aws.amazon.com/bedrock/knowledge-bases/) - [Documentation](https://docs.aws.amazon.com/bedrock/latest/userguide/knowledge-base.html)

#### OpenSearch:

- [Amazon OpenSearch Service’s vector database capabilities explained](https://aws.amazon.com/blogs/big-data/amazon-opensearch-services-vector-database-capabilities-explained/)
- [Build scalable and serverless RAG workflows with a vector engine for Amazon OpenSearch Serverless and Amazon Bedrock Claude models (Blog post)](https://aws.amazon.com/blogs/big-data/build-scalable-and-serverless-rag-workflows-with-a-vector-engine-for-amazon-opensearch-serverless-and-amazon-bedrock-claude-models/)

---
## Agents for Bedrock

Enable generative AI applications to execute multistep tasks across company systems and data sources

- [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents.html)
- [Demo Video - Agents for Amazon Bedrock](https://www.youtube.com/watch?v=UcehCSSOMQA)
- [Amazon Bedrock Agents Quickstart](https://github.com/build-on-aws/amazon-bedrock-agents-quickstart) - Functional code example
- [Build a foundation model (FM) powered customer service bot with agents for Amazon Bedrock](https://github.com/aws-samples/agentsforbedrock-retailagent)

---
## AWS Basics

- [AWS Cloud Essentials](https://aws.amazon.com/getting-started/cloud-essentials/)
- [AWS Security Essentials](https://assorted-market-2d4.notion.site/AWS-Security-Essentials-97e1020385564db4a59fe41cd0ce5929)
- [AWS Networking Essentials](https://assorted-market-2d4.notion.site/AWS-Networking-Essentials-cb0e377177eb4bfbbeebc58c8ca180cd)
- [AWS Technical Essentials](https://assorted-market-2d4.notion.site/AWS-Technical-Essentials-612efb1dde3c4ac1a8a68969b7fd8d5b)
- [Architecting on AWS - Online Course Supplement](https://explore.skillbuilder.aws/learn/course/external/view/elearning/8319/architecting-on-aws-online-course-supplement)

---
## Examples / Ideas 🤔

### Amazon Bedrock Series

- GitHub Link: [RAG-Bedrock-Titan](https://github.com/janakiramm/rag-bedrock-titan)
- Video: [Implementing RAG with Amazon Bedrock and Amazon Titan - Part 1](https://www.youtube.com/watch?v=RIw_Ivvrp8g)

From the creator: "In this tutorial, we will build a chatbot based on the Retrieval Augmented Context generation technique. Amazon OpenSearch Serverless is used as the vector database, Amazon Titan is used for generating text embeddings and as an LLM, and Amazon Bedrock API is used for invoking the Titan model."

### ICBC Chatbot

A chatbot that uses the ICBC website information as its knowledge base to answer questions that are asked by the users who want to learn more about driving licenses, insurance, and anything ICBC-related. This website can be hosted on an EC2 instance. This chatbot can be based on the [Flask Framework](https://flask.palletsprojects.com/), which provides a light-weight python-based web framework.

