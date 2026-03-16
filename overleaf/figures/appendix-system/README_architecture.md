# 整体架构图

`architecture.mmd` 为 Mermaid 源文件，需导出为 PNG 后论文才能正常编译。

## 生成 architecture.png

**方式一：在线**  
打开 [Mermaid Live Editor](https://mermaid.live)，将 `architecture.mmd` 内容粘贴进去，导出 PNG，保存为 `architecture.png` 放在本目录。

**方式二：命令行**（需已安装 Node.js）  
```bash
cd docs/thesis_template/figures
npx -y @mermaid-js/mermaid-cli mmdc -i architecture.mmd -o architecture.png
```

生成完成后，在模板目录执行 `xelatex main.tex` 即可在论文中看到架构图。
