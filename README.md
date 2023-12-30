# My Blog

> Start at 2022.11.19 23:45

**Link:** [https://benn314.github.io/](https://benn314.github.io/)

### Common Instruction

- `hexo clean` 清除 `public` 静态目录
- `hexo s` 本地启动默认指定 `4000` 端口预览
- `hexo g` 生成 `public` 静态目录
- `hexo d` 部署
- 
- `hexo new post “文章名”` 新建文章
- `hexo new page “菜单页面名”` 新建菜单页

<br />

站点Site基于Hexo-next搭建，搭建教学 [请戳这里👈](https://juejin.cn/post/7169115268944560135)


### Todo

- [x] warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it
- [x] 图片预览
- [ ] 开发 Short 时刻
  - [x] 将 Short 分类改为标签
- [x] 全局懒加载（<u>如果加载速度足够快，是不用占位符的</u>）
  - [ ] 懒加载占位符（不然容易造成页面抖动和用户等待加载体验不好，渐进式图片懒加载和占位gif，选个）
  - [ ] 图片 or 网站全局CDN加速（又拍云），线上环境预览文章，图片显示体验效果太差了！
    - 使用又拍云，网站域名需要先备案（ICP服务码 100/个）
  - [x] 更改为 cloudflare CDN 加速（无需备案），更改为 cloudflare  CDN后感觉变快了（需要到network测试一下数据才对）
- [x] 鼠标光标样式定制
- [x] Hexo 图片圆角样式修改
- [x] Waline评论系统样式优化
- [x] 移除 post 页面的光标样式和点击样式
- [ ] 通过SEO搜索发现，博客目前没有被谷歌和百度站点收录，需要去注册申请上传站点
- [ ] 修改 a标签的文字颜色（正常和hover都修改），区分正文颜色内容（style.styl）
- [ ] 自定义个人博客主页（[参考链接🔗](https://codepen.io/jcoulterdesign/pen/MwVbjY)）

---

- [ ] 博客从 Hexo 迁移至 <u>xLog or jekyll or cards</u>
