### 单元测试简介
#### src/androidTest/java/ningbaoqi/com/androidtool/ExampleInstrumentedTest.java

```
/**
  * 在其他测试方法执行之前进行调用，可以做一些对象初始化
  * */
@Before
public void setUp(){}
/**
  * 在其他测试方法执行之后进行调用，可以做一些数据库关闭的动作
  * */
@After
public void tearDown(){}
```
