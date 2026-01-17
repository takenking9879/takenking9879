# Jorge Ángel Manzanares Cortés  

---

## Stack (Frameworks que he usado en proyectos)
<p align="center">
  <!-- ML & Data -->
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?logo=apache-spark&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/KubeRay-000000?logo=ray-project&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/Airflow-0173B2?logo=apache-airflow&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/Kafka-231F20?logo=apache-kafka&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/MLflow-00A0B0?logo=mlflow&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/Evidently-007ACC" height="40"/>
  <!-- Infra & DevOps -->
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=github-actions&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/Hetzner%20Cloud-0F0F0F" height="40"/>
  <!-- Cloud -->
  <img src="https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/Amazon%20EKS-FF9900?logo=amazon-eks&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/Amazon%20EC2-FF9900?logo=amazon-ec2&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/Amazon%20S3-569A31?logo=amazon-s3&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/Amazon%20CloudFront-8C4FFF?logo=amazon-cloudfront&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/Amazon%20API%20Gateway-FF4F8B?logo=amazon-api-gateway&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/AWS%20Lambda-FF9900?logo=aws-lambda&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/Amazon%20EFS-FF9900?logo=amazon-efs&logoColor=white" height="40"/>
  <!-- AI & Vector / Agents -->
  <img src="https://img.shields.io/badge/LangGraph-4B9CD3?logo=python&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/Pinecone-8B5CF6?logo=pinecone&logoColor=white" height="40"/>
  <img src="https://img.shields.io/badge/RAG-FF6F61?logo=python&logoColor=white" height="40"/>
</p>


## Qué busco construir
Hago que **Kubernetes y la infraestructura ML no sean cajas negras**: que la gente pueda montar pipelines distribuidos (Spark, Ray, Kafka, Airflow) en infra económica y entendible — por ejemplo con **Kube-Hetzner** — optimizando costos, autoscaling y minimizando pods ociosos. Mi objetivo: plataformas ML reproducibles y accesibles que cualquiera pueda usar sin depender 100% de cloud managed.

---

## Principios y estilo de trabajo
- **No me gustan los notebooks como final**: los uso solo para prototipar. El resultado debe ser código modular, claro y deployable (Docker + K8s + OOP).  
- **Automatizo para evitar trabajo manual**: prefiero invertir tiempo en automatizaciones que reduzcan tareas repetitivas.  
- **Transparencia infra**: quiero ver y controlar lo que hay “detrás” (scheduling, CRDs, recursos).  
- **Cost & observability first**: medir consumo por componente (Spark, Ray, Kafka), ahorrar GPU/CPU y documentar decisiones.  
- **Código explicable y modular**: cada módulo con responsabilidad clara, fácil de leer y mantener.

---

## Fortalezas técnicas
- CT / CD, feature engineering distribuido, HPO práctico.  
- Spark on Kubernetes, KubeRay para entrenamiento distribuido.  
- Airflow + operators K8s, Kafka (Strimzi / Confluent).  
- Observabilidad: Prometheus, Grafana, Evidently (ML monitoring).  
- Infra reproducible: Terraform, Kubecost, Cluster Autoscaler, HPA.  
- Versionado y tracking: DVC + MLflow.  
- CI/CD: GitHub Actions; GitOps opcional (ArgoCD).
