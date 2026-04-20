# 我的第一个自动化测试项目 (Selenium + Python)

这是一个使用 Selenium WebDriver 和 pytest 框架，对 React 示例项目进行自动化测试的实战练习。

## 测试对象

一个运行在 `http://localhost:3000` 的 React 应用，主要包含：
- 一个可点击并计数的按钮
- 一个可跳转的链接
- 页面标题和 Logo 的验证

## 测试覆盖的功能点

- ✅ 验证页面标题是否为 "React App"
- ✅ 验证链接文字是否为 "我的第一个测试项目"
- ✅ 验证计数器按钮：点击 3 次后，显示数字是否为 3
- ✅ 验证 Logo 图片是否存在且可见
- ✅ 验证点击链接后是否能正确打开新窗口

## 环境准备

1.  **确保你有 Python 3.7+** 环境
2.  **安装依赖**：在项目根目录下打开终端，运行：
    ```bash
    pip install -r requirements.txt
3.  启动被测应用：
    克隆 React 项目并启动
    确保 http://localhost:3000 可以正常访问
