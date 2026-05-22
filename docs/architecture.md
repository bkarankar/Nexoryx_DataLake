# Architecture

MinIO Object Storage
        |
Alluxio Cache Layer
        |
+------------------+
| Spark | Trino |
+------------------+
        |
Hive Metastore
        |
PostgreSQL
