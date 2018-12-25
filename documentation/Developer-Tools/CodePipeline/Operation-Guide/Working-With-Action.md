# 使用操作

操作是流水线管道某个阶段中的一个原子动作，在该阶段对项目执行的任务。流水线管道中的阶段并行执行，阶段中的操作串行执行。
流水线支持四种操作类型：
* 源代码：支持git、GitHub私有\公有库、京东云codecommit
* 构建：支持京东云codebuild
* 测试：支持京东云codebuild
* 部署：支持京东云Kubernetes集群部署


## 常用操作
* [手工确认](Check-Action.md)
* [添加操作](Edit-Pipeline.md)
* [编辑操作](Edit-Pipeline.md)
* [删除操作](Edit-Pipeline.md)