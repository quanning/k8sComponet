# k8sComponet

docker pull registry.aliyuncs.com/google_containers/coredns:1.3.1
docker tag registry.aliyuncs.com/google_containers/coredns:1.3.1 k8s.gcr.io/coredns:1.3.1

docker pull registry.aliyuncs.com/google_containers/metrics-server-amd64:v0.3.5
docker tag registry.aliyuncs.com/google_containers/metrics-server-amd64:v0.3.5 k8s.gcr.io/metrics-server-amd64:v0.3.5

docker pull registry.aliyuncs.com/google_containers/fluentd-elasticsearch:v2.4.0
docker tag registry.aliyuncs.com/google_containers/fluentd-elasticsearch:v2.4.0 k8s.gcr.io/fluentd-elasticsearch:v2.4.0

docker pull quay.io/fluentd_elasticsearch/elasticsearch:v6.7.2
docker pull quay.io/fluentd_elasticsearch/fluentd:v2.5.2
