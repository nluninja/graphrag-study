# Awesome GraphRAG [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome GraphRAG (Graph Retrieval-Augmented Generation) resources, papers, frameworks, tools, and tutorials.

GraphRAG combines knowledge graphs with retrieval-augmented generation to enhance LLM responses with structured, interconnected information. This approach enables more accurate, contextual, and explainable AI systems.

## Contents

- [Papers](#papers)
  - [Foundational](#foundational)
  - [Methods and Techniques](#methods-and-techniques)
  - [Applications](#applications)
- [Frameworks and Tools](#frameworks-and-tools)
  - [Open Source Frameworks](#open-source-frameworks)
  - [Graph Databases](#graph-databases)
  - [Visualization Tools](#visualization-tools)
- [Tutorials and Courses](#tutorials-and-courses)
- [Videos and Talks](#videos-and-talks)
- [Blog Posts and Articles](#blog-posts-and-articles)
- [Datasets](#datasets)
- [Use Cases and Applications](#use-cases-and-applications)
- [Community](#community)
- [Contributing](#contributing)

## Papers

### Foundational

- **From Local to Global: A Graph RAG Approach to Query-Focused Summarization** (Microsoft Research, 2024)
  - [Paper](https://arxiv.org/abs/2404.16130) | Introduces GraphRAG methodology for query-focused summarization using knowledge graphs
  - Key contribution: Global vs. local retrieval strategies in graph-based RAG

- **Graph Retrieval-Augmented Generation: A Survey** (2024)
  - Comprehensive survey of GraphRAG approaches, architectures, and applications
  - Covers integration of graph neural networks with RAG systems

- **KG-RAG: Bridging the Gap Between Knowledge and Creativity** (2024)
  - Explores knowledge graph integration with creative text generation
  - Demonstrates improved factual consistency in generation tasks

### Methods and Techniques

- **HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models** (2024)
  - [Paper](https://arxiv.org/abs/2405.14831) | Brain-inspired approach to long-term memory using knowledge graphs
  - Implements hippocampal indexing theory for LLM memory systems

- **Retrieval-Augmented Generation with Knowledge Graphs for Customer Service Question Answering** (2024)
  - Practical implementation of GraphRAG in customer service domain
  - Addresses entity disambiguation and multi-hop reasoning

- **SURGE: Structured Retrieval for Graph-Enhanced Generation** (2024)
  - Novel structured retrieval methods for graph-based contexts
  - Improves multi-hop reasoning capabilities

- **Graph Neural Prompting with Large Language Models** (2024)
  - [Paper](https://arxiv.org/abs/2309.15427) | Combines GNNs with LLM prompting strategies
  - Enhances reasoning over graph-structured data

- **Reasoning on Graphs: Faithful and Interpretable Large Language Model Reasoning** (2023)
  - [Paper](https://arxiv.org/abs/2310.01061) | Focus on interpretable reasoning using graph structures
  - Proposes RoG (Reasoning on Graphs) framework

### Applications

- **BiomedRAG: Graph-Enhanced Retrieval for Biomedical Question Answering** (2024)
  - Domain-specific GraphRAG for biomedical literature
  - Integrates MeSH ontology and PubMed knowledge graphs

- **Financial Knowledge Graph RAG for Risk Assessment** (2024)
  - Application in financial services and risk modeling
  - Demonstrates regulatory compliance use cases

- **CodeGraphRAG: Enhancing Code Understanding with Graph-Based Retrieval** (2024)
  - Uses code dependency graphs for improved code generation
  - Supports cross-file context understanding

## Frameworks and Tools

### Open Source Frameworks

- **[Microsoft GraphRAG](https://github.com/microsoft/graphrag)** - Official implementation from Microsoft Research
  - Python-based framework for building GraphRAG applications
  - Supports local and global search strategies
  - Integrates with Azure OpenAI and other LLM providers

- **[LlamaIndex](https://github.com/run-llama/llama_index)** - Data framework for LLM applications with GraphRAG support
  - Knowledge Graph Index for graph-based retrieval
  - Property Graph Index for complex relationships
  - Extensive connector ecosystem

- **[LangChain](https://github.com/langchain-ai/langchain)** - Framework with graph database integrations
  - Neo4j, Neptune, and other graph database connectors
  - Graph QA chains and retrievers
  - Cypher query generation

- **[Haystack](https://github.com/deepset-ai/haystack)** - NLP framework with graph store support
  - Graph document stores
  - Knowledge graph integration pipelines
  - Multi-modal document processing

- **[AutoGen](https://github.com/microsoft/autogen)** - Multi-agent framework with GraphRAG capabilities
  - Agent-based graph exploration
  - Collaborative reasoning over knowledge graphs

- **[DSPy](https://github.com/stanfordnlp/dspy)** - Programming framework for LMs with graph reasoning modules
  - Structured prompting for graph queries
  - Optimization of graph-based retrieval pipelines

- **[Cognee](https://github.com/topoteretes/cognee)** - Memory management framework with graph backend
  - Automatic knowledge graph construction
  - Incremental graph updates

### Graph Databases

- **[Neo4j](https://neo4j.com/)** - Leading graph database platform
  - Native graph storage and processing
  - Cypher query language
  - Vector similarity search integration
  - GenAI integrations and plugins

- **[Amazon Neptune](https://aws.amazon.com/neptune/)** - Fully managed graph database service
  - Supports Property Graph and RDF
  - SPARQL and Gremlin query languages
  - Serverless option available

- **[ArangoDB](https://www.arangodb.com/)** - Multi-model database with graph capabilities
  - Native graph, document, and key-value storage
  - AQL query language
  - Graph analytics and traversal

- **[TigerGraph](https://www.tigergraph.com/)** - Scalable graph database and analytics platform
  - Real-time deep link analytics
  - GSQL query language
  - ML and AI integration

- **[Nebula Graph](https://www.nebula-graph.io/)** - Open-source distributed graph database
  - High performance and scalability
  - nGQL query language
  - Native support for graph algorithms

- **[Memgraph](https://memgraph.com/)** - In-memory graph database
  - Real-time analytics
  - Cypher-compatible
  - Streaming data support

- **[JanusGraph](https://janusgraph.org/)** - Scalable open-source graph database
  - Distributed architecture
  - Multiple storage backend support
  - Gremlin query language

### Visualization Tools

- **[Neo4j Bloom](https://neo4j.com/product/bloom/)** - Graph visualization and exploration
- **[Graphistry](https://www.graphistry.com/)** - GPU-accelerated graph visualization
- **[yEd](https://www.yworks.com/products/yed)** - Desktop graph editor
- **[Gephi](https://gephi.org/)** - Open-source graph visualization platform
- **[Cytoscape](https://cytoscape.org/)** - Network visualization and analysis

## Tutorials and Courses

### Official Documentation

- [Microsoft GraphRAG Documentation](https://microsoft.github.io/graphrag/) - Official docs with quickstart guides
- [LlamaIndex Knowledge Graph Guide](https://docs.llamaindex.ai/en/stable/examples/index_structs/knowledge_graph/) - Building KG-based RAG systems
- [Neo4j GraphRAG Examples](https://neo4j.com/developer/genai/) - Neo4j + LLM integration tutorials

### Community Tutorials

- **Building GraphRAG from Scratch** - Step-by-step implementation guide
  - Knowledge graph construction from unstructured text
  - Entity and relationship extraction
  - Query generation and retrieval

- **GraphRAG for Enterprise Search** - Production deployment patterns
  - Scaling considerations
  - Security and access control
  - Performance optimization

- **Multi-hop Reasoning with GraphRAG** - Advanced retrieval techniques
  - Path-based retrieval
  - Subgraph extraction
  - Confidence scoring

### Jupyter Notebooks

- [GraphRAG Examples Repository](https://github.com/microsoft/graphrag/tree/main/examples) - Official examples
- Community notebooks on practical implementations

## Videos and Talks

### Conference Presentations

- **GraphRAG: Revolutionizing LLM Context** - Microsoft Build 2024
  - Overview of GraphRAG architecture and benefits
  - Live demonstrations

- **Knowledge Graphs Meet Large Language Models** - NeurIPS 2024 Workshop
  - Academic perspective on GraphRAG research
  - Future directions

### Tutorial Videos

- **GraphRAG Explained: From Theory to Practice** (YouTube)
  - Conceptual overview for beginners
  - Implementation walkthrough

- **Building Production GraphRAG Systems** (YouTube)
  - Engineering best practices
  - Deployment strategies

- **Neo4j + LLM: GraphRAG Tutorial Series** (YouTube)
  - Multi-part hands-on tutorial
  - Real-world use cases

### Webinars and Workshops

- Monthly GraphRAG community calls
- Enterprise implementation workshops
- Research paper reading groups

## Blog Posts and Articles

### Technical Deep Dives

- [Introducing GraphRAG: Improving Question-Answering at Scale](https://www.microsoft.com/en-us/research/blog/graphrag-unlocking-llm-discovery-on-narrative-private-data/) - Microsoft Research Blog
- [Why Knowledge Graphs are the Future of RAG](https://neo4j.com/blog/) - Neo4j Blog Series
- [Building Scalable GraphRAG Applications](https://medium.com/llamaindex-blog) - LlamaIndex Engineering

### Comparative Analysis

- GraphRAG vs Traditional RAG: Performance Comparison
- Vector Search vs Graph Search in RAG Systems
- Cost-Benefit Analysis of GraphRAG Implementation

### Industry Insights

- GraphRAG in Healthcare: HIPAA-Compliant Implementations
- Financial Services GraphRAG Use Cases
- Legal Tech: Document Analysis with GraphRAG

## Datasets

### Knowledge Graph Datasets

- **[Wikidata](https://www.wikidata.org/)** - Free collaborative knowledge base
- **[DBpedia](https://www.dbpedia.org/)** - Structured information from Wikipedia
- **[YAGO](https://yago-knowledge.org/)** - Large semantic knowledge base
- **[ConceptNet](https://conceptnet.io/)** - Multilingual knowledge graph
- **[Freebase](https://developers.google.com/freebase)** - Community-curated database

### Domain-Specific Graphs

- **[PubMed Knowledge Graph](https://www.ncbi.nlm.nih.gov/research/bionlp/)** - Biomedical literature
- **[Financial Knowledge Graph](https://www.gleif.org/)** - Legal entity identifiers
- **[Open Academic Graph](https://www.microsoft.com/en-us/research/project/open-academic-graph/)** - Academic publications

### Benchmark Datasets

- **HotpotQA** - Multi-hop question answering dataset
- **ComplexWebQuestions** - Complex questions over knowledge graphs
- **MetaQA** - Multi-hop reasoning benchmark

## Use Cases and Applications

### Healthcare and Life Sciences

- Medical diagnosis support systems
- Drug discovery and interaction analysis
- Clinical trial matching
- Patient history analysis

### Financial Services

- Regulatory compliance monitoring
- Risk assessment and fraud detection
- Investment research and analysis
- Market intelligence

### Enterprise Knowledge Management

- Corporate knowledge bases
- Technical documentation systems
- Customer support automation
- Research and competitive intelligence

### Legal and Compliance

- Contract analysis and extraction
- Legal precedent research
- Regulatory document processing
- Due diligence automation

### E-commerce and Recommendations

- Product knowledge graphs
- Personalized recommendations
- Supply chain optimization
- Customer behavior analysis

### Software Development

- Code understanding and generation
- Dependency analysis
- Documentation generation
- Bug detection and analysis

## Community

### Forums and Discussion

- [Microsoft GraphRAG Discussions](https://github.com/microsoft/graphrag/discussions)
- [Neo4j Community Forum](https://community.neo4j.com/)
- [LlamaIndex Discord](https://discord.gg/dGcwcsnxhU)
- [r/GraphRAG](https://reddit.com/r/GraphRAG) - Reddit community

### Social Media

- Twitter hashtags: #GraphRAG #KnowledgeGraphs #RAG
- LinkedIn groups: Graph Technologies, Knowledge Engineering

### Events

- Graph + AI Summit (Neo4j)
- Knowledge Graph Conference
- GraphRAG Meetups (various cities)

### Research Groups

- Stanford NLP Group
- Microsoft Research AI
- Google Research - Knowledge & Language
- Allen Institute for AI

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

### How to Contribute

1. Fork the repository
2. Add your resource in the appropriate section
3. Ensure your addition follows the format
4. Submit a pull request

### Contribution Guidelines

- Add one link per pull request
- Include a brief description
- Use the existing format
- Verify all links are working
- Place new entries in alphabetical order within sections
- For papers, include publication year and conference/journal

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, contributors have waived all copyright and related rights to this work.
