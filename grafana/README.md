### Please follow these steps to deploy Prometheus

1. Install Prometheus Server agent on the cluster thats provided to you

<ul>
  <pre>
  kubectl create -f https://raw.githubusercontent.com/gvijayar/pks-workshop/master/grafana/InstallPrometheusAgent.yaml
  </pre>
</ul>

2. Install the Grafana Dashboard Service


<ul>
  <pre>
  kubectl create -f https://raw.githubusercontent.com/gvijayar/pks-workshop/master/grafana/InstallGrafana.yaml
  </pre>
</ul>
