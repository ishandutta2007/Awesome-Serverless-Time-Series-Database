# Awesome-Serverless-Time-Series-Database

# Top Serverless Time-Series Database Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Time-Series Ingestion, Metrics Storage & Self-Hosted Analytics Engines*  
**Last updated: October 2026**

This repository tracks notable **commercial time-series database platforms** and **open-source projects** that ingest, store, and query time-stamped data at scale. These tools power monitoring, observability, IoT telemetry, and real-time analytics — with serverless options that scale automatically.

**Examples** include Amazon Timestream, InfluxDB Cloud, Timescale Cloud, QuestDB Cloud, ClickHouse Cloud, Grafana Mimir, VictoriaMetrics Cloud, Warp 10, CrateDB Cloud, and TDengine Cloud (the category leaders).

**Open-source emphasis**: Time-series databases are one of the strongest open-source domains. **Prometheus** and **VictoriaMetrics** anchor metrics. **TimescaleDB**, **InfluxDB**, and **QuestDB** handle general time-series. **ClickHouse** dominates analytical workloads. **Grafana Mimir** provides scalable long-term metrics storage. **TDengine**, **Apache Druid**, **Apache Pinot**, and **Apache IoTDB** cover specialized use cases. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Amazon Timestream](https://aws.amazon.com/timestream/)**  
  **AWS's serverless time-series database** — automatically scales to trillions of events per day . **No infrastructure to manage** — pay per ingestion and query . **Best for AWS-native IoT and monitoring** .

- **[InfluxDB Cloud](https://www.influxdata.com/)**  
  **The leading time-series platform** — managed InfluxDB with unlimited cardinality, SQL support, and built-in visualization . **Best for observability and IoT** .

- **[Timescale Cloud](https://www.timescale.com/)**  
  **Managed TimescaleDB** — PostgreSQL-based time-series with full SQL and hyperfunctions . **Best for teams wanting PostgreSQL compatibility** .

- **[QuestDB Cloud](https://questdb.io/)**  
  **High-performance time-series database** — SQL with time-series extensions, SIMD-optimized . **Best for fast ingestion and queries** .

- **[ClickHouse Cloud](https://clickhouse.com/)**  
  **The leading analytical database** — columnar storage, real-time ingestion, and SQL . **Best for large-scale analytics and observability** .

- **[Grafana Mimir](https://grafana.com/oss/mimir/)**  
  **Scalable long-term metrics storage** — Prometheus-compatible with multi-tenancy . **Best for enterprise observability** .

- **[VictoriaMetrics Cloud](https://victoriametrics.com/)**  
  **High-performance, cost-effective metrics storage** — Prometheus-compatible . **Best for scalable monitoring** .

- **[Warp 10](https://warp10.io/)**  
  **Time-series platform for IoT and industrial data** — geospatial and sensor analytics . **Best for IoT and industrial** .

- **[CrateDB Cloud](https://crate.io/)**  
  **Distributed SQL database for time-series** — real-time analytics on machine data . **Best for industrial IoT** .

- **[TDengine Cloud](https://tdengine.com/)**  
  **Purpose-built time-series database** — high-performance ingestion and compression . **Best for IoT and industrial** .

## Open-Source GitHub Projects

### Metrics & Observability

- **[Prometheus](https://github.com/prometheus/prometheus)**  
  **The de facto standard for metrics monitoring**, Apache-2.0 licensed with **55,000+ GitHub stars** . **Pull-based metrics collection with PromQL** . **The foundation for cloud-native observability** . **Best for Kubernetes and infrastructure monitoring** .

- **[VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics)**  
  **High-performance, cost-effective time-series database**, Apache-2.0 licensed with **12,000+ GitHub stars** . **Prometheus-compatible with better performance and compression** . **10x more efficient than Prometheus** in some benchmarks . **Best for scalable metrics storage** .

- **[Grafana Mimir](https://github.com/grafana/mimir)**  
  **Scalable long-term metrics storage**, AGPL-3.0 licensed with **4,000+ GitHub stars** . **Prometheus-compatible with multi-tenancy** . **The most scalable open-source metrics backend** . **Best for enterprise observability** .

- **[Thanos](https://github.com/thanos-io/thanos)**  
  **Highly available Prometheus with long-term storage**, Apache-2.0 licensed with **13,000+ GitHub stars** . **Global query view across Prometheus instances** . **Best for multi-cluster Prometheus** .

- **[Cortex](https://github.com/cortexproject/cortex)**  
  **Horizontally scalable Prometheus**, Apache-2.0 licensed . **Multi-tenant metrics storage** . **The predecessor to Grafana Mimir** . **Best for scalable Prometheus** .

### General Time-Series Databases

- **[TimescaleDB](https://github.com/timescale/timescaledb)**  
  **PostgreSQL-based time-series database**, Apache-2.0/Timescale License with **18,000+ GitHub stars** . **Full SQL with time-series hyperfunctions** . **The best open-source alternative to InfluxDB for SQL users** . **Best for PostgreSQL users needing time-series** .

- **[InfluxDB](https://github.com/influxdata/influxdb)**  
  **The leading open-source time-series database**, MIT licensed with **29,000+ GitHub stars** . **InfluxQL and Flux query languages** . **The reference for time-series databases** . **Best for IoT and observability** .

- **[QuestDB](https://github.com/questdb/questdb)**  
  **High-performance time-series database**, Apache-2.0 licensed with **14,000+ GitHub stars** . **SQL with time-series extensions** — SIMD-optimized . **The fastest open-source time-series database** for ingestion . **Best for high-throughput ingestion** .

- **[Apache Druid](https://github.com/apache/druid)**  
  **Real-time analytics database**, Apache-2.0 licensed with **13,000+ GitHub stars** . **Sub-second queries on streaming data** . **Best for real-time analytics** .

- **[Apache Pinot](https://github.com/apache/pinot)**  
  **Real-time distributed OLAP datastore**, Apache-2.0 licensed with **5,000+ GitHub stars** . **User-facing analytics** . **Best for real-time analytics at scale** .

- **[Apache IoTDB](https://github.com/apache/iotdb)**  
  **IoT-native time-series database**, Apache-2.0 licensed with **5,000+ GitHub stars** . **Optimized for industrial IoT** . **Best for IoT deployments** .

- **[TDengine](https://github.com/taosdata/TDengine)**  
  **Purpose-built time-series database**, AGPL-3.0 licensed with **23,000+ GitHub stars** . **High-performance ingestion and compression** . **Best for IoT and industrial** .

- **[CrateDB](https://github.com/crate/crate)**  
  **Distributed SQL database for time-series**, Apache-2.0 licensed . **Real-time analytics on machine data** . **Best for industrial IoT** .

- **[Warp 10](https://github.com/senx/warp10-platform)**  
  **Time-series platform for IoT**, Apache-2.0 licensed . **Geospatial and sensor analytics** . **Best for IoT and industrial** .

- **[OpenTSDB](https://github.com/OpenTSDB/opentsdb)**  
  **Scalable time-series database on HBase**, LGPL-2.1 licensed . **The original distributed time-series database** . **Best for legacy HBase deployments** .

### Analytical Databases

- **[ClickHouse](https://github.com/ClickHouse/ClickHouse)**  
  **The leading columnar analytical database**, Apache-2.0 licensed with **35,000+ GitHub stars** . **Real-time ingestion and sub-second queries** . **The best open-source alternative to data warehouses** . **Best for large-scale analytics and observability** .

- **[Apache Doris](https://github.com/apache/doris)**  
  **Real-time analytical database**, Apache-2.0 licensed with **12,000+ GitHub stars** . **High-performance SQL analytics** . **Best for real-time analytics** .

- **[StarRocks](https://github.com/StarRocks/starrocks)**  
  **High-performance analytical database**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Real-time analytics with lakehouse integration** . **Best for modern analytics** .

### Additional Strong Open-Source Options

- **InfluxDB IOx** — Next-gen InfluxDB with Apache Arrow and DataFusion .
- **GreptimeDB** — Cloud-native time-series database .
- **M3** — Uber's metrics platform .
- **OpenTelemetry Collector** — Vendor-neutral telemetry collection .
- **Graphite** — The classic metrics database .
- **RRDtool** — Round-robin database for metrics .
- **KairosDB** — Scalable time-series on Cassandra .
- **Heroic** — Spotify's time-series database .

**Frameworks for building custom time-series solutions**: Choose based on workload and query patterns. **Prometheus** + **Thanos** or **Grafana Mimir** for metrics monitoring . **VictoriaMetrics** for cost-effective metrics at scale . **TimescaleDB** for PostgreSQL compatibility with SQL . **QuestDB** for high-throughput ingestion and fast queries . **InfluxDB** for general-purpose time-series . **ClickHouse** for large-scale analytics . **TDengine** or **Apache IoTDB** for IoT-specific workloads . Note that true serverless time-series with managed infrastructure, automatic scaling, and vendor-supported SLAs (Timestream, InfluxDB Cloud, ClickHouse Cloud) remains primarily commercial territory; open-source stacks provide strong ingestion, storage, and query foundations that require integration for complete observability and analytics.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Time-series databases handle high-volume operational data. Self-hosted solutions require proper capacity planning, storage management, and high-availability configuration.
- **License considerations vary significantly** — TimescaleDB uses Apache-2.0 for core with Timescale License for advanced features, InfluxDB uses MIT, TDengine uses AGPL-3.0, and VictoriaMetrics uses Apache-2.0 . Verify licensing against your use case before committing .
- **Cardinality is the primary scaling challenge** — high-cardinality metrics can overwhelm time-series databases. Prometheus and VictoriaMetrics have different cardinality handling . Plan for label cardinality from the start.
- **Query performance depends on data layout** — time-series databases optimize for time-ordered ingestion and range queries. Design schemas and retention policies accordingly .
- The open-source ecosystem provides strong ingestion, storage, and query foundations, but **managed infrastructure, automatic scaling, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for SREs, observability engineers, and organizations seeking time-series database sovereignty.**  
Let's make serverless time-series databases more open, transparent, and performant.
