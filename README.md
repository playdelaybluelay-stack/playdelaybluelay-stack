# 한예빈 | Cloud & Infrastructure Engineer

AWS 기반 멀티 리전 DR 아키텍처 설계부터 On-premises 가상화 인프라 구축까지,  
비용·보안·가용성의 트레이드오프를 판단하고 실제 구축까지 수행합니다.

메가존클라우드 MSP 솔루션 아키텍트 양성과정 수료 (7개월)

## Projects

### 🛡️ [AWS Pilot-Light DR Architecture](https://github.com/playdelaybluelay-stack/aws-pilot-light-dr) — 팀 프로젝트

AWS 멀티 리전(서울-도쿄) 재해복구 아키텍처 | 보안·백업·DR 테스트 전담

- RTO 15분 / RPO 5분 달성, Warm-Standby 대비 평시 비용 98% 절감
- Terraform으로 2개 리전 50개 리소스 코드화, GitHub Actions 5개 워크플로우 자동화
- Custom WAF 7일 운영 중 실제 침입 23건 차단

`Terraform` `AWS` `GitHub Actions (OIDC)` `WAF` `StepFunctions` `Cognito`

### 🏗️ [On-premises 3-Tier Architecture](https://github.com/playdelaybluelay-stack/helpdesk-backend) — 개인 프로젝트

VMware 가상화 환경에서 고가용성 인프라 단독 설계·구축

- VM 5대 + 라우터 5대로 Web/WAS/DB/Shared 4개 티어 네트워크 분리
- HAProxy 이중화 failover 확인, MySQL 비동기 복제 구성
- OSPF 기반 라우팅 자동화로 수평 확장 대비

`VMware` `Vagrant` `HAProxy` `MySQL` `Nginx` `BIND9` `OSPF`

## Tech Stack

| 영역 | 기술 |
|------|------|
| Cloud | AWS (EC2, S3, VPC, IAM, Route 53, CloudFront, WAF, Backup, DynamoDB, Cognito, StepFunctions, Lambda 등) |
| IaC | Terraform |
| CI/CD | GitHub Actions (OIDC) |
| Container | Docker, Kubernetes (기초) |
| OS | Linux (Ubuntu) |
| DB | MySQL |
| Virtualization | VMware, Vagrant |

## Certifications

- AWS Solutions Architect – Associate (SAA)
- 정보처리기사 (실기 준비 중)
