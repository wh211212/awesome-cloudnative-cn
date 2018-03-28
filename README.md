# <img src="https://raw.githubusercontent.com/wh211212/Cloud-Native/master/Images/cloudnativelog.png" width="500" alt="Cloud Native">

[![jaywcjlove/sb](https://jaywcjlove.github.io/sb/lang/chinese.svg)](README-cn.md)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> 收集整理云原生技术学习资料，包括Cloud Native（云原生）和Service Mesh（服务网格）。

<!-- <img src="https://raw.githubusercontent.com/wh211212/Cloud-Native/master/Images/cloudnativelog.png" width="500" alt="Cloud Native"> -->

## 云原生技术栈

# <img src="https://raw.githubusercontent.com/wh211212/Cloud-Native/master/Images/CloudNativeLandscape_latest.png" width="800" alt="cloud native">

# <img src="https://raw.githubusercontent.com/wh211212/Cloud-Native/master/Images/TableOfContents.png" width="600" alt="cloud native">

## 构成 

- [云](#云)
- [供应](#供应)
- [运行](#运行)
- [编排和管理](#编排和管理)
- [应用程序定义和开发](#应用程序定义和开发)
- [平台](#平台)
- [无服务器](#无服务器)
- [可观测性和分析](#可观测性和分析)

## 云

- [公有云](https://www.redhat.com/en/topics/cloud-computing/what-is-public-cloud) - 公有云是指第三方提供商通过公共 Internet 提供的计算服务，面向希望使用或购买的任何人。

	- [阿里云](https://www.alibabacloud.com/) - 阿里云开发高度可扩展的云计算和数据管理服务。
	- [AWS](https://aws.amazon.com) - 亚马逊网络服务以网络服务的形式向企业提供信息技术基础设施服务。
	- [Azure云](https://azure.microsoft.com) -Microsoft是一家开发，制造，许可，支持和销售一系列软件产品和服务的软件公司。
	- [百度云](https://cloud.baidu.com/) - 百度是一个中文网站和搜索引擎，可以让个人获得信息并找到他们需要的信息。
	- [DigitalOcean](https://www.digitalocean.com/) - DigitalOcean是一家IaaS公司，为开发人员和企业提供了一种无缝的方式来部署和扩展云中的任何应用程序。
	- [Fujitsu K5](https://www.fujitsu.com/global/solutions/cloud/k5/) - 富士通提供信息技术和通信解决方案。
	- [谷歌云](https://cloud.google.com) - Google是一家跨国公司，专门从事与互联网有关的服务和产品。
	- [华为云](https://www.huaweicloud.com/) - 华为技术有限公司为基础设施应用软件和设备提供有线，无线和IP技术。
	- [IBM云](https://www.ibm.com/cloud/) - IBM是一家IT技术和咨询公司，提供计算机硬件，软件，基础设施和托管服务。
	- [Oracle云](https://cloud.oracle.com) - Oracle是一家计算机技术公司，开发和销售计算机硬件系统和企业软件产品。
	- [Joyent 云](https://www.joyent.com/) - 下一代云
	- [Packet 云](https://www.packet.net/) - Packet是为开发人员构建的裸机云。 8分钟部署，无管理程序和全球15个数据中心的全面自动化支持。
	- [腾讯云](https://cloud.tencent.com) - 腾讯是一家中国互联网服务门户，提供增值互联网，移动，电信和在线广告服务。
	- [思杰云](https://citrix.cloud.com/) - 移动更快，工作更好，降低IT成本。

- [私有云](https://azure.microsoft.com/en-us/overview/what-is-a-private-cloud/) - 私有云被定义为通过互联网或私人内部网络提供的计算服务，仅用于选择用户而不是普通大众。 也称为内部云或企业云，私有云计算为企业带来了公共云带来的诸多好处 - 包括自助服务，可扩展性和弹性 - 并通过托管在本地的计算基础架构上的专用资源提供额外的控制和定制。

	- [Openstack](https://www.openstack.org/) - OpenStack是一个开源的云计算管理平台项目，OpenStack是一个旨在为公共及私有云的建设与管理提供软件的开源项目。
	- [Scaleway](https://www.scaleway.com/) - Scaleway是全球首个云计算IaaS平台。
	- [Foreman](https://www.theforeman.org/) - 一个自动化服务器生命周期的应用程序。
	- [Digital Bebar](http://rebar.digital/) - Digital Rebar Provision是一个简单但功能强大的Golang可执行文件，可提供完整的API驱动的DHCP / PXE / TFTP配置系统。
	- [MAAS](https://maas.io/) - 官方MAAS存储库镜像。 
	- [VMware](https://cloud.vmware.com) - VMware是一家提供云和虚拟化服务的软件公司。
	
- [混合云](https://azure.microsoft.com/en-us/overview/what-is-hybrid-cloud-computing/) - 混合云是一种将公共云和私有云相结合的计算环境，允许数据和应用程序在它们之间共享。

	- [Ensono](https://www.ensono.com) - 完成混合IT服务 - 从云到大型机。 今天操作、 为明天优化。
	- [Dellemc](https://www.dellemc.com/) - 戴尔EMC是戴尔技术致力于转型的重要组成部分。
	- [Hpe](https://www.hpe.com/us/en/solutions/cloud.html) - 混合云解决方案。
	- [Scalr](https://www.scalr.com/) - 混合云管理平台。
	- [IBM混合云](https://www.ibm.com/it-infrastructure/z/capabilities/hybrid-cloud)	 - IBM混合云
	- [Rackspace混合云](https://www.rackspace.com/cloud/hybrid) - Rackspace混合云	
	- [Microsoft混合云](https://azure.microsoft.com/en-us/overview/hybrid-cloud/) - 微软混合云
	- [VMware混合云](https://cloud.vmware.com/) - VMware混合云
	- [AWS混合云](https://aws.amazon.com/cn/enterprise/hybrid/)	- AWS混合云					

## 供应

- 容器私服
  > 容器注册表是一个私人Docker存储库，可与流行的持续交付系统一起使用。

	- [ECR](https://aws.amazon.com/cn/ecr/) - Amazon Elastic Container Registry（ECR）是一个安全的完全托管的Docker容器注册表，使开发人员可以轻松存储，管理和部署Docker容器映像。
	- [Azure Registry](https://azure.microsoft.com/en-us/services/container-registry/) - 作为一流的Azure资源管理Docker私有注册表。
	- [Codefresh Registry](https://codefresh.io/registry-beta/) - Codefresh是一个Docker本地CI / CD平台。不断构建，测试和部署Docker镜像。
	- [Docker Registry](https://docs.docker.com/registry/) - Docker Trusted Registry（DTR）是一款商业产品，支持完整的图像管理工作流程，包括LDAP集成，图像签名，安全扫描以及与通用控制平面的集成。 DTR作为标准版或更高版本的Docker Enterprise订阅的附件提供。
	- [Google Container Registry](https://cloud.google.com/container-registry/) - Google云端平台上的高速私人Docker图像存储。
	- [Harbor](http://vmware.github.io/harbor/) - 基于Docker发行版的企业级容器注册服务器。
	- [JFrog Artifactory](https://jfrog.com/artifactory/) - 企业通用工件管理器。
	- [Portus](http://port.us.org/) - Portus是下一代Docker Registry的开源授权服务和用户界面。
	- [Project Atomic](https://www.projectatomic.io/) - 原子主机提供不可变的基础架构，用于部署到私有云或公共云中的数百或数千台服务器。
	- [QUAY Enterprise](https://coreos.com/quay-enterprise/) - 企业级容器注册表。
  
- 主机管理和工具集
  > 主机管理工具

	- [Ansible](https://www.ansible.com/) - Ansible的设计围绕着人们的工作方式和人们一起工作的方式。
	- [Chef](https://www.chef.io) - 发布更好的软件，速度更快。在您的所有应用程序和基础架构的基础架构，应用程序和合规性中启用协作和持续自动化。
	- [LniuxKit](https://github.com/linuxkit/linuxkit) - 用于为容器构建安全，便携和精益操作系统的工具包。
	- [CFEngine](https://cfengine.com/) - CFEngine社区。
	- [Puppet](https://puppet.com/) - 服务器自动化框架和应用
	- [Rundeck](https://www.rundeck.com/) - 启用自助服务操作：为特定用户提供对现有工具，服务和脚本的访问权限。
	- [Saltstack](https://saltstack.com/) - 针对软件定义世界的智能自动化。

- 基础设施自动化
  > 通过将管理任务和策略转换为代码，基础架构自动化使得服务器和虚拟机管理更加灵活，高效且可扩展。

	- [AWS CloudFormation](https://aws.amazon.com/cn/cloudformation/) - 为您的所有云基础设施资源建模并对其进行预配置。
	- [HOSH](https://bosh.io) - BOSH是用于发布工程，部署，生命周期管理和分布式系统监控的开源工具。
	- [Helm](https://helm.sh/) - Helm是查找，共享和使用为Kubernetes构建的软件的最佳方式。
	- [Infrakit](https://github.com/docker/infrakit) - 用于创建和管理声明式自我修复基础架构的工具包。
	- [Juju](https://jujucharms.com/) - Juju是一款开源应用程序建模工具。 在公共云和私有云上部署，配置，扩展和操作软件。
	- [Cloud Coreo](https://www.cloudcoreo.com/) - 现代云团队的平台。
	- [Cloudify](https://cloudify.co/) - 从根本上简化多云协调
	- [Kubicorn](http://kubicorn.io/) - 在公有云中创建，管理，快照和扩展Kubernetes基础设施。
	- [ManageIQ](http://manageiq.org/) - 发现，优化和控制混合IT。
	- [Terraform](https://www.terraform.io/) - 编写，规划和创建基础架构作为代码。

- [密钥管理](https://en.wikipedia.org/wiki/Key_management)
  > 密钥管理是密码系统中密码密钥管理的名称。

	- [Knox](https://knox.apache.org/) - Apache Knox™Gateway是用于与Apache Hadoop部署的REST API和UI进行交互的应用程序网关。Knox Gateway为所有与Apache Hadoop集群的REST和HTTP交互提供单一接入点。
	- [Oracle Policy Automation](https://www.oracle.com/applications/oracle-policy-automation/index.html) - Oracle Policy Automation是一个端到端的解决方案，用于捕获，管理和部署跨渠道和流程的复杂立法和其他基于文档的策略。
	- [Keywhiz](https://square.github.io/keywhiz/) - 秘密分配和管理系统.
	- [Lyft Confident](https://lyft.github.io/confidant/) - Confidant是一个开源的秘密管理服务，可以从Lyft的开发者那里以安全的方式提供用户友好的存储和访问秘密。
	- [SPIFFE](https://spiffe.io/) - SPIFFE（适用于所有人的安全生产身份识别框架）为现代生产环境中的每个工作负载提供安全身份，采用特制的x509证书形式。 SPIFFE不需要应用程序级别的认证和授权以及复杂的网络级ACL配置。
	- [Spire](https://github.com/spiffe/spire) - SPIFFE运行环境。
	- [Vault](https://www.vaultproject.io/) - 管理秘密的工具。
	  
- [Secure Images](https://docs.imgix.com/setup/securing-images)
  > 保护您的图像，以便保持对在互联网上的显示方式的控制。

	- [Notary](https://github.com/theupdateframework/notary) - 公证是一个允许任何人对任意数据集合有信任的项目。
	- [TUF](https://theupdateframework.github.io/) - 一个保护软件更新系统的框架.
	- [Aqua](https://www.aquasec.com/) - Aqua容器安全平台提供了开发到生产的生命周期控制，用于保护在Windows或Linux上运行在本地或云中的容器化应用程序，从而支持多种编排环境。
	- [Clair](https://coreos.com/clair) - Clair是一个开源项目，用于对appc和docker容器中的漏洞进行静态分析。
	- [OpenSCAP](https://www.open-scap.org/) - 发现各种管理系统安全和标准合规性的工具。
	- [Twistlock](https://www.twistlock.com/) - Docker，Kubernetes和Beyond的容器安全.
	- [Anchore](https://anchore.com/) - 公开和私人容器图像的合规性，认证，安全扫描和审核的开源完整解决方案。
	- [anchore.io](https://anchore.io/) - 发现，分析和验证容器图像。
	- [Black Duck](https://www.blackducksoftware.com/)  - 完全可见性。 自动化控制。
	- [NeuVector](https://neuvector.com/) - Kubernetes容器的连续网络安全.
	- [Sonatype Nexus](https://www.sonatype.com/) - 世界上最好的方式来组织，存储和分发软件组件。

## Runtime

- 云原生网络
  > 网络分段和策略，SDN和API（例如CNI，libnetwork）
  
  CNCF孵化项目
  - [CNI](https://github.com/containernetworking) - 容器网络接口 - 用于Linux容器的网络。
  
  CNCF会员产品/项目
  - [Aporeto](https://www.aporeto.com/) - 面向容器和微服务的云本地安全。
  - [Cannl](https://github.com/projectcalico/canal) - 云原生应用程序的基于策略的网络。
  - [Contiv](https://contiv.github.io/) - 适用于各种用例的容器网络。
  - [Flannel](https://github.com/coreos/flannel/) - flannel是用于容器的网络fabric，专为Kubernetes设计。
  - [NSX](https://www.vmware.com/products/nsx.html) - VMware是一家提供云和虚拟化服务的软件公司。
  - [Open vSwitch](https://openvswitch.org/) - Open vSwitch是一种多层软件开关，以开源Apache 2许可证授权。
  - [OpenContrial](http://www.opencontrail.org/) - 云的开源网络虚拟化平台。
  - [Project Calico](https://www.projectcalico.org/) - 云本地应用程序连接和网络策略。
  - [Weave Net](https://www.weave.works/oss/net/) - 简单，灵活的多主机Docker网络等等。
  
  非CNCF会员产品/项目
  - [Aviatrix](https://aviatrix.com/) - 该公司开发可帮助企业轻松构建混合云的软件。
  - [Big Switch Networks](https://www.bigswitch.com/) - Big Switch Networks是下一代数据中心网络公司，设计智能，灵活和灵活的网络。
  - [Cilium](https://www.cilium.io/) - 使用BPF和XDP的HTTP，gRPC和Kafka Aware安全和网络容器。
  - [Cumulus](https://cumulusnetworks.com/) - Cumulus Networks是一家软件公司，负责设计和销售用于网络硬件的Linux操作系统。
  - [GuardiCoreCentra](https://www.guardicore.com/workloads-protection-hybrid-clouds/) -GuardiCore为软件定义的数据中心提供网络安全解决方案。
  - [MidoNet](https://www.midonet.org/) - MidoNet是Openstack云的开源网络虚拟化系统。
  - [Nuage Networks](http://www.nuagenetworks.net/) - Nuage Networks基础：数据中心及其以外的软件定义网络。
  - [Plumgrid](https://www.vmware.com/products/nsx.html) - PLUMgrid参与虚拟网络和SDN / NFV，提供可转变业务的云基础设施解决方案。
  - [Romana](http://romana.io/) - Romana项目 - 安装脚本，文档，问题跟踪器和wiki。
  - [SnapRoute](https://snaproute.com/) - SnapRoute是一家开放的网络堆栈公司。
    
- 云原生存储
  > 卷驱动程序/插件，本地存储管理，远程存储访问
  
  Sandbox CNCF项目
  - [Rook](https://rook.io/) - 您的云本地环境的文件，块和对象存储服务。
  
  CNCF会员产品/项目
  - [Ceph](https://ceph.com/) - Ceph是一个统一的分布式存储系统，旨在实现出色的性能，可靠性和可扩展性。
  - [Container Storage Interface](https://github.com/container-storage-interface/spec) - 容器存储接口（CSI）规范。
  - [Dell EMC](https://www.dellemc.com) - IT和劳动力转型。 每天都变得真实。
  - [Diamanti](https://diamanti.com/) - Diamanti是第一个具有即插即用网络和持久存储的集装箱平台，可无缝集成最广泛采用的软件堆栈 - 标准开源Kubernetes和Docker - 因此不存在供应商锁定。 网络和存储上的QoS最大化了容器密度。
  - [Gluster](https://www.gluster.org/) - Gluster是免费的开源软件可扩展网络文件系统。
  - [Hatchway](https://vmware.github.io/hatchway/) - 云本地应用程序的永久存储。
  - [Kasten](https://kasten.io/) - Kasten的任务是大幅度简化有状态云本地应用程序的运营管理。
  - [Manta](https://github.com/Illumina/manta) - 映射测序数据的结构变体和indeller。
  - [Minio](https://minio.io/) - Minio是一款高性能的分布式对象存储服务器，专为大型私有云基础架构而设计。 Minio在全球范围内广泛部署，拥有超过64.2M +的码头牵引。
  - [NetApp](https://www.netapp.com) - NetApp HCI。 全新并且现在可用。
  - [OpenEBS](https://www.openebs.io) - OpenEBS是一个开源存储平台，为DevOps和容器环境提供持久和集装箱块存储。
  - [Portworx](https://portworx.com/) - 生产状态容器的解决方案。 专为DevOps设计。
  - [Rex-Ray](https://rexray.readthedocs.io) - REX-Ray是一款开源的存储管理解决方案，旨在支持Docker和Mesos等容器运行时。
  - [StorageOS](https://storageos.com/) - 企业持久性存储容器和云。
  
  非CNCF会员产品/项目
  - [Datera](https://datera.io/) - Datera是一家应用程序驱动的数据基础架构公司。
  - [Hedving](https://www.hedviginc.com/) - 现代化的商业存储。
  - [Infinit](https://www.infinit.sh/) - 基于Elle coroutine的异步C ++开发框架。
  - [LeoFS](https://leo-project.net/leofs/) - LeoFS存储系统
  - [OpenIO](https://www.openio.io/) - OpenIO软件定义存储
  - [Pure Storage](https://www.purestorage.com/) - Pure Storage是一家全闪存企业存储公司，能够在数据中心广泛部署闪存。
  - [Quobyte](https://www.quobyte.com/) - 数据中心文件系统。 快速和可靠的软件存储
  - [Robin Systems](https://robinsystems.com/) - 以数据为中心的计算和存储集装式基础设施软件
  - [Sheepdog](https://sheepdog.github.io/sheepdog/) - QEMU的分布式存储系统
  - [Springpath](http://springpathinc.com/) - Springpath是超融合软件，可将标准服务器选择为单一计算和存储资源池。
  - [Swift](https://docs.openstack.org/swift/latest/) - OpenStack存储（Swift）
  
  集装箱运行时间
  > 新的CF容器运行时为您提供更加细致的Kubernetes容器控制和管理。

  CNCF孵化项目
  - [containerd](https://containerd.io/) 
  - [rkt](https://github.com/rkt/rkt) - rkt是一个适用于Linux的pod本机容器引擎。 它是可组合的，安全的，并建立在标准之上。
  
  CNCF会员产品/项目
  - [CRI-O](http://cri-o.io/) - 基于容器计划的Kubernetes Container运行时接口的实现
  - [Intel Clear Containers](https://clearlinux.org/containers) - 使用虚拟机的OCI（Open Containers Initiative）兼容运行时
  - [Ixd](https://linuxcontainers.org/lxd/) - 基于liblxc的守护进程提供REST API来管理容器
  - [Pouch](https://github.com/alibaba/pouch) - Pouch是一个开源项目，旨在促进容器技术的运动。
  - [runc](https://www.opencontainers.org/) - 根据OCI规范生成和运行容器的CLI工具
  - [SmartOS](https://www.joyent.com/smartos) - 融合容器和虚拟机管理程序

  非CNCF会员产品/项目
  - [Kata Containers](https://katacontainers.io/) - Kata容器运行时间
  - [RunV](https://github.com/hyperhq/runv) - OCI的基于虚拟机管理程序的运行时
  - [Singularity](https://www.sylabs.io/) - 奇点：适用于Linux的应用程序容器   
  
## 编配和管理

- 定时和编排

  CNCF毕业项目
  - [Kubernetes](https://kubernetes.io/) - Kubernetes是一个开源系统，用于自动化容器化应用程序的部署，扩展和管理。
  
  CNCF Member Products/Projects
  - [ECS](https://aws.amazon.com/ecs/) - 亚马逊网络服务以网络服务的形式向企业提供信息技术基础设施服务。
  - [Docker Swarm](https://docs.docker.com/engine/swarm/) -  Swarm：一个Docker本地集群系统。
  - [Microsoft Azure Service Fabric](https://docs.microsoft.com/en-us/azure/service-fabric/) - Service Fabric是一个分布式系统平台，用于大规模打包，部署和管理无状态和有状态的分布式应用程序和容器。   
    
  非CNCF成员产品/项目
  - [Mesos](https://mesos.apache.org/) - Apache Mesos的镜像
  - [Nomad](https://www.nomadproject.io/) - Nomad是一款灵活的企业级集群调度程序，旨在轻松集成到现有工作流程中。  
    
- 协调和服务发现

  CNCF培育项目
  - [CoreDNS](https://coredns.io/) - CoreDNS是一个链接插件的DNS服务器。
    
  CNCF成员产品/项目
  - [ContainerPilot](https://www.joyent.com/containerpilot) - 自动发现和配置在容器中运行的应用程序的服务.
  - [etcD](https://coreos.com/etcd/) - 分布式可靠的键值存储用于分布式系统的最关键数据.
  - [VMware Haret](https://github.com/vmware/haret) - 一个高度一致的分布式协调系统，使用成熟的协议构建并在Rust中实现。
      
  非CNCF成员产品/项目
  - [Apache Zookeeper](https://zookeeper.apache.org/) - Apache ZooKeeper致力于开发和维护一个开源服务器，从而实现高度可靠的分布式协调。
  - [Consul](https://www.consul.io/) - Consul是一个分布式，高可用性和数据中心感知解决方案，可在动态分布式基础架构上连接和配置应用程序。
  - [Eureka](https://github.com/Netflix/eureka) - 适用于弹性中间层负载平衡和故障转移的AWS服务注册表。
  - [SkyDNS](https://github.com/skynetservices/skydns) - etcd的DNS服务发现.
  - [SmartStack](https://medium.com/airbnb-engineering/smartstack-service-discovery-in-the-cloud-4b8a080de619) - 一个透明的服务发现框架，用于连接SOA.

- 服务管理

  - [Envoy](https://envoyproxy.github.io/) - C ++前台/服务代理
  - [gRPC](https://grpc.io/) - 基于C的gRPC（C ++，Python，Ruby，Objective-C，PHP，C＃）
  - [Linkerd](https://linkerd.io/) - 适用于任何平台的生产级功能丰富的服务网格
  - [3Scale](https://www.3scale.net/) - 3scale api网关重新加载
  - [Ambassador](https://www.getambassador.io/) - 基于Envoy Proxy构建的微服务的开源Kubernetes本地API网关
  - [Avi Networks](https://avinetworks.com/) - Avi Networks是一家硅谷创业公司，在建立虚拟化，网络和软件解决方案方面拥有良好的记录。
  - [Conduit](https://conduit.io/) - Kubernetes的超轻型服务网格.
  - [F5](https://f5.com/) -  F5 Networks提供的应用交付网络技术可优化基于网络的应用的交付。
  - [Heptio Contour](https://github.com/heptio/contour) - Contour是Lyft Envoy代理的Kubernetes入口控制器。
  - [Kong](https://www.konghq.com/) - 🐒 微服务API网关
  - [NGINX](https://www.nginx.com/) - 应用程序交付的现代网络
  - [Open Service Broker API](https://www.openservicebrokerapi.org/) - 开放Service Broker API规范
  - [Turbine Labs](https://www.turbinelabs.io/) - 涡轮实验室
  - [Apache Thrift](https://thrift.apache.org/) - Apache Thrift的镜像
  - [Avro](https://avro.apache.org/) - Apache Avro
  - [Backplane](https://www.backplane.io/) - 一种服务，用于统一在任何云或数据中心内运行的以任何语言编写的Web服务器的发现，路由和负载平衡。
  - [HAProxy](https://www.haproxy.org/) - 可靠的高性能TCP / HTTP负载平衡器。   
  - [Hystrix](https://github.com/Netflix/Hystrix) - Hystrix是一个延迟和容错库，旨在隔离远程系统，服务和第三方库的访问点，阻止级联故障并在复杂的分布式系统中实现恢复能力，从而避免故障无法避免。
  - [Istio](https://istio.io/) -  一个开放平台，用于连接，管理和保护微服务。
  - [Netflix Zuul](https://github.com/Netflix/zuul) - 一个开放平台，用于连接，管理和保护微服务。
  - [Open Policy Agent (OPA)](https://www.openpolicyagent.org/) - 一个开放平台，用于连接，管理和保护微服务。
  - [Ribbon](https://github.com/Netflix/ribbon) - 功能区是一个内置软件负载平衡器的进程间通信（远程过程调用）库。 
  - [Traefik](https://traefik.io/) - Træfik，一个现代化的反向代理
  - [Vamp](https://vamp.io/) - Vamp - 金丝雀发布和微型服务系统自动缩放。

## 应用程序定义和开发

- 数据库和数据仓库
  
  CNCF培育项目
  - [Vitess](https://vitess.io/) - Vitess是一个用于MySQL水平缩放的数据库集群系统。
  
  CNCF成员产品/项目
  - [Cloudhbase](https://www.couchbase.com/) - 适用于iOS（和Mac！）应用程序的轻量级嵌入式可同步NoSQL数据库引擎。
  - [IBM DB2](https://www.ibm.com/analytics/us/en/db2/) - IBM是一家IT技术和咨询公司，提供计算机硬件，软件，基础设施和托管服务。
  - [Iguazio](https://www.iguazio.com/) - iguazio的Continuous Analytics Data Platform重新设计了数据堆栈，以加速大数据，物联网和云本地应用程序的性能。
  - [Infinispan](http://infinispan.org/) - Infinispan是一个开源数据网格平台和高度可扩展的NoSQL云数据存储。
  - [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server) - Microsoft是一家开发，制造，许可，支持和销售一系列软件产品和服务的软件公司。
  - [MySQL](https://www.oracle.com/mysql/index.html) - MySQL Server是全球最受欢迎的开源数据库，MySQL Cluster是一个实时的开源事务数据库。
  - [Oracle](https://developer.oracle.com/) - Oracle是一家计算机技术公司，开发和销售计算机硬件系统和企业软件产品。
  - [RethinkDB](https://www.rethinkdb.com/) - 实时网络的开源数据库。
  - [SQL Data Warehouse](https://azure.microsoft.com/en-us/services/sql-data-warehouse/) - Microsoft是一家开发，制造，许可，支持和销售一系列软件产品和服务的软件公司。
  - [YugaByte DB](https://www.yugabyte.com/product/yugabytedb/) - YugaByteDB是一个用于构建分布式云服务的事务性高性能数据库。 它目前支持Redis API（作为一个真正的数据库）和Cassandra API，SQL很快就会发布。
  
  非CNCF成员产品/项目
  - [ArangoDB](https://www.arangodb.com/) - 🥑 ArangoDB是一个原生的多模型数据库，具有灵活的文档，图表和键值数据模型。 使用方便的SQL查询语言或JavaScript扩展构建高性能应用程序。
  - [BigchainDB](https://www.bigchaindb.com/) - 满足BigchainDB。 区块链数据库。
  - [CarbonData](https://carbondata.apache.org/) - Apache CarbonData的镜像
  - [Cassandra](https://cassandra.apache.org/) - Apache Cassandra的镜像
  - [CockroachDB](https://www.cockroachlabs.com/) - CockroachDB - 开源的云本地SQL数据库。
  - [Crate.io](https://crate.io/) - CrateDB是一个分布式SQL数据库，可以实时存储和分析海量机器数据。
  - [Druid](http://druid.io/) - 面向列的分布式数据存储非常适合作为交互式应用程序
  - [Hadoop](https://hadoop.apache.org/) - Apache Hadoop的镜像
  - [MariaDB](https://mariadb.org/) - MariaDB服务器是社区开发的MySQL服务器分支。 MariaDB由原始MySQL团队的核心成员开始，积极与外部开发人员合作，为业内提供功能最强大，最稳定，最明智的开放式SQL服务器。
  - [MemSQL](https://www.memsql.com/) - 可以随处运行的实时数据仓库
  - [MongoDB](https://www.mongodb.com/) -MongoDB是一个文档数据库，具有您想要的查询和索引所需的可扩展性和灵活性。
  - [NomsDB](https://github.com/attic-labs/noms) - 版本化的，可分叉的，可同步的数据库。
  - [OrientDB](https://orientdb.com/why-orientdb/) -OrientDB是支持图形，文档，反应性，全文，地理空间和键值模型的最通用的数据库管理系统，在一个多模型产品中。 OrientDB可以运行分布式（Multi-Master），支持SQL，ACID事务，全文索引和反应查询。 OrientDB Community Edition使用自由Apache 2许可证开源。
  - [Pachyderm](https://www.pachyderm.io/) - 规模可重复的数据科学！
  - [Pilosa](https://www.pilosa.com/) - Pilosa是一个开源的分布式位图索引，可显着加速跨多个海量数据集的查询。
  - [PostgreSQL](https://www.postgresql.org/) - PostgreSQL是一个功能强大的开源对象关系数据库系统。
  - [Presto](https://prestodb.io/) - 大数据的分布式SQL查询引擎。
  - [Qubole](https://www.qubole.com/) - Qubole为基于亚马逊，微软，谷歌和Oracle云计算的大数据分析提供自助服务平台。
  - [Redis](https://redis.io/) - Redis是内存中的数据库，它保留在磁盘上。 数据模型是键值，但支持许多不同类型的值：字符串，列表，集合，排序集合，哈希，HyperLogLog，位图。
  - [Scylla](https://www.scylladb.com/) - NoSQL数据存储使用seastar框架，与Apache Cassandra兼容。
  - [Snowflake](https://www.snowflake.net/) - Snowflake是为云构建的唯一数据仓库。
  - [Software AG](https://www.softwareag.com/us/default.html) - Software AG在全球范围内提供业务流程管理，数据管理和咨询服务。
  - [Starburst](https://www.starburstdata.com/) - Starburst是提供SQL-on-Anything分析平台的企业Presto公司。
  - [TiDB](https://pingcap.com/index) - TiDB是一个与MySQL协议兼容的分布式HTAP数据库。
  - [Vertica](https://www.vertica.com/) - Vertica Systems开发了用于存储数据库的数据管理解决方案，并允许客户进行实时和即席查询。      

- 流

  Incubating CNCF Projects
  - [NATS](https://nats.io/) - High-Performance server for NATS, the cloud native messaging system.

  CNCF Member Products/Projects
  - [Amazon Kinesis](https://aws.amazon.com/kinesis/) - Amazon Web Services provides information technology infrastructure services to businesses in the form of web services.
  - [CloudEvents](https://openevents.io/) - CloudEvents Specification
  - [Google Cloud Dataflow](https://cloud.google.com/dataflow/) - Google is a multinational corporation that is specialized in internet-related services and products.
  - [Heron](https://twitter.github.io/heron/) - Heron is a realtime, distributed, fault-tolerant stream processing engine from Twitter
  
  Non-CNCF Member Products/Projects  
  - [Apache Apex](https://apex.apache.org/) - Mirror of Apache Apex core
  - [Apache NiFi](https://nifi.apache.org/) - Mirror of Apache NiFi
  - [Apache RocketMQ](https://rocketmq.apache.org/) - Mirror of Apache RocketMQ
  - [Apache Spark](https://spark.apache.org/) - Mirror of Apache Spark
  - [Apache Storm](https://storm.apache.org/) - Mirror of Apache Storm
  - [Flink](https://flink.apache.org/) - Mirror of Apache Flink	  
  - [Kafka](https://kafka.apache.org/) - Mirror of Apache Kafka
  - [Pulsar](https://pulsar.apache.org/) - Pulsar - distributed pub-sub messaging system
  - [RabbitMQ](https://www.rabbitmq.com/) - RabbitMQ is the most widely deployed open source message broker.
  - [StreamSets](https://streamsets.com/) - StreamSets DataCollector - Continuous big data ingest infrastructure. 	   
                  
- 源代码管理

  - [GitHub](https://github.com/) - GitHub is a web-based Git repository hosting service offering distributed revision control and source code management functionality of Git.
  - [GitLab](https://gitlab.com/) - GitLab CE | Please open new issues in our issue tracker on GitLab.com
  - [Visual Studio Team Services](https://www.visualstudio.com/team-services/) - Microsoft is a software corporation that develops, manufactures, licenses, supports, and sells a range of software products and services.
  - [Bitbucket](https://bitbucket.org/) - Atlassian provides collaboration software for teams with products including JIRA, Confluence, HipChat, Bitbucket, and Stash.
	                  
- 应用程序定义
  - [Bitnami](https://bitnami.com/) - Loved by Devs, Trusted by Ops. Easy to use cloud images, containers, and VMs that work on any platform
  - [Docker Compose](https://docs.docker.com/compose/) - Define and run multi-container applications with Docker
  - [Habitat](https://www.habitat.sh/) - Modern applications with built-in automation
  - [OpenAPI](https://www.openapis.org/) - The OpenAPI Specification Repository
  - [Telepresence](https://www.telepresence.io/) - Local development against a remote Kubernetes or OpenShift cluster
  - [Apache Brooklyn](https://brooklyn.apache.org/) - Apache Brooklyn
  - [KubeVirt](https://www.kubevirt.io/) - A virtualization API and runtime add-on for Kubernetes in order to define and manage virtual machines.
  - [Packer](https://www.packer.io/) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
  
- CI & CD

  > 持续集成和持续交付是软件开发的两种方法，旨在提高代码质量并实现代码的快速交付和部署。
  
  CNCF Member Products/Projects
  - [Argo](https://applatix.com/open-source/argo/) - Get stuff done with container-native workflows for Kubernetes.
  - [Cloud 66 Skycap](https://www.cloud66.com/containers/skycap) - Ops tools for Devs. Build, deliver, deploy and manage any applications on any cloud or server.
  - [Cloudbees](https://www.cloudbees.com/) - CloudBees offers CloudBees Jenkins Enterprise, an enterprise-grade continuous delivery platform powered by Jenkins.
  - [Codefresh](https://codefresh.io/) - Codefresh is a continuous delivery and collaboration platform for containers and microservices.
  - [Codeship](https://codeship.com/) - CloudBees offers CloudBees Jenkins Enterprise, an enterprise-grade continuous delivery platform powered by Jenkins.
  - [Concourse](https://concourse.ci/) - BOSH release and development workspace for Concourse
  - [ContainerOps](https://containerops.org/) - DevOps Orchestration Platform 
  - [Habitus](https://www.habitus.io/) - A Build Flow Tool for Docker
  - [Runner](https://docs.gitlab.com/runner/) - GitLab Runner is the open source project that is used to run your jobs and send the results back to GitLab. 
  - [Weave Flux](https://www.weave.works/oss/flux/) - A tool for deploying container images to Kubernetes services
  - [Wercker](https://www.wercker.com/) - The Wercker CLI can be used to execute pipelines locally for both local development and easy introspection.
  
  Non-CNCF Member Products/Projects
  - [Appveyor](https://www.appveyor.com/) - Appveyor Systems Inc. aim is to give powerful continuous integration and deployment tools to every .NET developer.  
  - [Bamboo](https://www.atlassian.com/software/bamboo/) - Atlassian provides collaboration software for teams with products including JIRA, Confluence, HipChat, Bitbucket, and Stash.
  - [BuddyBuild](https://www.buddybuild.com/) - Buddybuild is a Vancouver-based app tools company focused on continuous integration and debugging tools.
  - [Buildkite](https://buildkite.com/) - The Buildkite Agent is an open-source toolkit written in Golang for securely running build jobs on any device or network
  - [CircleCI](https://circleci.com/) - CircleCI provides software teams the confidence to build, test, and deploy across numerous platforms.
  - [Distelli](https://www.distelli.com/) - True Continuous Delivery from Source Control to Servers.
  - [Drone](http://try.drone.io/) - Drone is a Continuous Delivery platform built on Docker, written in Go
  - [Jenkins](https://jenkins.io/) - Build great things at any scale
  - [Octopus Deploy](https://octopus.com/) - Octopus Deploy is a user-friendly release management
  - [OpenStack Zuul CI](https://zuul-ci.org/) - The Gatekeeper, or a project gating system
  - [Semaphore](https://semaphoreci.com/) - Hosted continuous integration and deployment service
  - [Shippable](https://www.shippable.com/) - Shippable helps companies ship code faster by giving them a powerful continuous integration platform built natively on Docker.
  - [Solano Labs](https://www.solanolabs.com/) - Continuous Integration & Deployment       
  - [Spinnaker](https://www.spinnaker.io/) - Spinnaker is an open source, multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence.
  - [Travis](https://travis-ci.com/) - The Ember web client for Travis CI
  - [XL Deploy](https://xebialabs.com/products/xl-deploy/) - XebiaLabs develops enterprise-scale Continuous Delivery and DevOps software.    
  
## 平台

- 认证Kubernetes - 分销
  - [Apprenda Kismatic Enterprise Toolkit (KET)](https://apprenda.com/kismatic/)
  - [Appscode Pharmer](https://appscode.com/products/pharmer/)
  - [Caicloud Compass](https://caicloud.io/products/compass)
  - [Canonical Distribution of Kubernetes](https://www.ubuntu.com/kubernetes)
  - [Cloud Foundry Container Runtime](https://www.cloudfoundry.org/container-runtime/)
  - [CoreOS bootkube](https://github.com/kubernetes-incubator/bootkube)
  - [DaoCloud Enterprise](https://www.daocloud.io/)
  - [Diamanti Converged Container Infrastructure](https://diamanti.com/products/)
  - [Docker EE/CE](https://www.docker.com/kubernetes)
  - [Ghostcloud EcOS](https://www.ghostcloud.cn/ecos-kubernetes/)
  - [Giant Swarm Managed Kubernetes](https://giantswarm.io/product/)
  - [Google Kube-Up](https://github.com/kubernetes/kubernetes/tree/master/cluster)
  - [Heptio Quickstart for Kubernetes](https://aws.amazon.com/quickstart/architecture/heptio-kubernetes/)
  - [IBM Cloud Private](https://www.ibm.com/cloud-computing/products/ibm-cloud-private/)
  - [inwinSTACK kube-ansible](https://github.com/inwinstack/kube-ansible)
  - [Joyent Triton for Kubernetes](https://www.joyent.com/triton/compute)
  - [kube-spawn](https://github.com/kinvolk/kube-spawn)
  - [Kublr](https://kublr.com/)
  - [Loodse Kubermatic](https://cloud.kubermatic.io/)
  - [Mesosphere Kubernetes on DC/OS](https://mesosphere.com/kubernetes/)
  - [Mirantis Cloud Platform](https://www.mirantis.com/software/kubernetes/)
  - [Netease Container Service Dedicated](https://www.163yun.com/product/container-service-dedicated)
  - [OpenShift](https://www.openshift.com/)
  - [Oracle Linux Container Services](https://blogs.oracle.com/linux/announcing-oracle-linux-container-services-for-use-with-kubernetes)
  - [Oracle Terraform Kubernetes Installer](https://github.com/oracle/terraform-kubernetes-installer)
  - [Pivotal Container Service (PKS)](https://pivotal.io/platform/pivotal-container-service)
  - [Platform9 Managed Kubernetes](https://platform9.com/managed-kubernetes/)
  - [QFusion](http://www.woqutech.com/product.html)
  - [Rancher](https://rancher.com/)
  - [Samsung Kraken](https://samsung-cnct.github.io/)
  - [StackPointCloud](https://stackpoint.io/)
  - [SUSE CaaS Platform](https://www.suse.com/products/caas-platform)
  - [Tectonic](https://coreos.com/tectonic)
  - [VMWare Pivotal Container Service (PKS)](https://www.vmware.com/radius/pivotal-container-services/)
  - [Weaveworks kubeadm](https://kubernetes.io/docs/setup/independent/create-cluster-kubeadm/)
  - [WiseCloud](http://www.wise2c.com/solution)
  - [Typhoon](https://typhoon.psdn.io/)
          
- 认证Kubernetes - 平台
  - [Alauda EE](http://www.alauda.cn/product/detail/id/144.html)
  - [Alibaba Cloud Container Service](https://www.alibabacloud.com/product/container-service?spm=a3c0i.7911826.709257.dproducta4.1010a3feFbGgBW)
  - [Azure (ACS) Engine](https://github.com/Azure/acs-engine)
  - [Azure Container Service (AKS)](https://azure.microsoft.com/en-us/services/container-service/)
  - [Baidu Cloud Container Engine](https://cloud.baidu.com/product/cce.html)
  - [BoCloud BeyondcentContainer](http://bocloud.com.cn/product_container.html)
  - [Cisco Container Platform](https://www.cisco.com/c/en/us/products/cloud-systems-management/container-platform/index.html)
  - [EasyStack Kubernetes Service (EKS)](https://easystack.cn/eks/)
  - [eKing Cloud Container Platform](http://www.haihangyun.com/landing)
  - [Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/)
  - [HarmonyCloud Container Platform](http://harmonycloud.cn/)
  - [Hasura](https://hasura.io/)
  - [Huawei Cloud Container Engine (CCE)](https://www.huaweicloud.com/en-us/product/cce.html)
  - [IBM Cloud Container Service](https://console.bluemix.net/docs/containers/cs_ov.html#cs_ov)
  - [Nirmata Managed Kubernetes](https://www.nirmata.com/)
  - [Oracle Container Engine](https://cloud.oracle.com/containers/engine/features)
  - [SAP Certified Gardener](https://cloudplatform.sap.com/index.html)
  - [Tencent Cloud Container Service (CCS)](https://cloud.tencent.com/product/ccs?lang=en)
  - [TenxCloud Container Engine (TCE)](https://tenxcloud.com/enterprise.html)
  - [ZTE TECS](https://sdnfv.zte.com.cn/en/products/126)  

- 未经认证的Kubernetes
  - [Amazon Elastic Container Service for Kubernetes (EKS)](https://aws.amazon.com/eks/)
  - [Cloud 66 Maestro](https://www.cloud66.com/containers/maestro)
  - [Containership](https://containership.io/)
  - [Gravitatonal Telekube](https://gravitational.com/telekube/)
  - [Huawei FusionStage](http://e.huawei.com/us/solutions/technical/cloud-computing)
  - [Navops](https://www.navops.io/)
  - [Supergiant](https://supergiant.io/)
  - [goPaddle](https://www.gopaddle.io/#/)
  - [Stratoscale Symphony](https://www.stratoscale.com/products/symphony/)
  
- PaaS和集装箱服务
  - [Apcera](https://www.apcera.com/) - Ericsson is a technology company that provides and operates telecommunications networks, television and video systems, and related services.
  - [Cloud Foundry Application Runtime](https://www.cloudfoundry.org/application-runtime/) - Cloud Foundry Application Runtime utilizes containers as part of its DNA, and has since before Docker popularized containers. The new CF Container Runtime gives you more granular control and management of containers with Kubernetes.
  - [Datawire](https://www.datawire.io/) - An early stage startup that's focused on making it easy for developers to build resilient microservices.
  - [Exoscale](https://www.exoscale.ch/) - Exoscale is the cloud hosting platform for SaaS companies, developers and systems administrators.
  - [Galactic Fog](http://www.galacticfog.com/) - Build Future-Proof Applications. Simplify integration. Run applications anywhere. Adapt to changes instantly.
  - [Heroku](https://www.heroku.com/) - Salesforce is a global cloud computing company that develops CRM solutions and provides business software on a subscription basis.
  - [Atomist](Atomist) - Atomist make microservice applications Easy and fun to build, through a cloud-based service.
  - [Clouber](https://www.clouber.io/) - Clouber is a provider of mCenter, an Application Modernization/Migration / Management platform across hybrid (public and private) clouds.
  - [Convox](https://convox.com/) - Launch a Private Cloud in Minutes.
  - [Empire](http://engineering.remind.com/) - A PaaS built on top of Amazon EC2 Container Service (ECS)
  - [Flynn](https://flynn.io/) - A next generation open source platform as a service (PaaS
  - [Hyper](https://www.hyper.sh/) - Hyper.sh is a secure container cloud service.
  - [JHipster](https://www.jhipster.tech/) - Open Source application generator for creating Spring Boot + Angular projects in seconds!
  - [Kontena](https://kontena.io/) - The developer friendly container and micro services platform. Works on any cloud, easy to setup, simple to use.
  - [Lightbend](https://www.lightbend.com/) - Lightbend (formerly Typesafe) is dedicated to helping developers build Reactive applications on the JVM.
  - [No Code](https://github.com/kelseyhightower/nocode) - The best way to write secure and reliable applications. Write nothing; deploy nowhere.
  - [PaaSTA](https://github.com/Yelp/paasta) - An open, distributed platform as a service
  - [Platform.sh](https://platform.sh/) - Platform.sh is an automated, continuous-deployment high-availability cloud hosting solution
  - [Portainer](https://portainer.io/) - Simple management UI for Docker
  - [Scalingo](https://scalingo.com/) - Scalingo a Docker Platform Service Transform your code as Docker container & run it on our cloud, making it instantly available & scalable.
  - [Tsuru](https://tsuru.io/) - Open source, extensible and Docker-based Platform as a Service (PaaS).

## 无服务器

- 安全
  - [PureSec](https://www.puresec.io/) - PureSec is the world's leading Serverless Security Runtime Environment
  - [Snyk](https://snyk.io/) - Snyk is a security company helping to monitor app vulnerabilities.
  
- 库函数
  - [Python Lambda](https://aws.amazon.com/lambda/) - A toolkit for developing and deploying serverless Python code in AWS Lambda.

- 工具
  - [Architect](https://arc.codes/) - 🔑 cloud function signatures for http handlers, pubsub, scheduled functions and table triggers
  - [Dashbird](https://www.dashbird.io/) - AWS Lambda monitoring & debugging platform. Serverless observability & troubleshooting. Serverless monitoring.
  - [IOpipe](https://www.iopipe.com/) - IOpipe provides a toolbox for developing, monitoring, and operating serverless applications.
  - [Microcule](https://github.com/Stackvana) - SDK and CLI for spawning streaming stateless HTTP microservices in multiple programming languages
  - [Node Lambda](https://github.com/motdotla/node-lambda) - Command line tool to locally run and deploy your node.js application to Amazon Lambda
  - [Stackery](https://www.stackery.io/) - Run serverless in production with Stackery's serverless operations console.
  - [Thundra](https://www.thundra.io/) - IT Alert and Notifications Management
  
- 框架
  - [AWS Chalice](https://github.com/aws/chalice) - Python Serverless Microframework for AWS
  - [SAM Local](https://github.com/awslabs/serverless-application-model) - AWS Serverless Application Model (AWS SAM) prescribes rules for expressing Serverless applications on AWS.
  - [Serverless](https://serverless.com/) - Serverless Framework – Build web, mobile and IoT applications with serverless architectures using AWS Lambda, Azure Functions, Google CloudFunctions & more! 
  - [Spring Cloud Function](https://cloud.spring.io/spring-cloud-function/) - Pivotal is a software company that provides digital transformation technology and services.
  - [Apex](http://apex.run/) - Build, deploy, and manage AWS Lambda functions with ease (with Go support!).
  - [Bustle Shep](https://www.bustle.com/labs) - A framework for building JavaScript Applications with AWS API Gateway and Lambda
  - [ClaudisJS](https://claudiajs.com/) - Deploy Node.js projects to AWS Lambda and API Gateway easily
  - [Dawson](https://github.com/dawson-org) - A serverless web framework for Node.js on AWS (CloudFormation, CloudFront, API Gateway, Lambda)
  - [Flogo](http://flogo.io/) - Ultralight Edge Microservices Framework
  - [Gordon](http://jorgebastida.com/) - λ Gordon is a tool to create, wire and deploy AWS Lambdas using CloudFormation
  - [GunIO Zappa](https://www.zappa.io/) - Serverless Python
  - [KappaIO](https://github.com/garnaat/kappa) - What precedes Lambda 
  - [Mitoc Group Deep](https://docs.deep.mg/) - Full-stack JavaScript Framework for Cloud-Native Web Applications (perfect for Serverless use cases)
  - [Sparta](https://gosparta.io/) - A GO FRAMEWORK FOR AWS LAMBDA 
  
- 平台

  CNCF Member Products/Projects 
  - [AWS Lambda](https://aws.amazon.com/lambda/) - Amazon Web Services provides information technology infrastructure services to businesses in the form of web services.
  - [Azure Functions](https://azure.microsoft.com/en-us/services/functions//) - Microsoft is a software corporation that develops, manufactures, licenses, supports, and sells a range of software products and services.
  - [Google Cloud Functions](https://cloud.google.com/functions/) - https://cloud.google.com/functions/
  - [IBM Cloud Functions](https://console.bluemix.net/openwhisk/) - IBM is an IT technology and consulting firm providing computer hardware, software, and infrastructure and hosting services.
  - [Twilio Functions](https://www.twilio.com/functions) - Twilio is a cloud communication company that enables users to use standard web languages to build voice, VoIP, and SMS apps via a web API.
  
  Non-CNCF Member Products/Projects
  - [Algorithmia](https://algorithmia.com/serverless-ai-layer) - Algorithmia is an open marketplace for algorithms, enabling developers to create tomorrows smart applications today.
  - [Apache OpenWhisk](https://openwhisk.apache.org/) - Apache OpenWhisk is a serverless event-based programming service and an Apache Incubator project.
  - [AppScale](https://www.appscale.com/) - AppScale is an easy-to-manage serverless platform for building and running scalable web and mobile applications on any infrastructure.
  - [Clay](https://www.clay.run/) - Rapid Prototyping for Developers
  - [Hyper Func](https://docs.hyper.sh/Feature/container/func.html) - Hyper.sh is a secure container cloud service.
  - [Iron.io](https://www.iron.io/) - Iron.io is a scalable cloud-based message queue and processing platform for building distributed cloud applications.
  - [Nano Lambda](http://nano-lambda.com/) - Explore deploying code in lambda.Run server-side code with an API call.
  - [Overclock](https://www.ovrclk.com/) - Overclock Labs develops protocols, tools, and infrastructure to make foundational elements of the internet open, decentralized, and simple
  - [OVH Functions](https://labs.ovh.com/ovh-functions) - OVH.com is an independent French company that offers web, dedicated, and cloud hosting solutions.
  - [PubNub Functions](https://www.pubnub.com/products/functions/) - The PubNub Data Stream Network enables mobile and web developers to build and scale realtime apps.
  - [Spotinst Functions](https://spotinst.com/products/spotinst-functions/) - Our SaaS optimization platform delivers significant cost reduction for AWS and GCE, while maintaining high availability and performance.
  - [StdLib](https://stdlib.com/) - StdLib Service Creation, Deployment, and Management Tools
  - [Syncano](https://syncano.io/#/) - A serverless application platform to build powerful realtime apps more efficiently.
  - [Weblab](https://weblab.io/) - Microservices at your fingertips
  - [Webtask](https://webtask.io/) - Webtasks is a simple, lightweight, and secure way of running isolated backend code that removed or reduces the need for a backend.
  - [Zeit Now](https://zeit.co/now) - Now – Realtime Global Deployments
            
- 混合平台
  - [Galactic Fog Gestalt](http://www.galacticfog.com/product/) - Build Future-Proof Applications. Simplify integration. Run applications anywhere. Adapt to changes instantly.
  - [Nuclio](https://nuclio.io/) - High-Performance Serverless event and data processing platform
  - [Binaris](https://www.binaris.com/) - A high-performance serverless platform for interactive and real-time applications.
  - [Cloudboost](https://www.cloudboost.io/) - One Complete NoSQL Database Service for your app.
  - [Fn](https://fnproject.io/) - The container native, cloud agnostic serverless platform.
  - [fx](https://minghe.me/) - fx is a tool to help you do Function as a Service with painless on your own servers
  - [LunchBadger](https://www.lunchbadger.com/) - LunchBadger is a multi-cloud platform for microservices and serverless.        
  
- Kubernetes原生平台
  - [Fission](https://fission.io/) - Fast Serverless Functions for Kubernetes
  - [Oracle Application Container Cloud](https://cloud.oracle.com/acc) - Oracle is a computer technology corporation developing and marketing computer hardware systems and enterprise software products.
  - [Riff](https://projectriff.io/) - riff is for functions
  - [Funktion](https://funktion.fabric8.io/) - a CLI tool for working with funktion
  - [Kubeless](http://kubeless.io/) - Kubernetes Native Serverless Framework
  - [OpenFAAS](https://www.openfaas.com/) - OpenFaaS - Serverless Functions Made Simple for Docker & Kubernetes
  - [OpenLambda](https://open-lambda.org/)  -  An open source serverless computing platform
  - [PubNub](https://www.pubnub.com/docs/blocks-catalog) - The PubNub Data Stream Network enables mobile and web developers to build and scale realtime apps.
  
## 可观测性和分析

- 监控

  CNCF Member Products/Projects 
  - [Prometheus](https://prometheus.io/) - The Prometheus monitoring system and time series database.
  - [Amazon CloudWatch](https://aws.amazon.com/cloudwatch/) - Amazon Web Services provides information technology infrastructure services to businesses in the form of web services.
  - [Datadog](https://www.datadoghq.com/) - Datadog offers a cloud-scale monitoring service.
  - [Dynatrace](https://www.dynatrace.com/) - Dynatrace transform how Web and non-Web business-critical applications are monitored, managed, and optimized throughout their lifecycle.
  - [Google Stackdriver](https://cloud.google.com/stackdriver/) - Google is a multinational corporation that is specialized in internet-related services and products.  
  - [Grafana](https://grafana.com/) - The tool for beautiful monitoring and metric analytics & dashboards for Graphite, InfluxDB & Prometheus & More
  - [InfluxDB](https://www.influxdata.com/) - Scalable datastore for metrics, events, and real-time analytics
  - [Instana](https://www.instana.com/) - Instana is an APM solution that automatically monitors dynamic modern apps.
  - [Lighstep](https://lightstep.com/) - LightStep's mission is to cut through the scale and complexity of today's software to help organizations stay in control of their systems.
  - [Log Analytics](https://azure.microsoft.com/en-us/services/log-analytics/) - Microsoft is a software corporation that develops, manufactures, licenses, supports, and sells a range of software products and services.
  - [Netsil](https://netsil.com/) - Observability and Monitoring for Modern Cloud Applications
  - [SignalFX](https://signalfx.com/) - Advanced monitoring platform for modern applications
  - [Snap](https://snap-telemetry.io/) - A powerful open telemetry framework.Easily collect, process, and publish telemetry data at scale.
  - [SysDig](https://sysdig.com/) - Linux system exploration and troubleshooting tool with first class support for containers
  - [Weave Cloud](https://www.weave.works/product/cloud/) - Weaveworks provides a simple and consistent way to connect and manage containers and microservices.
  
  Non-CNCF Member Products/Projects
  - [AppDynamics](https://www.appdynamics.com/) - AppDynamics develops application performance management (APM) solutions that deliver problem resolution for highly distributed applications.
  - [AppNeta](https://www.appneta.com/) - AppNeta is the only app performance monitoring company with solutions for apps you develop, SaaS apps you use & networks that deliver them.
  - [Axibase](https://axibase.com/) - Purpose-built solution for analyzing and reporting on massive volumes of time-series data collected at high frequency.
  - [Catchpoint Systems](https://www.catchpoint.com/) - Catchpoint is a leading digital experience intelligence company.
  - [Centreon](https://www.centreon.com/en/) - Centreon is a network, system, applicative supervision and monitoring tool.
  - [Cobe](https://cobe.io/) - Cobe delivers an aggregated view of every element related to your business.
  - [CoScale](https://www.coscale.com/) - Full stack performance monitoring. Built for container and microservices applications. Powered by anomaly detection.
  - [Graphite](https://graphiteapp.org/) - A highly scalable real-time graphing system
  - [Honeybadger](https://www.honeybadger.io/) - Exception, uptime, and performance monit.
  - [Icinga](https://www.icinga.com/) - Monitoring as code
  - [IronDB](https://www.circonus.com/irondb/) - Realtime Monitoring and Analytics
  - [Librato](https://www.librato.com/) - Real time operations analytics for metrics from any source
  - [Meros](https://meros.io/) - Meros is creating enterprise monitoring and management tools for Docker
  - [Nagios](https://www.nagios.com/) - The Industry Standard In IT Infrastructure Monitoring.
  - [New Relic](https://newrelic.com/) - New Relic is a leading digital intelligence company, delivering full-stack visibility and analytics to enterprises around the world.
  - [NodeSource](https://nodesource.com/) - Building products focused on Node.js security and performance for the Enterprise.
  - [OpBeat](https://opbeat.com/) - Opbeat is joining forces with Elastic.
  - [OpenTSDB](http://opentsdb.net/) - A scalable, distributed Time Series Database.
  - [OpsClarity](https://www.opsclarity.com/) - Intelligent Monitoring for Modern Applications and Data Infrastructure
  - [Outlyer](https://www.outlyer.com/) - Infrastructure monitoring platform made for DevOps and microservices.
  - [Rocana](https://www.rocana.com/) - Rocana is a San Francisco, CA-based provider of root cause analysis software company
  - [Sensu](https://sensuapp.org/) - Monitoring for today's infrastructure.
  - [Sentry](https://sentry.io/) - Sentry is a cross-platform crash reporting and aggregation platform.
  - [Server Density](https://www.serverdensity.com/) - Monitoring agent for Server Density (Linux, FreeBSD and OS X)
  - [StackRox](https://www.stackrox.com/) - StackRox delivers the industry's only adaptive threat protection for containers.
  - [StackState](https://www.stackstate.com/) - The market-leading Algorithmic IT Operations platform
  - [Tingyun](http://www.tingyun.com/tingyun_app.html) - Observability and Analysis, Monitoring
  - [Wavefront](https://www.wavefront.com/) - Wavefront is a hosted platform for ingesting, storing, visualizing and alerting on time series data.
  - [Zabbix](https://www.zabbix.com/) - The Ultimate Enterprise - class Monitoring Platform  
    
- 日志记录

  - [Fluentd](https://www.fluentd.org/) - Fluentd: Unified Logging Layer (project under CNCF)
  - [Humio](https://www.humio.com/) - Log everything, answer anything
  - [Splunk](https://www.splunk.com/) - Splunk provides operational intelligence software that monitors, reports, and analyzes real-time machine data.
  - [Elastic](https://www.elastic.co/) - Open Source, Distributed, RESTful Search Engine.
  - [Graylog](https://www.graylog.org/) - Free and open source log management
  - [Loggly](https://www.loggly.com/) - Loggly parses your log files, shows you the code in GitHub which caused the log errors. 10,000+ customers, including 1/3 of the Fortune 500.
  - [Logz](https://logz.io/) - Logz.io is an enterprise-grade ELK as a service with alerts, unlimited scalability, and predictive fault detection.
  - [Loom Systems](https://www.loomsystems.com/) - Predict & Prevent Problems in the Digital Business
  - [Sematext](https://sematext.com/) -  Sematext is a Search and Big Data analytics products and services company.
  - [Sumo Logic](https://www.sumologic.com/) - Sumo Logic, a log management and analytics service, transforms big data into sources of operations, security and compliance intelligence.

- 追踪

  - [Jaeger](http://jaegertracing.io/) - CNCF Jaeger，分布式追踪系统。
  - [OpenTracing](http://opentracing.io/) - Go的OpenTracing API
  - [Spring Cloud Sleuth](https://cloud.spring.io/spring-cloud-sleuth/) - spring cloud分布式追踪
  - [Appdash](https://github.com/sourcegraph/appdash) - Go的应用程序追踪系统基于Google的Dapper。
  - [SkyWalking](http://skywalking.io/) - 分布式跟踪系统和APM（应用程序性能监视）
  - [Zipkin](https://zipkin.io/) - Zipkin是一个分布式追踪系统
 

## 贡献

欢迎提交合并请求, 请参照 [contribution guidelines](Contributing.md).

**[⬆ 回到顶部](#components)**

## 开源许可

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).