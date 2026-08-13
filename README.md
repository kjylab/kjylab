<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:6DD5FA,100:2980B9&height=180&section=header&text=Hi%2C%20I'm%20kjylab&fontSize=45&fontColor=ffffff&animation=fadeIn&desc=Infrastructure%20%26%20Platform%20Engineer&descAlignY=62&descSize=18)

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&size=18&pause=1000&color=2980B9&center=true&vCenter=true&width=600&lines=Terraform%EB%A1%9C+%EC%9D%B8%ED%94%84%EB%9D%BC%EB%A5%BC+%EC%BD%94%EB%93%9C%EB%A1%9C+%EB%A7%8C%EB%93%AD%EB%8B%88%EB%8B%A4;Kubernetes+%EC%9C%84%EC%97%90%EC%84%9C+%EC%84%9C%EB%B9%84%EC%8A%A4%EA%B0%80+%EB%8F%8C%EC%95%84%EA%B0%80%EA%B2%8C+%ED%95%A9%EB%8B%88%EB%8B%A4;%EC%9E%A5%EC%95%A0+%EC%97%86%EB%8A%94+%ED%95%98%EB%A3%A8%EB%A5%BC+%EB%A7%8C%EB%93%AD%EB%8B%88%EB%8B%A4)](https://github.com/kjylab)

</div>

Terraform/Ansible로 베어 EC2를 프로비저닝하는 것부터, 서비스 메시·GitOps 구성, 관측성(Observability) 구축까지 Kubernetes 기반 인프라를 엔드투엔드로 설계하고 운영합니다. 많은 사람들이 블랙박스로 여기는 계층을 직접 이해하는 걸 좋아합니다.

<br>

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

<br>

### 📌 주요 프로젝트

**kjylab MSA Platform**
Terraform + Ansible로 베어 EC2부터 프로비저닝한 셀프호스팅 Kubernetes 플랫폼. Istio(mTLS, 트래픽 관리) 기반 마이크로서비스 스택을 ArgoCD로 배포하고, CNPG PostgreSQL(Database-per-Service)과 Strimzi Kafka로 데이터 계층을 구성, Prometheus/Grafana/Loki/Tempo로 관측성을 확보했습니다.
`Terraform` `Ansible` `kubeadm` `Istio` `ArgoCD` `CNPG` `Strimzi`

**DropMong — 프로비저닝 파이프라인**
EC2 인스턴스가 하나도 없는 상태에서 실제 서비스 배포가 가능한 Kubernetes 클러스터가 되기까지의 전체 과정을 자동화한 파이프라인. Terraform이 인프라를 만들고 cloud-init을 거쳐 Ansible에 핸드오프, kubeadm으로 클러스터를 부트스트랩합니다. 여러 환경에서 재현 가능하도록 멱등성(Idempotency)을 보장합니다.
`Terraform` `Ansible` `cloud-init` `kubeadm`

**GO!비서 (AICD2)** — *과거 AI 프로젝트*
대화 속에서 시간·장소를 자동으로 추출해 최적의 약속 일정을 추천/확정해주는 텔레그램 기반 일정 조율 챗봇. 규칙 기반 키워드 추출과 GPT 기반 대화 요약을 결합해 별도 포맷 없이 자연스러운 대화만으로 일정을 조율합니다. 교통시스템공학·디지털미디어 전공 4인 팀 캡스톤 프로젝트.
`Python` `Telegram Bot` `Naver Map API` `GPT`

<br>

### 📈 Activity

<div align="center">

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=kjylab&bg_color=ffffff&color=2980B9&line=2980B9&point=6DD5FA&area=true&hide_border=true)

</div>

<br>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:6DD5FA,100:2980B9&height=100&section=footer)
