### 中文版 README.md

# VS Code Blame Inline 插件

## 插件简介

该插件为 VS Code 提供了类似 WebStorm 的 "Annotate with Git Blame" 功能。在编辑器右侧显示每行代码的 Git 提交记录（包括提交哈希、作者和日期），并支持悬停复制和右键菜单操作。

## 功能特点

- **内联显示 Git 提交记录**：在代码每行左侧显示提交信息。
- **支持悬停复制**：鼠标悬停可查看详情，点击复制。
- **多仓库支持**：支持 monorepo 等多仓库工作区，自动识别文件所属仓库。
- **右键菜单**：提供显示、隐藏、复制等快捷操作。

## 使用方法

1. 右键代码文件，选择 **Show Blame Inline** 显示内联注解。
2. 鼠标悬停到代码行可查看详情和复制。
3. 右键选择 **Hide Blame Inline** 隐藏注解。
4. 右键选择 **Copy Blame Text** 复制当前行 Blame 信息。

## 安装

1. 下载 `.vsix` 文件
2. 在 VS Code 中按 `Ctrl+Shift+P`，输入 `Extensions: Install from VSIX...`
3. 选择下载的 `.vsix` 文件

---

### English README.md

# VS Code Blame Inline Extension

## Introduction

This extension brings WebStorm's "Annotate with Git Blame" feature to VS Code. It displays Git commit information (commit hash, author, and date) inline next to each line of code in the editor.

## Features

- **Inline Git Blame**: Shows commit info on the left side of each code line.
- **Hover to Copy**: Hover over a line to view details and copy.
- **Multi-Repository Support**: Automatically detects which repository a file belongs to in monorepo workspaces.
- **Context Menu**: Quick access to show, hide, and copy actions.

## Usage

1. Right-click in a code file and select **Show Blame Inline** to display annotations.
2. Hover over any line to view details and copy the blame info.
3. Right-click and select **Hide Blame Inline** to hide annotations.
4. Right-click and select **Copy Blame Text** to copy the current line's blame info.

## Installation

1. Download the `.vsix` file
2. In VS Code, press `Ctrl+Shift+P` and type `Extensions: Install from VSIX...`
3. Select the downloaded `.vsix` file
