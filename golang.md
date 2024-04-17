# GoLang开发语言站点

<a href="https://www.sysadm.cn" target="_blank"><img src="./images/sysadm.png"></a>

---

# <a id="catalog">目录分类 </a>
- <a href="#basic">语言基础</a>
- <a href="#framework">组件和框架</a>
- <a href="#kubernetes">Kubernetes生态组件</a>
- <a href="#thirdparty">Kubernetes第三方组件</a>


---
## <a id="basic">语言基础</a>


---
## <a id="framework">组件和框架</a> 
<a href="#catalog">返回项部</a>     [返回总分类](./README.md)
<table>
<tr bgcolor="#4169E1">
    <td>序号</td> <td>名称</td> <td>描述</td> <td>仓库</td> <td>官网</td><td>使用手册</td><td>状态</td>
</tr>
<tr>
  <td>1</td> <td>logrus</td> <td>完全兼容标准log的结构化日志处理器(logger)</td> <td><a href="https://github.com/sirupsen/logrus" target="_blank"> https://github.com/sirupsen/logrus</a></td><td></td><td></td><td>维护状态，不引入新功能</td>
</tr>
<tr>
  <td>2</td> <td>gin</td> <td>GO语言的HTTP Web框架</td> 
  <td><a href="https://github.com/gin-gonic/gin" target="_blank">https://github.com/gin-gonic/gin</a> </td>
  <td><a href="https://gin-gonic.com/" target="_blank">https://gin-gonic.com/</a> </td>
  <td><a href="https://gin-gonic.com/docs/" target="_blank">https://gin-gonic.com/docs/</a> </td>
  <td>正常</td>
</tr>
</table>


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

</table>