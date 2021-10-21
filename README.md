# README

https://medium.com/@mattiaperi/create-a-public-helm-chart-repository-with-github-pages-49b180dbb417

Repository Guide: https://helm.sh/docs/topics/chart_repository/

`helm lint helm-chart-sources/*`

`helm package helm-chart-sources/helm-chart-test`

`helm repo index helm-chart-sources/* --url https://mastrogiovanni.github.io/helm-chart`