# awesome-cicd-security（ 优秀的 CI/CD 安全资源 ）
一份关于 CI/CD 安全的优秀资源列表，包含书籍、博客、视频、工具和案例。

## 书籍

- [高级基础设施渗透测试](https://www.packtpub.com/product/advanced-infrastructure-penetration-testing/9781788624480)

## 指南
- [保护 CI/CD 环境的指南（来自 CISA & NSA）](https://media.defense.gov/2023/Jun/28/2003249466/-1/-1/0/CSI_DEFENDING_CI_CD_ENVIRONMENTS.PDF)

## 博客

### 通用

- [CI/CD 安全风险十大排名](https://github.com/nathanawmk/top-10-cicd-security-risks)
- [持续交付 3.0 成熟度模型（CD3M）](https://nisi.nl/continuousdelivery/articles/maturity-model)
- [从攻击者的角度可视化 CI/CD](https://medium.com/cider-sec/visualizing-ci-cd-from-an-attackers-perspective-22dfa38c9d09)
- [云供应链管道攻击的剖析](https://www.paloaltonetworks.com/blog/2021/10/anatomy-ci-cd-pipeline-attack/)
- [供应链攻击遇到 CI/CD 基础设施](https://blogs.vmware.com/networkvirtualization/2021/12/29260.html/)
- [CI/CD 供应链攻击：数据窃取或云账号劫持](https://www.praetorian.com/blog/ci-cd-supply-chain-attacks-for-data-exfiltration-or-cloud-account-takeover/)
- [使用 Tracee 检测 CI/CD 管道中的恶意活动](https://blog.aquasec.com/cicd-pipeline-security-tool-tracee)
- [破解管道：参数注入](https://devblogs.microsoft.com/devops/pipeline-argument-injection/)
- [破解管道：窃取其他仓库](https://devblogs.microsoft.com/devops/pipeline-stealing-another-repo/)
- [破解管道：共享基础设施](https://devblogs.microsoft.com/devops/pipeline-shared-infrastructure/)
- [配置不良的 CI/CD 系统可能成为进入基础设施的后门](https://thenewstack.io/poorly-configured-ci-cd-systems-can-be-a-backdoor-into-your-infrastructure/)
- [评估 CI/CD 管道中的漏洞和配置问题：第一部分](https://success.qualys.com/discussions/s/article/000005841)
- [评估 CI/CD 管道中的漏洞和配置问题：第二部分](https://success.qualys.com/discussions/s/article/000005842)
- [保护软件构建管道免受恶意攻击](https://www.ncsc.gov.uk/blog-post/defending-software-build-pipelines-from-malicious-attack)
- [云原生最佳实践：CI/CD 管道中的安全策略](https://blog.aquasec.com/cloud-native-security-best-practices-devops-security)

### Azure DevOps 服务器

- [Azure DevOps 服务器供应链攻击树（地图、攻击面、威胁建模）](https://github.com/sergiomarotco/Azure-DevOps-server-supply-chain-attack-tree)

### GitLab

- [滥用 GitLab Runners](https://frichetten.com/blog/abusing-gitlab-runners/)
- [GitLab 漏洞可能导致攻击者窃取 runner 注册令牌](https://portswigger.net/daily-swig/critical-gitlab-vulnerability-could-allow-attackers-to-steal-runner-registration-tokens)
- [理解 GitLab 的安全威胁并加强防御](https://www.mitiga.io/blog/understanding-gitlabs-security-threats-and-strengthening-your-preparedness)
- [使用 Sysbox 保护 GitLab CI 管道](https://blog.nestybox.com/2020/10/21/gitlab-dind.html)
- [GitLab - 自管理 runners 的安全性](https://docs.gitlab.com/runner/security/)

### GitHub Actions

- [窃取任意 GitHub Actions 密钥](https://blog.teddykatz.com/2021/03/17/github-actions-write-access.html)
- [在开源项目中利用 GitHub Actions](https://medium.com/tinder/exploiting-github-actions-on-open-source-projects-5d93936d189f)
- [GitHub Actions 运行环境分析与安全措施](https://www.trendmicro.com/vinfo/us/security/news/cybercrime-and-digital-threats/github-action-runners-analyzing-the-environment-and-security-in-action)
- [GitHub Actions 供应链攻击及其防护](https://securitylab.github.com/research/github-actions-preventing-pwn-requests/)

### Jenkins

- [攻击 Jenkins](https://msgpeek.net/blog/2020/02/attacking-jenkins/)
- [使用共享库攻击 Jenkins](https://oxhat.blogspot.com/2022/07/attacking-backdooring-and-exfiltrating.html)
- [反思插件的信任：后门 Jenkins 构建](https://www.synopsys.com/blogs/software-security/backdooring-jenkins-builds-and-security-measures/)

### ArgoCD

- [ArgoCD SSRF 漏洞](https://blog.calif.io/p/argo-cd-csrf)

## 视频

- [攻击开发管道以获取实际利益](https://www.youtube.com/watch?v=AQCvfzwcGso)
- [利用 CI 和自动构建系统的漏洞](https://www.youtube.com/watch?v=mpUDqo7tIk8)

## 代码库
- [CI/CD 管道的威胁矩阵](https://github.com/rung/threat-matrix-cicd)

## 工具
- [Gato](https://github.com/praetorian-inc/gato) - 帮助蓝队人员和渗透测试人员发现 GitHub 组织公共和私有仓库中的弱点的工具。

## 练习场

- [CI/CD Goat](https://github.com/cider-security-research/cicd-goat)

## 案例

- [CI/CD 管道攻击：不断增长的企业安全威胁](https://limacharlie.io/blog/cicd-pipeline-attacks)
- [利用泄露的凭证破坏 CI/CD 管道](https://blog.gitguardian.com/security-zines-2-compromising-ci-cd-pipelines/)

