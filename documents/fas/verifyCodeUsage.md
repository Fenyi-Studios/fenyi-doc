<fenyi-document-header>
    <title>验证码使用教程</title>
    <tags>
        <tag>fas</tag>
        <tag>tutorial</tag>
    </tags>
    <category>fas</category>
    <time>1753053660</time>
    <author>
        <name>Fenyi Studios</name>
        <link>https://www.github.com/Fenyi-Studios/</link>
    </author>
</fenyi-document-header>

## 表格式验证码

![一个表格式验证码的示例](/images/verifycode-example-1.jpg)  
如上图所示，这是一个表格式验证码，内容包括一个表格和一个提示语，将两个信息提取出来后，即可完成验证。这里我们可以知道，提示语是 `请将该表格“GAMMA 列 EPSILON 行”的数据写在下方` ，表格是下方的这张表格，那么我们找到 `GAMMA` 列，再找到该列中属于 `EPSILON` 行的数据，填入框中即可，这张图的验证码也就是 `岳麓山` 。  
||DELTA|BETA|ALPHA|GAMMA|
|--|--|--|--|--|
|ETA|辽宁省|西藏自治区|湖南省|贵阳市|
|THETA|太原市|阿里山|哈尔滨市|重庆市|
|EPSILON|故宫博物院|广东省|江苏省|岳麓山|
|ZETA|澳门特别行政区|台湾省|贵阳市|广东省|
