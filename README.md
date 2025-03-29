# Versatile Bot Project

Shun Tsukamoto

2025-03-29+09

## Introduction

This project aims to share prompt documents that help turn NotebookLM into a versatile bot of the types specified there. NotebookLM, developed and operated by Google, is an AI-powered assistant that specializes in analyzing materials provided beforehand and aligning all outputs with those materials. Nevertheless, once you add a prompt document of your interest in this project to a notebook of yours and send one or a few trigger messsage(s), NotebookLM will behave as described in that prompt document.

The Versatile Bot Project supports both main modes of NotebookLM: the text chat mode and the Audio Overview mode. The "Bot" prompt document series is designed to characterize the response pattern of the AI in the text chat mode. The "Episode" prompt document series is designed to provide new usages of and/or modify the conversation style in the Audio Overview mode.

Please note that this is an experimental project. Although I (Shun Tsukamoto) have tested each prompt document several times (except for the Chat Episode one, which I have not sufficiently tested yet), I could not fix all unexpected responses, most of which are those summarizing that prompt document and/or stating thinking processes. These responses are crucially related to how NotebookLM is expected to work, and therefore appear to be difficult to avoid.

## Prompt Documents

This project currently consists of the following three prompt documents: two Bot prompt documents and an Episode prompt document.

### Conversational Bot

This prompt document enables you to talk on general topics with NotebookLM.
1. Add the prompt document to the notebook that you want to chat in.
2. Deselecting any other materials in the source list (if applicable), ask to behave as a Conversational Bot (e.g., *Behave as a Conversational Bot.*).
3. Making sure that you have received the "I will behave as a Conversational Bot from now on." response, start to talk to the AI in the text chat mode. You can select any deselected materials or add extra ones. However, I recommend that you select the Conversational Bot prompt document only because I cannot guarantee how compatible it and other materials are.

### Custom Bot

This prompt document turns NotebookLM into a chatbot that can be customized with the system messages provided in additional materials.
1. Add the prompt document to the notebook that you want to have a custom bot installed in.
2. Deselecting any other materials in the source list (if applicable), ask to behave as a Custom Bot (e.g., *Behave as a Custom Bot.*).
3. Making sure that you have received the "I will behave as a Custom Bot from now on." response, add or select the system message material(s) that you want to apply. You actually do not necessarily need to deselect those materials in the previous step. However, I recommend that you follow these steps to increase the success rate.
4. Start to talk to the AI in the text chat mode.

### Chat Episode

This prompt document allows you to generate live streams on arbitrary topics of your interest with NotebookLM.
1. Add the prompt document to the notebook that you want to set up a live stream in.
2. Deselecting any other materials in the source list (if applicable), move to the Audio Overview section, press the Customize button, and generate an audio file with an extra request to follow the instructions stated in this prompt document (e.g., *Follow the instructions stated in the "Chat Episode" document.*). Although the prompt document might work even if there are other materials included in the source list, I recommend that only the Chat Episode prompt document be added to the notebook. Please note that the audio file generated here itself does not necessarily contain a substantial conversation because the prompt document asks to wait for you to join the episode.
3. Once the audio file is generated, move to the Interactive mode and join the episode while playing it. You can ask to talk on specific topics and/or (hopefully) to speak specific language. Moreover, as a nonnative English speaker, I hope that the prompt document helps learners practice English conversation by participating in the same session again and again.

In addition, by specifying your request(s) beforehand, this prompt document may be used to listen to arbitrary conversations with NotebookLM.
1. Proceed with the first and second steps stated above before you generate an audio file.
2. Besides the extra request mentioned above, add your request(s) on the topic(s?) and/or (hopefully) the language(s?) as the listener's (e.g., *The listener is requesting the AI hosts to ...*) when generating an audio file.

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
- [My profile on Facebook](https://www.facebook.com/shun0t)
- I also have an account on some other socials.
