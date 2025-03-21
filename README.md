# 单纯形法演示程序（随机生成实例）

本项目实现了一个随机生成线性规划问题的单纯形法演示程序，支持手动迭代和最优解判断。程序通过网页交互的方式帮助用户理解单纯形法的迭代过程。

## 文件说明

### `simplexmin17.html`
- **功能**：实现了一个随机生成线性规划问题的单纯形法演示程序。
- **特点**：
  - 随机生成问题实例，确保至少有一个负检验数。
  - 支持分数形式的数值显示。
  - 显示迭代前和迭代后的单纯形表。
  - 在达到最优解时，先显示最终表格，再弹出提示窗口。

## 使用说明 

1. **生成新问题**：
   - 点击“生成新问题”按钮，程序将随机生成一个新的线性规划问题实例。

2. **确定入基和出基变量**：
   - 查看初始单纯形表，确定入基变量（最小负检验数对应的列）。
   - 根据最小比值规则确定出基变量。

3. **执行迭代**：
   - 输入入基和出基变量后，点击“执行迭代”按钮，程序将展示迭代后的单纯形表。

4. **最优解判断**：
   - 如果所有检验数非负，程序将提示已达到最优解。

## 运行方式

1. 将 `simplexmin17.html` 文件下载到本地。
2. 使用浏览器打开文件即可运行程序。

## 依赖

- 本程序为纯 HTML 和 JavaScript 实现，无需额外依赖。

## 贡献

欢迎提交 Issue 或 Pull Request 来改进代码或文档。

## 许可证

本项目采用 [MIT 许可证](LICENSE)。
