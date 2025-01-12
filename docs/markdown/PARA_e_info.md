> Created on Sun Oct 10 22\24\40 2021 @author: Richie Bao-python_code_archi_la_design_method_study 西安建筑科技大学-规划/建筑/景观本科数字化系列课程

# 参数化景观|建筑 设计方法 parameterize archi|la design and data analysis

### 高校课程信息
**课程名称**：软件基础CAAD与创新设计 （日后课程名称可能修改为：参数化景观设计方法）

**学分**：1.5

**总学时/课内实践学时**：24

**课程性质**：选修课程

**课程类型**：通识核心课程

**适应对象**：建筑、风景、规划

### 组队
每6人一组，如不能归整，余数分别自由组到已有组别。每组自行推选一个组长，组名自选任何一种动物名。

推选课程代表1-2人，负责课程事宜。

### 考核

* 平时成绩

1. 小组实验，组内成员贡献度由小组根据个人贡献大小共同确定（需诚实守信）， 百分比计算，综合为100%。
2. 签到，由课代表及组长负责（需诚实守信）。

* 期末成绩

### 小组名单
由课代表完成汇总，格式为（Excel编写）：

* 表1

| 序号  |  组名 | 组员名 |学号 | 组长  |  备注 |签到-1 |签到-2 |... |签到-12 | 签到成绩 |小组实验个人贡献-1|...|小组实验个人贡献-n|小组实验个人贡献成绩|期末实验个人贡献度|总成绩|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1  | Kitty  | 张三  |   | 是  |   |  1 |   |   |   |   |   |   |   |   |   |   |
| 2  |   | 李四  |   |   |   |  1 |   |   |   |   |   |   |   |   |   |   |
| 3  |   | 王五  |   |   |   |  0 |   |   |   |   |   |   |   |   |   |   |
| 4  |   | .  |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| 5  |   | .  |   |  |   |   |   |   |   |   |   |   |   |   |   |   |
| 6  |   | .  |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| 7  | Squirrel  | 赵六 |   | 是  |   | 1  |   |   |   |   |   |   |   |   |   |   |
| 8  |   | 孙七  |   |   |   |  2 |   |   |   |   |   |   |   |   |   |   |
| ...  |   | .  |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
| n  |   |  . |   |   |   |   |   |   |   |   |   |   |   |   |   |   |

* 表2

| 序号  | 组名   | 小组实验-1  | ...  |  小组实验-n |期末实验|
|---|---|---|---|---|---|
|  1 | Kitty  |   |   |   |   |
|  2 | Squirrel  |   |   |   |   |
| ...  |  . |   |   |   |   |
| n  |  . |   |   |   |   |


> 签到，1为到，0为未到，2为请假（需假条）。最后汇总，由课代表在grasshopper中读取Excel文件编写代码，计算最终签到成绩，小组实验成绩。

### 小组实验
#### 实验-1
个人实验。自修完[参数化逻辑构建过程](http://cadesign.cn/course/2010_2020/3_gh_parameterized_logical_build_process/), 完成时间为第5次课前。练习的.gh及.3dm文件单独存储为独立的一个文件夹内，文件夹统一命名为“Experi_01_姓名_学号”。最后提交图文并茂A4若干张的一个.pdf自修报告文件，文件命名为`Experi_01_姓名_学号.pdf`。

评分粗略标准：

1. 不要完全照抄源代码，建议可以自行变化实验，并反应到报告文件中；
2. 报告文件内容包括自修课程自己练习的参数化设计图表达及代码，和理解注释等。另排版合理，美观。

#### 实验-2
个人实验。对应完成**风景园林工程与技术**场地三维地形参数化模型的建立。文件夹统一命名为“Experi_02_姓名_学号”,文件命名为`Experi_02_topography.3dm`，以及`Experi_02_topography.gh`。并任一设置一个场地，随机生成一个地形，参数化标注高程等信息，文件命名为`Experi_02_topography_generation.gh`。最后提交图文并茂A4若干张的一个.pdf报告文件，文件命名为`Experi_02_姓名_学号.pdf`。

#### 实验-3
小组实验。阅读《图解木构造》，从中选择一种建筑形式，或者根据内容讲解，自行设计。全部设计均由参数化实现（不能在RH空间中增加辅助线），最后提交整体的参数化设计程序模型，以及任意3组参数化节点构造详图。文件命名为`Experi_03_design_of_wood_小组名.gh`。并提交图文并茂A4若干张的一个.pdf报告文件，文件命名为`Experi_03_小组名.pdf`。

#### 实验-4(deprecated)


#### 实验-5(deprecated)


#### 实验-6(deprecated)


### 期末实验
基于“风景园林工程与技术”课程场地，以参数化方式，从新完成所有设计。提交材料：

1. 一个.gh文件，一个.3dm文件；
2. A4大小，5-8页一个.pdf设计说明文件。

（已确定，需要打印纸质版，批分见红并提交至教务处存档。因此打印后汇总到课程负责人处）