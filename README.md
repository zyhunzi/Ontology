# Ontology
基于本体的无代码平台-FeiShun通用业务系统，理论上可以配置任何业务，类似合同管理、客户管理、学籍管理，根据自己的需要只要配置即可。

演示 http://demo.feishun.net

# 历史
    这是十几年前用.net MVC做的，到现在感觉这个思想还是不错，以前用作知识图谱，后来发现用它做业务系统也是相当好的。由于工作特别忙，没时间改进它。
    非常较适合中小企业自己管理自己的简单业务。
    不需要写任何代码，只需要技术人员配置好站点，然后由业务人员根据自己的业务配置即可。

# 优点
  对于一般的业务不需要建表，加字段，不需要建表关系,更不需要写代码，直接在这里面建业务就行。

# 功能描述
通过创建业务类、子类、属性、业务关系，根据这些配置自己生成业务表格。
<img width="1250" alt="1750929098556" src="https://github.com/user-attachments/assets/9f1dd9d1-790f-4fad-930e-040835263feb" />

## 业务类
   类就是业务，可创建根类、子类，子类可继承父类的属性。
     <img width="337" alt="{79F9BD31-D605-4CF7-B784-E77B5A9BD735}" src="https://github.com/user-attachments/assets/1f921b9f-339f-44dd-b02e-a51dd594b308" />

## 类属性
   属性相当于数据库的字段，但这里的属性还包括计算属性(例如含税价/税率=不含税单价)，关系属性（例如合同对应的客户）、实体属性，当然还包括单选、多选、图片、附件等等。
类属性是可以继承的，也可以有默认值。
<img width="977" alt="1750928435444" src="https://github.com/user-attachments/assets/6f2657f3-912c-4d21-a28d-cd45dc830310" />

## 类关系
   相当于表关系，可以定义两个业务之间的关系，例如合同与客户之间的关系，客户与产品、客户与联系人，合同与收款等等，可自己定义。
<img width="779" alt="1750928868256" src="https://github.com/user-attachments/assets/03f0868f-ad60-4237-aca8-b4d0eafb1680" />
<img width="377" alt="1750929007417" src="https://github.com/user-attachments/assets/0cae5f96-35d4-41d1-9027-f56c37fbf224" />

## 显示配置
  可配置业务表格中筛选条件，合计属性等,以控制业务筛选和条件。
<img width="668" alt="1750929292622" src="https://github.com/user-attachments/assets/c81d22c4-11ee-4d76-b80a-cae5730310ba" />

## 业务导出
  当配置好一套业务后，可将该业务导出至xml文件，在新系统中再导入就可不需要重新配置了。
  <img width="648" alt="1750929583655" src="https://github.com/user-attachments/assets/e9bdd27c-2834-4188-82fb-edd36bda6fa1" />

## 其它
  这里还包括用户管理、权限管理等其它功能。

## 改进
  由于工作比较忙，没时间将它改成比较流行的框架，更没时间增加手机端等工作，希望以后可以多交流，持续改进它。

