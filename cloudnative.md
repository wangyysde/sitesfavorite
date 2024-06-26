# 云原生相关站点

<a href="https://www.sysadm.cn" target="_blank"><img src="./images/sysadm.png"></a>

---
# <a id="catalog">目录分类 </a>
- <a href="#genernal">综合站点</a>
- <a href="#image">镜像相关</a>
- <a href="#cri">容器运行时</a>
- <a href="#spec">规格书Spec</a>
- 
---
## <a id="genernal">综合站点</a>
<table>
<tr bgcolor="#4169E1">
    <td>序号</td> <td>名称</td> <td>地址</td> <td>描述</td>
</tr>
<tr>
  <td>1</td> <td>CNCF Landscape</td> <td><a href="https://landscape.cncf.io" target="_blank">https://landscape.cncf.io</a></td>  <td>列出CNCF基金会当前处于沙箱、孵化和已经毕业项目清单，CNCF会员清单，帮助向导以及CNCF相关统计</td>
</tr>
<tr>
  <td>2</td> <td>Cloud Native Glossary</td>
  <td><a href="https://glossary.cncf.io/" target="_blank">https://glossary.cncf.io/</a> </td>
  <td>仓库： <a href="https://github.com/cncf/glossary" target="_blank">https://github.com/cncf/glossary</a> </td>
</tr>
</table>


---
## <a id="image">镜像相关</a>
<a href="#catalog">返回项部</a>     [返回总分类](./README.md)
<table>
<tr bgcolor="#4169E1">
    <td>序号</td> <td>名称</td> <td>描述</td> <td>仓库</td> <td>官网</td><td>使用手册</td><td>状态</td><td>备注</td>
</tr>
<tr>
    <td>1</td> <td>distribution</td><td>镜像仓库Registry</td>
    <td><a href="https://github.com/distribution/distribution" target="_blank">https://github.com/distribution/distribution</a> </td>
    <td><a href="https://distribution.github.io/distribution" target="_blank">https://distribution.github.io/distribution</a> </td>
    <td></td><td>正常</td><td></td>
</tr>

<tr>
    <td>2</td> <td>harbor</td><td>harbor镜像仓库</td>
    <td><a href="https://github.com/goharbor/harbor" target="_blank">https://github.com/goharbor/harbor</a> </td>
    <td><a href="https://goharbor.io/" target="_blank">https://goharbor.io/</a> </td>
    <td><a href="https://goharbor.io/docs/2.10.0/" target="_blank">https://goharbor.io/docs/2.10.0/</a> </td>
    <td>正常</td> <td></td>
</tr>

</table>

---
## <a id="cri">容器运行时</a>
<a href="#catalog">返回项部</a>     [返回总分类](./README.md)
<table>
<tr bgcolor="#4169E1">
    <td>序号</td> <td>名称</td> <td>描述</td> <td>仓库</td> <td>官网</td><td>使用手册</td><td>状态</td><td>备注</td>
</tr>
<tr>
    <td>1</td> <td>containerd</td><td>一个工业标准的容器运行时</td>
    <td><a href="https://github.com/containerd/containerd" target="_blank">https://github.com/containerd/containerd</a> </td>
    <td><a href="https://containerd.io" target="_blank">https://containerd.io</a> </td>
    <td><a href="https://containerd.io/docs/" target="_blank">https://containerd.io/docs/</a> </td><td>正常</td><td></td>
</tr>
<tr>
    <td>2</td> <td>cri-o</td> <td>基于OCI的Kubernetes容器运行时接口实现</td>
    <td><a href="https://github.com/cri-o/cri-o" target="_blank">https://github.com/cri-o/cri-o</a> </td>
    <td><a href="https://cri-o.io/" target="_blank">https://cri-o.io/</a> </td>
    <td></td><td>正常</td><td></td>
</tr>

</table>

---
## <a id="spec">规格书Spec</a>
<a href="#catalog">返回项部</a>     [返回总分类](./README.md)

<table>
<tr bgcolor="#4169E1">
    <td>序号</td> <td>名称</td> <td>描述</td> <td>仓库</td> <td>官网</td><td>状态</td><td>备注</td>
</tr>
<tr>
    <td>1</td> <td>OCI Distribution Specification</td><td>是用于规范内容分发，如容器镜像的上传和下截的API协议规范</td>
    <td><a href="https://github.com/opencontainers/distribution-spec" target="_blank">https://github.com/opencontainers/distribution-spec</a> </td>
    <td><a href="https://opencontainers.org/" target="_blank">https://opencontainers.org/</a> </td>
    <td>正常</td> <td>这个规范与下面的镜像格式规范,运行时规范相关</td>
</tr>
<tr>
    <td>2</td> <td>镜像格式规范OCI Image Format Specification</td><td>规范容器镜像格式</td>
    <td><a href="https://github.com/opencontainers/image-spec" target="_blank">https://github.com/opencontainers/image-spec</a> </td>
    <td><a href="https://opencontainers.org/" target="_blank">https://opencontainers.org/</a> </td>
    <td>正常</td> <td>这个规范与内容分发规范和运行时规范相关</td>
</tr>
<tr>
    <td>3</td> <td>容器运行时规范 OCI Runtime Specification</td> <td>容器运行时规范</td>
    <td><a href="https://github.com/opencontainers/runtime-spec" target="_blank">https://github.com/opencontainers/runtime-spec</a> </td>
    <td><a href="https://opencontainers.org/" target="_blank">https://opencontainers.org/</a> </td>
    <td>正常</td> <td></td>
</tr>

</table>