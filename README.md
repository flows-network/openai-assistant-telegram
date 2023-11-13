# <p align="center">A Telegram bot for you OpenAI Assistant Applications</p>

<p align="center">
  <a href="https://discord.gg/ccZn9ZMfFf">
    <img src="https://img.shields.io/badge/chat-Discord-7289DA?logo=discord" alt="flows.network Discord">
  </a>
  <a href="https://twitter.com/flows_network">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&amp;logoColor=white" alt="flows.network Twitter">
  </a>
   <a href="https://flows.network/flow/createByTemplate/openai-assistant-telegram">
    <img src="https://img.shields.io/website?up_message=deploy&url=https%3A%2F%2Fflows.network%2Fflow%2Fnew" alt="Create a flow">
  </a>
</p>

[Deploy this function on flows.network](#deploy-your-telegram-bot-in-3-simple-steps), and you will get a Telegram 🤖 to interact with your OpenAI applications based on the Assitant APIs. It helps expand the usage of your Assistants apps and connect the app with your audiences. It's an essential but simple step to make your Assistant apps in production.

## How it works

This flow function (or 🤖) will be triggered when a new message is sent to the Telegram bot. Then, the flow function will create a new thread for this user, call the retrieval API from OpenAI's Assistants, and finally answer the user's questions. The user can also type `/restart` to the bot to create a new thread.

## Deploy your telegram bot in 3 simple steps

1. Create a bot from a template
2. Configure the Configurations

### 0 Prerequisites

Before we start, you need to create an Assistants app with [the OpenAI playground](https://platform.openai.com/assistants). The OpenAI's Assistant basically is a RAG-based LLM agent. You can upload your own knowledge base to customize the Assistant's behavior and make sure the assistant provides correct answers. After that, you can easily see your assistant ID beginning with `asst_` on the dashboard. You will need to bring your own [OpenAI API key](https://openai.com/blog/openai-api). 

You will also need to sign into [flows.network](https://flows.network/) from your GitHub account. It is free.

### 1 Create a bot from a template

[**Just click here**](https://flows.network/flow/createByTemplate/openai-assistant-telegram) to load the template.


### 2 Configure the Configurations


[<img width="450" alt="image" src="https://github.com/flows-network/openai-assistant-telegram/assets/45785633/86ec46bc-a931-4420-918c-cf744471cd1d">](https://github.com/flows-network/openai-assistant-telegram/assets/45785633/86ec46bc-a931-4420-918c-cf744471cd1d)

Review the four configurations.

|Congiguration| Description |
|----|---|
| ASSISTANT_ID | Get the Assistant ID from [the OpenAI Assistants dashboard](https://platform.openai.com/assistants) |
| OPENAI_API_KEY | OpenAI API key|
|telegram_token| Get the Telegram token from @botfather |


Then click on the Create and Build button to continue.

We don't need to set up other SaaS providers here. Click Deploy to finish the deployment.


### Wait for the magic!

This is it! You are now on the flow details page waiting for the flow function to build. As soon as the flow's status becomes `running`, the bot is ready to answer questions from your users! 

<img width="450" alt="image" src="https://github.com/flows-network/openai-assistant-telegram/assets/45785633/84805f7b-a3c5-49fd-bad7-4dbdace07fd6">

If you don't want to use OpenAI to create embeddings for your domain knowledge, please refer to 

* [RAG-embedding](https://github.com/flows-network/demo-RAG-embeddings)
* [RAG-discord](https://github.com/flows-network/demo-RAG-discord-bot)
* [RAG-web-ui](https://github.com/flows-network/demo-RAG-chatbot-web)


