# Guapit Typora文档



<p align="center">
<a href="https://www.mql5.com"><img src="https://img.shields.io/badge/软件-Typora-critical.svg"/></a>
<a href="#"><img src="https://img.shields.io/badge/主题名-Guapit-blue"/></a>
<a href="#"><img src="https://img.shields.io/badge/版本-v1.1.0-f1c232"/></a>
<img src="https://img.shields.io/badge/作者-阿龙-d90429"/>
<a href="#"><img src="https://img.shields.io/badge/QQ-8199231-ff69b4"/></a>
<a href="#"><img src="https://img.shields.io/badge/微信-guapitcom-success"/></a>
<a href="https://www.guapit.com"><img src="https://img.shields.io/badge/学习资料-guapit.com-yellowgreen"/></a>
<a href="#"><img src="https://img.shields.io/badge/E--mail-guapit%40qq.com-yellowgreen"/></a>
<a href="https://space.bilibili.com/342693735"><img src="https://img.shields.io/badge/B站-点击进入B站 >> 免费零基础 快速入门编程-0096c7"/></a>
</p><br>



## 官方文档参考

> Github: https://github.com/guapit/guapit-typora-theme
>
> Gitee: https://gitee.com/guapit/guapit-typora-theme

### 安装方法

1 克隆下载

```bash
# github
git clone https://github.com/guapit/guapit-typora-theme.git
# gitee
git clone https://gitee.com/guapit/guapit-typora-theme.git
```

2 打开Typora文档软件

`文件(F)` > `偏好设置` > 选择 `外观` > `打开主题文件夹`

将下载好的 `theme` 目录的所有文件复制到 `Typora\themes`即可

<img src="https://gitee.com/guapit_com/mt5-tutorial-pictures/raw/master/images/mt5/gp-20221114210417.png" alt="image-20221114210415816" style="zoom:50%;" />

## 代码效果

### JavaScript

```javascript
var globalVar;
/**
 * Constructor for AjaxRequest class
 * @param {string} url the url for the request<p/>
 */
function AjaxRequest(url) {
  function local() {}
  var urls = [ "www.cnn.com", 5, globalVar];
  this.request = new XMLHttpRequest();
  url = url.replace(/^\s*(.*)/, "$1"); // skip leading whitespace
  /* check the url to be in urls */
  var a = "\u1111\z\n\u11";
  this.foo = new function() {};
  foo();
  #
  var hello = () => console.log("hello")}

@decorator()
class NameClass {
}
declare module name{
  declare export var exportedVar: string;
  declare export function exportedFunction(): void;
  declare export class ExportedClass {}
}
interface MyInterface { }
type FooBarAlias = string;
var html =`<div title='HTML injection'>Injected language fragment</div>`;
var x: MyInterface, y: string, z: FooBarAlias;

```

### java

```java
/* Block comment */
import java.util.Date;
import static AnInterface.CONSTANT;
import static java.util.Date.parse;
import static SomeClass.staticField;
/**
 * Doc comment here for <code>SomeClass</code>
 * @param T type parameter
 * @see Math#sin(double)
 */
@Annotation (name=value)
public class SomeClass<T extends Runnable> { // some comment
  private T field = null;
  private double unusedField = 12345.67890;
  private UnknownType anotherString = "Another\nStrin\g";
  public static int staticField = 0;
  public final int instanceFinalField = 0;
  protected final int protectedField = 0;
  final int packagePrivateField = 0;  

  /**
   * 语义高亮显示:
   * 生成的光谱为局部变量和参数选择颜色:
   *  Color#1 SC1.1 SC1.2 SC1.3 SC1.4 Color#2 SC2.1 SC2.2 SC2.3 SC2.4 Color#3
   *  Color#3 SC3.1 SC3.2 SC3.3 SC3.4 Color#4 SC4.1 SC4.2 SC4.3 SC4.4 Color#5
   * @param param1
   * @param param2
   * @param param3
   */
  public SomeClass(AnInterface param1,
                  int param2,
                  int param3) {
    int reassignedValue = this.staticField + param2 + param3;
    long localVar1, localVar2, localVar3, localVar4;
    int localVar = "IntelliJ"; // Error, incompatible types
    System.out.println(anotherString + toString() + localVar);
    int sum = protectedField + packagePrivateField + staticField;
    long time = parse("1.2.3"); // Method is deprecated
    new Thread().countStackFrames(); // Method is deprecated and marked for removal
    reassignedValue ++; 
    field.run(); 
    new SomeClass() {
      {
        int a = localVar;
      }
    };
    int[] l = new ArrayList<String>().toArray(new int[CONSTANT]);
  }
}
enum AnEnum { CONST1, CONST2 }
interface AnInterface {
  int CONSTANT = 2;
  void method();
}
abstract class SomeAbstractClass {
  protected int instanceField = staticField;
}
```

### Python

```python
@decorator(param=1)
def f(x):
    """
    Syntax Highlighting Demo
    @param x Parameter

    Semantic highlighting:
    Generated spectrum to pick colors for local variables and parameters:
     Color#1 SC1.1 SC1.2 SC1.3 SC1.4 Color#2 SC2.1 SC2.2 SC2.3 SC2.4 Color#3
     Color#3 SC3.1 SC3.2 SC3.3 SC3.4 Color#4 SC4.1 SC4.2 SC4.3 SC4.4 Color#5
    """

    def nested_func(y):
        print(y + 1)

    s = ("Test", 2+3, {'a': 'b'}, f'{x!s:{"^10"}}')   # Comment
    f(s[0].lower())
    nested_func(42)

class Foo:
    tags: List[str]

    def __init__(self: Foo):
        byte_string: bytes = b'newline:\n also newline:\x0a'
        text_string = u"Cyrillic Я is \u042f. Oops: \u042g"
        self.make_sense(whatever=1)
    
    def make_sense(self, whatever):
        self.sense = whatever

x = len('abc')
print(f.__doc__)
```

### C++

```c++
/*
 * Block comment 
 */
#include <vector>

using namespace std;  // line comment
namespace foo {

  typedef struct Struct {
    int field;
  } Typedef;
  enum Enum {Foo = 1, Bar = 2};

  Typedef *globalVar;
  extern Typedef *externVar;

  template<typename T, int N>
  class Class {
    T n;
  public:
    /**
     * 语义高亮显示:
     * 生成的光谱为局部变量和参数选择颜色:
     *  Color#1 SC1.1 SC1.2 SC1.3 SC1.4 Color#2 SC2.1 SC2.2 SC2.3 SC2.4 Color#3
     *  Color#3 SC3.1 SC3.2 SC3.3 SC3.4 Color#4 SC4.1 SC4.2 SC4.3 SC4.4 Color#5
     */
    void function(int param1, int param2, int param3) {
      int localVar1, localVar2, localVar3;
      int *localVar = new int[1];
      this->n = N;
      localVar1 = param1 + param2 + localVar3;

    label:
      printf("Formatted string %d\n\g", localVar[0]);
      printf(R"**(Formatted raw-string %d\n)**", 1);
      std::cout << (1 << 2) << std::endl;  

    /**
     * Macro documentation comment
     * @param A description
     */
    #define FOO(A) A
    #ifdef DEBUG
      printf("debug");
    #endif
    }
  };

  template <typename T>
  concept Concept = requires (T t) {
    t.field;
  };

  template<typename T>
  struct Widget {
      Widget(T t);
  };

  template<typename T>
  Widget(T) -> Widget<typename T::value_type>;
}

```

### CSharp

```c#
using System;
// ReSharper disable All
#pragma warning disable 67
#pragma warning disable 169

class All
{
  /**
    * let's C# how it used to be
    */
  public delegate void EventHandler(object sender, EventArgs s);
  public event EventHandler Event;

  private int myField;

  public All(int field, int property)
  {
    myField = field;
    Property = property;
  }

  public int Property { get; }

  private int Method(int parameter)
  {
    var mutable = Property ^ myField;
    var usual = 31 * parameter;
    mutable += usual + 13;
    return mutable;
  }

  private static int StaticMethod(int parameter)
  {
    unchecked
    {
      var usual = 31 * parameter;
      var sum = 0;
      foreach (var number in new[] {1, 2, 3, 4, 5})
      {
        sum += number << 2;
#if !RELEASE
        Console.Write($"Trace: {sum}\r\n\r\n");
#endif
        Local();
      }

      void Local()
      {
        sum += usual + 13;
      }

      return sum;
    }
  }
}

public static class Util
{
  /// <summary>
  /// Checks of the properties of <see cref="IComparable"/> objects
  /// </summary>
  /// <param name="value">value to be checked</param>
  /// <typeparam name="T">type of the value</typeparam>
  /// <returns>true if the property holds</returns>
  public static bool CheckReflexivity<T>(this T value)
      where T : IComparable<T>
  {
      return value.CompareTo(value) == 0;
  }
}

```

### SQL

```sql
-- DDL section
create table crm.product (
  id numeric primary key,
  title varchar(255) character set utf8
);
-- DML section
insert into product
  values (1, 'Product1');

select count(*) from crm.product;
select id as ProductID, title as ProductName
  from crm.product where id = :id;

\set content `cat data.txt`

```

### Json

```json
{
  // Line comments are not included in standard but nonetheless allowed.
  /* As well as block comments. */
  "the only keywords are": [true, false, null],
  "strings with": {
    "no escapes": "pseudopolinomiality"
    "valid escapes": "C-style\r\n and unicode\u0021",
    "illegal escapes": "\0377\x\"
  },
  "some numbers": [
    42,
    -0.0e-0,
    6.626e-34
  ] 
}
```



### XML

```xml
<?xml version='1.0' encoding='ISO-8859-1'  ?>
<!DOCTYPE index>
<!-- Some xml example -->
<index version="1.0" xmlns:pf="http://test">
   <name>Main Index</name>
   <indexitem text="rename" target="refactoring.rename"/>
   <indexitem text="move" target="refactoring.move"/>
   <indexitem text="migrate" target="refactoring.migrate"/>
   <indexitem text="usage search" target="find.findUsages"/>
   <indexitem>Matched tag name</indexitem>
   <someTextWithEntityRefs>&amp; &#x00B7;</someTextWithEntityRefs>
   <withCData><![CDATA[
          <object class="MyClass" key="constant">
          </object>
        ]]>
   </withCData>
   <indexitem text="project" target="project.management"/>
   <custom-tag>hello</custom_tag>
   <pf:foo pf:bar="bar"/>
</index>
```

### html

```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 3.2//EN">
<!--
*        Sample comment
-->
<HTML>
<head>
<title>DataGrip</title>
</head>
<body>
<h1>DataGrip</h1>
<p><br><b><IMG border=0 height=12 src="images/hg.gif" width=18 >
What is DataGrip? &#x00B7; &Alpha; </b><br><br>
<custom-tag>hello</custom_tag>
</body>
</html>
```

### Css

```css
@import "manual.css";

@font-face {
  font-family: DroidSans;
  src: url(DroidSans.ttf);
  unicode-range: U+000-5FF, U+1e00-1fff, U+2000-2300;
}

h1.mystyle:lang(en) {
  color:blue; /* TODO: change THIS to yellow for next version! */
  border:rgb(255,0,0);
  background-color: #FAFAFA;
  background:url(hello.jpg) !important;
}

div > p, p ~ ul, input [type="radio"] {
  color: green;
  width: 80%;
}

#header:after {
  color: red;
}

&!
```

### Vue

```vue
<template>
  <div id="app">
    <img alt="Vue logo"
         src="./assets/logo.png">
    <HelloWorld
        msg="Welcome to Your Vue.js App"/>
  </div>
  <span>{{ descr }}</span>
  <span>{{
      (function () {
        alert("Vue is great!")
      } return "Really great!")()
    }}</span>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
}
</style>
```

### React

```react
import logo from './logo.svg';
import './App.css';

function App() {
  return (
    <div className="App">
      <header className="App-header">
        <img src={logo} className="App-logo" alt="logo" />
        <p>
          Edit <code>src/App.js</code> and save to reload.
        </p>
        <a
          className="App-link"
          href="https://reactjs.org"
          target="_blank"
          rel="noopener noreferrer"
        >
          Learn React
        </a>
      </header>
    </div>
  );
}

export default App;

```



### Yaml

```yaml
---
# Read about fixtures at http://ar.rubyonrails.org/classes/Fixtures.html
static_sidebar:
  id: "foo"
  name: 'side_bar'
  staged_position: 1
  blog_id: 1
  config: |+
    --- !map:HashWithIndifferentAccess
      title: Static Sidebar
      body: The body of a static sidebar
  type: StaticSidebar
  description: >
    Sidebar configuration example
  extensions:
    - &params 
        auto_run: true
        reload: true
    - *params
```

### Scss

```scss
/* Some loud comment here */
// And silent one

$padding: 1% !default
@import variables

=large-text
  :font
    :family Arial
    :size 20px
    :weight bold
  :color #ff0000

#main a.class:visited span[lang="en"]
  @extend .shadow !optional
  +large-text
  p.info
    color: #00ddcc
  &:width 97% !important

@mixin with-shadow($color: black)
  box-shadow: $color, 1px, 2px, 3px

.shadowBlock
  @include with-shadow(blue)

$grid-width: 40px
$gutter-width: 10px

@function grid-width($n)
$grid-width: 10px !global
  @return $n * $grid-width + ($n - 1) * $gutter-width

@for $i from 1 through 3
  .item-#{$i} 
    width: 2em * $i

@font-face
  font-family: DroidSans
  src: url(DroidSans.ttf)
  unicode-range: U+000-5FF, U+1e00-1fff, U+2000-2300
```

## 引用展示

> * 变量的名称不可以使用系统默认的关键字
>
> * 变量名称只能是由字母,数字,下划线 `_` 组成
>
> * 变量名称只能有字母或者下划线 `_` 作为开头,不可以使用数字作为开头
>
> * 变量名称区分大小写
>
> * `_` 下划线的约定俗成的特殊含义为私有变量
>
>   -- 表示该变量不可以由外部改变和使用,作为程序内部的私有变量

## 表格效果展示

| 数据类型 | 含义                                     | ASCII码(十进制) |
| -------- | ---------------------------------------- | --------------- |
| \a       | 警报符号                                 | 007             |
| \b       | 退格(FF), 将当前位置光标移动到前一列     | 008             |
| \f       | 换页(LF), 将当前位置光标移动到下一行开头 | 012             |
| \n       | 换行(LF),将当前位置光标移动下一行开头    | 010             |
| \r       | 回车(CR),将当前位置光标移动到本行的开头  | 013             |
| \t       | 水平制表(HT) (跳转到下一个Tab的位置)     | 009             |

## 标签展示

赋值的几种格式

完整日期型: `D'2022.02.09 19:09:06'`

只有日期型: `D'2022.02.09'`,默认时间为 `00:00:00`

只有时间型: `19:09:06'` ,默认当天为日期

有日期和小时型: `D'2022.02.09 19'` ,实际显示为: `D'2022.02.09 19:00:00'`

有日期,小时,分钟型: D'2022.02.09 19:10' 实际显示为: `D'2022.02.09 19:10:00'`

## 目录展示

[TOC]

## 标题展示

# 我是标题 H1

## 我是标题 H2

### 我是标题 H3

#### 我是标题 H4

##### 我是标题 H5

###### 我是标题 H6