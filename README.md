# 荆棘鸟文学社美编参考文档
[![GitHub commit activity](https://img.shields.io/github/commit-activity/t/szhhwh/jingji_LayoutTutorial?style=flat-square)](https://github.com/szhhwh/jingji_LayoutTutorial) [![GitHub Repo stars](https://img.shields.io/github/stars/szhhwh/jingji_LayoutTutorial?style=flat-square)](https://github.com/szhhwh/jingji_LayoutTutorial)
## 本书目录 Menu

- [ChapterNo1 美编的开始](src/ChapterNo1/README.md)
    - [荆棘鸟文学社美编标准](src/ChapterNo1/1.1.md)
    - [前期准备](src/ChapterNo1/1.2.md)
- [ChapterNo2 排版的基本知识](src/ChapterNo2/README.md)
    - [文字基本属性](src/ChapterNo2/2.1.md)
    - [文字排版及规范](src/ChapterNo2/2.2.md)
    - [特殊文字效果](src/ChapterNo2/2.3.md)
- [ChapterNo3 InDesign软件](src/ChapterNo3/README.md)
    - [安装和新建文档](src/ChapterNo3/3.1.md)
    - [新建文本框和页面管理](src/ChapterNo3/3.2.md)
    - [图层和参考线的使用](src/ChapterNo3/3.3.md)
    - [其他常用功能](src/ChapterNo3/3.4.md)
- [ChapterNo4 图片处理](src/ChapterNo4/README.md)
    - [搜寻图片素材](src/ChapterNo4/4.1.md)
    - [图片的存储原理和格式转换](src/ChapterNo4/4.2.md)
    - [修缮图片](src/ChapterNo4/4.3.md)
- [ChapterNo5 素材管理](/src/ChapterNo5/README.md)
    - [字体管理](src/ChapterNo5/5.1.md)
    - [素材管理](src/ChapterNo5/5.2.md)
- [ChapterNo6 大功告成](src/ChapterNo6/README.md)
    - [上交排版作品](src/ChapterNo6/6.1.md)
    - [汇总排版](src/ChapterNo6/6.2.md)
    - [出刊的其他注意事项](src/ChapterNo6/6.3.md)

## 构建 Build
- 安装 **mdbook**
```shell
cargo install mdbook
```
- 构建
```shell
mdbook build
```
- 通过 HTTP 在 `localhost:3000` 提供预览服务
```shell
mdbook serve --open
```
> [mdbook 官方参考文档](https://rust-lang.github.io/mdBook/index.html)
## 更新日志 Update log
### v0.2.1 Latest
New
- 4.1 新增 使用搜索引擎搜寻图片素材
- 4.2 调整 内容顺序；修改部分内容
- 4.3 新增 去除图片背景
### v0.2.0
New
- 更新 6.2 排版汇总
- 更新 6.3 出刊的其他注意事项

Fixed
- 修复carbin块的显示问题
- 许多细节优化

### v0.1.2
Fixed
- 部分链接不能点击的问题
- 添加了分页标题
- 修复carbin块的显示问题

New
- 更新 4.2 图片的存储原理和格式转换
- 更新 3.3 图层和参考线的使用

Other
- 非常多的细节修复
- 放弃使用obsidian作为编辑器

### v0.1.0
- 从gitbook迁移到mdbook

### v0.0.1
- 使用gitbook新建项目