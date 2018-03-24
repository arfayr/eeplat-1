所谓元数据（metadata）即描述数据的数据(data about data)，在EEPlat中，对于描述业务系统(包括业务数据、逻辑和UI)的元数据我们称之为模型（model）或声明式业务对象（Declarative Domain Object），下面图文中元数据、模型、声明式业务对象的概念可以互相替换，如下图：
![eeplat meta data](https://raw.githubusercontent.com/arfayr/eeplat-1/patch-7/imgs/eeplat_meta_data.png)

元模型体系

在模型的基础上，EEPlat又进行了进一步的抽象，称之为元模型（metamodel）,这样又进一步提高了系统的灵活性和可扩展性。 EEPlat拥有世界领先的元模型体系。元模型是声明式业务对象的模型，声明式业务对象由元模型描述。EEPlat元模型体系是对企业信息化、电子政务等信息化领域业务的高度抽象，拥有自描述和动态扩展特性，能准确得完成业务领域模型的描述。 元模型从承担职责的角度分为功能元模型、业务对象元模型、服务元模型、规则元模型、工作流元模型、组织元模型、UI元模型等。

业务对象元模型主要描述业务功能的静态结构，服务元模型主要完成业务逻辑，同时负责业务对象元模型之间的交互；工作流元模型主要完成业务流程及业务对象元模型的协作；组织元模型通过组织元模型之间的职责关系可以实现灵活的组织结构，UI元模型是菜单、面板、表格、表格元素、功能树等的UI模型的元模型，可以实现复杂的界面表现，如下图：

![eeplat meta model](https://raw.githubusercontent.com/arfayr/eeplat-1/patch-7/imgs/EEPlat_metamodel_en.png)

EEPlat元模型是声明式业务对象的模型，是对信息管理系统的合理抽象。在元模型体系下，声明式业务对象是通过元数据（配置数据）进行描述。
声明式业务对象在EEPlat执行引擎的引导下形成用户可用的界面、逻辑等构成的业务系统，本质上执行引擎对EEPlat元数据的解析。
对应于OMG提出的MOF，EEPlat只有三层：
信息层（information layer）：利用EEPlat开发的信息管理系统
模型层（model layer）：声明式业务对象
元模型层（metamodel layer）：EEplat元模型