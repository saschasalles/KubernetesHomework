# tp-k8s
Wordpress + kubernetes + kubedb 



### 1 - Découpage en namespaces

`Voulu` :
  - app: pour wordpress
  - db: pour kubedb
  - monitoring: pour prometheus et grafana


En réalité nous n'avons qu'un seul namespace.
  
