# Setup

To install the required packages for this plugin, run the following command:

```
pip install -r requirements.txt
```
To run the plugin, enter the following command:

```
python app.py
```
Once the local server is running:

1. Navigate to https://chat.openai.com.
2. In the Model drop down, select "Plugins" (note, if you don't see it there, you don't have access yet).
3. Select "Plugin store"
4. Select "Develop your own plugin"
5. Enter in localhost:5002 since this is the URL the server is running on locally, then select "Find manifest file".

The plugin should now be installed and enabled! You can start with a question like "What is on my todo list" and then try adding something to it as well!

# Getting Help

All above is a copied document from [OpenAi-QuickStart](https://github.com/openai/plugins-quickstart)

If there are any questions, you can raise an [issue](https://github.com/kulee-ai/ai-sample/issues) or refer to the [official documentation](https://platform.openai.com/docs/plugins/introduction).