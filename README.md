csharp
====

**http://www.ipip.net/** ,专业IP识别网站

17mon IP库解析代码

##基本用法
```csharp

IP.EnableFileWatch = true; // 默认值为：false，如果为true将会检查ip库文件的变化自动reload数据

IP.Load("IP库本地绝对路径");

IP.Find("8.8.8.8");//返回字符串数组["GOOGLE","GOOGLE"]

```

IPExt的用法与IP的用法相同，只是用来解析datx格式文件。
