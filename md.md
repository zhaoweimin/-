# 一级菜单
## 二级菜单
### 三级菜单
#### 四级菜单
##### 五级菜单
###### 六级菜单
```
# 一级菜单
## 二级菜单
### 三级菜单
#### 四级菜单
##### 五级菜单
###### 六级菜单
```

这是一级菜单
==========================================
这是二级菜单
------------------------------------------

```
这是一级菜单
==========================================
这是二级菜单
------------------------------------------
```

# 一级 #
## 二级 ##

```
# 一级 #
## 二级 ##
```


### 无序列表
* 1
* 2
* 3
+ 1
+ 2
+ 3
- 1
- 2
- 3
```
* 1
* 2
* 3
+ 1
+ 2
+ 3
- 1
- 2
- 3
```

### 有序列表
1. 列表1
2. 列表1
3. 列表1
```
1. 列表1
2. 列表1
3. 列表1
```
### 有序列表2
6. 列表1
2. 列表1
3. 列表1
```
6. 列表1
2. 列表1
3. 列表1
```

### 区块引用
* 不以结婚为目的的谈恋爱都是耍流氓
    > 这是毛主席说的
* 前方高能
    > 注意：这里是为了体现前有刺激的事情发生，请做好准备
```
* 不以结婚为目的的谈恋爱都是耍流氓
    > 这是毛主席说的
* 前方高能
    > 注意：这里是为了体现前有刺激的事情发生，请做好准备
```

### 区块镶嵌
> ## 标签
> * 不以结婚为目的的谈恋爱都是耍流氓
>     > 这是毛主席说的
> * 前方高能
>     > 注意：这里是为了体现前有刺激的事情发生，请做好准备
```
> ## 标签
> * 不以结婚为目的的谈恋爱都是耍流氓
>     > 这是毛主席说的
> * 前方高能
>     > 注意：这里是为了体现前有刺激的事情发生，请做好准备
```

###  /> 
> 1
>> 2
>>> 3
>>>> 4
>>>>> 5
>>>>>> 6
```
> 1
>> 2
>>> 3
>>>> 4
>>>>> 5
>>>>>> 6
```

### 分割线
 ***
 ************
 ---
  - - -
  ----------------------------
  _________
```
 ***
 ************
 ---
  - - -
  ----------------------------
  _________
```
### 链接
> 行内式 [github](https://github.com)
> 带title[github](https://github.com "github")
```
行内式 [github](https://github.com)
带title[github](https://github.com "github")
```
### 声明
[name]: http://www.baidu.com "name"
[home]: http://www.baidu.com "home"
[名称]: http://www.baidu.com "名称"
这里是[name], 有个[home], 哈哈哈哈 [名称]

```

声明
[name]: http://www.baidu.com "name"
[home]: http://www.baidu.com "home"
[名称]: http://www.baidu.com "名称"
这里是[name], 有个[home], 哈哈哈哈 [名称]
```

### 图片
用法跟链接的基本一样，唯一的不同就是，图片前面要写一个！（这是必须的），没什么好说的
![图片](https://image.shutterstock.com/image-vector/merry-christmas-happy-new-year-600w-1856929237.jpg)


### 代码框
#### 第一种 单行用 ``
`const name = "Jaken"`
#### 多行用 ```
```
function binarySearch(arr, target, start, end) {
    var idx = Math.floor((start + end) / 2);
    if (idx == start && arr[idx] != target) {
        return -1;
    } else if (idx == start && arr[idx] == target) {
        return idx;
    }
    if (target < arr[idx]) {
        return binarySearch(arr, target, start, idx);
    } else if (target > arr[idx]) {
        return binarySearch(arr, target, idx, end);
    } else {
        return idx;
    }
}
```

### 表格
|name|age|sex|
|-|-|-|
|Tony|20|男|
|Lucy|18|女|
```
|name|age|sex|
|-|-|-|
|Tony|20|男|
|Lucy|18|女|
```

### 强调
*字体斜体*
_字体斜体_
**字体斜体**
__字体斜体__
```
*字体斜体*
_字体斜体_
**字体斜体**
__字体斜体__
```

### 删除
~~请删除我吧~~
```
~~请删除我吧~~
```
