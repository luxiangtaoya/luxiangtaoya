# GitHub个人主页README文件（带详细注释）

<!-- 头部欢迎语部分 -->
### Hey <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">，I'm An Zhihe
<!-- 动态GIF表情，宽度25像素 -->

<!-- Feedly订阅数动态徽章 -->
![](https://img.shields.io/badge/dynamic/json?color=2bb24c&label=Feedly%20RSS&query=%24.data.totalSubs&url=https%3A%2F%2Fapi.spencerwoo.com%2Fsubstats%2F%3Fsource%3Dfeedly%26queryKey%3Dhttps%3A%2F%2Fchegva.com%2Ffeed%2F&logo=feedly)
<!-- 
  颜色：2bb24c(绿色)
  标签：Feedly RSS 
  数据源：通过API获取订阅数
  徽章图标：Feedly logo
-->

<!-- 个人信息表格开始 -->
<table>
<tr>
<!-- 左侧栏：文字信息 -->
<td valign="top" width="50%">

<!-- 个人信息列表 -->
- 🤖 I'm currently a SRE working in Beijing, China.  <!-- 当前职业：SRE(站点可靠性工程师) -->
- 👨‍💻 I'm currently learning Golang, Python, Devops, Cloud Native, JS & TS、Vue、React，etc... <!-- 正在学习的技术栈 -->
- ✍️ [MyBlog](https://chegva.com)  <!-- 个人博客链接 -->
- 💬 Ask me about Anything you want~  <!-- 欢迎提问 -->
- 📫 Reach me: [email](mailto:anzhihe@foxmail.com)  <!-- 联系邮箱 -->
- 👏 Follow Me: [![](https://img.shields.io/github/followers/anzhihe?label=follow%20me&style=social)](https://github.com/anzhihe/) <!-- GitHub关注按钮 -->
- 🎣 Fun fact: Reading, poetry, watching movies, traveling, exercising, thinking, sunbathing, minimalist <!-- 兴趣爱好 -->

**「Stay hungry，Stay foolish.」** ❤️  <!-- 座右铭 -->
</td>

<!-- 右侧栏：动态图片 -->
<td valign="center" width="100%" height="100%">
<img src="https://github.com/anzhihe/anzhihe/blob/main/.github/workflows/Le%20Petit%20Prince.gif" width="500" height="300">
<!-- 《小王子》主题GIF动图 -->
</td>
</tr>
</table>

<hr/>  <!-- 分隔线 -->

<!-- GitHub统计部分 -->
🏆 **my github stats:**  <!-- 统计标题 -->

<!-- 统计卡片布局 -->
|![](https://github-readme-stats.vercel.app/api?username=anzhihe)|![Anzhihe's Most used languages](https://github-readme-stats.vercel.app/api/top-langs/?username=anzhihe&layout=compact&hide_border=true&langs_count=10)|
|-|-|
<!-- 
  左侧：GitHub总体统计卡片
  右侧：最常用语言统计卡片(紧凑布局，隐藏边框，显示前10种语言)
-->

<!-- 底部内容表格 -->
<table>
<tr>
<!-- 左侧：贡献日历蛇形图 -->
<td valign="top" width="50%">

#### 🐍 contributions  <!-- 贡献图标题 -->
![](https://raw.githubusercontent.com/anzhihe/anzhihe/output/github-contribution-grid-snake.svg)
<!-- GitHub贡献日历的蛇形可视化图 -->
</td>

<!-- 右侧：最新博客文章 -->
<td valign="top" width="50%">

#### 👉 [Recent Blog](https://chegva.com)  <!-- 博客链接 -->

{{ range $index, $item := $.Articles }}  <!-- 动态生成博客列表(需要后端支持) -->
- [{{$item.Title}} - {{$item.PublishedParsed.Local.Format "2006-01-02"}}]({{$item.Link}})
{{- end}}
</td>
</tr>
</table>

<!-- 
  技术说明：
  1. 使用GitHub Flavored Markdown语法
  2. 动态徽章通过shields.io生成
  3. 统计卡片使用github-readme-stats服务
  4. 蛇形贡献图是GitHub自动生成的SVG
  5. 博客列表需要配合后端API动态生成
-->
