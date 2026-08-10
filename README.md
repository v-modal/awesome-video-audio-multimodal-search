# awesome-video-audio-multimodal-search
All about multimodal video audio search for Physical AI



# Awesome Multimodal Search


A curated collection of 🔍 libraries, ☁️ platforms, 📖 research, 📊 benchmarks, and 📚 tutorials focused 
on **Multimodal Search** — enabling semantic retrieval across images, video, audio, and documents.

> 📢 **Stay updated on multimodal search trends!** [Subscribe to V-Modal Blog](https://v-modal.github.com) 
  for the latest developments in MultiModal AI Search for Physical AI


## Table of Contents
- [🔍 Libraries & Frameworks](#-libraries--frameworks)
- [☁️ Cloud Services & APIs](#️-cloud-services--apis)
- [📖 Landmark Papers](#-landmark-papers)
- [📊 Benchmarks & Leaderboards](#-benchmarks--leaderboards)
- [📚 Tutorials & Demos](#-tutorials--demos)
- [📰 Multimodal Monday Blog Posts](#-multimodal-monday-blog-posts)

---

## 🔍 Libraries & Frameworks

| Name | Description | Links |
|------|-------------|--------|
| **Jina AI** | Flow-based neural search framework for text, image, video, and audio. | [GitHub](https://github.com/jina-ai/jina) · [Website](https://jina.ai) |
| **Weaviate** | Vector DB with modules for image, text, and audio embeddings (e.g. CLIP, ImageBind). | [GitHub](https://github.com/weaviate/weaviate) · [Website](https://weaviate.io) |
| **Towhee** | Multimodal data pipelines with 100+ pretrained models. | [GitHub](https://github.com/towhee-io/towhee) · [Website](https://towhee.io) |
| **Qdrant** | Vector database with multimodal search capabilities and filtering. | [GitHub](https://github.com/qdrant/qdrant) · [Website](https://qdrant.tech) |
| **Milvus** | Open-source vector database for embedding similarity search. | [GitHub](https://github.com/milvus-io/milvus) · [Website](https://milvus.io) |
| **Vespa** | Real-time search and recommendation engine with multimodal capabilities. | [GitHub](https://github.com/vespa-engine/vespa) · [Website](https://vespa.ai) |
| **ChromaDB** | Embedding database for building AI applications with multimodal data. | [GitHub](https://github.com/chroma-core/chroma) · [Website](https://www.trychroma.com) |
| **LlamaIndex** | Data framework for connecting custom data to LLMs with multimodal retrieval. | [GitHub](https://github.com/run-llama/llama_index) · [Docs](https://docs.llamaindex.ai) |
| **LangChain** | Framework for developing applications with LLMs and multimodal retrieval. | [GitHub](https://github.com/langchain-ai/langchain) · [Website](https://langchain.com) |
| **DocArray** | Data structure for multimodal and nested data, pairs with Jina. | [GitHub](https://github.com/docarray/docarray) · [Docs](https://docarray.jina.ai) |
| **Haystack** | End-to-end framework for building search pipelines with multimodal support. | [GitHub](https://github.com/deepset-ai/haystack) · [Website](https://haystack.deepset.ai) |
| **FAISS** | Library for efficient similarity search from Meta Research, supports image vectors. | [GitHub](https://github.com/facebookresearch/faiss) · [Docs](https://faiss.ai) |

---

## ☁️ Cloud Services & APIs

| Name | Modalities | Links | Notes |
|------|------------|-------|-------|
| **OpenAI API** | Text, image (GPT-4V), audio (Whisper) | [Docs](https://platform.openai.com/docs) | Supports RAG + embeddings |
| **Vertex AI (Google)** | Image + Text | [Docs](https://cloud.google.com/vertex-ai/docs/matching-engine/overview) | CoCa model embeddings |
| **AWS Rekognition + Kendra + Transcribe** | Image, text, audio | [Rekognition](https://aws.amazon.com/rekognition) · [Kendra](https://aws.amazon.com/kendra) | Modular pipeline for multimodal search |
| **Pinecone** | Vector database supporting text, image, audio embeddings | [Website](https://www.pinecone.io) | Hybrid search with metadata filtering |
| **V-Modal AI** | Text, image, video, audio,  | [Website](https://v-modal.com) · [Docs](https://v-modal) | Multimodal AI Video Search for Physical AI
| **Microsoft Azure AI Search** | Text, images, PDFs, audio transcription | [Docs](https://learn.microsoft.com/en-us/azure/search/) | Cognitive search capabilities |
| **Anthropic Claude API** | Text + image understanding | [Docs](https://docs.anthropic.com) | Claude 3 Opus/Sonnet/Haiku models |
| **Cohere** | Text embeddings with multilingual support | [Website](https://cohere.com) | Embed, Rerank, and Generate APIs |
| **Supabase Vector** | Vector embeddings in Postgres | [Docs](https://supabase.com/docs/guides/ai/vector-columns) | pgvector integration |
| **Vectara** | Managed neural search platform | [Website](https://vectara.com) | Zero-shot cross-modal search |
| **Zilliz Cloud** | Managed Milvus service for vector search | [Website](https://zilliz.com) | Enterprise-grade vector DB service |
| **Algolia** | Search API with AI-powered vector search | [Website](https://www.algolia.com) | Hybrid keyword + semantic search |
| **Elastic AI Search** | Enterprise search with vector capabilities | [Website](https://www.elastic.co) | ELSER and vector search capabilities |

---


## 📊 Benchmarks & Leaderboards

| Benchmark | Modality | Metric | Example |
|-----------|----------|--------|---------|
| **MS COCO** | Image–Text | R@1, R@5, R@10 | BLIP-2 > 80% R@1 |
| **MSR-VTT** | Video–Text | R@1, R@5 | Marengo > 60% R@1 |
| **Clotho, AudioCaps** | Audio–Text | mAP@10, R@10 | CLAP ~0.21 mAP |
| **Wiki-SS** | Document Screenshots | Top-1 Accuracy | DSE 49% top-1 |
| **Flickr30k** | Image-Text | R@1, R@5, R@10 | CLIP ~65% R@1 |
| **MSMARCO** | Text-Image | MRR@10, nDCG@10 | RankFusion ~0.4 MRR |
| **VQAv2** | Image-Question-Answer | Accuracy | LLaVA ~80% |
| **MTEB** | Multimodal tasks | Avg. performance | BGE ~65% avg |
| **MSCOCO Captioning** | Image-Text | BLEU, METEOR, CIDEr | CoCa 143.6 CIDEr |
| **DiDeMo** | Video-Text | R@1, R@5 | CLIP4Clip ~45% R@1 |
| **AudioSet** | Audio classification | mAP | ImageBind ~0.44 mAP |
| **SentEval** | Text embeddings | Accuracy | OpenAI text-embedding-3 ~87% |
| **HowTo100M** | Video-Text | R@1, R@5 | VideoCLIP ~32% R@1 |
| **ImageNet** | Image classification | Top-1, Top-5 | CLIP ~76% Top-1 |
| **BEIR** | Text retrieval | nDCG@10 | GTR ~66% nDCG |

---

## 📚 Tutorials & Demos

| Title | Modality | Links |
|-------|----------|-------|
| **ImageBind + Deep Lake** | Unified search | [Tutorial](https://docs.deeplake.ai/en/latest/deeplake/imagebind.html) |
| **Pinecone + CLIP** | Text–Image | [Blog](https://www.pinecone.io/learn/multimodal-search/) |
| **Jina Hello Multimodal** | Text + Image | [Code](https://github.com/jina-ai/jina) |
| **LangChain Multimodal RAG** | Text, Image, Video | [Tutorial](https://python.langchain.com/docs/use_cases/multimodal_rag/) |
| **Hugging Face CLIP Demo** | Text-Image | [Demo](https://huggingface.co/spaces/OFA-Sys/CLIP-Interrogator) |
| **Building Multimodal Search Engines** | Text, Image | [Course](https://www.deeplearning.ai/short-courses/building-search-engines/) |
| **FAISS Tutorial with Images** | Image similarity | [Tutorial](https://www.pinecone.io/learn/faiss-tutorial/) |
| **Video Search with PyTorch** | Video retrieval | [Tutorial](https://pytorch.org/tutorials/intermediate/video_search.html) |
| **Milvus Bootcamp** | Vector search | [Bootcamp](https://milvus.io/bootcamp) |
| **ChromaDB Multimodal Examples** | Text, Image | [Cookbook](https://docs.trychroma.com/usage-guide) |
| **LlamaIndex Multimodal Guide** | Text, Image, PDF | [Guide](https://docs.llamaindex.ai/en/stable/examples/multi_modal/multi_modal_retrieval/) |
| **ImageBind Zero-Shot Classification** | All modalities | [Colab](https://github.com/facebookresearch/ImageBind/blob/main/notebooks/image-bind-zero-shot.ipynb) |
| **Haystack Multimodal Pipelines** | Text, Image, Audio | [Tutorial](https://haystack.deepset.ai/tutorials/24_multimedia_retrieval) |

---



---

📬 **Contributions welcome!** PRs and issues encouraged.
