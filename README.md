# Versatile Bot Project

Shun Tsukamoto

2026-06-27+09

## Introduction

This project aims to share prompt documents that help turn NotebookLM into a versatile bot of the types specified there. NotebookLM, developed and operated by Google, is an AI-powered assistant that specializes in analyzing materials provided beforehand and aligning all outputs with those materials. Nevertheless, once you import a prompt document of your interest in this project to a notebook of yours and add or send one or a few trigger messsage(s), NotebookLM will behave as described in that prompt document.

The Versatile Bot Project currently supports the text chat mode and the Audio Overview mode of NotebookLM. The "Bot" prompt document series is designed to characterize the response pattern of the AI in the text chat mode. The "Episode" prompt document series is designed to provide new usages of and/or modify the conversation style in the Audio Overview mode.

Please note that this is an experimental project. Although I (Shun Tsukamoto) have tested each prompt document several times, I could not fix all unexpected outputs, most of which are those explaining how the AI is responding and/or summarizing that prompt document. These outputs are crucially related to how NotebookLM is expected to work, and therefore appear to be hard to avoid.

## Prompt Documents

This project now consists of the following four prompt documents: three Bot prompt documents and an Episode prompt document.

### Conversational Bot

This prompt document enables you to talk on arbitrary topics to the AI assistant for NotebookLM without adding any sources on those topics.
1. Add the prompt document to the notebook that you want to chat in, and select that in the source list.
2. Having no other materials added to the notebook or selected in the source list (if applicable), apply one of the following settings.
   - Configure the notebook to turn on a custom prompt and add `Behave as a Conversational Bot.` as the custom prompt.
   - Ask `Behave as a Conversational Bot.` in the chat interface, where you will receive an "I will behave as a Conversational Bot from now on." response.
3. Start to talk in the chat interface. You can add or select extra materials. However, I recommend that you add and select only the Conversational Bot prompt document because I cannot guarantee how compatible it is with those extra materials.

### Custom Bot

This prompt document is designed to customize your AI chat experience in NotebookLM with the system messages provided in additional materials.
1. Add the prompt document and the system message material(s) to the notebook that you want to have a custom bot installed in, and select them in the source list.
2. Having no other materials added to the notebook or selected in the source list (if applicable), apply one of the following settings.
   - Configure the notebook to turn on a custom prompt and add `Behave as a Custom Bot.` as the custom prompt.
   - Ask `Behave as a Custom Bot.` in the chat interface, where you will receive an "I will behave as a Custom Bot from now on." response.
3. Start to talk in the chat interface. You can add or select extra materials, but I recommend as few of those as possible because those extra materials may also affect the behavior of the custom bot. In particular, I do not suggest using the prompt document and the Conversational Bot prompt document together.

### Listener Bot

This prompt document turns the chat interface of NotebookLM into an LLM-powered tool that helps you glue fragments of an idea and generate a piece of content based on the idea.
1. Add the prompt document to a notebook of your preference and select that in the source list, where adding or selecting no other materials is highly recommended to avoid ilegally using such a material.
2. Ask `Behave as a Listener Bot.` and start to brainstorm in the chat interface. You can begin the brainstorming either in the message that asks the AI assistant or in one of the next messages, and it should also work to enable the Listener Bot after chatting about something. Regardless of how you proceed with the chat session, you will receive a brief explanation at the time of asking to behave as a Listener Bot.
3. Request in the chat interface to switch to Export Mode if you find the brainstorm completed once and want to generate works that describe or summarize the idea. You will then see a response that discusses how the mode is defined in great detail and what you should do now, which includes the source deselection and selection instructions in order to continue the generation. For a better result, I suggest pursuing a better intermediate output added to the source list (where you need to delete the existing output to redo the step) and sending the AI assistant a detailed prompt about the specifications of the work being generated at the moment.

As you are supposed to include a small amount of information in each message and also usually send at least three messages during an Export Mode cycle, this prompt document is message-demanding more than the other prompt documents. Please be careful about your daily message limit. To save the number of messages that you can send until the limit is reset next time, consider manually proceeding with the content generation step of Export Mode in Studio instead of asking the AI assistant to complete it.

### Chat Episode

The Chat Episode prompt document was originally written before the Audio Overview mode started to cover non-English languages, and is usable in two different approaches. While I have not confirmed whether and how many non-English languages this prompt document works in, I am gradually getting sure that the prompt document can be used at least for Japanese audios generated in the second approach. As for the English language, the prompt document not surely but probably functions in both approaches.

This prompt document allows you to generate live streams on arbitrary topics of your interest with NotebookLM.
1. Add the prompt document to the notebook that you want to set up a live stream in, and select that in the source list.
2. Having no other materials added to the notebook or selected in the source list (if applicable), move to the Audio Overview section, press the Customize button, and generate an audio file with an extra request to follow the instructions stated in the prompt document where the exact file name of the document is specified (e.g., ``Follow the instructions stated in `chat_episode.md` instead of discussing that material itself.``). Between adding only the Chat Episode prompt document and selecting no materials but the prompt document, I personally recommend the former option. Please note that you need not worry too much about the content of the audio file generated here itself as long as it more or less reflects the instructions stated in the prompt document.
3. Once the audio file is generated, move to the Interactive mode and join the episode while playing it. You can ask to talk on specific topics. Moreover, as a nonnative English speaker, I hope that the prompt document helps learners practice English conversation by participating in the same session again and again.

In addition, by specifying your request(s) beforehand, this prompt document may be used to listen to arbitrary conversations with NotebookLM.
1. Proceed with the first and second steps stated above before you generate an audio file.
2. Besides the extra request mentioned above, add your request(s) on the topic(s?) as the listener's (e.g., "The listener is requesting ... ...") when generating an audio file.

## Legal Notices

I have founded this project, written this and the prompt documents, and been maintaining them.

This project is available in the way of content sharing at my discretion and is not based on any contracts or other legal relationships. Please use any of the contributions in the project solely at your own risk. I am not liable for any troubles caused by your use of any content in the project, and I am also not responsible for the quality of each document written for the project.

I retain all copyrights and other relevant rights (like the moral rights) in all documents written for this project. Please do not copy, share, or otherwise use the readme document unless that usage is permitted in the applicable law or in the Github Terms of Service. As for the use of the prompt documents, here are the conditions.
- You are allowed to add the verbatim version of each prompt document to a notebook of yours on NotebookLM to use the feature described in the document for yourself.
- You are allowed to modify each prompt document and add that modified version to a notebook of yours on NotebookLM to use the feature described in that version for yourself.
- I have not determined the policy for the other usages of the prompt documents yet. At the moment, please do not copy, share, or otherwise use them unless that usage is permitted in this section, in the applicable law, or in the Github Terms of Service. I am not planning to permit copying-and-pasting any prompt document in other materials (please instead share the URL of this project).

## Contact

- [My profile on GitHub](https://github.com/shun0t)
- [My profile on LinkedIn](https://www.linkedin.com/in/shuntsukamoto)
- [My profile on X for my AI-related activities](https://x.com/_shun0t)
- [My profile on Facebook for my AI-related activities](https://www.facebook.com/shun0t)
