# GoLang开发语言站点

<a href="https://www.sysadm.cn" target="_blank"><img src="./images/sysadm.png"></a>

---
# <a id="catalog">目录分类 </a>
- <a href="#kubernetes">Kubernetes生态组件</a>
- <a href="#thirdparty">Kubernetes第三方组件</a>
- <a href="#development">应用定义和部署</a>

---
## <a id="kubernetes">Kubernetes社区组件</a>
<a href="#catalog">返回项部</a>     [返回总分类](./README.md)
<table>
<tr bgcolor="#4169E1">
    <td>序号</td> <td>名称</td> <td>描述</td> <td>仓库</td> <td>官网</td><td>使用手册</td><td>状态</td><td>备注</td>
</tr>
<tr>
  <td>1</td> <td>dashboard</td> <td>用于管理kubernetes的Web UI系统</td> <td><a href="https://github.com/kubernetes/dashboard" target="_blank"> https://github.com/kubernetes/dashboard</a></td><td></td>
    <td><a href="https://github.com/kubernetes/dashboard/blob/master/docs/user/README.md" target="_blank">https://github.com/kubernetes/dashboard
    /blob/master/docs/user/README.md</a> </td><td>正常</td>
    <td></td>
</tr>

<tr>
    <td>2</td> <td>kwok(Kubernetes WithOut Kubelet)</td><td>一个用于创建和管理不带kubelet的kubernetes集群的管理，声称可以在秒级内创建出拥有数千个节点的集群</td>
    <td><a href="https://github.com/kubernetes-sigs/kwok" target="_blank">https://github.com/kubernetes-sigs/kwok</a> </td>
    <td><a href="https://kwok.sigs.k8s.io" target="_blank">https://kwok.sigs.k8s.io/</a> </td>
    <td></td><td>正常</td>
    <td>很有意思的工具，有空需要研究一下:1. 如何实现的不带kubelet， 2.快速配置数千节点的实现原理</td>
</tr>
<tr>
  <td>3</td> <td>kubernetes</td> <td>kubernetes总仓库</td>
  <td><a href="https://github.com/kubernetes/kubernetes" target="_blank">https://github.com/kubernetes/kubernetes</a> </td>
  <td><a href="https://kubernetes.io/" target="_blank">https://kubernetes.io/</a> </td>
  <td><a href="https://kubernetes.io/docs/home/" target="_blank">https://kubernetes.io/docs/home/</a> </td>
  <td>正常</td> <td></td>
</tr>

<tr>
  <td>4</td> <td>minikube</td><td>一个适合部署、管理单节点kubernetes集群的工具</td>
  <td><a href="https://github.com/kubernetes/minikube" target="_blank">https://github.com/kubernetes/minikube</a> </td>
  <td><a href="https://minikube.sigs.k8s.io/" target="_blank">https://minikube.sigs.k8s.io/</a> </td>
  <td></td><td>正常</td><td></td>
</tr>

<tr>
    <td>5</td> <td>enhancements</td><td>Kuberentes的增强跟踪仓库</td>
    <td><a href="https://github.com/kubernetes/enhancements">https://github.com/kubernetes/enhancements</a> </td>
    <td></td><td></td><td>正常</td>
    <td>对kubernetes组件有特性方面的改进时，需要在这个仓库里先提交Issue，并提交PR，合并后再实施新特性添加</td>
</tr>

<tr>
    <td>6</td> <td>kubeadm</td> <td>一个创建和管理kubernetes集群的工具</td>
    <td><a href="https://github.com/kubernetes/kubeadm" target="_blank">https://github.com/kubernetes/kubeadm</a> </td>
    <td></td><td></td><td></td><td>kubeadm代码在kubernetes仓库里</td>
</tr>

<tr>
    <td>7</td> <td>website</td><td>kubernetes官网仓库</td>
    <td><a href="https://github.com/kubernetes/website" target="_blank">https://github.com/kubernetes/website</a> </td>
    <td><a href="https://kubernetes.io/" target="_blank">https://kubernetes.io/</a> </td>
    <td></td><td>正常</td><td></td>
</tr>

<tr>
    <td>8</td> <td>org</td><td>这个仓库是用于管理kubernetes在GitHub上的组织的，即当给某个ID授予某个角色时，即是修改这个仓库里config下指定文件内容</td>
    <td><a href="https://github.com/kubernetes/org" target="_blank">https://github.com/kubernetes/org</a> </td>
    <td></td><td></td><td>正常</td><td></td>
</tr>
    <td>9</td> <td>community</td><td>这个仓库存放的是与kuberneter社区治理相关的文档</td>
    <td><a href="https://github.com/kubernetes/community">https://github.com/kubernetes/community</a> </td>
    <td></td><td></td><td>正常</td><td>阅读这个仓库里的文档可以了解kubernetes社区的日常运作流程</td>
<tr>
    
</tr>

</table>

---
## <a id="thirdparty">Kubernetes第三方组件</a>
<a href="#catalog">返回项部</a>     [返回总分类](./README.md)
<table>
<tr bgcolor="#4169E1">
    <td>序号</td> <td>名称</td> <td>描述</td> <td>仓库</td> <td>官网</td><td>使用手册</td><td>状态</td><td>备注</td>
</tr>
<tr>
    <td>1</td> <td>Prometheus Go client library</td><td>Prometheus的Go Client Library</td>
    <td><a href="https://github.com/prometheus/client_golang" target="_blank">https://github.com/prometheus/client_golang</a> </td>
    <td></td><td></td><td>正常</td><td></td>
</tr>

<tr>
    <td>2</td> <td>clusterpedia </td> <td>一个多集群同步，搜索和简单的资源控制工具</td>
    <td><a href="https://github.com/clusterpedia-io/clusterpedia" target="_blank">https://github.com/clusterpedia-io/clusterpedia</a> </td>
    <td><a href="https://clusterpedia.io/" target="_blank">https://clusterpedia.io/</a> 
    <td><a href="https://clusterpedia.io/docs/" target="_blank">https://clusterpedia.io/docs/</a> </td>
    <td>正常</td> 
    <td>DaoCloud公司团队开发</td>
</tr>

<tr>
    <td>3</td> <td>clusternet</td> <td>kubernetes多集群管理工具</td>
    <td><a href="https://github.com/clusternet/clusternet" target="_blank">https://github.com/clusternet/clusternet</a> </td>
    <td><a href="https://clusternet.io" target="_blank">https://clusternet.io/</a> </td>
    <td><a href="https://clusternet.io/docs/" target="_blank">https://clusternet.io/docs/</a> </td>
    <td>正常</td> <td>CNCF 沙箱项目</td>
</tr>
<tr>
    <td>4</td> <td>pushgateway</td><td>用于向Prometheus暴露批处理和短时任务的metrics.</td>
    <td><a href="https://github.com/prometheus/pushgateway" target="_blank">https://github.com/prometheus/pushgateway</a></td>
    <td></td><td></td><td>正常</td><td></td>
</tr>
<tr>
    <td>5</td> <td>kube-prometheus</td> <td>这个仓库收集了使用prometheus监控kubernetes可能用到的manifests，grafana模板和prometheus规则等</td>
    <td><a href="https://github.com/prometheus-operator/kube-prometheus" target="_blank">https://github.com/prometheus-operator/kube-prometheus</a> </td>
    <td><a href="https://prometheus-operator.dev/" target="_blank">https://prometheus-operator.dev/</a> </td>
    <td></td><td>正常</td><td></td>
</tr>
<tr>
    <td>6</td> <td>kubeedge</td><td>kubernetes原生边缘计算框架</td>
    <td><a href="https://github.com/kubeedge/kubeedge" target="_blank">https://github.com/kubeedge/kubeedge</a> </td>
    <td><a href="https://kubeedge.io/" target="_blank">https://kubeedge.io/</a> </td>
    <td></td><td></td><td>这是CNCF的一个孵化项目</td>
</tr>

<tr>
    <td>7</td> <td>envoy</td><td>一款云原生的服务代理服务器</td>
    <td><a href="https://github.com/envoyproxy/envoy" target="_blank">https://github.com/envoyproxy/envoy</a>  </td>
    <td><a href="https://www.envoyproxy.io/" target="_blank">https://www.envoyproxy.io/</a> </td>
    <td><a href="https://www.envoyproxy.io/docs" target="_blank">https://www.envoyproxy.io/docs</a> </td>
    <td>正常</td><td></td>
</tr>

<tr>
    <td>8</td> <td>istio</td><td>服务网络的可观测性、流量、安全及策略管理</td>
    <td><a href="https://github.com/istio/istio.io" target="_blank">https://github.com/istio/istio.io</a> </td>
    <td><a href="https://istio.io/" target="_blank">https://istio.io/</a> </td>
    <td><a href="https://istio.io/latest/docs/" target="_blank">https://istio.io/latest/docs/</a> </td>
    <td>正常</td><td>CNCF毕业项目</td>
</tr>

</table>

---
## <a id="development">应用定义和部署</a>
<a href="#catalog">返回项部</a>     [返回总分类](./README.md)
<table>
<tr bgcolor="#4169E1">
    <td>序号</td> <td>名称</td> <td>描述</td> <td>仓库</td> <td>官网</td><td>使用手册</td><td>状态</td><td>备注</td>
</tr>

<tr>
    <td>1</td> <td>helm</td> <td>微服务应用的管理工具</td>
    <td><a href="https://github.com/helm/helm" target="_blank">https://github.com/helm/helm</a> </td>
    <td><a href="https://helm.sh/" target="_blank">https://helm.sh/</a> </td>
    <td><a href="https://helm.sh/docs/" target="_blank">https://helm.sh/docs/</a> </td>
</tr>


</table>