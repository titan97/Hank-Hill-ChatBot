# Hank-Hill-ChatBot
Discord ChatBot that imitates Hank Hill from King of the Hill.
This model was trained on DialoGPT-small with 12 epochs on Google Colab.

## Usage
The inference API for this chatbot is available on my HuggingFace[profile](#%20Hank-Hill-ChatBot%20Discord%20ChatBot%20that%20imitates%20Hank%20Hill%20from%20King%20of%20the%20Hill%20%20##%20Usage%20The%20inference%20API%20for%20this%20chatbot%20is%20available%20on%20https://huggingface.co/tngo/DialoGPT-small-HankHill).

The server for the Discord ChatBot was hosted on Replit.com and the dependencies can be found in package.json.
This application requires a Discord API key and a HuggingFace API key to serve the intended Discord server and get a response from the model.
The chatbot is currently not shipped as a publicly available discord bot, but can used on a private server running your own bot.

## Example Conversation

![](https://github.com/titan97/Hank-Hill-ChatBot/blob/main/Screenshot%202022-10-04%20142230.png)

## Notes

Occasionally the chatbot just responds with just multiple '!' characters. The chatbot frequently responds with "I'm not your buddy, pal" to uncomfortable/strange prompts/messages. This has to do with how the model was trained and the device from which the inference is obtained (CPU or GPU, where GPU is preferred). I plan on training it on a bigger model such as DialoGPT-medium and perform more hyperparameter tuning to reduce overfitting.
