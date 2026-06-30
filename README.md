# LLM Infra on Kubernetes

本项目是一个面向 AI Infra / LLMOps 场景的云原生大模型推理服务平台实践。

## 项目目标

基于 Kubernetes、vLLM、NVIDIA Device Plugin、DCGM Exporter、Prometheus、Grafana、Helm 和 Argo CD，验证大模型推理服务在私有化环境下的部署、发布、监控、压测和故障排查能力。

## 技术栈

- Kubernetes
- vLLM
- Helm
- Argo CD
- NVIDIA Device Plugin
- DCGM Exporter
- Prometheus
- Grafana
- Loki
- Qwen / DeepSeek

## 项目路线

- Week 1: vLLM 单机部署与基础压测
- Week 2: vLLM 参数与推理服务压测
- Week 3: Kubernetes GPU 调度
- Week 4: Helm Chart 标准化部署
- Week 5: Prometheus + DCGM Exporter
- Week 6: Grafana Dashboard + 告警
- Week 7: Argo CD GitOps 发布
- Week 8: 多环境发布与回滚
- Week 9: 扩缩容与容量评估
- Week 10: RAG Demo 接入
- Week 11: 故障演练与排障手册
- Week 12: 作品集整理与面试材料

## 目录结构

```text
docs/          项目文档、学习笔记、部署记录
charts/        Helm Chart
manifests/     Kubernetes YAML
monitoring/    Prometheus、Grafana、DCGM 配置
benchmark/     压测脚本与压测报告
scripts/       辅助脚本
rag-demo/      RAG 示例应用