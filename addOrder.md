> 每天的订单计划都要通过新增订单导入。

<center class="half">
    <img src="https://container-system.oss-cn-shanghai.aliyuncs.com/container/doc/addOrder_1.png" width="100%"/>
</center>

- 系统支持两种方式的订单导入。一种是**按票录入**，另一种是**批量导入**。

### 批量导入
 
 > 批量导入是系统中的一大特色，可以极大的提高导入效率。

 - 首先，根据业务实际场景，选择**下载出口/进口模板**。
 - **根据模板排列顺序**将客户发给你的计划表粘贴到模板中。其中**装箱日期和装箱时间既可以分开填写也可以合并在一起填入其中一列即可**。
 - **点击批量导入**按钮，选择货代名称，然后将整理好的**excel表格上传**点击确认即可看到导入的订单列表信息，确认无误后即可点击导入。
 <center class="half">
    <img src="https://container-system.oss-cn-shanghai.aliyuncs.com/container/doc/add_order_2.jpg" width="100%"/>
</center>

`注意：每票提单号只允许导入一次，若重复多次导入同一提单号，则会提示重复。重复的提单号可通过按票录入的方式添加，只需要填入提单号或委托编号就会自动联想出该票订单的所有信息，只需在后面追加新的订单特有信息即可。`

<center class="half">
    <img src="https://container-system.oss-cn-shanghai.aliyuncs.com/container/doc/addOrder_2.png" width="100%"/>
</center>

- 如上所示，这种方式避免了追加计划的重复导入问题。

### 按票录入

- 如上图所示，**上半部分是一票订单的公有信息**。
- 点击添加按钮，则可增加每票订单的**每个计划的特有信息**。
- 其中LID.NO是一个唯一识别编号，**每个订单的LID.NO不可相同**，否则会**提示重复**，避免重复导入订单。

<center class="half">
    <img src="https://container-system.oss-cn-shanghai.aliyuncs.com/container/doc/addOrder_3.jpg" width="100%"/>
</center>

- 对于**每票订单的配舱计划或者追加计划**，只需**录入委托编号或者提单号**，然后在页面中**其他地方点击一下**，就会**自动匹配出该票订单**的所有信息，只需点击添加再新增然后点击完成即可保存新的计划。