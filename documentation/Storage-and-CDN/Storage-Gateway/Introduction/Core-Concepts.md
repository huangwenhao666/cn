# 核心概念

名称|说明
-|-
存储网关|存储网关是云存储服务的一种，提供了存储协议转换功能。存储网关自身不提供存储能力，其数据是持久化保存在OSS中的，存储网关主要是起到中转和协议转换作用。
文件网关|支持文件协议访问的存储网关也称为文件网关，文件网关将OSS Bucket的对象结构与NAS文件系统的目录与文件建立映射关系。
共享文件系统|存储网关可开启共享文件系统。一个文件系统对应一个OSS Bucket。用户通过访问存储网关上的共享文件系统。
缓存|云主机所挂载的云硬盘为存储网关提供缓存，写入存储网关的数据首先会保存于缓存盘中，提供低延迟的读写访问；缓存盘中数据会异步传输至OSS中。
NFS|网络文件系统，由NFS Client和NFS Server组成，存储网关作为NFS Server为各来访Client提供文件存储服务。