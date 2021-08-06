![](https://github.com/wniemiec-util-data/pair/blob/master/docs/img/logo/logo.jpg)

<h1 align='center'>Pair</h1>
<p align='center'>Text pair.</p>
<p align="center">
	<a href="https://github.com/wniemiec-util-data/pair/actions/workflows/windows.yml"><img src="https://github.com/wniemiec-util-data/pair/actions/workflows/windows.yml/badge.svg" alt=""></a>
	<a href="https://github.com/wniemiec-util-data/pair/actions/workflows/macos.yml"><img src="https://github.com/wniemiec-util-data/pair/actions/workflows/macos.yml/badge.svg" alt=""></a>
	<a href="https://github.com/wniemiec-util-data/pair/actions/workflows/ubuntu.yml"><img src="https://github.com/wniemiec-util-data/pair/actions/workflows/ubuntu.yml/badge.svg" alt=""></a>
	<a href="https://codecov.io/gh/wniemiec-util-data/pair"><img src="https://codecov.io/gh/wniemiec-util-data/pair/branch/master/graph/badge.svg?token=R2SFS4SP86" alt="Coverage status"></a>
	<a href="http://java.oracle.com"><img src="https://img.shields.io/badge/java-11+-D0008F.svg" alt="Java compatibility"></a>
	<a href="https://github.com/wniemiec-util-data/pair/releases"><img src="https://img.shields.io/github/v/release/wniemiec-util-data/pair" alt="Release"></a>
	<a href="https://github.com/wniemiec-util-data/pair/blob/master/LICENSE"><img src="https://img.shields.io/github/license/wniemiec-util-data/pair" alt="License"></a>
</p>
<hr />

## ❇ Introduction
Represents pairs of two elements. This implementation was based on std::pair (from C++). You can see more [here](https://www.geeksforgeeks.org/pair-in-cpp-stl/).

## ❓ How to use
1. Add this to pom.xml:
```
<dependency>
  <groupId>wniemiec.util.data</groupId>
  <artifactId>pair</artifactId>
  <version>1.0.0</version>
</dependency>
```

2. Run
```
$ mvn install
```

3. Use it
```
[...]

import wniemiec.util.data.Pair;

[...]

Pair<String, String> example = Pair.of("Hello", "World");

System.out.println( example.getFirst() + " " + example.getSecond() );
```

## 📖 Documentation
|        Property        |Type|Description|Default|
|----------------|-------------------------------|-----------------------------|--------|
|of |`first: T, second: T: Pair<T,T>`|Creates a pair from two objects| - |
|get{first, second} |`void: Pair<T,T>`|Gets a position of the pair| - |
|set{first, second} |`value: T`|Sets a position of the pair| - |


## 🚩 Changelog
Details about each version are documented in the [releases section](https://github.com/williamniemiec/wniemiec-util-data/pair/releases).

## 🤝 Contribute!
See the documentation on how you can contribute to the project [here](https://github.com/wniemiec-util-data/pair/blob/master/CONTRIBUTING.md).

## 📁 Files

### /
|        Name        |Type|Description|
|----------------|-------------------------------|-----------------------------|
|dist |`Directory`|Released versions|
|docs |`Directory`|Documentation files|
|src     |`Directory`| Source files|
