# awtk-patterns

用一个简单计算器为例，展示传统、MVC、MVP和MVVM几种模式在AWTK上的实现方法。

## 准备

1.获取awtk并编译

```
git clone https://github.com/zlgopen/awtk.git
cd awtk; scons; cd -
```

2.获取awtk-mvvm并编译

```
git clone https://github.com/zlgopen/awtk-mvvm.git
cd awtk-mvvm; scons
```

3.获取awtk-patterns并编译

```
git clone https://github.com/zlgopen/awtk-patterns.git
cd awtk-patterns; scons
```

> awtk、awtk-mvvm和awtk-patterns在同一目录。

## 运行

```
./bin/calculator
```

> 本文以Linux/MacOS为例，Windows可能会微妙差异，请酌情处理。


## 目录说明

* src/calculator 传统实现方法。

* src/calculator-mvc MVC实现方法

* src/calculator-mvp MVP实现方法

* src/calculator-mvvm MVVM实现方法

