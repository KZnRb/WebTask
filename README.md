## Web homework

### 北大培文晋中实验学校 ①

- 注册页面 ① register.html

1. 学校位置

   - 榆次 ① ycHomepage.html √

     1. 总体介绍
        - 更多: 文字 ① ycIntroduction.html √
     2. 历史沿革
        - 更多: 文字 ① ycEvolution.html √
     3. 行政区划
        - 更多 : 文字 ① ycDivisions.html
     4. 城市荣誉
        - 更多 : 视频 ① ycHonor.html √
     5. 查看更多内容
        - 自然资源：文字 ① ycNature.html √

2. 学校简介

   - 更多 ①
     1. 办学目标
     2. 校风
     3. 教风
        - 更多 : 优秀教师 ①
     4. 学风
     5. 学校使命
     6. 交流平台
     7. 学校文化
        - 更多 : 校歌 ① schSong.html √

3. 设施设备

4. 学部介绍

   1. 小学部 ①
   2. 初中部 ①
   3. 高中部 ①
   4. 国际交流中心 ①

5. 学校社团

6. 学校环境
   - 更多 : 图片 ①

## 学习的内容梳理

### 第一章 初识 HTML

#### 未写的：

- `<a href="跳转目标" target="目标窗口的弹出方式">文本或图像</a>`
  - 在上面的语法中，<a>标记是一个行内标记，用于定义超链接，href 和 target 为其常用属性，具体解释如下：
    > href：用于指定链接目标的 url 地址，当为`<a>`标记应用 href 属性时，它就具有了超链接的功能。
    >
    > target：用于指定链接页面的打开方式，其取值有\_self 和\_blank 两种，
    > 其中\_self 为默认值，意为在原窗口中打开，\_blank 为在新窗口中打开

### 第二章 HTML 页面元素和属性

#### 未写的(不全)：

- 很多，很烦

- article

  > article 元素代表文档、页
  > 面或者应用程序中与上下文不
  > 相关的独立部分，该元素经常
  > 被用于定义一篇日志、一条新
  > 闻或用户评论等。article 元素
  > 通常使用多个 section 元素进行
  > 划分，一个页面中 article 元素
  > 可以出现多次。

  ```
    <article>
      <header>
        <h2>第一章</h2>
      </header>
      <section>
        <header>
          <h2>第1节</h2>
        </header>
      </section>
      <section>
        <header>
          <h2>第2节</h2>
        </header>
      </section>
    </article>
    <article>
      <header>
        <h2>第二章</h2>
      </header>
    </article>
  ```

- aside

  > aside 元素用来定义当前页面或者文
  > 章的附属信息部分，它可以包含与当前页
  > 面或主要内容相关的引用、侧边栏、广告
  > 、导航条等其他类似的有别于主要内容的
  > 部分。
  > aside 元素的用法主要分为两种：
  > • 被包含在 article 元素内作为主要
  > 内容的附属信息。
  > • 在 article 元素之外使用，作为页
  > 面或站点全局的附属信息部分。

  ```
    <article>
      <header>
        <h1>标题</h1>
      </header>
      <section>主要内容</section>
      <aside>相关文章</aside>
    </article>
    <aside>右侧菜单</aside>
  ```

- section

  > section 元素用于对网站或应用程序中页面上的内容进行分块，一个 section 元素通常由内 容和标题组成。习惯上，在使用 section 元素时，
  >
  > - 不要将 section 元素用作设置样式的页面容器，那是 div 的特性。section 元素并非一个普通的容器元素，当一个容器需要被直接定义样式或通过脚本定义行为时，推荐使用 div。
  > - 如果 article 元素、aside 元素或 nav 元素更符合使用条件，那么不要使用 section 元素。
  > - 没有标题的内容区块不要使用 section 元素定义。

- footer
  > footer 元素用于定义一个页面或者区域的底部，它可以包含所有通常放在页面底部的内容。在 HTML5 出现之前，一般使用`<div id=“footer”></div>`标记来定义页面底部，而现在通过 HTML5 的 footer 元素可以轻松实现

### 第三章 CSS 入门 √

### 第四章 CSS3 选择器 √

### 第五章 盒子模型

- CSS3 渐变属性（教的样式很丑）

### 第六章 浮动与定位 √

- 清除浮动

### 第七章 表单的应用（可以整三页）

- 注册
- 登录
- 个人主页

### 第八章 多媒体技术

- 表格
  - 用途：
    1. 排列数据，用来呈现数据间的关系；
    2. 网页布局（已过时）

### 第九章 CSS3 高级应用
