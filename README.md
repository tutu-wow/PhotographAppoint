# PhotographAppoint
写真馆预约管理系统

所有源码均本人开发，项目是前后端分离的，所有的项目都具备了完整的业务逻辑，不仅仅局限于基础的增删改查（CRUD）操作，系统亮点众多。

本文注重于计算机毕业设计选题指导，列出题目均有源码， 大家可以去【公众号】(毕业终点站)获取或者加我【qq】(2112698948)提意见(别忘记Star哟)。备注：git

声明：仅用于学习使用，请勿用于任何商业行为！

1.系统非商用，非开源，非无偿。

2.由本人开发，如需源码，请联系以下方式，qq:2112698948。

3.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。

<font style="color:#117CEE;">🎈</font><font style="color:#117CEE;">系统亮点：邮箱通知、WebSocket及时通讯、协同过滤算法、Echarts图形化分析；</font>

# <font style="color:rgb(72, 179, 120);">一.系统开发工具与环境搭建</font>
## <font style="color:rgb(38, 38, 38);">1.系统设计开发工具</font>
<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">前后端分离</font>

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">项目架构：B/S架构  
</font><font style="color:rgb(38, 38, 38);">运行环境：win10/win11、jdk17</font>

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">前端：</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">技术：框架Vue.js；UI库：ElementUI； </font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">开发工具：Visual Studio Code；</font>

---

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">后端:</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">技术：Java语言、mybatis plus、Spring boot框架； </font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">开发工具：IDEA 2023.3.3版本；</font>

---

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">数据库：</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">数据库：mysql5.7/8.0 </font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">数据库工具：Navicat12版本；</font>

---

# <font style="color:rgb(72, 179, 120);">二.系统实现(部分截图)</font>
## 2.1 用户
### 2.1.1首页
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259728366-ecdb8979-55f7-4be4-ba2c-ba8621b5c0c1.png)

### 2.1.2 摄影项目
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259733381-124258c7-6aab-4042-b6af-3df66570d4c3.png)

### 2.1.3 摄影服务详情
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259737689-e3ede139-0d8f-473b-8fa4-7c7443a5cd78.png)

### 2.1.4 预约
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259743203-a66b928e-a8ec-4fa0-bf48-1b5503523bfe.png)

### 2.1.5 我的订单
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259747905-6826963d-62bc-4ff1-a97b-af9ed1e2aa3e.png)

### 2.1.6 摄影写真交流（协同过滤算法推荐话题）
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259757288-d3855103-a062-407c-aa5f-875b40b9f6a5.png)

### 2.1.7 话题详情
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259760287-f2578fed-abb5-4e84-899a-eb242081c356.png)

### 2.1.8 聊天会话
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259763304-c2fd56ca-7647-4d92-930b-9d0f5eee6361.png)

### 2.1.9 关于我们
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259768420-d69414ed-0ea0-41db-8c40-facc86e09cc9.png)

### 2.1.10 我的反馈
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259777209-5ec89a8f-f0fb-45c3-8d64-f6d88fcc2fba.png)

## 2.2 管理员
### 2.2.1 用户管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259782087-f18964d3-0162-4d2e-af2b-2cc75b4effd3.png)

### 2.2.2 消息通知
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259788963-fd6184c8-b350-4444-b70d-428ddd443a08.png)

### 2.2.3接待中心
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259792210-3f4fedee-816b-42f9-93f1-0f6820cd8118.png)

### 2.2.4 留言反馈
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259795343-4fe98765-b4b9-4f04-83f9-bdb34a5f8c1f.png)

### 2.2.5 作品管理
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259798203-f8e7cb32-eccd-42a8-a375-e3ea6979a7b7.png)

### 2.2.6 摄影项目
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259800851-356fa42c-1065-4c0b-b816-072b53f44472.png)

### 2.2.7 摄影项目配置
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259803460-466dfc64-1403-4bac-b6e3-f528862a0bfa.png)

### 2.2.8 摄影预约订单
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259806098-2c38e1af-4ecd-47b0-927c-b77984935fc0.png)

### 2.2.9 话题信息
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259808800-82a8fb4f-3223-42cf-a834-004af29574b9.png)

### 2.2.10 文章信息
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259811687-a70985a6-6ee1-4899-b125-053472aee17a.png)

### 2.2.11 图形化分析
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259814488-e79205c1-29ef-4b77-9ef9-cc89ec7eee3a.png)

# <font style="color:rgb(72, 179, 120);">三.系统代码结构截图</font>
## 3.1 前端
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259821484-c74dc3f0-41c0-4e81-8d98-4aaa942448c8.png)

## 3.2 后端
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259823804-fa052182-e5df-49a1-9fc0-bb6f7f8410ca.png)

## 3.3 数据库
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/45326128/1781259826227-cc82e9e0-7417-421c-8ab4-3cbfdcfabf55.png)

## <font style="color:rgb(79, 79, 79);">四.系统代码获取</font>
<font style="color:rgb(77, 77, 77);">1.系统非商用，非开源，非无偿。</font>

<font style="color:rgb(77, 77, 77);">2.由本人开发，如需源码，请后台直接联系我。</font>

<font style="color:rgb(77, 77, 77);">3.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。</font>

