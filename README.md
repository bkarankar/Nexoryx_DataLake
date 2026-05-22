# Nexoryx_DataLake

Production-ready cloud-native Data Lake platform for Kubernetes with Spark, Trino, MinIO, Alluxio, Hive Metastore, PostgreSQL, autoscaling, and distributed analytics infrastructure.

## Features

- Distributed Data Lake architecture
- Apache Spark processing engine
- Trino distributed SQL engine
- MinIO object storage
- Alluxio distributed caching
- Hive Metastore integration
- Kubernetes-native deployment
- Persistent storage
- Ingress support
- Monitoring-ready architecture
- Horizontal autoscaling
- Production-ready manifests

## Stack

- Kubernetes
- Apache Spark
- Trino
- MinIO
- Alluxio
- Hive Metastore
- PostgreSQL
- Prometheus
- Grafana
- NGINX Ingress

## Deployment

```bash
kubectl apply -f kubernetes/
```

## Namespace

```bash
nexoryx-datalake
```

## Components

- Spark Master
- Spark Workers
- Trino Coordinator
- Trino Workers
- MinIO
- Alluxio
- Hive Metastore
- PostgreSQL
- Ingress
- Monitoring

## Notes

Update storage classes, ingress domains, passwords, and secrets before production deployment.
