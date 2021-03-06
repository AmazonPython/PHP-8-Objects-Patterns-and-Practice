# 内容目录

- [关于作者](./About_the_Author.md)
- [关于技术评审员](./About_the_Technical_Reviewer.md)
- [致谢](./Acknowledgments.md)
- [前言](./Introduction.md)
- [第一部分：对象](./Part_I_Objects.md)
  - [第一章 PHP：设计和管理](./Chapter_1.md)
    - [问题](./The_Problem.md)
    - [PHP 和其他语言](./PHP_and_Other_Languages.md)
    - [关于本书](./About_This_Book.md)
      * [对象](./Objects.md)
      * [模式](./Patterns.md)
      * [实践](./Practice.md)
      * [第六版新增内容](./What_is_New_in_the_Sixth_Edition.md)
    - [总结](./Summary_of_Chapter_1.md)
  - [第二章 PHP 和对象](./Chapter_2.md)
    - [PHP 对象的意外成功](./The_Accidental_Success_of_PHP_Objects.md)
      * [PHP/FI 的起源](./In_the_Beginning_of_PHP_and_FI.md)
      * [语法糖：PHP3](./Syntactic_Sugar_PHP3.md)
      * [PHP4：寂静的革命](./PHP4_and_the_Quiet_Revolution.md)
      * [拥抱变革：PHP5](./Change_Embraced_PHP5.md)
      * [PHP7：缩小差距](./PHP7_Closing_the_Gap.md)
      * [PHP8：整合继续](./PHP8_Consolidation_Continues.md)
    - [拥护与怀疑：对象之争](./Advocacy_and_Agnosticism_The_Obeject_Debate.md)
    - [总结](./Summary_of_Chapter_2.md)
  - [第三章 对象基础](./Chapter_3.md)
    - [类与对象](./Classes_and_Objects.md)
      * [第一个类](./A_First_Class.md)
      * [第一个对象（或第二个）](./A_First_Object.md)
    - [在类中设置属性](./Setting_Properties_in_a_Class.md)
    - [使用方法](./Working_With_Methods.md)
    - [创建构造函数方法](./Creating_a_Constructor_Method.md)
      * [构造器属性提升](./Constructor_Property_Promotion.md)
    - [默认参数和命名参数](./Default_Arguments_and_Named_Arguments.md)
    - [参数和类型](./Arguments_and_Types.md)
      - [基本类型](./Primitive_Types.md)
        * [基本类型示例](./Primitive_Types_An_Example.md)
      - [其他的一些类型检查函数](./Some_Other_Type_Checking_Functions.md)
      - [类型声明：对象类型](./Type_Declarations_Object_Types.md)
      - [类型声明：基本类型](./Type_Declarations_Primitive_Types.md)
      - [混合类型](./mixed_Types.md)
      - [联合类型](./Union_Types.md)
      - [可为空类型](./Nullable_Types.md)
      - [返回类型声明](./Return_Type_Declarations.md)
      - [继承](./Inheritance.md)
        - [继承问题](./The_Inheritance_Problem.md)
        - [使用继承](./Working_with_Inheritance.md)
          * [构造器和继承](./Constructors_and_Inheritance.md)
          * [调用重写方法](./Invoking_Overridden_Method.md)
        - [公开，私有和受保护：类属性的访问控制](./Public_Private_and_Protected_Managing_Access_to_Your_Classes.md)
          * [访问器方法](./Accessor_Methods.md)
        - [类型属性](./Typed_Properties.md)
          * [ShopProduct类](./The_Shop_Product_Classes.md)
        - [总结](./Summary_of_Chapter_3.md)
  - [第四章 高级特性](./Chapter_4.md)
    - [静态方法和属性](./Static_Methods_and_Properties.md)
    - [常量属性](./Constant_Properties.md)
    - [抽象类](./Abstract_Classes.md)
    - [接口](./Interfaces.md)
    - [特征](./Traits.md)
      * [一个特征可以解决的问题](./A_Problem_for_Traits_to_Solve.md)
      * [定义和使用特征](./Defining_and_Using_a_Trait.md)
      * [使用多种特征](./Using_More_Than_One_Trait.md)
      * [结合特征与接口](./Combining_Traits_and_Interfaces.md)
      * [用 insteadof 关键字管理方法名冲突](./Managing_Method_Name_Conflicts_with_insteadof.md)
      * [重写特征方法的别名](./Aliasing_Overridden_Trait_Methods.md)
      * [在特征中使用静态方法](./Using_Static_Methods_in_Traits.md)
      * [访问宿主类属性](./Accessing_Host_Class_Properties.md)
      * [在特征中定义抽象方法](./Defining_Abstract_Methods_in_Traits.md)
      * [更改特征方法的访问权限](./Changing_Access_Rights_to_Trait_Methods.md)
      * [延迟静态绑定：static 关键字](./Late_Static_Bindings_The_Static_Keyword.md)
    - [处理错误](./Handling_Errors.md)
      - [异常情况](./Exceptions.md)
        * [抛出异常](./Throwing_an_Exception.md)
        * [子类化异常](./Subclassing_Exception.md)
        * [用 finally 清理 try/catch 代码块后面的内容](./Cleaning_Up_After_try_catch_Blocks_with_finally.md)
      - [final 类和方法](./Final_Classes_and_Methods.md)
      - [内部错误类](./The_Internal_Error_Class.md)
      - [与拦截器一起工作](./Working_with_Interceptors.md)
      - [定义构析函数方法](./Defining_Destructor_Methods.md)
      - [用 __clone( ) 复制对象](./Copying_Objects_with_clone.md)
      - [为对象定义字符串值](./Defining_String_Values_for_Your_Objects.md)
      - [回调、匿名函数和闭包](./Callbacks_Anonymous_Functions_and_Closures.md)
      - [匿名类](./Anonymous_Classes.md)
      - [总结](./Summary_of_Chapter_4.md)
  - [第五章 对象工具](./Chapter_5.md)
    - [PHP 和包](./PHP_and_Packages.md)
      - [PHP 包和命名空间](./PHP_Packages_and_Namespaces.md)
        * [命名空间的救援](./Namespaces_to_the_Rescue.md)
        * [使用文件系统模拟软件包](./Using_the_File_System_to_Simulate_Packages.md)
        * [PEAR 方式的命名](./Naming_the_PEAR_Way.md)
        * [包含路径](./Include_Paths.md)
      - [自加载](./Autoload.md)
    - [类和对象函数](./The_Class_and_Object_Functions.md)
      * [查找类](./Looking_for_Classes.md)
      * [了解一个对象或类](./Learning_About_an_Object_or_Class.md)
      * [获取类的完全限定字符串引用](./Getting_a_Fully_Qualified_String_Reference_to_a_Class.md)
      * [了解方法](./Learning_About_Methods.md)
      * [了解属性](./Learning_About_Properties.md)
      * [了解继承](./Learning_About_Inheritance.md)
      * [方法调用](./Method_Invocation.md)
    - [反射 API](./The_Reflection_API.md)
      * [入门](./Getting_Started.md)
      * [是时候卷起你的袖子了](./Time_to_Roll_Up_Your_Sleeves.md)
      * [检查类](./Examining_a_Class.md)
      * [检查方法](./Examining_Methods.md)
      * [检查方法参数](./Examining_Method_Arguments.md)
      * [使用反射 API](./Using_the_Reflection_API.md)
    - [属性](./Attributes.md)
    - [总结](./Summary_of_Chapter_5.md)
  - [第六章 对象与设计](./Chapter_6.md)
    - [定义代码设计](./Defining_Code_Design.md)
    - [面向对象和程序化编程](./Object_Oriented_and_Procedural_Programming.md)
      * [职责](./Responsibility.md)
      * [内聚力](./Cohesion.md)
      * [耦合](./Coupling.md)
      * [正交性](./Orthogonality.md)
    - [选择类](./Choosing_Your_Classes.md)
    - [多态性](./Polymorphism.md)
    - [封装](./Encapsulation.md)
    - [忘记怎么做吧](./Forget_How_to_Do_It.md)
    - [四个路标](./Four_Signposts.md)
      * [代码重复](./Code_Duplication.md)
      * [知之甚详的类](./The_Class_Who_Knew_Too_Much.md)
      * [万事通](./The_Jack_of_All_Trades.md)
      * [条件语句](./Conditional_Statements.md)
    - [统一建模语言](./The_UML.md)
      - [类图](./Class_Diagrams.md)
        * [表达类](./Representing_Classes.md)
        * [属性](./Attributes_of_UML.md)
        * [操作](./Operations.md)
        * [描述继承和实现](./Describing_Inheritance_and_Implementation.md)
        * [关联](./Associations.md)
        * [聚合和组合](./Aggregation_and_Composition.md)
        * [描述使用情况](./Describing_Use.md)
        * [使用注释](./Using_Notes.md)
      - [序列图](./Sequence_Diagrams.md)
    - [总结](./Summary_of_Chapter_6.md)