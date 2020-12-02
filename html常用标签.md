# HTML的常用标签
## a标签
href：链接的地址

target：不设置默认是当前页面打开，-blank是新页面打开

作用：跳转外部页面,跳转内部锚点,跳转电话或者邮箱等  

例：
``` <a href="https://baidu.com" target="_blank">百度一下</a>
    <a href="http://baidu.com" target="_blank">百度一下</a>
    <a href="//baidu.com" target="_blank">百度一下</a>
    <a href="/a/b.html" target="_blank">B html</a>
    <a href="a/b.html" target="_blank">B html</a>
    <a href="JavaScript:;">执行一个空的JS</a>
    <a href="id">跳转到某个ID的瞄点</a>
    <a href="mailto:907248402@qq.com">发邮件</a>
```
## img标签
发出get请求，展示一张图片

src："地址"

alt："加载失败以后的提示"

width和height：设置宽和高，只设置一项剩下一项自适应，同时设置图片可能会变形

如果图标过宽可以使用 max-width: 100%;

例
```
<img width="400" src="dog.jpg" alt="一只狗子">
```

## table标签
thead

tbody

tfoot

th 表头  默认会加粗

tr 一行

table代码
```
<table>
        <thead>
            <th></th>
            <th>小红</th>
            <th>小明</th>
            <th>小芳</th>
        </thead>
        <tbody>
            <tr>
                <th>语文</th>
                <td>90</td>
                <td>91</td>
                <td>92</td>
            </tr>
            <tr>
                <th>数学</th>
                <td>93</td>
                <td>94</td>
                <td>95</td>
            </tr>
            <tr>
                <th>英语</th>
                <td>96</td>
                <td>97</td>
                <td>98</td>
            </tr>
        </tbody>
        <tfoot>
            <th>总分</th>
            <td>279</td>
            <td>282</td>
            <td>285</td>
        </tfoot>
    </table>
```
style代码
```
 <style>
        table{
            width: 200px;
            table-layout: auto;
            border-collapse: collapse;
            /* border合并 */
            border-spacing: 0px;
            /* border之间的距离 */
        }
        td,
        th{
            border:1px solid green;
        }
    </style>
```

![效果图](\table.png)
## Form标签
get或post刷新页面
```
<form action="//baidu.com">
      <!-- action=请求的页面 默认使用get 可以用method=post改成用post-->
      <input type="text">
      <!-- 文本框 -->
      <input type="submit" value="提交按钮">
      <!-- 按钮  value提交按钮的提示-->
      <hr>
      <button type="submit">
          <strong>提交按钮</strong>
      </button>
      <hr>
      <!-- button和input的区别，button里面也可以有任何东西标签，input不能有其他标签 -->
      <input type="color">
      <hr>
      <input type="password">
      <!-- 输入的会显示成小黑点 -->
      <hr>
      <input name="gender" type="radio">男
      <input name="gender" type="radio">女
      <input type="submit">
      <!-- 单选 type=radio name要等于同一个name -->
      <hr/>
      <input type="checkbox" name="hobby">唱
      <input type="checkbox" name="hobby">跳
      <input type="checkbox" name="hobby">演
      <!-- 多选框 -->
      <input type="submit">
      <hr>
      <select>
          <option value="1">1</option>
          <option value="2">2</option>
          <option value="3">3</option>
      </select>
      <input type="submit">
      <!-- 下拉选择框 -->
      <hr>
      <input type="file">
      <input type="file" multiple> 
      <input type="submit">
      <!-- 选择文件 multiple可以选择多个文件 -->
      <hr>
      <input type="hidden">
      <!-- 看不见的 -->
      <hr>
      <textarea>
      </textarea>
      <input type="submit">
      <hr>
</form>
```

![效果图](\form.png)

