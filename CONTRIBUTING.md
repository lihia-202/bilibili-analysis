# Contributing
提交代码的规范。

## File Structure
`src/`目录放所有的代码，生成的数据用 `.csv` 格式保存在 `data/`文件夹中。

最终 presentaion 拟用 jupyter 的 Slideshow 模式（无他，除非你想把 可视化的内容挨个截图放到 PowerPoint 里），当然也可以其他形式。保存在 `pre/`目录。

可能需要的图片保存在`img/`里。

最终的实验报告不呈现在项目文档中，单独保存。

## Branch
`master` 放 release 版本，`dev` 放开发版本，每个功能分别新建分支，然后合并到 `dev`（当然可能比较麻烦，但至少别全扔master...）

## Coding Style
- python: pep8 格式

## Commit
说明白干了什么，解决了什么。最好说清楚还有哪些已知问题。