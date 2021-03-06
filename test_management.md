## 测试管理

### 1. 用例与测试计划管理

用例与测试计划管理是对用例与测试计划的管理活动，包含用例管理和测试计划管理两大部分。

### 1.1 用例管理

用例管理是对用例集、子用例集和用例的管理活动。

##### 应包含以下基本功能：

——用例集中可以包含多个用例和子用例集

——树形展示用例集中包含的用例和子用例集，子用例集可以逐层下钻

——设置用例的测试步骤，包括步骤描述、输入测试数据，期望结果

——用例支持不同的优先级、重要程度。

——可以区分手工和自动化用例

——用例集、子用例集和用例支持标签分类

——支持用例集、子用例集、用例和版本、需求、特性、故事关联

——支持自动化测试用例和测试脚本关联

##### 可以包含以下高级功能：

——用例或子用例集，可以属于多个用例集

——支持在用例上添加附件

——不创建测试计划情况下用例可以随机执行

——可以从用例关联到测试计划

——支持对版本、需求关联用例的统计分析

——支持对用例执行情况的统计分析

### 1.2测试计划管理

测试计划管理是对测试计划的管理活动。

##### 应包含以下基本功能：

——支持测试计划创建和变更

——可以将用例集、子用例集和用例添加到计划以关联到用例

——可以按照标签批量添加用例集、子用例集和用例

——测试计划可以支持多轮次执行

——计划执行可以设置测试版本、测试环境、测试周期

——计划执行支持不同用例给不同测试人员执行，可以是指派或认领方式

——计划执行测试人员可以反馈用例的测试结果，自动给出计划执行进展和结果

——测试用例可以反馈失败原因

——失败原因是版本故障的用例，可以关联到缺陷

——可以对测试计划执行情况统计分析

##### 可以包含以下高级功能：

——测试计划可以直接从需求自动添加关联的测试用例

——支持将测试用例设置到不同的测试环境执行

——用例执行测试时可以针对每个测试步骤测试并反馈结果

——自动化用例可以驱动测试工具执行脚本并自动反馈测试结果

——自动化用例驱动测试工具执行后可以自动分析用例的失败原因

——测试计划执行自动化用例对接测试工具具有可扩展性

——失败原因是版本故障的用例，可以自动向缺陷管理系统提交缺陷

——可以基于版本、需求对测试计划执行情况统计分析

——可以对测试计划执行效率进行统计分析

### 2. 缺陷管理

专家建议：严重程度放到基本功能里面。-已改
缺陷管理是指在软件生命周期中识别、管理、沟通任何缺陷的过程，确保缺陷从被识别到解决关闭的过程被跟踪管理而不丢失。应包含以下基本功能：

##### 应包含以下基本功能：

——标记缺陷优先级和严重程度；

——将缺陷指派给特定的人；

——标记缺陷的不同状态，状态覆盖从新建到解决关闭的整个过程。

——缺陷可以关联截图、视频等；

——可区分缺陷类型；

——可按解决者、作者、优先级严重程度、当前状态等字段过滤；

——缺陷可关联到需求和用例；

##### 可以包含以下高级功能：

——可添加评论；

——指派缺陷、更改缺陷状态，发送消息给相关人员；

——缺陷可关联到修复该缺陷的代码。

——可过滤未关联需求或用例的缺陷。

专家评审：
基本功能：
1、文本框不需要具体讲
2、缺陷可以关联截图、视频等
3、过滤建议放到基本
4、建议增加 记录缺陷关联到的需求和用例
5、建议增加 缺陷分类属性？
高级功能：
1、权限控制属于通用的，是不是需要单独提出？
2、高级5建议去除？
3、可以过滤未关联用例和需求的缺陷； 

### 3. 测试数据管理

测试数据管理指的是针对测试过程中所使用和产生的数据进行的管理。

##### 应包含以下基本功能：

-	支持自动生成测试数据，包括但不限于以下方式
  - 基于CSV、关系型数据库、文档数据库等类型的数据源提取生成
  - 通过录制接口请求和响应生成
  - 设置规则批量生成
  - 使用脚本语言批量生成
-	支持按照指定逻辑提取、转换测试数据
-	支持设置测试数据的元数据信息
-	支持创建和编辑测试数据，包括CSV等形式
-	支持存储测试数据至外部存储库，包括但不限于CSV、关系型数据库、文档数据库等
-	支持自定义测试数据展示样式
-	支持对测试数据进行版本管理
-	支持测试数据的回滚
-	支持分环境管理测试数据
-	支持对接其他测试服务调用测试数据

##### 可以包含以下高级功能：

- xxxx
- xxxx
