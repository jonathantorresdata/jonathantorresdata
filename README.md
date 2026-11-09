### Hi, I'm Jonathan 👋

**Data Engineer** based in Valencia, Spain. I build data pipelines end to end: incremental ingestion, dimensional models, data quality tests, orchestration and infrastructure as code. I come from a BI background (Power BI, Excel), so I design data for the people who will use it.

#### Projects

| Project | What it shows | Result |
|---|---|---|
| [**E-commerce Data Pipeline**](https://github.com/jonathantorresdata/ecommerce-data-pipeline) | 100,000 real orders replayed as a live store on **Azure**: Data Lake, **Databricks** (Unity Catalog), **dbt** with 39 tests and incremental merge, **Data Factory** daily schedule, **Terraform**, Power BI | Late deliveries drop reviews from 4.28★ to 2.55★ |
| [**Spain Grid Pulse**](https://github.com/jonathantorresdata/spain-grid-pulse) | Daily pipeline over the public Red Eléctrica and Open-Meteo APIs: incremental, idempotent extraction with retries, **dbt + DuckDB** with 24 tests, a public page rebuilt every morning by GitHub Actions | Days with ≥60% renewables: 33.5 €/MWh vs 127.2 €/MWh below 40% · [live page](https://jonathantorresdata.github.io/spain-grid-pulse/) |
| [**Grid Pulse on Airflow**](https://github.com/jonathantorresdata/grid-pulse-airflow) | **Apache Airflow 3**: DAGs linked by assets, dynamic task mapping, dbt as a quality gate, retries, alerts and DAG tests in CI | A real failure caught, retried and diagnosed: an unpinned dependency |
| [**Wiki Stream Pulse**](https://github.com/jonathantorresdata/wiki-stream-pulse) | **Streaming** from the live Wikimedia event stream (~2,000 events/min, Kafka underneath): resumable offsets and checkpoints, micro-batches, at-least-once delivery with deduplication, event-time windows | Stopped and resumed with no data loss; median edit-to-arrival delay 1.2 s |
| [**Fuel Price History**](https://github.com/jonathantorresdata/fuel-price-history) | Daily prices of ~11,500 Spanish petrol stations: **SCD type 2** history with gaps and islands, **change data capture** from snapshots, reconciliation tests | The brand moves diesel prices 16× more than the day of the week |

#### Stack

`SQL` `Python` `dbt` `Streaming` `Azure (Data Lake, Databricks, Data Factory)` `Apache Airflow` `Terraform` `DuckDB` `GitHub Actions` `Power BI`

#### How I work

- Know the data before modelling it: grain, keys, gaps.
- Nothing is deleted silently: issues are fixed or flagged, and documented.
- Every pipeline is idempotent, tested and documented with decision records.

📫 [LinkedIn](https://www.linkedin.com/in/jonathan-torres-rosas) · jonathan.torres.data@gmail.com
