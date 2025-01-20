# carpet假人指令介绍

使用 carpet 模组中的假人组件可以召唤假人为自己挂机，这样可以使用抢夺三或精准采集等附魔工具来实现其它伤害或破坏方式所无法达到的效率。常用的假人指令教程可以参看如下视频：

<https://www.bilibili.com/video/BV1XZ421T7Ed?spm_id_from=333.788.videopod.sections&vd_source=0d9fd16925133a828635e3f4d9b75526>

以下是一些常用指令：

### 1. **创建假人**
   - `/player <假人名> spawn`  
     创建一个假人。

### 2. **控制假人**
   - `/player <假人名> attack`  
     让假人攻击。
   - `/player <假人名> use`  
     让假人使用物品（如右键点击）。
   - `/player <假人名> jump`  
     让假人跳跃。
   - `/player <假人名> sneak`  
     让假人潜行。
   - `/player <假人名> stopSneak`  
     让假人停止潜行。
   - `/player <假人名> sprint`  
     让假人疾跑。
   - `/player <假人名> stopSprint`  
     让假人停止疾跑。

### 3. **移动假人**
   - `/player <假人名> move <方向> [距离]`  
     让假人朝指定方向移动，可选距离（默认为1）。
   - `/player <假人名> look <方向>`  
     让假人看向指定方向（如`north`、`south`、`east`、`west`）。

### 4. **物品操作**
   - `/player <假人名> drop`  
     让假人丢弃手中的物品。
   - `/player <假人名> swapHands`  
     让假人交换主手和副手的物品。

### 5. **假人管理**
   - `/player <假人名> kill`  
     移除假人。
   - `/player <假人名> shadow`  
     让假人模仿你的动作。
   - `/player <假人名> stopShadow`  
     停止假人模仿你的动作。

### 6. **其他指令**
   - `/player <假人名> mount`  
     让假人骑乘最近的实体。
   - `/player <假人名> dismount`  
     让假人下马。

### 7. **批量操作**
   - `/player all <指令>`  
     对所有假人执行指令（如`/player all kill`移除所有假人）。

### 8. **假人信息**
   - `/player <假人名> info`  
     查看假人的状态信息。
