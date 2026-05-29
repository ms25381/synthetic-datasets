# Synthetic Datasets

A curated collection of synthetic datasets, sample data generators, and reference data models used for data engineering, analytics, AI, streaming, and IoT demonstrations.

All datasets are artificially generated and contain **no proprietary, customer, employer, or personally identifiable information (PII)**.

---

# Purpose

This repository serves as the shared data foundation for:

- Architecture demonstrations
- Data engineering portfolio projects
- Streaming and IoT simulations
- AI and RAG prototypes
- Data quality testing
- Lakehouse reference implementations
- Technical articles and presentations
- Interview demonstrations

---

# Repository Structure

```text
synthetic-datasets
│
├── industrial-iot/
│   ├── sensor-telemetry/
│   ├── equipment-health/
│   ├── predictive-maintenance/
│   └── alarm-events/
│
├── energy-and-utilities/
│   ├── market-data/
│   ├── generation-assets/
│   ├── transmission-events/
│   └── pricing-data/
│
├── streaming/
│   ├── kafka-events/
│   ├── clickstream/
│   ├── cdc-events/
│   └── transaction-streams/
│
├── lakehouse/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── ai/
│   ├── rag-documents/
│   ├── embeddings/
│   ├── vector-search/
│   └── prompt-evaluation/
│
├── scada/
│   ├── operational-data/
│   ├── historian-data/
│   └── process-control/
│
└── generators/
    ├── python/
    ├── sql/
    └── notebooks/
```

---

# Dataset Categories

## Industrial IoT

Synthetic sensor data representing:

- Temperature
- Pressure
- Flow
- Vibration
- Humidity
- Equipment utilization
- Failure indicators

Typical use cases:

- Predictive maintenance
- Anomaly detection
- Streaming analytics
- Real-time dashboards

---

## Energy & Utilities

Synthetic utility and power market data including:

- Asset telemetry
- Generation metrics
- Market transactions
- Operational events
- Time-series measurements
- Resource ownership examples

Typical use cases:

- Lakehouse architecture demonstrations
- Market analytics
- Data curation examples
- Historical time-series analysis

---

## Streaming Data

Synthetic event streams for:

- Kafka
- Kinesis
- CDC pipelines
- Event-driven architectures

Example event types:

- Device telemetry
- Application logs
- User activity
- Transactions
- Operational alerts

---

## SCADA & Historian Data

Synthetic process-control datasets inspired by:

- Industrial automation
- Manufacturing systems
- Utility operations
- Process monitoring environments

Typical measurements:

- Process variables
- Operational alarms
- Equipment status
- Control loop data

---

## AI & RAG

Datasets used for:

- Retrieval-Augmented Generation (RAG)
- Vector search demonstrations
- Embedding experiments
- Knowledge management systems

Contents may include:

- Technical documentation
- Architecture notes
- Incident reports
- Operational procedures

---

# Supported Formats

Datasets may be provided in:

- CSV
- JSON
- JSONL
- Parquet
- Delta-compatible structures
- SQL seed files

---

# Sample Use Cases

## Databricks Lakehouse

```text
Bronze → Silver → Gold
```

Demonstrate:

- ETL/ELT pipelines
- Data quality validation
- Incremental processing
- Delta Lake optimization

---

## Streaming Analytics

```text
Producer
   ↓
Kafka
   ↓
Spark Streaming
   ↓
Lakehouse
   ↓
Dashboard
```

Demonstrate:

- Event processing
- Checkpoint recovery
- Late-arriving data
- Stateful processing

---

## Predictive Maintenance

```text
Equipment
   ↓
Sensor Telemetry
   ↓
Feature Engineering
   ↓
ML Model
   ↓
Failure Prediction
```

Demonstrate:

- Time-series feature generation
- Anomaly detection
- Asset health scoring

---

# Data Generation Principles

All datasets follow these principles:

- 100% synthetic
- Repeatable generation logic
- Realistic distributions
- Scalable record volumes
- Cloud-ready formats
- Safe for public sharing

---

# Related Repositories

- Portfolio
- Architecture Notes
- Engineering Articles
- Presentations
- Lakehouse Frameworks
- Streaming Demonstrations
- IoT Platform Examples

---

# Disclaimer

This repository contains synthetic data only.

No employer, customer, operational, confidential, or personally identifiable information is included.

All schemas, records, values, and examples are generated solely for demonstration, education, testing, and portfolio purposes.
