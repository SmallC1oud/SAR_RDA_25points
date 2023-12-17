# SAR_RDA_25points  仅供参考

### RDA流程图
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/e1ab9790-dc67-43c1-a917-967efa87e701)

### 参数设置
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/839eaef4-a65d-486a-86a5-e93d1f2e7809)

### 设计LFM信号带宽
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/2be37856-b7a0-4e4e-be32-97e7d7087082)

### 设计天线尺寸
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/f5021afd-8f64-4b0b-b062-04dc94948124)
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/3f198bbc-4cec-4eb5-a859-b4b025dac6a4)
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/b70b2455-2d2e-4150-b70b-646907d110d5)

### 设计雷达接收机波们起始时刻和中止时刻
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/8435cfed-4988-4210-9bb5-ff19aae3f81e)
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/6e24637a-8806-42f5-ba6b-f3d7b18eefe4)
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/dcf4b921-2135-4c92-a129-ce61d23c4985)
（代码中并没有实现这一要求）

### 设计两个方向上的过采样因子
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/877b84e0-6686-4ebb-a344-4deb246d7a86)

### 正侧视SAR成像几何关系
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/97e643ac-7210-4b71-a0f7-09bbf940cb67)

## 结果展示
### 仅存在中心点（10000，0，0）时
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/200f7ada-5674-4616-a745-197b9c6152d7)
相位图为正扫频情况下的结果，呈现双曲线形状，同时相位图中出现了多出来的“目标点”，这是因为缠绕状态的相位只代表了复数信号的部分信息，因此相位图等价于把复数信号表示为实数信号，因此出现了虚像。

### 25个点
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/ee05c66b-0449-4a12-809c-823a003df9c9)
无法观察出距离徙动等有效信息，相位图也变得无法识别。

### 距离徙动校正
距离多普勒域中的弯曲示意：
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/78601ab8-a56e-4f33-962d-3e62a404717a)

距离徙动校正示意：
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/b0d8e645-a236-43a9-9e49-a6e001b6dbf7)

本次仿真中看不出来弯曲，可将斜视角改为3.5°，能看出比较明显的弯曲

## 点目标成像
![图片](https://github.com/SmallC1oud/SAR_RDA_25points/assets/77475570/10798072-eacc-4d70-8e58-c118959d7aa4)

