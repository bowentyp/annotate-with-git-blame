# Welcome to your VS Code Extension

## What's in the folder

* This folder contains all of the files necessary for your extension.
* `package.json` - this is the manifest file in which you declare your extension and command.
  * The sample plugin registers a command and defines its title and command name. With this information VS Code can show the command in the command palette. It doesn’t yet need to load the plugin.
* `src/extension.ts` - this is the main file where you will provide the implementation of your command.
  * The file exports one function, `activate`, which is called the very first time your extension is activated (in this case by executing the command). Inside the `activate` function we call `registerCommand`.
  * We pass the function containing the implementation of the command as the second parameter to `registerCommand`.

## Setup

* install the recommended extensions (amodio.tsl-problem-matcher, ms-vscode.extension-test-runner, and dbaeumer.vscode-eslint)


## Get up and running straight away

* Press `F5` to open a new window with your extension loaded.
* Run your command from the command palette by pressing (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac) and typing `Hello World`.
* Set breakpoints in your code inside `src/extension.ts` to debug your extension.
* Find output from your extension in the debug console.

## Make changes

* You can relaunch the extension from the debug toolbar after changing code in `src/extension.ts`.
* You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes.


## Explore the API

* You can open the full set of our API when you open the file `node_modules/@types/vscode/index.d.ts`.

## Run tests

* Install the [Extension Test Runner](https://marketplace.visualstudio.com/items?itemName=ms-vscode.extension-test-runner)
* Run the "watch" task via the **Tasks: Run Task** command. Make sure this is running, or tests might not be discovered.
* Open the Testing view from the activity bar and click the Run Test" button, or use the hotkey `Ctrl/Cmd + ; A`
* See the output of the test result in the Test Results view.
* Make changes to `src/test/extension.test.ts` or create new test files inside the `test` folder.
  * The provided test runner will only consider files matching the name pattern `**.test.ts`.
  * You can create folders inside the `test` folder to structure your tests any way you want.

## Go further

* Reduce the extension size and improve the startup time by [bundling your extension](https://code.visualstudio.com/api/working-with-extensions/bundling-extension).
* [Publish your extension](https://code.visualstudio.com/api/working-with-extensions/publishing-extension) on the VS Code extension marketplace.
* Automate builds by setting up [Continuous Integration](https://code.visualstudio.com/api/working-with-extensions/continuous-integration).

---

## 中文翻译

## 欢迎使用您的 VS Code 扩展

### 文件夹内容

* 此文件夹包含您的扩展所需的所有文件。
* `package.json` - 这是声明您的扩展和命令的清单文件。
  * 示例插件注册了一个命令并定义了其标题和命令名称。通过这些信息，VS Code 可以在命令面板中显示该命令。此时还不需要加载插件。
* `src/extension.ts` - 这是您将提供命令实现的主文件。
  * 该文件导出一个函数 `activate`，在您的扩展首次激活时调用（在本例中通过执行命令激活）。在 `activate` 函数中，我们调用 `registerCommand`。
  * 我们将包含命令实现的函数作为第二个参数传递给 `registerCommand`。

### 设置

* 安装推荐的扩展（amodio.tsl-problem-matcher、ms-vscode.extension-test-runner 和 dbaeumer.vscode-eslint）

### 立即开始

* 按 `F5` 打开一个加载了您的扩展的新窗口。
* 通过按 `Ctrl+Shift+P`（Mac 上为 `Cmd+Shift+P`）并在命令面板中输入 `Hello World` 来运行您的命令。
* 在 `src/extension.ts` 中的代码上设置断点以调试您的扩展。
* 在调试控制台中查看扩展的输出。

### 修改代码

* 更改 `src/extension.ts` 中的代码后，可以从调试工具栏重新启动扩展。
* 更改代码后，您也可以重新加载（Mac 上按 `Ctrl+R` 或 `Cmd+R`）VS Code 窗口以加载您的更改。

### 探索 API

* 打开文件 `node_modules/@types/vscode/index.d.ts` 可以查看完整的 API。

### 运行测试

* 安装 [Extension Test Runner](https://marketplace.visualstudio.com/items?itemName=ms-vscode.extension-test-runner)
* 通过 **Tasks: Run Task** 命令运行 "watch" 任务。确保此任务正在运行，否则测试可能无法被发现。
* 从活动栏打开测试视图并点击 "Run Test" 按钮，或使用快捷键 `Ctrl/Cmd + ; A`
* 在测试结果视图中查看测试输出。
* 修改 `src/test/extension.test.ts` 或在 `test` 文件夹内创建新的测试文件。
  * 提供的测试运行器只会考虑匹配名称模式 `**.test.ts` 的文件。
  * 您可以在 `test` 文件夹内创建子文件夹，以任意方式组织您的测试。

### 更进一步

* 通过 [打包您的扩展](https://code.visualstudio.com/api/working-with-extensions/bundling-extension) 来减小扩展体积并提高启动速度。
* 在 VS Code 扩展市场上 [发布您的扩展](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)。
* 通过设置 [持续集成](https://code.visualstudio.com/api/working-with-extensions/continuous-integration) 来自动化构建。
