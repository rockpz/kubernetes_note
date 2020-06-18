# 进阶指南

## 1 核心组件

### 1.1 etcd

### 1.2 kube-apiserver

### 1.3 kube-controller-manager

### 1.4 kube-scheduler

### 1.5 kube-proxy

### 1.6 docker

## 2 附加组件

### 2.1 DNS

#### 2.1.1 kube-dns

#### 2.1.2 coredns

### 2.2 ingress Controller

#### 2.2.1 traefik

#### 2.2.2 NGINX Ingress Controller

#### 2.2.3 Nginx Plus

#### 2.2.4 HAProxy Ingress

#### 2.2.5 AppsCode Voyager

#### 2.2.6 contour

#### 2.2.7 Cloudflare Warp Ingress

#### 2.2.8 F5 Big IP Controller

#### 2.2.9 Gloo

#### 2.2.10 gRPC Load balancing

#### 2.2.11 Kong

#### 2.2.12 nghttpx Ingress Controller

#### 2.2.13 Ambassador

#### 2.2.14 Skipper

### 2.3 Heapster

### 2.4 Dashboard

### 2.5 Kubernator

### 2.6 Federation

### 2.7 eventrouter

## 3 资源对象

### 3.1 Pod

#### 3.1.1 init container

#### 3.1.2 Pod Security Policy

#### 3.1.3 Pod Lifecycle

#### 3.1.4 Pod Hook

#### 3.1.5 Pod Preset

#### 3.1.6 Disruption

#### 3.1.7 Resource Quota

#### 3.1.8 liveness和readliness

### 3.2 集群配置

#### 3.2.1 Node

#### 3.2.2 Namespace

#### 3.2.3 Label

#### 3.2.4 Annotation

#### 3.2.5 Taint和Toleration

#### 3.2.6 亲和性(Affinity)和反亲和性(anti-affinity)

#### 3.2.7 Garbage Collection

### 3.3 控制器

#### 3.3.1 Deployment

#### 3.3.2 DaemonSet

#### 3.3.3 StateSet

#### 3.3.4 ReplicaSet

#### 3.3.5 Job

#### 3.3.6 CroneJob

#### 3.3.7 Horizontal Pod Autoscaling

#### 3.3.8 cron-hpa-controller

#### 3.3.9 Escalator

### 3.4 服务发现

#### 3.4.1 Service

#### 3.4.2 Ingress

### 3.5 身份与权限控制

#### 3.5.1 Service Account

#### 3.5.2 Network Policy

##### 3.5.2.1 kubernetes-network-policy-recipes

#### 3.5.3 Security Context

#### 3.5.4 RBAC

### 3.6 存储配置

#### 3.6.1 Secret

#### 3.6.2 ConfigMap

#### 3.6.3 Volume

#### 3.6.4 Persistent Volume

#### 3.6.5 Local Volume

#### 3.6.7 Storage Class

#### 3.6.8 Stork

### 3.7 API扩展

## 4 部署配置

### 4.1 单机部署

#### 4.1.1 minikube

#### 4.2.2 kubeasz

### 4.2 集群部署

#### 4.2.1 kubeasz

#### 4.2.2 Breeze

#### 4.2.3 Kubeadmin

#### 4.2.4 Kubeadm

#### 4.2.5 Kubespray

#### 4.2.6 LinuxKit

### 4.3 部署Windows节点

### 4.4 Kubernetes on Azure

## 5 插件扩展

### 5.1 CNI

### 5.2 CSI

### 5.3 CRI

### 5.4 Scheduler扩展

### 5.5 Device插件

### 5.6 keepalived-vip

### 5.7 External DNS

### 5.8 kubevirt

## 6 服务治理

### 6.1 Helm

#### 6.1.1 Helmfile

### 6.2 service mesh

#### 6.2.1  Istio

##### 6.2.1.1 Envy

##### 6.2.1.2 Fortio

##### 6.2.1.3 outlier-istio

#### 6.2.2 Linkerd

#### 6.2.3 Conduit

### 6.3 持续集成

#### 6.3.1 Jenkins

#### 6.3.2 Drone

#### 6.3.3 Apollo

### 6.4 CI/CD

### 6.5 Kompose

### 6.6 灰度发布

#### 6.6.1  Shipper

## 7 Kubernetes周边项目

### 7.1 客户端

#### 7.1.1 Kubenetic

#### 7.1.2 Cabin

### 7.2 Dashboard

#### 7.2.1 konstellate

#### 7.2.2 fist

### 7.3 多集群管理

#### 7.3.1 Gardener

#### 7.3.2 Aptomi

### 7.4 大数据与机器学习

#### 7.4.1 Spark

#### 7.4.2 Kubeflow

#### 7.4.3 mxnet-operator

#### 7.4.4 seldon-core

#### 7.4.5 FfDL

### 7.5 Serverless架构

#### 7.5.1 OpenFaaS

#### 7.5.2 FaaS-netes

#### 7.5.3 Funktion

#### 7.5.4 Fission

#### 7.5.5 Kubeless

#### 7.5.6 OpenWhisk

#### 7.5.7 Iron.io

#### 7.5.8 Nuclio

#### 7.5.9 Virtual Kubelet

### 7.6 Paas平台

#### 7.6.1 Rancher

#### 7.6.2 Openshift Origin

#### 7.6.3 Kel

#### 7.6.4 IBM Bluemix Container Service

#### 7.6.5 Hasura

#### 7.6.6 teresa

### 7.7 企业级产品

#### 7.7.1 CoreOS Tectonic

#### 7.7.2 CoreOS Tectonic

#### 7.7.3 OpenShift - Container Platform

#### 7.7.4 SUSE Container as a Service

#### 7.7.5 Canonical Distribution of Kubernetes - CDK

### 7.8 命令行工具

#### 7.8.1 click

#### 7.8.2 kube-prompt

#### 7.8.3 Kube-shell

#### 7.8.4 Kubebot

#### 7.8.5 kubectx

#### 7.8.6 kubens

#### 7.8.7 StackStorm

#### 7.8.8 kubectld

#### 7.8.9 Kubectl Aliases

#### 7.8.10 Vikube

#### 7.8.11 kube-ps1

#### 7.8.12 kube-tmux

#### 7.8.13 kubensx

#### 7.8.14 Kubetail

#### 7.8.15 stern

#### 7.8.16 kubeval

#### 7.8.17 Kube YAML validations

#### 7.8.18 Ksd

#### 7.8.19 kubectl-service-plugin

#### 7.8.20 kubectl-plugins

#### 7.8.21 Kedge

#### 7.8.22 Koki Short

#### 7.8.23 Kustomize

#### 7.8.24 kube-score

#### 7.8.25 kubespy

#### 7.8.26 kube-capacity

### 7.9 监控项目

#### 7.9.1 Datadog

#### 7.9.2 Node Problem Detector

#### 7.9.3 eventrouter

#### 7.9.4 Grafana Kubernetes App

#### 7.9.5 Heapster

#### 7.9.6 Kubernetes Operational View

#### 7.9.7 Kubewatch

#### 7.9.8 Prometheus

#### 7.9.9 Loki

#### 7.9.10 Sysdig Monitoring

#### 7.9.11 Weave Scope

#### 7.9.12 Cockpit

#### 7.9.13 Searchlight

#### 7.9.14 IngressMonitorController

### 7.10 测试

#### 7.10.1 k8s-testsuite

#### 7.10.2 Test-Infra

#### 7.10.3 Sonobuoy

#### 7.10.4 PowerfulSeal

#### 7.10.5 Kubesquash

#### 7.10.6 Kubectl-debug

#### 7.10.7 kboom

### 7.11 自愈合

#### 7.11.1 Node-problem-detector

#### 7.11.2 Draino

#### 7.11.3 K8s-cleanup

#### 7.11.4 Remediation Collection

## 8 Kubernetes素材

## 9 Kubernetes社区
