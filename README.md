# Aashir Haque
**Senior Software Engineer · Backend Systems & Agentic AI**

I build payment services, search APIs, and AI workflows. At Golootlo I designed a shared payment service for one-time charges and subscriptions. At Stats AI I build retrieval and inference pipelines for review data.

Glen Ellyn, Illinois · Authorized to work in the U.S. without sponsorship  
[Portfolio](https://aashirhaq.github.io/) · [LinkedIn](https://www.linkedin.com/in/aashirhaq/) · [Email](mailto:aashirulhaque@gmail.com)

## Production dashboard · Golootlo

| Payments | Search | Distributed systems |
|:---|:---|:---|
| **35K+** daily subscription transactions | **50+** customer-facing APIs | **500K+** monthly background jobs |
| **10+** gateways behind one service | **50%** lower database load after caching and query optimization | **60K+** peak concurrent users across the platform |

I integrated Google Pay through CyberSource and worked with QA and finance to verify checkout and reconcile transactions before launch. For search, I moved reads to Elasticsearch and kept the index in sync with MySQL. [Read the payment architecture case study →](https://aashirhaq.github.io/projects/payment-orchestration/)

## Engineering projects

| System | Engineering decision | Explore |
|:---|:---|:---|
| **Job Hunter** · AWS | A scheduled Lambda workflow scores listings with Bedrock and falls back to weighted keywords when model scoring fails. | [Source](https://github.com/aashirhaq/job-hunter) |
| **Steam Review Sentiment** · Python | Daily batch inference scores reviews across five games. Streamlit reads a JSON report, keeping the roughly 260 MB model out of the web process. | [Source](https://github.com/aashirhaq/steam-review-sentiment) |
| **Multimodal Image Search** · Team contribution | I updated the vector-search integration and added fallbacks for generated summaries in a CLIP and Qdrant application. | [Public fork](https://github.com/aashirhaq/streamlit_image_search_db) |
| **Little Ummah Studio** · Local AI | Scene and dialogue checks identify failed takes. The pipeline uses the failure reason to adjust the next attempt, caps retries, and routes the episode for human review. | [Walkthrough](https://www.linkedin.com/in/aashirhaq/details/featured/) · [Series](https://www.youtube.com/@LittleMuslimsCorner) |

### Agent reliability

In an operations workflow I built, the model drafts a request, application code enforces policy, and a reviewer approves the exact version that can execute. In a separate publishing workflow, the system records completed steps so retries can resume after a partial failure.

## GitHub activity

**1,238 contributions** in the preceding year as of November 8, 2026. The contribution calendar below shows the current count.

**Backend** · PHP/Laravel, Node.js/NestJS, Python/FastAPI  
**Data and infrastructure** · MySQL, Redis, Elasticsearch/OpenSearch, AWS SQS and SNS  
**AI engineering** · PyTorch, Hugging Face Transformers, Amazon Bedrock, CLIP, Qdrant
