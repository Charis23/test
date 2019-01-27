# Quick Learning Markdown

## Contents

### <a href="#title" target="_self">Learn Title</a>
### <a href="#list">Learn List</a>
### <a href="#reference">Learn Reference</a>
### <a href="#link">Learn Link</a>
### <a href="#image">Learn Image</a>
### <a href="#font">Learn Font</a>
### <a href="#code">Learn Code</a>
### <a href="#table">Learn Table</a>
---

## <span id="title">Learn Title</span>
### Use one or more \# to present titles
### Use \*\*\* to present delimiter line


***
## <span id="list">Learn List</span>
### Unordered list (\*)
* list 1
* list 2
* list 3

### Ordered list (1. 2. n.)
1. list 1
2. list 2


***
## <span id="reference">Learn Reference</span>
> Use \> to present reference


***
## <span id="link">Learn Link</span>
    Use [] () to present link
Link to my [README.md](README.md) file!


***
## <span id="image">Learn Image</span>
    Use ![] () to present image
![Cat Image](img/cat.jpg)


***
## <span id="font">Learn Font</span>
### Learn Bord Font (\*\*text\*\*)
> **For example** is in bord font.

### Learn Italic Font(\*text\*)
> *For example* is in italic font.


***
## <span id="code">Learn Code</span>
``` Use `code` to present code ```

### Javascript Code Demo
```Javascript    
function add(a, b) {
    return a + d;
}
```

### Java Code Demo
```Java
public class Test {
    private String name;
    
    public void setName(String name) {
        this.name = name;
    }

    public String getName() {
        return this.name;
    }
}
```


***
### <span id="table">Learn Table</span>
### Table Demo1
Header1 | Header2 | Header3 |
--------|:-------:|--------:|
test1   | test2   | test3   |
test11  | test22  | test33  |

### Table Demo2
<table style="border: 1px solid white">
    <tr>
        <th>Name</th>
        <th>Age</th>
        <th>Class</th>
    </tr>
    <tr>
        <td>Jack</td>
        <td>11</td>
        <td>1</td>
    </tr>
        <tr>
        <td>Mary</td>
        <td>22</td>
        <td>2</td>
    </tr>
</table>