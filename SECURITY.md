# Security Policy


# ☁ zerohat consulting.MANIFESTO ☁
We're a [DevOps/SRE Professional Services](https://ctopilot.de) & we ❤️  [Open Source Software](https://github.com/) and are ☁ [Public Cloud Enthusiast's](https://ctopilot.de).


---

- [x] Member privileges are separated through GitHub Teams and repository rules
- [x] We use dedicated Github Runners for mid-/large-sized customer deployments
- [x] We use dedicated private repos for customers
- [x] References to our public infrastructure-as-code repos are non-sensitive and only referring to fully parameterized variables
- [x] GitHub Audit Logs are validated on a regular basis
- [x] GitHub Security Analysis are activated for all public & private repos
- [x] We only allow APPROVED domains to send/receive alerts
- [x] ANY secrets are stored in an encrypted way & using GitHub [security best-practices](https://docs.github.com/en/actions/security-guides/security-hardening-for-github-actions) (GitHub Secrets, AWS KMS or Azure KeyVault)
- [x] We DO NOT ALLOW using pipelines (GitHub Actions/Workflows) with ANY clear-text, sensitive variable references
- [x] Third [party application](https://github.com/organizations/cloudeteer/settings/oauth_application_policy) access is going through org admin approval process
- [x] GitHub Apps are also following strict approval process
- [x] Infrastructure-as-Code templates are approved through a strict QA-process 
- [x] Container images (like Docker) are scanned through Trivy, Clair, OPA or another 3rd-party scanner
- [x] ANY changes in customer private repos are going through strict ITSM change approval process

## Supported Versions

| Repo | Supported          |
| ------- | ------------------ |
| Private   | :white_check_mark: |          |
| Public   | :white_check_mark: |

---

## :warning: Reporting a Vulnerability :warning:

> [!IMPORTANT]  
> SECURITY-MATTERS FOR THE WHOLE COMMUNITY - \
> IF YOU FIND ANY SECURITY ISSUES, PLEASE OPEN AN ISSUE ON OUR PUBLIC REPO'S OR DROP AS A PRIVATE NOTE/EMAIL disclosure @ ctopilot.de

