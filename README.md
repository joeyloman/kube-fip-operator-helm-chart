# Kube-fip-operator Helm Chart

## Prerequisites

- Helm 3.x

## Adding the Chart

```SH
helm repo add kube-fip-operator https://joeyloman.github.io/kube-fip-operator-helm-chart
helm repo update
```

## Installing the Chart

```SH
helm install kube-fip-operator kube-fip-operator/kube-fip-operator -n kube-fip --create-namespace
```

# License

Copyright (c) 2021 Joey Loman <joey@binbash.org>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
