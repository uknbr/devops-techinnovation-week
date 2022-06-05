# Amdocs TechInnovation Week 2022
## DevOps

<img src="png/01.png" width="680" height="382">

---

<img src="png/02.png" width="680" height="382">

---

<img src="png/03.png" width="680" height="382">

---
<img src="png/04.png" width="680" height="382">

---

<img src="png/05.png" width="680" height="382">

---

<img src="png/06.png" width="680" height="382">

---

### Requirements
- Kubernetes Cluster
- Ansible
- [GitHub runner](https://docs.github.com/en/actions/hosting-your-own-runners/about-self-hosted-runners)

### Configuration
- [playbook](hello.yaml)
- [kubernetes](cluster.ini)

### GitHub Action Workflow
```terminal
$ mkdir .github/workflows/
$ cp -fv CD/deploy.yaml .github/workflows/deploy.yaml
```