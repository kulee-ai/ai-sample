[![en](https://img.shields.io/badge/lang-en-blue.svg)](https://github.com/kulee-ai/ai-sample/blob/master/openai/plugin/usage.md)
# 启动项目

使用以下命令安装python依赖：

```
pip install -r requirements.txt
```
使用以下命令来运行插件服务：

```
python app.py
```
当本地服务运行成功以后：

1. 点击 https://chat.openai.com.
2. 在下拉列表中选择"Plugin"选项，需要拥有插件的开放权限
3. 选择"Plugin Store"
4. 选择"Develop your own plugin"
5. 输入 localhost:5002 , 就是本地服务的地址, 然后选择 "Find manifest file".

现在插件应该已经可以使用了! 你可以尝试发送 "我的todo列表有什么？" 然后添加自己的todo信息了!

# 帮助

以上文档（英文版）来自于官方仓库 [OpenAi-QuickStart](https://github.com/openai/plugins-quickstart)

如果有任何问题，可以提交 [issue](https://github.com/kulee-ai/ai-sample/issues) 或者查看OpenAi [官方开发文档](https://platform.openai.com/docs/plugins/introduction).