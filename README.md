# hands-on-camp

## Web3入门技术沙龙分享会实操代码仓库

欢迎参与未来科技开发者论坛的Web3入门技术沙龙分享会。此仓库旨在为参与者提供一个平台，以上传课程相关的实操环节代码。

### 如何参与（如下或者通过网页端操作）

#### 1. Fork 仓库
- 点击本仓库页面右上角的 **Fork** 按钮，这将在你的 GitHub 账户下创建该仓库的一个副本。

#### 2. Clone Fork 到本地
- 在你的 forked 仓库页面，点击 **Code** 按钮，然后复制 URL。
- 在你的本地机器上，打开命令行或终端，运行以下命令：
  ```
  git clone [复制的URL]
  ```

#### 3. 创建新分支
- 进入仓库的目录：
  ```
  cd [仓库名]
  ```
- 创建一个新分支：
  ```
  git checkout -b [新分支名]
  ```

#### 4. 在新分支上做更改
- 进入指定文件夹：
  ```
  cd web3-starter-nft-contracts
  ```
- 根据实践课，在该文件夹下创建合约文件，例如：`example_stone.sol`（为了避免重名，“_”后加名字后缀），使用编辑器或 IDE 对代码进行修改。
- 保存更改。

#### 5. 提交更改
- 添加更改：
  ```
  git add .
  ```
- 提交更改：
  ```
  git commit -m "[提交信息]"
  ```

#### 6. 推送到 GitHub
- 推送你的分支到 GitHub：
  ```
  git push origin [新分支名]
  ```

#### 7. 创建 Pull Request
- 返回到你 fork 的仓库页面。
- 你会看到一个 **New Pull Request** 的提示，点击它。
- 确保基分支是原始仓库你想要合并到的分支，而比较的分支是你的分支。
- 填写 PR 的标题和描述，解释你的更改和为什么你认为它们应该被合并。
- 点击 **Create Pull Request** 按钮。

#### 8. 等待反馈或合并
仓库的维护者可能会查看你的 PR，并给出反馈或直接合并。我们分享现场或之后有反馈或请求更改，你可以在本地进行修改，然后再次提交，并推送到同一分支。这将自动更新你的 PR。
