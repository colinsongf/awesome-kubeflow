# awesome-kubeflow
A curated list of awesome kubeflow tutorials, projects and communities


## Table of Contents

- [Tutorials](#tutorials)
- [Deployment-platform](#deployment-platform)
- [simple-kubeflow-demo](#simple-kubeflow-demo)
- [Links](#links)
- [deployment-demo](#deployment-demo)
- [k8s-demo](#k8s-demo)

## Tutorials
- Introduction to distributed TensorFlow on Kubernetes https://banzaicloud.com/blog/tensorflow-on-k8s/
- Let’s Flow within Kubeflow https://www.intel.ai/lets-flow-within-kubeflow/
- Getting started with Kubeflow Pipelines https://cloud.google.com/blog/products/ai-machine-learning/getting-started-kubeflow-pipelines
- 新Kubeflow，新征程 （一）：简化部署体验 https://yq.aliyun.com/articles/686672
- Scaling Object Detection with Kubernetes* and Kubeflow https://software.intel.com/en-us/node/783861?wapkw=kubeflow
- How to create and deploy a Kubeflow Machine Learning Pipeline (Part 1) https://towardsdatascience.com/how-to-create-and-deploy-a-kubeflow-machine-learning-pipeline-part-1-efea7a4b650f
- How to create and deploy a Kubeflow Machine Learning Pipeline (Part 1-complete code) https://github.com/GoogleCloudPlatform/training-data-analyst/tree/master/courses/machine_learning/deepdive/06_structured/pipelines
- How to deploy Jupyter notebooks as components of a Kubeflow ML pipeline (Part 2) https://towardsdatascience.com/how-to-deploy-jupyter-notebooks-as-components-of-a-kubeflow-ml-pipeline-part-2-b1df77f4e5b3
- Kubeflow on Amazon EKS https://aws.amazon.com/cn/blogs/opensource/kubeflow-amazon-eks/
- Kubeflow 使用指南 https://yq.aliyun.com/articles/680267
- 基于 Kubeflow 的机器学习调度平台落地实战 http://www.uml.org.cn/ai/201901303.asp
- Yarn已过时！Kubeflow实现机器学习调度平台才是未来 https://www.jiqizhixin.com/articles/2019-01-31-14
- MXNet结合kubeflow进行分布式训练 https://www.opsdev.cn/post/mxnet.html
- Kubeflow使用Kubernetes进行机器学习 https://www.opsdev.cn/post/kubeflow-intro.html
- Kubeflow – Jupyter Notebook on Kubernetes https://www.lotharschulz.info/2018/05/06/kubeflow-jupyter-notebook-on-kubernetes/
- Kubeflow使用Kubernetes进行机器学习 https://xigang.github.io/2018/12/08/kubeflow-intro/
- MXNet结合kubeflow进行分布式训练 https://xigang.github.io/2019/01/17/mxnet/
- Tensorflow结合kubeflow进行分布式训练 https://xigang.github.io/2019/01/30/tensorflow/
- Kubeflow: Cloud-native machine learning with Kubernetes-openshift https://opensource.com/article/18/6/kubeflow
- Using GitOps to Deploy Kubeflow with Argo CD https://www.colabug.com/5046530.html
- How to create and deploy a Kubeflow Machine Learning Pipeline (Part 1) https://www.colabug.com/5329927.html
- Getting started with Kubeflow Pipelines https://www.colabug.com/5279442.html
- Kubeflow使用Kubernetes进行机器学习 https://www.colabug.com/5385292.html
- Kubeflow 快速入门 https://my.oschina.net/u/2306127/blog/1807788
- 无人驾驶场景下 Kubeflow 的应用与开发 https://mp.weixin.qq.com/s?src=11&timestamp=1549604252&ver=1415&signature=ofKVVbBc4pwYxfAEopAixkXyeh7GnALCWBTmykgb6vp*nS3vSVmZQ5cFcnFgqQNq-sGNpYlIq079bGmrUK10XEqSJPOp2AojiNYhhyYAL4D6BaCY5WA8yJX7Ny6KtPm8&new=1
- Distributed Tensorflow deployed to Azure AKS Kubernetes using GPU instances https://banzaicloud.com/blog/tensorflow-on-gpu-azure/
- Deep Learning Reference Stack kubeflow 0.4.1 https://clearlinux.org/documentation/clear-linux/tutorials/dlrs
- Kubeflow安裝及入門 http://tblog.pp4fun.com/2018/11/Kubeflow安裝及入門.html
- KubeFlow安装指南 https://bbs.huaweicloud.com/blogs/413d1821c1a211e89fc57ca23e93a89f
- Kubeflow 使用指南 https://my.oschina.net/u/2306127/blog/1808582
- Running Kubeflow On IBM Cloud Private https://medium.com/ibm-cloud/icp-for-kubeflow-30416b928e8e
- Using Kubeflow to manage TensorFlow applications (Part 1) https://www.inwinstack.com/en/2018/12/04/kubeflow-tensorflow-part1/
- Using Kubeflow to manage TensorFlow applications (Part 2) https://www.inwinstack.com/en/2018/12/04/kubeflow-tensorflow-part2/
- Experiment with Kubeflow https://mc.ai/experiment-with-kubeflow/
- 我试过触摸kubeflow https://techbird.site/ohtaman-items-05e4e117a81c7393d875/
- When Deep Learning with GPUs, use a Cluster Manager https://www.logicalclocks.com/deep-learners-use-a-cluster-manager-for-your-gpus/
- Distributed Tensorflow deployed to Azure AKS Kubernetes using GPU instances https://banzaicloud.com/blog/tensorflow-on-gpu-azure/
- ChainerMN on Kubernetes with GPUs https://chainer.org/general/2018/05/10/chainermn-on-kubernetes.html
- Use GPUs for compute-intensive workloads on Azure Kubernetes Service (AKS) https://docs.microsoft.com/en-us/azure/aks/gpu-cluster
- Setup guide for the ultimate Deep Learning workstation, powered by NVIDIA https://nvaitc.github.io/workstation-setup-guide/kubeflow-setup.html
- K8s Custom Resource and Operator For TensorFlow jobs https://www.diycode.cc/projects/tensorflow/k8s
- Kubeflow Mnist范例介绍 http://tblog.pp4fun.com/2019/2/Kubeflow%20Mnist%E7%AF%84%E4%BE%8B%E4%BB%8B%E7%B4%B9.html
- Kubeflow安裝及入門 http://tblog.pp4fun.com/2018/11/Kubeflow%E5%AE%89%E8%A3%9D%E5%8F%8A%E5%85%A5%E9%96%80.html
- Kubeflow Pipeline 研究心得 http://tblog.pp4fun.com/2019/2/Kubeflow%20Pipeline%20%E7%A0%94%E7%A9%B6%E5%BF%83%E5%BE%97.html
- Seldon Core on KubeFlow http://tblog.pp4fun.com/2019/1/Seldon%20Core%20on%20KubeFlow.html
- tensorflow-on-kubeflow https://blog.spider.im/2018/06/29/tensorflow-on-kubeflow/
## trouble shooting
- Kubernetes hack/local-up-cluster.sh 无法启动 DNS 的问题溯源 http://gaocegege.com/Blog/kubernetes/kubernetes-localup
## ksonnet
- ksonnet 一个简化编写以及部署kubernetes的工具 https://www.cnblogs.com/rongfengliang/p/9977414.html
- ksonnet 使用教程  https://my.oschina.net/u/2306127/blog/1808581
- Introducing kuku: kubernetes template tool https://plugaru.org/2018/09/27/kuku/
- A Jsonnet builder for Container Builder https://medium.com/@DazWilkin/a-jsonnet-builder-for-container-builder-71a0f6c18db7
- Draft vs Gitkube vs Helm vs Ksonnet vs Metaparticle vs Skaffold https://blog.hasura.io/draft-vs-gitkube-vs-helm-vs-ksonnet-vs-metaparticle-vs-skaffold-f5aa9561f948/
- ksonnet modules https://blil.es/ksonnet-modules-7041b2b398b6
- Ksonnet example applications https://github.com/jessesuen/ksonnet-examples
- Super quick view at ksonnet https://medium.com/@enxebre/super-quick-view-at-ksonnet-20defac2962
- Ksonnet Tutorial https://medium.com/@soulplant/ksonnet-tutorial-23350a04a482
## Polyaxon
- Polyaxon: 一个帮助您构建，管理和监控深度学习模型的平台 https://javascript.ctolib.com/article/wiki/48067
- Polyaxon, Argo and Seldon for model training, package and deployment in Kubernetes https://danielfrg.com/blog/2018/10/model-management-polyaxon-argo-seldon/ https://github.com/danielfrg/polyaxon-argo-seldon-example
## Deployment-platform
- Fabric for Deep Learning (FfDL) https://github.com/IBM/FfDL
- tensorflow serving https://www.tensorflow.org/serving/
- GraphPipe https://oracle.github.io/graphpipe/#/
- Seldon https://www.seldon.io
- nauta https://github.com/IntelAI/nauta
- MapR: Unified Management, No Overhead https://mapr.com/
- Meet Horovod: Uber’s Open Source Distributed Deep Learning Framework for TensorFlow https://eng.uber.com/horovod/
- Jenkins 与 Docker 的持续集成实践一 https://www.opsdev.cn/post/jenkins-docker-01.html
- Installing Kubeflow with MapR https://mapr.com/blog/installing-kubeflow-with-mapr/
## Simple-kubeflow-demo
- iris-simple-demo train using tensorflow and serve using seldon https://github.com/alvinhenrick/kube-demo-simple
- kube-demo-dist Distributed Training and Serving Tensorflow Model at Scale with Kubeflow , Kubernetes and Seldon. https://github.com/alvinhenrick/kube-demo-dist
- A Tutorial for Serving Tensorflow Models using Kubernetes https://github.com/google-aai/tf-serving-k8s-tutorial
- https://github.com/dwhitena/oreilly-ai-k8s-tutorial#1-connect-to-the-tutorial-machine
## Links
- deploying deep learning-based models in production. https://github.com/ahkarami/Deep-Learning-in-Production
- Kubeflow in 2018: A year in perspective https://medium.com/kubeflow/kubeflow-in-2018-a-year-in-perspective-49c273b490f4
- Distributed training framework for TensorFlow, Keras, PyTorch, and MXNet https://github.com/uber/horovod
- NVIDIA RAPIDS Accelerate Kubeflow Pipeline with GPUs on Kubernetes https://medium.com/kubeflow/nvidia-rapids-accelerate-kubeflow-pipeline-with-gpus-on-kubernetes-b17fc1ce7ec
- Kubeflow 0.4: Release Update & What’s Coming https://medium.com/kubeflow/kubeflow-0-4-release-update-whats-coming-c55820e28915
- Kubeflow 0.4 Release: Enhancements for Machine Learning productivity https://medium.com/kubeflow/kubeflow-0-4-release-enhancements-for-machine-learning-productivity-d77c54df07a9
- 开发 | 2018 年最富含金量的 6 款开源机器学习项目 https://mp.weixin.qq.com/s?__biz=MzI5NTIxNTg0OA==&mid=2247493799&idx=2&sn=4e4e7132d3cb6617660a46c1eaed007c&scene=0#wechat_redirect
- 业界 | 谷歌发布机器学习工具库Kubeflow：可提供最佳OSS解决方案 https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650734516&idx=3&sn=33b6048ed12d08e9fd741f8811b84227
- 实例+代码，你还怕不会构建深度学习的代码搜索库吗 https://ai.yanxishe.com/page/TextTranslation/707
- Introduction to Kubeflow https://www.oliverwyman.com/content/dam/oliver-wyman/v2/events/2018/March/Google_London_Event/Public%20Introduction%20to%20Kubeflow.pdf
- https://radanalytics.io
- https://conjure-up.io
- Some utilities to help with kubeflow development https://github.com/jlewi/kubeflow-dev
- How To Create Data Products That Are Magical Using Sequence-to-Sequence Models https://towardsdatascience.com/how-to-create-data-products-that-are-magical-using-sequence-to-sequence-models-703f86a231f8
- http://issuehub.io/?label[]=community%2Fquestion
## deployment-demo
### tensorflow serving
- How to deploy Machine Learning models with TensorFlow. Part 1 — make your model ready for serving. https://towardsdatascience.com/how-to-deploy-machine-learning-models-with-tensorflow-part-1-make-your-model-ready-for-serving-776a14ec3198
- How to deploy Machine Learning models with TensorFlow. Part 2— containerize it! https://towardsdatascience.com/how-to-deploy-machine-learning-models-with-tensorflow-part-2-containerize-it-db0ad7ca35a7
- How to deploy Machine Learning models with TensorFlow. Part 3— into the Cloud! https://towardsdatascience.com/how-to-deploy-machine-learning-models-with-tensorflow-part-3-into-the-cloud-7115ff774bb6 
- Creating REST API for TensorFlow models https://becominghuman.ai/creating-restful-api-to-tensorflow-models-c5c57b692c10
- Istio Integration (for TF Serving) https://www.kubeflow.org/docs/components/istio/
- Gather how to deploy tensorflow models using nginx, hadoop, kafka, flask, gunicorn, socketio, docker swarm, luigi spotify, airflow, celery and so much more! https://github.com/huseinzol05/Gather-Tensorflow-Serving
- 使用Kubernetes和TensorFlow Serving将神经网络镜像分类进行弹性扩容 https://segmentfault.com/a/1190000004829764?utm_source=tag-newest
- Deploying Keras models using TensorFlow Serving and Flask https://towardsdatascience.com/deploying-keras-models-using-tensorflow-serving-and-flask-508ba00f1037
- TensorFlow 模型如何对外提供服务 saved_model_cli https://blog.csdn.net/zjerryj/article/details/80308713
### pytorch serving
- Train PyTorch models with Azure Machine Learning service https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-train-pytorch
- Deploy your PyTorch model to Production https://medium.com/datadriveninvestor/deploy-your-pytorch-model-to-production-f69460192217
### seldon
- Seldon and TensorFlow Serving https://github.com/SeldonIO/seldon-core/blob/master/examples/models/tfserving-mnist/tfserving-mnist.ipynb
- Manage ML Deployments Like A Boss: Deploy Your First AB Test With Sklearn, Kubernetes and Seldon-core using Only Your Web Browser & Google Cloud  https://medium.com/analytics-vidhya/manage-ml-deployments-like-a-boss-deploy-your-first-ab-test-with-sklearn-kubernetes-and-b10ae0819dfe
- Introducing Seldon Core — Machine Learning Deployment for Kubernetes https://medium.com/seldon-open-source-machine-learning/introducing-seldon-core-machine-learning-deployment-for-kubernetes-e10e94c19fd8
- End-to-End Kubeflow tutorial using a Pytorch model in Google Cloud Platform https://medium.com/devopslinks/end-to-end-kubeflow-tutorial-using-a-pytorch-model-in-google-cloud-platform-20f310e12e46
### Istio
- Running Istio on kubernetes in production. Part I. https://medium.com/avitotech/running-istio-on-kubernetes-in-production-part-i-a8bbf7fec18e

## k8s-demo
- Kubernetes单机部署手册 https://blog.csdn.net/u011641865/article/details/73845460
- 基于kubernetes的tensorflow单机训练与服务部署 https://blog.csdn.net/xingyuzhe/article/details/83863823
- Kubernetes NetworkPolicy工作原理浅析 https://www.opsdev.cn/post/kubernetes-netwrok-policy-details.html
- Kubernetes持久化存储Cephfs https://www.opsdev.cn/post/k8s-cephfs.html
- nvidia-docker2在kubernetes上实践 https://www.opsdev.cn/post/nvidia-docker2.html
- kubernetes 中 deployment 支持哪些键值 https://www.opsdev.cn/post/kubernetes-deployment-fileds.html
- Nvidia-Docker2在kubernetes上实践 https://xigang.github.io/2018/11/05/nvidia-docker2/
- Kubernetes DNS 介绍 https://xigang.github.io/2018/11/24/kube-dns/
- kubernetes持久化存储Ceph RBD https://xigang.github.io/2018/05/05/ceph-rbd/
- Kubernetes持久化存储cephfs https://xigang.github.io/2018/05/05/cephfs/
- 基于Kubernetes容器云日志采集与处理实践 https://xigang.github.io/2018/05/19/kubernetes-docker-log/
- Etcd集群备份及容灾恢复 https://xigang.github.io/2018/08/18/etcd-back/
- GPU Container on Kubernetes https://xigang.github.io/2018/09/01/gpu/ 
- Etcd入门篇-集群搭建及基本使用 https://xigang.github.io/2018/05/05/etcd-md/
- 浅谈Linux服务管理器Systemd https://xigang.github.io/2018/05/05/systemctl/
- Kubernetes集成TensorFlow服务 https://my.oschina.net/u/2306127/blog/1811348
- Getting Started with Kubernetes: Deploy a Docker Container with Kubernetes in 5 minutes https://codeburst.io/getting-started-with-kubernetes-deploy-a-docker-container-with-kubernetes-in-5-minutes-eb4be0e96370
- Getting started with HDFS on Kubernetes https://blog.hasura.io/getting-started-with-hdfs-on-kubernetes-a75325d4178c/
- Accessing an application on Kubernetes in Docker https://medium.com/@lizrice/accessing-an-application-on-kubernetes-in-docker-1054d46b64b1
## k8s-install 
- OKD: The Origin Community Distribution of Kubernetes https://github.com/openshift/origin?spm=a2c4e.11153940.blogcont680267.54.19f4541fXeBcpW https://www.okd.io
- Create a Kubernetes cron job in OKD https://opensource.com/article/19/1/create-build-and-deploy-cron-job-okd
- The Origin Community Distribution of Kubernetes that powers Red Hat OpenShift. https://www.okd.io
- AWS RHEL/CentOS 7快速安装配置OpenShift http://blog.51cto.com/7308310/2171091?source=dra
- Openshift概念 https://www.jianshu.com/p/a4712351142d
- ubuntu install k8s https://github.com/demoyuw/k8s
- kubeadm install k8s https://github.com/kian1990/k8s
- 和我一步步部署 kubernetes 集群 https://github.com/opsnull/follow-me-install-kubernetes-cluster
- rancher https://github.com/ziozzang/k8s-offline-installer/blob/master/run-rancher.sh
- 快速建立Kubernetes集群，从零开始 https://my.oschina.net/u/2306127/blog/2222927
- ubuntu下使用kubeadm安装部署kubernetes v1.10 https://blog.csdn.net/qq_37423198/article/details/79762687
- Kubernetes on Ubuntu https://kubernetes.io/docs/getting-started-guides/ubuntu/
- Local Kubernetes development with LXD https://kubernetes.io/docs/getting-started-guides/ubuntu/local/
- A Kubernetes multi-node test cluster based on kubeadm https://github.com/kubernetes-sigs/kubeadm-dind-cluster
- 必须收藏！50个最流行的免费Kubernetes工具集 http://cloud.51cto.com/art/201806/576406.htm
- A simple way to bootstrap a Kubernetes cluster. https://github.com/valentin2105/Simplekube
- Setting up a single node Kubernetes Cluster https://ninetaillabs.com/setting-up-a-single-node-kubernetes-cluster/
- Get a Shell to a Running Container https://kubernetes.io/docs/tasks/debug-application-cluster/get-shell-running-container/
## LXD 容器
- 在 Ubuntu 上体验 LXD 容器 https://www.imooc.com/article/252477
- Creating and using your first container https://linuxcontainers.org/lxd/getting-started-cli/
- 可爱的 LXD 系统容器 https://yq.aliyun.com/articles/578196
- Ubuntu 16.04系统下安装LXD容器的详细教程 https://www.osetc.com/archives/20176.html
- Tutorial Part 1: Kubernetes up and running on LXC/LXD https://itnext.io/tutorial-part-1-kubernetes-up-and-running-on-lxc-lxd-b760c79cd53f
## docker in docker 
- Trying New Features in Docker, Part 2: Setting Up a Kubernetes Cluster Using Docker in Docker https://dzone.com/articles/trying-new-features-in-docker-part-2-setting-up-a
- Setting up a Kubernetes cluster using Docker in Docker http://callistaenterprise.se/blogg/teknik/2017/12/20/kubernetes-on-docker-in-docker/
## rancher 
- Kubernetes-基于Rancher进行Kubernetes的离线安装 https://yq.aliyun.com/articles/679302






