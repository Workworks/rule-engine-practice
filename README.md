# rule-engine-practice

drools camunda 等基于规则引擎的实践


# 资源
1. [drools官方gitHub](https://github.com/kiegroup/drools)
2. [drools官方网站](https://www.drools.org/)

# Q & A
### camunda可以用来做什么？
1. 业务流程建模：使用BPMN（Business Process Model and Notation）来建模你的业务流程。在这些流程中，你可以定义决策节点，这些节点可以用来执行特定的规则。
2. 决策管理：Camunda支持DMN（Decision Model and Notation），这是一种用于建模和执行决策逻辑的标准。你可以使用DMN来定义复杂的业务决策规则。
3. 集成规则引擎：虽然Camunda自身可以作为一个轻量级的规则引擎，但它也可以与其他规则引擎（如Drools）集成，以提供更强大的规则处理能力。
4. 执行规则：在业务流程的执行过程中，根据流程定义，Camunda会在特定的决策点执行相应的规则。
5. 应用程序集成：Camunda提供了丰富的REST API和Java API，使得它可以轻松地与Java应用程序集成，从而在业务流程中执行规则。

### camunda作为规则引擎有什么优势？



### 业界常用轻量级规则引擎解决方案 drools Vs Camunda




# 规则引擎实战

## drools实战

#### 开发步骤
1. 获取KieServices
2. 获取KieContainer
3. KieSession
4. Insert fact
5. 出发规则
6. 关闭KieSession


#### 案例
1. 低代码平台（BPMN + Drools + Grovvy）[jeecgboot](https://github.com/jeecgboot/jeecg-boot)


