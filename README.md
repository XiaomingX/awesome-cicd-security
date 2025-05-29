# awesome-cicd-security（优秀的 CI/CD 安全资源）

本项目汇集了2025年最新、最前沿的CI/CD安全相关资源，涵盖书籍、指南、博客、视频、工具、练习场和案例，帮助开发者、运维和安全团队构建更安全的持续集成与持续交付环境。

---

## 书籍

- 《高级基础设施渗透测试》——深入探讨基础设施安全与渗透测试技术，适合想提升CI/CD环境安全防护能力的专业人士。

---

## 指南

- [保护 CI/CD 环境的权威指南（CISA & NSA，2023）](https://media.defense.gov/2023/Jun/28/2003249466/-1/-1/0/CSI_DEFENDING_CI_CD_ENVIRONMENTS.PDF) — 官方发布，涵盖CI/CD环境的威胁模型与防御策略。

- **2025年CI/CD安全最佳实践**  
  - 集成DevSecOps理念，将安全自动化嵌入每个流水线阶段  
  - 采用NIST SP 800-204D标准，确保配置完整性、自动化安全测试和全链路可追溯  
  - 应用OWASP CI/CD Top 10风险防护，防止凭证泄露、权限滥用和恶意代码执行  
  - 秘密管理遵循最小权限原则，使用专业工具如HashiCorp Vault、AWS Secrets Manager等进行加密存储和自动轮换  
  - 定期进行威胁建模，动态识别和修复新出现的安全漏洞和配置风险

---

## 博客精选

### 通用安全趋势与技术

- [2025年CI/CD管道安全趋势与创新](https://www.linkedin.com/pulse/top-7-cicd-pipeline-trends-2025-kairos-technologies-inc-fcuuc)  
  重点介绍AI与机器学习驱动的智能自动化、微服务与Kubernetes的主导地位、Shift-Left测试、无服务器架构、DevSecOps安全内建、基础设施即代码（IaC）集成及云原生混合云CI/CD。

- [CI/CD安全威胁建模与防御实践](https://spacelift.io/blog/ci-cd-security)  
  介绍如何通过威胁建模识别风险，结合自动化扫描和访问控制强化管道安全。

- [Xygeni：端到端CI/CD安全解决方案及标准遵循](https://xygeni.io/blog/what-security-standards-for-cicd-pipelines-apply-in-2025/)  
  详述如何通过工具实现NIST SP 800-204D、OWASP CI/CD Top 10和SLSA合规，自动化发现和阻断安全威胁。

### 平台与工具安全专题

- **GitHub Actions安全**  
  - [GitHub Actions安全威胁与防护](https://securitylab.github.com/research/github-actions-preventing-pwn-requests/)  
  - [利用GitHub Actions自动化检测和防止密钥泄露](https://blog.teddykatz.com/2021/03/17/github-actions-write-access.html)

- **GitLab安全**  
  - [GitLab Runner滥用案例分析](https://frichetten.com/blog/abusing-gitlab-runners/)  
  - [保护自管理Runner的最佳实践](https://docs.gitlab.com/runner/security/)

- **Jenkins安全**  
  - [Jenkins攻击手法与防御](https://msgpeek.net/blog/2020/02/attacking-jenkins/)  
  - [插件信任与后门风险](https://www.synopsys.com/blogs/software-security/backdooring-jenkins-builds-and-security-measures/)

- **ArgoCD安全漏洞分析**  
  - [ArgoCD SSRF漏洞详解](https://blog.calif.io/p/argo-cd-csrf)

---

## 视频推荐

- [攻击开发管道以获取实际利益](https://www.youtube.com/watch?v=AQCvfzwcGso)  
- [利用CI和自动构建系统的漏洞](https://www.youtube.com/watch?v=mpUDqo7tIk8)

---

## 工具与代码库

- [Gato](https://github.com/praetorian-inc/gato) — 自动发现GitHub组织中公共和私有仓库安全弱点的工具，适合蓝队和渗透测试。

- [Sysdig](https://github.com/draios/sysdig) — 云安全平台，提供实时威胁检测、漏洞管理和云态势感知，支持零信任权限管理。

- [CI/CD管道威胁矩阵](https://github.com/rung/threat-matrix-cicd) — 系统化展示CI/CD安全威胁，助力风险评估和防护设计。

---

## 练习场

- [CI/CD Goat](https://github.com/cider-security-research/cicd-goat) — 一个专门设计用于CI/CD安全攻防演练的靶场，帮助团队实战演练漏洞利用与防御。

---

## 案例分析

- [CI/CD管道攻击的企业安全威胁增长趋势](https://limacharlie.io/blog/cicd-pipeline-attacks)  
- [利用泄露凭证破坏CI/CD管道的真实案例](https://blog.gitguardian.com/security-zines-2-compromising-ci-cd-pipelines/)

---

## 2025年CI/CD安全前沿洞察

- **AI与机器学习驱动智能自动化**：自动识别构建异常、预测失败，提升流水线智能化和自愈能力。

- **微服务与Kubernetes为核心架构**：支持复杂应用的模块化部署和弹性扩展，CI/CD管道需适配容器编排和服务网格。

- **Shift-Left安全测试**：安全检测贯穿开发早期，结合SAST、DAST、IAST和SCA实现全生命周期漏洞防护。

- **无服务器架构加速部署**：事件驱动的自动化流水线减少基础设施管理负担，提高响应速度。

- **DevSecOps安全内建**：安全策略和合规检查自动嵌入流水线，确保每次代码提交安全合规。

- **基础设施即代码（IaC）安全**：自动扫描IaC模板，防止配置错误导致的安全风险。

- **云原生与混合云支持**：CI/CD工具和安全方案适配多云环境，保障跨平台安全与合规。

- **秘密管理与访问控制强化**：采用集中加密管理，自动轮换与最小权限原则，防止凭证泄露。

- **合规与审计自动化**：流水线全链路日志和安全事件自动记录，支持NIST、ISO、DORA等标准审计。

---

通过持续更新和整合上述资源，您可以构建一条安全、智能、高效的CI/CD流水线，抵御日益复杂的安全威胁，助力企业软件交付的稳定与合规。
