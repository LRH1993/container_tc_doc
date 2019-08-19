> 所有**异常费用**、与费用信息中**不一致的费用**、小程序回传的**箱信息**以及**报销费用**都会触发审核任务，需要对应责任人审批才可进入系统。

### 异常费用

<center class="half">
    <img src="https://container-system.oss-cn-shanghai.aliyuncs.com/container/doc/task_1.jpg" width="100%"/>
</center>

- 在待派订单中，确认订单时，若检测到**异常费用**、与费用信息中**不一致的费用**，就会提示操作人员进行申报批准流程。
- 申报后，在该页面内**对应审批责任人就会看到费用产生的原因以及详情**，审核无误后即可通过，**进入到财务核对核销流程**。

`此项流程避免费用的胡乱支出，规范人员操作。`

### 财务打回

<center class="half">
    <img src="https://container-system.oss-cn-shanghai.aliyuncs.com/container/doc/task_2.jpg" width="100%"/>
</center>

- 若订单**已被财务处理，进入到核销流程**；此时费用信息需要打回更改或添加，则会**触发审批流程**。

`此项流程避免费用的重复核销，多次支出相同费用。`

### 箱信息审核

<center class="half">
    <img src="https://container-system.oss-cn-shanghai.aliyuncs.com/container/doc/task_3.jpg" width="100%"/>
</center>

- 司机在小程序上**填写封号、皮重，上传箱号、封号照片，会触发审核操作**。
- 右侧有两列数据，一列是回传，一列是系统中已有的，可以与箱号、封号照片**比对，最终将正确的填入输入框内并保存**。

`此项流程通过审核比对照片及相应数据，避免司机填写封号和皮重错误导致后续流程受影响。`

### 报销审核

<center class="half">
    <img src="https://container-system.oss-cn-shanghai.aliyuncs.com/container/doc/task_4.jpg" width="100%"/>
</center>

- 左侧图片是司机**垫付费用的发票照片**。
- 右侧有两列数据，一列是**司机填写的报销费用**，另一列是将要加入到系统中的**付给司机的报销费用**，责任人根据实际情况填写并保存。

`此项流程审核报销费用金额的正确性和真实性。`