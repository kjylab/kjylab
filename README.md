<div align="center">

# 안녕하세요, kjylab 입니다 👋

**Infrastructure & Platform Engineer** — 애플리케이션이 올라갈 기반을 직접 만듭니다.

Terraform/Ansible로 베어 EC2를 프로비저닝하는 것부터, 서비스 메시·GitOps 구성, 관측성(Observability) 구축까지 Kubernetes 기반 인프라를 엔드투엔드로 설계하고 운영합니다. 많은 사람들이 블랙박스로 여기는 계층을 직접 이해하는 걸 좋아합니다.

</div>

---

### 🛠 기술 스택

**인프라 & 프로비저닝**

![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Kubernetes & 클라우드 네이티브**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat-square&logo=istio&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)

**데이터 & 메시징**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL(CNPG)-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka(Strimzi)-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**관측성(Observability)**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

---

### 📌 주요 프로젝트

**kjylab MSA Platform**
Terraform + Ansible로 베어 EC2부터 프로비저닝한 셀프호스팅 Kubernetes 플랫폼. Istio(mTLS, 트래픽 관리) 기반 마이크로서비스 스택을 ArgoCD로 배포하고, CNPG PostgreSQL(Database-per-Service)과 Strimzi Kafka로 데이터 계층을 구성, Prometheus/Grafana/Loki/Tempo로 관측성을 확보했습니다.
`Terraform` `Ansible` `kubeadm` `Istio` `ArgoCD` `CNPG` `Strimzi`

**DropMong — 프로비저닝 파이프라인**
EC2 인스턴스가 하나도 없는 상태에서 실제 서비스 배포가 가능한 Kubernetes 클러스터가 되기까지의 전체 과정을 자동화한 파이프라인. Terraform이 인프라를 만들고 cloud-init을 거쳐 Ansible에 핸드오프, kubeadm으로 클러스터를 부트스트랩합니다. 여러 환경에서 재현 가능하도록 멱등성(Idempotency)을 보장합니다.
`Terraform` `Ansible` `cloud-init` `kubeadm`

---

<div align="center">

📫 각 리포지토리의 Issue/Discussion으로 연락 주세요

</div>
