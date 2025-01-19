# 如何从spigot服务端迁移到fabric服务端

spigot 端的世界结构为主文件夹下`world`,`world_nether`,`world_the_end`,这些文件存储了三个维度的服务器数据，

* world
* world_nether
  * DIM-1
  * level.dat
  * session.lock
  * uid.dat
* world_the_end
  * DIM1
  * level.dat
  * level.dat_old
  * session.lock
  * uid.dat

然而 fabric 端的三个维度全部摆放在`world`文件夹中，

* world
  * DIM1
  * DIM-1

为了保持存档不变，必须把 spigot 端中的 `DIM1`，`DIM-1` 都正确地转移。
