# SQLTools MaxCompute Driver

This is a [SQLTools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools) plugin to integrate with Alibaba Cloud [MaxCompute](https://maxcompute.console.aliyun.com/). Providing for running MaxCompute SQL and getting results, SQL formatting, generating SQL statements and SQL completion.

# Premises and Recommends

This plugin is only for connection testing and local resources management and does not support MaxCompute schema features (by now), please use below products for development and production.

- Big data development, recommend to use [DataWorks Data IDE](https://ide-cn-shanghai.data.aliyun.com/) instead.

- Data API development, recommend to use [DataWorks Data API](https://ds-cn-shanghai.data.aliyun.com/) instead.

- Data Analytics development, recommend to use [DataWorks Data Analytics](https://da-cn-shanghai.data.aliyun.com/) instead.

- Managing projects, recommend to use [MaxCompute Console](https://maxcompute.console.aliyun.com/) instead.

# Quick Start

- Getting your MaxCompute accessId and accessKey from [Aliyun Console](https://ram.console.aliyun.com/manage/ak)

- Prepare a MaxCompute environment, goto [MaxCompute Console](https://maxcompute.console.aliyun.com/) and apply projects.

![MaxCompute Projects](https://img.alicdn.com/imgextra/i4/O1CN019dBglK1KfWdhBxMIU_!!6000000001191-0-tps-2878-1506.jpg)

- Install the [SQLTools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools) plugin

- Install the [SQLTools MaxCompute Driver](https://marketplace.visualstudio.com/items?itemName=dataworks.sqltools-driver-maxcompute) plugin

- Open the SQLTools plugin and create a new connection, input your accessId, accessKey, MaxCompute project and [endpoint](https://help.aliyun.com/zh/maxcompute/user-guide/endpoints) (endpoint depends on your MaxCompute regions, for example: http://service.cn-shanghai.maxcompute.aliyun.com/api)

![SQLTools Connection](https://img.alicdn.com/imgextra/i4/O1CN01XYtcHI1r3OzP34QjG_!!6000000005575-0-tps-2878-1668.jpg)

- Run SQL and get results

![SQLTools Results](https://img.alicdn.com/imgextra/i1/O1CN01VedGCa1Mw8ER5v7Bg_!!6000000001498-0-tps-2878-1666.jpg)

- Support auto table and column names SQL completion.

![MaxCompute SQLTools Demo1"](https://img.alicdn.com/imgextra/i3/O1CN01p88eOE23vEwOTMSvH_!!6000000007317-0-tps-2878-1670.jpg)

![MaxCompute SQLTools Demo2"](https://img.alicdn.com/imgextra/i2/O1CN011LmXUV1al3GwIdYPR_!!6000000003369-0-tps-2878-1668.jpg)

- Support generate SQL insert statements.

![MaxCompute SQLTools Demo3"](https://img.alicdn.com/imgextra/i3/O1CN01aYlVaP1mn8SotwFOq_!!6000000004998-0-tps-2878-1668.jpg)

- Support SQL format.

![MaxCompute SQLTools Demo4"](https://img.alicdn.com/imgextra/i2/O1CN018kFl5e1GepZpKD3zW_!!6000000000648-0-tps-2878-1668.jpg)

