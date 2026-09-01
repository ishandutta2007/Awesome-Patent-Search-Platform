# Awesome-Patent-Search-Platform

## Top Patent Search Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Patent Search, Prior-Art Discovery, Patent Landscaping, Intellectual Property Intelligence & Patent Data Analysis*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms**, commercial patent intelligence products, public patent search services, and **open-source projects** for **Patent Search Platforms**. These tools help researchers, patent professionals, IP teams, inventors, R&D organizations, universities, and legal teams search patent literature, discover prior art, analyze patent families, monitor competitors, perform patent landscaping, and explore global intellectual-property datasets.

**Examples** include PatSnap, Questel Orbit, Google Patents Public Datasets, Lens.org, IFI CLAIMS, Gridlogics PatSeer, Derwent Innovation, InnovationQ Plus, IP.com, and Ambercite (the category leaders).

**Open-source emphasis**: This section is heavily expanded with open-source patent research platforms, patent-data pipelines, EPO OPS clients, USPTO data tooling, patent analytics repositories, semantic-search frameworks, natural-language-processing libraries, knowledge-graph tools, and self-hosted search infrastructure. While comparatively few complete commercial-grade patent search interfaces are fully open source, the underlying ecosystem for building custom patent search and analysis systems is extensive. Projects such as PatZilla, PQAI, Google Patents Public Data examples, EPO OPS clients, PatentsView pipelines, Elasticsearch/OpenSearch, Apache Solr, and modern embedding frameworks can be combined to build powerful self-hosted patent intelligence platforms. PatZilla, for example, provides a modular patent information research platform and data integration toolkit, while Google’s public-data repository demonstrates patent landscaping, claim extraction, and claim-breadth analysis workflows.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

* [SaaS/Hosted Platforms](#saas-hosted-platforms)
* [Open-Source GitHub Projects](#open-source-github-projects)
* [Additional Strong Open-Source Options](#additional-strong-open-source-options)
* [How to Contribute](#how-to-contribute)
* [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Description | Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[PatSnap](https://www.patsnap.com/)** | Global patent intelligence and innovation platform providing patent search, technology landscaping, competitive intelligence, analytics, and AI-assisted research workflows. | Starts at ~$100/month (Eureka Engineering Pro / Open Platform Pro); Patent Searching Pro at ~$400/month | Free basic tier (Eureka Basic & Open Platform Starter with 10,000 API credits, ~10 searches/month); 7-day free trial on select modules |
| **[Questel Orbit Intelligence](https://www.questel.com/)** | Enterprise patent search and IP intelligence platform offering global patent databases, sophisticated search, patent family analysis, competitive monitoring, and patent analytics. | Starts at ~$3,000 – $5,000/user/year (entry commercial single-seat quote) | 15-day free trial upon request and registration; no permanent free tier |
| **[Google Patents](https://patents.google.com/)** | Widely used public patent search platform offering full-text patent search, patent-family information, citations, classifications, inventor and assignee discovery, and machine-readable patent data access. | Free ($0) | Free forever; unrestricted global patent search and document downloads (subject to standard automated request limits) |
| **[Google Patents Public Datasets](https://console.cloud.google.com/marketplace/product/google_patents_public_datasets/public_patents)** | Large-scale patent datasets available through BigQuery for SQL-based patent analysis, patent landscaping, claim analysis, and custom research workflows. | Starts at $6.25 per TB (BigQuery on-demand analysis beyond monthly free allowance) | Free forever for first 1 TB/month of query data processing under Google Cloud Free Tier |
| **[The Lens](https://www.lens.org/)** | Patent and scholarly knowledge platform supporting structured patent search, classification search, filtering, collections, alerts, visualizations, and links between patents and scholarly literature. | Free for non-commercial/academic use; Commercial licenses start at $1,000/year (~$83.33/month) | Free forever for non-commercial and individual research (unlimited searching, up to 10,000 items in saved collections, alerts); 14-day free trial for patent API |
| **[IFI CLAIMS Patent Services](https://www.ificlaims.com/)** | Patent data and intellectual-property intelligence provider offering structured patent information, patent search, analytics, and enterprise data products. | Starts at ~$10,000/year for direct API subscriptions; BigQuery access at standard $6.25/TB | Free trial access provided for API testing upon request; free public bibliographic dataset table on Google BigQuery (up to 1 TB/month free queries) |
| **[Gridlogics PatSeer](https://patseer.com/)** | Patent research and analytics platform focused on prior-art search, patent landscaping, competitive intelligence, portfolio analysis, and technology monitoring. | Starts at ~$900/user/quarter (~$300/user/month or ~$3,600/year for Explorer/Premier base tier) | 14-day free trial (no credit card required); no permanent free tier |
| **[Derwent Innovation](https://clarivate.com/derwent/)** | Enterprise patent intelligence platform from Clarivate combining global patent content, enhanced indexing, patent search, citation analysis, and IP analytics. | Starts at ~$15,000/year for entry enterprise licenses (scales with DWPI indexing and analytics modules) | Free trial / pilot demo available upon request (typically 7–14 days evaluation); no permanent free tier |
| **[InnovationQ Plus](https://www.ip.com/innovationq-plus/)** | AI-assisted patent and prior-art search platform designed to help researchers and IP professionals discover relevant technical documents and intellectual-property information. | Starts at $49/user/month (Basic plan) or $199/user/month (Premium plan / Day Pass) | 2-day free trial with platform feature access upon registration; no permanent free tier |
| **[IP.com](https://www.ip.com/)** | Intellectual-property intelligence platform offering prior-art search, patent search, technical disclosure management, innovation intelligence, and IP research services. | Starts at $49/user/month (InnovationQ Plus Basic); Prior Art Database defensive publishing from $195/disclosure | 2-day free trial for search platform; free public searching of the IP.com Prior Art Database |
| **[Ambercite](https://www.ambercite.com/)** | Patent citation-search and prior-art discovery platform focused on citation networks, related-document discovery, and identifying relevant patent literature. | Starts at ~$1,500 – $2,500/year for small firm / consultant licenses | 21-day or 20-search free trial (limited to top 25 results with 5 obscured, max 3 input patents, no Excel exports); no permanent free tier |
| **[PatSeer Pro](https://patseer.com/)** | Advanced patent intelligence environment supporting complex patent queries, analytics, technology landscapes, portfolio evaluation, and competitive monitoring. | Starts at ~$1,200/user/quarter (~$400/user/month for ProX edition with advanced analytics) | 14-day free trial (no credit card required); no permanent free tier |
| **[PatentSight](https://www.patentsight.com/)** | Patent analytics and portfolio intelligence platform emphasizing patent value, competitive benchmarking, technology landscapes, and strategic portfolio analysis. | Starts at ~$10,000 – $20,000/year for corporate patent analytics licenses (LexisNexis IP suite) | Free guided portfolio pilot demo upon request; free PatentAdvisor browser extension for basic examiner statistics; no permanent free SaaS plan |
| **[PatBase](https://www.patbase.com/)** | Global patent database and search platform providing professional patent searching, family information, monitoring, alerts, and patent analytics. | Starts at ~$4,000 – $6,000/user/year (approx. £3,000–£4,500/year for single seat) | 14-day free trial for PatBase (7-day free trial for PatBase Express); no permanent free tier |
| **[STN](https://www.cas.org/solutions/stn)** | Professional scientific and patent information platform supporting complex searches across patents, scientific literature, chemistry, and technical information. | Connect time starting at ~$100 – $300/connect hour plus file search/display fees ($2–$10+ per record) | Free assisted demo via CAS; free command syntax checks (`EXPAND`) and sample training database files; no permanent free tier |
| **[PatentInspiration](https://www.patentinspiration.com/)** | Patent search and innovation intelligence platform focused on visual patent exploration, semantic discovery, technology landscapes, and competitive intelligence. | Starts at €99/month (Basic plan; Team at €199/month, Enterprise at €499/month) | Free forever tier (basic searches and visualization, watermarked images, limited report saving); 7-day full-featured free trial |
| **[IPRally](https://www.iprally.com/)** | AI-powered patent intelligence platform focused on prior-art discovery and technology intelligence using machine learning and semantic analysis. | Starts at €3,000/year (~€250/month) for individual plan; team plans scale to $24,000+/year | 3-day free trial with AI graph search capabilities; no permanent free tier |
| **[PatentBuddy](https://www.patentbuddy.com/)** | Patent search and patent portfolio intelligence service providing access to patent information, prosecution data, and patent-related analytics. | Starts at $29.95/month for Pro/Premium analytics tier (basic portal is free) | Free forever tier for standard US patent application searches, inventor profiles, and assignee summaries |
| **[FreePatentsOnline](https://www.freepatentsonline.com/)** | Public patent search service providing searchable patent documents and patent-related information across major patent jurisdictions. | Free ($0 for web search engine); optional SearchAlerts/bulk services start at ~$15/month | Free forever with unlimited patent search, full-text viewing, and single PDF downloads across US, EP, JP, and PCT documents |
| **[Espacenet](https://worldwide.espacenet.com/)** | European Patent Office patent search service providing access to extensive worldwide patent documentation, bibliographic data, legal information, and patent families. | Free (€0) | Free forever; unlimited global search across 140M+ patent documents (up to 500 results per export download; OPS API has 4 GB/week free limit) |
| **[WIPO PATENTSCOPE](https://patentscope.wipo.int/)** | Global patent information platform from WIPO supporting searches across PCT applications and participating national and regional patent collections. | Free ($0) | Free forever; unlimited search across 115M+ patent records, up to 10,000 records exportable per search |
| **[USPTO Patent Center](https://patentcenter.uspto.gov/)** | Official United States patent information system for accessing patent applications, prosecution information, and related patent records. | Free ($0) | Free forever; unrestricted public access to US patent applications, patent grants, and public prosecution history (file wrapper) documents |
| **[Patent Field](https://patentfield.com/)** | Patent search and analysis service focused on searchable patent records and technology intelligence. | Starts at ¥10,000/month (~$70/month; ¥100,000/year on annual plan) | Free forever tier limited to 20 searches per month with basic AI search and classification features |

## Open-Source GitHub Projects

* **[PatZilla](https://github.com/ip-tools/patzilla)**
  Modular open-source patent information research platform and data integration toolkit with a modern user interface, command-line tooling, and connectors to multiple patent data sources, including EPO Open Patent Services. It can serve as a foundation for custom patent research systems.

* **[PQAI – Patent Quality Artificial Intelligence](https://github.com/pqaidevteam)**
  Open-source-oriented patent prior-art and semantic-search ecosystem focused on AI-assisted discovery of technically relevant patent documents. Suitable for building custom prior-art search and patent similarity workflows.

* **[Google Patents Public Data](https://github.com/google/patents-public-data)**
  Open-source examples and analysis workflows for the Google Patents Public Datasets, including automated patent landscaping, patent claim extraction, and machine-learning-based claim breadth analysis. The repository was archived in 2026 but remains a valuable reference implementation for patent analytics workflows.

* **[EPO OPS Go Client](https://github.com/patent-dev/epo-ops)**
  Open-source Go client for the European Patent Office Open Patent Services API supporting patent bibliographic data, claims, descriptions, abstracts, full-text retrieval, CQL search, patent-family retrieval, classifications, images, and legal-status data.

* **[python-epo-ops-client](https://github.com/ip-tools/python-epo-ops-client)**
  Apache-licensed Python client library for accessing the European Patent Office Open Patent Services API, supporting bibliographic data, descriptions, claims, and other patent information retrieval workflows.

* **[Node.js EPO OPS Client](https://github.com/sujith3g/epo-ops)**
  Open-source JavaScript wrapper for the EPO Open Patent Services API, supporting publication retrieval and patent search workflows through Node.js applications.

* **[OPS Patent Search MCP](https://github.com/navisbio/OPS-patent-search-mcp)**
  Open-source Model Context Protocol server for searching and retrieving patent data through EPO Open Patent Services. Supports searches across title, abstract, applicants, inventors, IPC/CPC classifications, dates, citations, claims, descriptions, and patent details.

* **[Google Patent CLI](https://github.com/sonesuke/google-patent-cli)**
  Open-source command-line and AI-agent-oriented tool for searching and retrieving structured patent information from Google Patents, including titles, abstracts, filing dates, assignees, descriptions, claims, and images.

* **[PatentsView to BigQuery](https://github.com/Innovation-Information-Initiative/bigquery_patentsview)**
  Open-source ETL pipeline for downloading USPTO PatentsView datasets, converting them into Parquet, and loading structured patent metadata into Google BigQuery for custom analytics and patent search applications.

* **[PatentsView](https://github.com/USPTO/PatentsView-API)**
  USPTO open-data ecosystem providing structured patent data suitable for custom patent search, inventor analysis, assignee analysis, technology landscaping, and bibliometric research.

* **[Lens API Documentation and Examples](https://github.com/lens-org/lens-api-doc)**
  Open-source code examples and documentation for integrating patent search and patent data retrieval into applications using the Lens API. Examples are available for R, Python, Java, Node.js, and cURL-based workflows.

* **[WIPO Analytics Manual](https://github.com/wipo-analytics/manual)**
  Open-source educational and analytical resource for patent data processing, patent databases, patent indicators, and reproducible intellectual-property analytics workflows.

* **[Awesome Patent Retrieval](https://github.com/mahesh-maan/awesome-patent-retrieval)**
  Community-curated open-source resource listing patent search engines, patent retrieval tools, research papers, APIs, datasets, and patent information resources.

* **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**
  Fully open-source distributed search and analytics engine that can be used as the core full-text search layer for self-hosted patent databases containing titles, abstracts, descriptions, claims, classifications, and metadata.

* **[OpenSearch Dashboards](https://github.com/opensearch-project/OpenSearch-Dashboards)**
  Open-source visualization and dashboard layer for OpenSearch, useful for patent portfolio analytics, technology landscapes, classification analysis, and patent monitoring dashboards.

* **[Elasticsearch](https://github.com/elastic/elasticsearch)**
  Distributed search and analytics engine widely used for large-scale text indexing and retrieval. Earlier fully open-source versions and compatible forks remain useful foundations for custom patent search infrastructure.

* **[Apache Solr](https://github.com/apache/solr)**
  Mature open-source enterprise search platform built on Apache Lucene, suitable for indexing large patent collections and supporting faceted search, full-text search, filtering, highlighting, and classification queries.

* **[Apache Lucene](https://github.com/apache/lucene)**
  Foundational open-source full-text search library used to build custom patent search engines, supporting advanced indexing, scoring, query parsing, and text retrieval.

* **[Meilisearch](https://github.com/meilisearch/meilisearch)**
  Open-source search engine offering fast full-text search and developer-friendly APIs. Suitable for smaller self-hosted patent datasets and experimental patent search interfaces.

* **[Typesense](https://github.com/typesense/typesense)**
  Open-source typo-tolerant search engine that can be adapted for fast patent metadata search, assignee discovery, inventor search, and technology catalog interfaces.

* **[Vespa](https://github.com/vespa-engine/vespa)**
  Open-source big-data serving and AI platform supporting large-scale search, ranking, vector retrieval, and recommendation workflows. Suitable for advanced patent semantic-search systems.

* **[Qdrant](https://github.com/qdrant/qdrant)**
  Open-source vector database suitable for semantic patent search using embeddings generated from patent abstracts, claims, descriptions, or technology concepts.

* **[Weaviate](https://github.com/weaviate/weaviate)**
  Open-source vector database and semantic-search platform that can be used to build natural-language patent discovery and similarity-search systems.

* **[Milvus](https://github.com/milvus-io/milvus)**
  Open-source vector database designed for large-scale similarity search and AI applications, useful for indexing patent embeddings at large scale.

* **[FAISS](https://github.com/facebookresearch/faiss)**
  Open-source similarity-search library for dense vector embeddings. Commonly used to build high-performance patent similarity and semantic prior-art retrieval systems.

* **[Sentence Transformers](https://github.com/UKPLab/sentence-transformers)**
  Open-source framework for generating semantic embeddings from patent abstracts, claims, and technical descriptions for similarity search and prior-art discovery.

* **[Hugging Face Transformers](https://github.com/huggingface/transformers)**
  Major open-source machine-learning library containing transformer models that can be adapted or fine-tuned for patent classification, similarity search, prior-art retrieval, entity extraction, and patent summarization.

* **[Haystack](https://github.com/deepset-ai/haystack)**
  Open-source framework for building retrieval and question-answering pipelines. Can combine patent databases, vector search, keyword retrieval, reranking, and language models into AI-powered patent research assistants.

* **[LangChain](https://github.com/langchain-ai/langchain)**
  Open-source application framework for combining patent data sources, search engines, vector databases, APIs, and language models into patent research and analysis workflows.

* **[LlamaIndex](https://github.com/run-llama/llama_index)**
  Open-source data framework for retrieval-augmented applications. Useful for indexing patent claims, descriptions, patent families, and technical literature for conversational patent search.

* **[spaCy](https://github.com/explosion/spaCy)**
  Open-source natural-language-processing library that can support patent entity extraction, terminology analysis, technology classification, and information extraction.

* **[GROBID](https://github.com/kermitt2/grobid)**
  Open-source machine-learning library for extracting structured information from scientific and technical documents. Useful when building combined patent-and-scientific-literature research systems.

* **[BERTopic](https://github.com/MaartenGr/BERTopic)**
  Open-source topic-modeling framework that can help create patent technology landscapes by clustering patent abstracts and descriptions into thematic groups.

* **[NetworkX](https://github.com/networkx/networkx)**
  Open-source Python library for graph analysis, useful for patent citation networks, inventor networks, assignee relationships, technology diffusion, and patent-family graphs.

* **[Neo4j Community Edition](https://github.com/neo4j/neo4j)**
  Open-source graph database platform suitable for building patent knowledge graphs connecting patents, inventors, assignees, citations, classifications, and technology concepts.

* **[Gephi](https://github.com/gephi/gephi)**
  Open-source network visualization platform useful for exploring patent citation networks, inventor collaboration networks, and technology relationship graphs.

* **[Apache Superset](https://github.com/apache/superset)**
  Open-source analytics and business-intelligence platform that can visualize patent datasets stored in databases or warehouses.

* **[Metabase](https://github.com/metabase/metabase)**
  Open-source business-intelligence platform useful for building patent portfolio dashboards, technology landscapes, patent filing trends, and assignee analytics.

* **[Jupyter](https://github.com/jupyter/jupyter)**
  Open-source computational notebook ecosystem suitable for reproducible patent analysis, patent landscaping, data cleaning, visualization, and machine-learning experiments.

### Additional Strong Open-Source Options

* **Patent data acquisition**: EPO Open Patent Services clients, USPTO Open Data APIs, PatentsView datasets, Google Patents Public Datasets, and jurisdiction-specific open-data sources.

* **Patent search engines**: Apache Solr, OpenSearch, Lucene, Meilisearch, Typesense, and Vespa for building self-hosted full-text patent search infrastructure.

* **Semantic and AI search**: Sentence Transformers, Hugging Face Transformers, FAISS, Qdrant, Milvus, Weaviate, Haystack, LangChain, and LlamaIndex.

* **Patent NLP and information extraction**: spaCy, Transformers, BERTopic, KeyBERT, scikit-learn, and custom domain-specific language models.

* **Patent landscaping**: Python, pandas, scikit-learn, BERTopic, NetworkX, Jupyter, and Apache Superset can be combined to analyze technology clusters and patent trends.

* **Citation and knowledge graphs**: Neo4j Community Edition, NetworkX, Gephi, and graph-processing frameworks for patent citations, inventor relationships, and assignee networks.

* **Patent data warehouses**: PostgreSQL, ClickHouse, DuckDB, BigQuery-compatible pipelines, Apache Spark, and Parquet-based data lakes.

* **Visualization**: Apache Superset, Metabase, Grafana, Plotly, matplotlib, and Gephi for technology landscapes and patent analytics.

* **AI-assisted prior-art research**: Combine BM25 keyword search with vector search, cross-encoder reranking, classification filtering, patent-family analysis, and retrieval-augmented language models.

* **Patent monitoring**: Open-source schedulers such as Apache Airflow, Prefect, Dagster, and cron-based pipelines can periodically query patent APIs and generate alerts.

* **Custom patent interfaces**: React, Next.js, Vue, Django, FastAPI, and Node.js can be combined with OpenSearch or Solr to create specialized patent search portals.

* Many community projects exist for **patent scraping, patent classification, claim analysis, citation analysis, technology clustering, prior-art retrieval, patent embeddings, and IP knowledge graphs**.

**Frameworks for building custom systems**: A powerful self-hosted patent search stack can combine **PatZilla or EPO OPS clients** for patent-data acquisition, **PostgreSQL or object storage** for structured data, **OpenSearch or Apache Solr** for keyword search, **Qdrant, Milvus, or FAISS** for semantic similarity search, **Sentence Transformers or Hugging Face models** for patent embeddings, and **Neo4j or NetworkX** for citation and inventor graphs. Add **Apache Superset or Metabase** for patent analytics dashboards and **Haystack, LangChain, or LlamaIndex** for AI-assisted patent research.

For organizations needing global patent search, a practical architecture is to combine official or open-access sources with local indexing rather than relying exclusively on web scraping. EPO OPS clients provide programmatic access to bibliographic records, full text, patent families, classifications, images, and legal-status information, while public datasets can support large-scale patent landscaping and analytics.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

* This is a **community-curated** list — not exhaustive and not an endorsement.
* Patent search results should not be treated as definitive legal opinions or complete freedom-to-operate analyses.
* Prior-art searches can produce false negatives because patent terminology, translations, classifications, indexing quality, unpublished applications, and jurisdictional coverage vary.
* Patent databases differ in update frequency, full-text availability, legal-status coverage, and family normalization.
* Commercial patent databases may provide proprietary indexing, enhanced metadata, and curated content that are not directly reproducible using public datasets alone.
* Self-hosted open-source solutions require significant work in data acquisition, normalization, deduplication, patent-family resolution, indexing, NLP, ranking, and ongoing database updates.
* Legal decisions involving patentability, infringement, validity, freedom to operate, or intellectual-property strategy should involve qualified patent professionals.

---

**Made for patent professionals, IP attorneys, inventors, researchers, R&D teams, innovation leaders, data scientists, and developers building patent intelligence systems.**
Let's make patent research more open, searchable, transparent, and accessible through open data and open-source technology.
