# 游戏关卡编辑器流程图

## 数据初始化与配置
- **WjzlLevelDistributionData**
  - `ID`: 关卡ID
  - `Map`: 地形
  - `ContainerCount`: 货柜总数量
  - `time`: 时间
  - 其他关卡配置数据

- **WjzlContainerProperty**
  - `ID`: 货柜ID
  - `Type`: 货柜类型
  - `LayerCount`: 货柜层数

## 关卡数据处理
- **WjzlLevelLevelData**
  - 管理关卡数据
  - 物品层级分配
  - 错误检测

## 关卡生成与编辑
- **WjzlLevelEditor.generateLevelData()**
  - 根据输入数据生成关卡
  - 物品随机分配
  - 空白处理

## 错误处理与调试
- 使用`isError`标志和`errorInfo`数组收集和报告错误

## 实用工具函数
- **getItems()**
  - 获取指定数量的物品
- **PrintLog()**
  - 打印日志信息

<!--stackedit_data:
eyJoaXN0b3J5IjpbNzg1NDcwNTMxXX0=
-->