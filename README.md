# Sylvia-Doc
Sylvia Project Link：[Sylvia](https://github.com/FOXFOUND/Sylvia) 
Sylvia-Doc English Version：[README-EN.md](README-EN.md) 

## Sylvia功能

面向边缘计算的DevOps平台，具备如下功能
```
管理平面：
  |- 多集群/高可用
边缘节点：
  |- CI/CD流水线功能
  |- 作业调度
  |- 状态检查/日志上报（第二版）
```

## 架构(草稿状态)

### 管理平面：

![](IMG/control-panel-architecture.png)

### 边缘节点：

#### 裸机模式：
![](IMG/Edge-Panel-Bare-Machine.png)

#### 容器(基于K8S)模式：
![](IMG/Edge-Panel-Container-K8S-pattern.png)
