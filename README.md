# README-GoF设计模式讲解与实现

最近系统复习设计模式，边学习边实现，学习过程中我主要参考了程杰的《大话设计模式》和 [这个网站](http://c.biancheng.net/view/1317.html)。大话中的示例代码是C++，后者网站虽然用的是Java，但每一个示例都用窗体展示，夹杂了大量无关模式的awt和swing代码，不利于集中理解模式运作过程。网上大量关于设计模式的文章总是充斥着很多抽象说明和到处复制粘贴的UML图，对初学者理解模式本身反而造成干扰。例如下面这种抽象描述，实际上是对模式完全理解之后的高度概括，很多文章上来就写这种抽象定义，完全是浪费读者时间。这种描述对模式识别的理解是不是必须的，甚至对初学者是有害的。
> 状态（State）模式的定义：对有状态的对象，把复杂的“判断逻辑”提取到不同的状态对象中，允许状态对象在其内部状态发生改变时改变其行为。



在本仓库中，我会侧重每一个模式的代码实现，去芜存菁地讲解每一个模式，每一个代码示例我都已确保在本地成功运行，且代码尽可能遵守Java编程规范(主要是阿里的规范)。每一个模式讲解顺序如下：

- **模式说明**：简要说明模式使用场景和该模式相比简单粗暴的方法(通常是if-esle或者单个类封装)的好处，另外像组合模式里有透明方式和安全方式，单例模式里有饿汉方式和懒汉方式，模板模式里有钩子方法也会简要说明。
- **结构**：列明该模式用到的抽象和具体类。
- **代码演示**：可执行的符合Java编程规范的模式示例代码，并对关键语句都加上了注释。

