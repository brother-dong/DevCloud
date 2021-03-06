# **创建项目、进行项目规划**<a name="devcloud_qs_0302"></a>

**项目管理**为开发团队提供简单高效的团队协作服务，包含多项目管理、敏捷迭代、需求管理等功能。

本节通过以下四步介绍如何使用项目管理服务进行项目规划的管理。

1.  [新建项目](#section798823141415)
2.  [使用需求规划新建工作项](#section139932346144)
3.  [新建迭代](#section9562202911416)
4.  [向迭代中添加工作项](#section2905184419141)

## **新建项目**<a name="section798823141415"></a>

DevCloud支持两种研发流程：[Scrum流程](https://support.huaweicloud.com/usermanual-projectman/devcloud_hlp_00021sm.html#section0)、[看板流程](https://support.huaweicloud.com/usermanual-projectman/devcloud_hlp_00021.html#section0)，本例选择使用Scrum流程项目。

新建项目操作步骤如下：

1.  登录[华为云DevCloud](https://devcloud.cn-north-4.huaweicloud.com/home)，单击页面右上角“新建项目“。

    ![](figures/DevCloud首页.png)

      

2.  单击选择“Scrum“，输入项目名称，单击“确定“，完成项目创建。

    ![](figures/PHP-新建项目.png)

      


## **使用需求规划新建工作项**<a name="section139932346144"></a>

“需求规划“是以思维导图的形式将工作项的层级结构展示出来，直观的展示父子关系。在“需求规划“页面中新建的工作项，会自动生成到后面的Epic、Feature、Backlog页面。

在项目初期，Product Owner（项目经理）将从客户获取的所有需求信息，逐一落实到项目规划中，分解细化，逐步形成“Epic\>Feature\>Story“的结构，并为工作项设置优先级。

![](figures/PHP-需求规划.png)

需求规划操作步骤如下：

1.  单击页面上方导航栏中“需求规划“，进入“需求规划“页面。

    ![](figures/选择目录-需求规划.png)

      

2.  单击“Epic“一栏中的“+“。

    ![](figures/需求规划.png)

      

    输入工作项名称，敲击回车，完成Epic创建。

    ![](figures/PHP-新建Epic.png)

      

3.  <a name="li9720104911419"></a>单击Epic卡片，在右侧滑出框中编辑工作项详情（例如描述信息、带\*的必填项），单击“保存“，完成工作项编辑。

    ![](figures/PHP-编辑Epic.png)

      

4.  <a name="li17459141712531"></a>单击图标![](figures/icon-新建工作项.png)，输入工作项名称，敲击回车，完成Feature创建。

    ![](figures/PHP-新建Feature.png)

      

5.  参照[步骤3](#li9720104911419)的操作，编辑Feature详情。
6.  参照[步骤4](#li17459141712531)的操作创建其它Feature、Story的创建，并参照[步骤3](#li9720104911419)的操作完成Feature、Story详情的编辑。

## **新建迭代**<a name="section9562202911416"></a>

Scrum项目周期通常被划分为若干个“迭代“，在每个迭代中完成一部分Story。

1.  单击页面上方导航栏中“迭代“，进入“迭代“页面。

    ![](figures/选择目录-迭代.png)

      

2.  系统会自动创建3个迭代，单击迭代卡片上的，选择编辑，即可编辑名称、计划时间以及迭代描述。

    ![](figures/编辑迭代.png)

      

3.  若需要创建新的迭代，单击“创建迭代“，在弹窗中输入迭代名称、计划时间，单击“新建“，完成迭代创建。

    ![](figures/PHP-新建迭代.png)

      


## **向迭代中添加工作项**<a name="section2905184419141"></a>

在迭代1开始前，在Backlog中过滤出优先级“高”且重要程度为“关键”的工作项。

评估工作量后，将story纳入迭代1，与开发人员进行需求澄清。

其余迭代，均可根据组内实际情况，按照优先级从高到低，重要程度减弱的顺序进行开发。

1.  单击“未规划工作项“，单击工作项列表上方“高级过滤“。

    ![](figures/PHP-过滤Story.png)

      

2.  单击“增加过滤字段“，在弹框中选择“优先级“、“重要程度“，单击“确定“。

    单击图标![](figures/icon-删除筛选条件.png)，删除其它筛选条件。

    ![](figures/选择过滤条件.png)

      

3.  优先级选择“高“，重要程度选择“关键“，单击“临时过滤“。

    ![](figures/设置过滤条件.png)

      

4.  单击每个工作项对应的“迭代“一列，在下拉列表中选择“迭代1“。

    ![](figures/PHP-选择迭代.png)

      


至此，您已经完成了对项目的规划操作。

  

