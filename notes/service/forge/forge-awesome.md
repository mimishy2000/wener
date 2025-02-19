---
tags:
  - Awesome
---

# Forge Awesome

- [Git](./git/README.md)
- hg
- [fossil](https://fossil-scm.org/)
  - VCS, tickets, wiki, docs, notes, forum, chat, UI, RBAC
  - [vs Git](https://fossil-scm.org/home/doc/trunk/www/fossil-v-git.wiki)
  - [whynotgit](https://www.sqlite.org/whynotgit.html)
- Hosted
  - gitee
  - [github](./github.md)
  - gitee
    - CI/CD Jenkins,GiteeGo
  - [coding](./coding.md)
    - 腾讯
    - CI/CD Jenkins
  - Codeberg
    - 基于 Gitea (2019)
    - fork Gitea -> Forgejo (2022)
- 开源
  - [theonedev/onedev](./onedev.md)
    - MIT, Java
    - CI/CD
    - Symbol Search, Navigation - 类似 IDE 体验
    - Static Analysis
    - Kanban
    - SLOC trend
    - https://code.onedev.io/
  - [gitlab](./gitlab/README.md)
    - 非常重
  - [gitea](./gitea.md)
    - 轻量级
    - 内置 package
    - 无 CI/CD - 可外置 drone
  - gogs
  - [gitness](https://github.com/harness/gitness)
    - Apache-2.0, Golang
    - by Harness
    - Drone 参考重命名为了 gitness
    - Drone 3.0 ~-> Drone+/Code
    - https://news.ycombinator.com/item?id=37598082
      - Harness 名声不太好

## Package

-

## CI/CD Pipeline

- [Jenkins](./jenkins/README.md)
  - MIT, Java
- [GoCD](https://github.com/gocd/gocd)
  - Apache-2.0, Java
- [rundeck](./rundeck.md)
- CircleCI
- [drone](./drone/README.md)
  - 不太活跃
  - 非完全开源协议
- [woodpecker](./woodpecker/README.md)
  - Apache-2.0, Go
  - community fork of the Drone CI 0.8
- [gitlab runner](./gitlab/gitlab-runner.md)
  - 只能 Gitlab
  - 集成度最高
- [agola-io/agola](https://github.com/agola-io/agola)
- [argocd](../../devops/kubernetes/app/argocd.md)
- [argo workflow](../../devops/kubernetes/app/argo-workflow.md)
- [dagger/dagger](https://github.com/dagger/dagger)
  - Apache-2.0, Go, CUE
  - 可在本地使用
  - 使用 CUE 定义
  - 使用 BuildKit 构建
  - https://docs.dagger.io/1222/core-actions-reference/
- [earthly/earthly](https://github.com/earthly/earthly)
  - MPLv2, Go
- [openspug/spug](https://github.com/openspug/spug)
  - 运维平台
- [concourse/concourse](https://github.com/concourse/concourse)
- https://github.com/buildbot/buildbot
- [spinnaker/spinnaker](https://github.com/spinnaker/spinnaker)
  - 停滞

```bash
brew install dagger/tap/dagger
```
