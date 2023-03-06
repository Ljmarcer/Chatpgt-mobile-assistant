# Tasker Chat Assistant

This project contains a Tasker task that interacts with the OpenAI GPT-3.5-turbo API to provide a simple chatbot-like experience. The chat assistant is triggered by user voice input and responds with short answers.

*It is recommended to follow all these instructions from the phone itself.*
## Requirements
- Tasker app (https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm)
- OpenAI API key (https://openai.com/docs/authentication/)
- Android device with Google Assistant enabled
- Task turbo_context (https://taskernet.com/shares/?user=AS35m8mZm0JiBySjrKLp6%2Bjxl2n5r6kjOM47Cs0t6O4WDEeX8qkhxBP7jMjj3v2d7pdAWbHD634%3D&id=Task%3Aturbo_context)
- Task SetOpenAI (https://taskernet.com/shares/?user=AS35m8mZm0JiBySjrKLp6%2Bjxl2n5r6kjOM47Cs0t6O4WDEeX8qkhxBP7jMjj3v2d7pdAWbHD634%3D&id=Task%3ASetOpenAI)

## Usage
1. Import the tasks into Tasker.
2. Set your OpenAI API key using the `setOpenAI` task.
3. Run the `turbo_context` task.
4. Talk to the assistant with `[your message]`.
5. The assistant will respond to your message with a short answer obtained from the OpenAI GPT-3.5-turbo(Chat GPT) API. If you want to stop the assistant, say "quit" and the assistant will say a goodbye. The assistant will also stop automatically after 5 interactions on default for not adding so much context.

## Video Demo
Here is a short video demo of the Tasker Chat Assistant in action.

[![Tasker Chat Assistant Demo](https://img.youtube.com/vi/70R2A1C6zXI/0.jpg)](https://www.youtube.com/watch?v=70R2A1C6zXI)

## License
This project is licensed under the MIT License - see the LICENSE file for details.
