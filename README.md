# Neo4j Schema Guardrail & Cypher Assistant 🚀

A portable, production-grade **Agent Skill** built according to the `agentskills.io` open standard. This skill teaches AI coding assistants and agents how to reliably interface with a Neo4j Graph Database by enforcing a strict data ontology, eliminating hallucinations, and mandating modern Cypher syntax.

## 📁 Repository Structure

Following the standardized Agent Skills specification, this asset is organized into a clean, portable folder structure:

```text
neo4j-schema-guardrail/
├── SKILL.md          # Required: Metadata frontmatter + agent execution rules
└── assets/           # Optional: Supplementary data files
    └── corporate_ontology.json   # The canonical graph database schema
