# SophieLab 24/365 Infrastructure Demo 

> 인프라를 코드로 완전히 재현하는 **소피 실험실**
>  
> “장애, 보안, 확장성, 복구 — 모두 코드 한 줄로 통제하는..00급 인프라”

---


## 📈 Sophie Labs Focus!
- IaC (Terraform) + GitOps (Argo CD) + Observability Stack 완전 자동화
- SLO / SLI / Error Budget 기반 운영문화 시뮬레이션
- FinOps / DR / Policy / Supply Chain Security 내장형 설계


---
## ✅ 요즘 작업 완료
| feat | repo | des |
|------|------|------|
|  Control Tower | [platform-argocd](https://github.com/2025-demo-01/platform-argocd) | 모든 서비스 배포를 총괄하는 App-of-Apps 구조의 GitOps Control Tower |
|  Infra as Code | [infra-terraform](https://github.com/2025-demo-01/infra-terraform) | AWS 인프라(EKS, MSK, Aurora, Route53, Karpenter 등) 완전 코드화 |
|  API Gateway | [svc-gateway](https://github.com/2025-demo-01/svc-gateway) | Istio Gateway + Envoy RateLimit + Policy Enforcement Sidecar |
|  Trading API | [svc-trading-api](https://github.com/2025-demo-01/svc-trading-api) | 주문 생성/조회 REST API, Kafka → Aurora 파이프라인, HPA + KEDA |

---

## 🚧 지금 진행 중~~~
| feat | repo | des |
|------|------|------|
|  Matching Engine | [svc-matching-engine](https://github.com/2025-demo-01/svc-matching-engine) | Rust 기반 초저지연 매칭엔진, Kafka 소비 및 ClickHouse 연동 |
|  Wallet Service | [svc-wallet](https://github.com/2025-demo-01/svc-wallet) | FastAPI 기반 입출금 큐 시스템, SOPS 암호화 Secret 적용 |
|  Risk Control | [svc-risk-control](https://github.com/2025-demo-01/svc-risk-control) | Flink/Faust 스트리밍 기반 리스크 파이프라인 |
|  Policy-as-Code | [policy-as-code](https://github.com/2025-demo-01/policy-as-code) | Kyverno + OPA + SOPS 기반 보안/운영 정책 자동화 |
|  Tests & DR | [tests-and-dr](https://github.com/2025-demo-01/tests-and-dr) | Route53 Failover + Chaos Mesh 기반 DR 리허설 자동화 |
|  Observability Stack | [observability-stack](https://github.com/2025-demo-01/observability-stack) | Prometheus, Loki, Tempo, Grafana + Error Budget Burn Rule |
|  Data Pipeline | [data-pipeline](https://github.com/2025-demo-01/data-pipeline) | Debezium → Kafka → Flink/Faust → ClickHouse CDC 파이프라인 |
|  Architecture Docs | [exchange-architecture](https://github.com/2025-demo-01/exchange-architecture) | 시스템 다이어그램 / 기술문서 / 릴리즈 노트 아카이브 |



---

## 🔗 다은 작업은 뭘까!
 [2025-demo-01](https://github.com/2025-demo-01)  
