# KVstorageBaseRaft-cpp
【代码随想录知识星球】项目分享-基于Raft的k-v存储数据库

## 使用方法

### 1.库准备
- muduo
- boost

### 2.编译启动
```
mkdir cmake-build-debug
cd cmake-build-debug
cmake ..
make
```
之后在目录bin就有对应的可执行文件生成：
- consumer
- provider
运行即可。

## Docs
- 如果你想创建自己的rpc，请参考example中rpc的md文件和friendRPC相关代码

## todoList

- [ ] 完成raft节点的集群功能
- [ ] 去除冗余的库
- [ ] 代码精简优化
- [ ] 代码解读 maybe