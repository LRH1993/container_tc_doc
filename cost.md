> 若要自动匹配费用，那么就要先维护好车队业务的费用信息。

<center class="half">
    <img src="https://container-system.oss-cn-shanghai.aliyuncs.com/container/doc/fee_3.png" width="100%"/>
</center>

- 需要设置的费用信息分为三块，分别是长途、短驳、堆场费用。
- 若要按油耗将燃油承包给自有车辆，则还需要设置油价信息。

#### 长途费用
<center class="half">
    <img src="https://container-system.oss-cn-shanghai.aliyuncs.com/container/doc/fee_4.png" width="100%"/>
</center>

- 长途费用并不是绝对意义上的长途，只是相对于短驳区别而言。
- 我们根据**门点、货代、尺寸、还箱点四个元素**来定义一条费用信息，只要这四个元素固定，那么对应运费、短驳费、油耗、油费都会有一个**固定的金额或数量**。
- 其中**一个门点可设置多个地址**，具体在门点信息中可以维护。所以这里我们可以将门点定义的宽泛一些，将门点定义为**一个业务地点的总称**，在门点信息中维护其具体的多个地址。
- 其中尺寸分为**40、20两种**。平时做业务时，这两种尺寸箱子价格是不同的。
- 具体定义原则，车队可灵活控制。只要坚持门点、货代、尺寸、还箱点四个元素固定一条费用即可。

<center class="half">
    <img src="https://container-system.oss-cn-shanghai.aliyuncs.com/container/doc/fee_6.png" width="100%"/>
</center>

- 这一步我们主要设置应收的费用，主要**包含运费、短驳费**。
- 其中运费是都有的，**短驳费可根据业务实际情况填入，没有则不写**。
- 最后一步，要选择费用的生效日期，可以按照船期、委托日期、装箱日期填入。**生效日期即这个价格的执行日期**，如果后续**调动价格，则在编辑中更改价格**，**选择新的生效日期即可，那么在生效日期范围内的运单将使用新的价格**，保证费用的准确有效。

<center class="half">
    <img src="https://container-system.oss-cn-shanghai.aliyuncs.com/container/doc/fee_5.png" width="100%"/>
</center>

- 这一步主要是维护应付给驾驶员的**运费以及自由车辆承包的油耗/油费**。
- 分为三类车辆，一类是**自由车辆**，一类是**外挂车辆**，还有一类是**外挂车队**，这三者价格不同，分开区分。
- 燃油费，可**根据车队情况选择油耗或者油费的方式结算**。当然结算**只会发生在自有车辆上**。
- 最后，选择生效日期，**和上一步意义相同**，区别就是**针对于驾驶员的运费和油耗/油费**。

#### 短驳费用

<center class="half">
    <img src="https://container-system.oss-cn-shanghai.aliyuncs.com/container/doc/fee_7.jpg" width="100%"/>
</center>

- 首先，按照上图步骤添加一条短驳费用。
- 短驳费用**主要维护的是付给司机的短驳费**，其中应**收的短驳费已经在长途费用中填好**了。
- 每一条短驳费，是按照**提箱点、门点、还箱点**三者固定的，只要这三者确定，那么就会产生一条短驳费。
- 下面的具体费用信息的含义和长途费用中一致。

#### 堆场费用

<center class="half">
    <img src="https://container-system.oss-cn-shanghai.aliyuncs.com/container/doc/fee_8.jpg" width="100%"/>
</center>

- 堆场费用就是在堆场**提空箱、落重箱**所产生的固定费用。

`到此，费用相关设置已经完成，派车时即可实现自动匹配费用，无需担心乱填漏填的情况。若在设置过程中遇到任何客服，可咨询客服。`