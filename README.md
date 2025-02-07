# Versatile Bot Project

Shun Tsukamoto

2025-02-08+09

## Introduction

This project aims to share prompt documents that help turn NotebookLM into a versatile bot of the types specified there. Developed and operated by Google, NotebookLM is an AI-powered assistant that specializes in analyzing materials provided beforehand and aligning all outputs with those materials. Nevertheless, once you add a document in this project to a notebook of yours and send a trigger messsage, NotebookLM will behave as a bot described in that added document.

Please note that this is an experimental project. Although I have tested each document several times, I could not fix all unexpected responses, most of which are those summarizing that document or stating thinking processes. These responses are crucially related to how NotebookLM is expected to work and therefore appear to be difficult to avoid.

## Prompt Documents

At the time of writing this readme document, this project consists of the following two prompt documents.

- **Conversational Bot.** This prompt document enables you to chat on general topics with NotebookLM.
  1. Add the document to the notebook that you want to chat in.
  2. Deselecting any other materials in the source list (if applicable), ask to behave as a Conversational Bot (e.g., "Behave as a Conversational Bot").
  3. Making sure that you have received the "I will behave as a Conversational Bot from now on." response, start to chat with the AI. You can select any deselected materials or add extra ones. However, I recommend that you select the Conversational Bot only because I cannot guarantee how compatible it and other materials are.
- **Custom Bot.**  This prompt document turns NotebookLM into a chatbot that can be customized with the system messages provided in additional materials.
  1. Add the document to the notebook that you want to chat in.
  2. Deselecting any other materials in the source list (if applicable), ask to behave as a Custom Bot (e.g., "Behave as a Custom Bot").
  3. Making sure that you have received the "I will behave as a Custom Bot from now on." response, add or select the system message material(s) that you want to apply. You actually do not necessarily need to deselect those materials in the previous step. However, I recommend that you follow these steps to increase the success rate.
  4. Start to talk to the AI.

## Copyright

The project maintainer (Shun Tsukamoto) has written this and the prompt documents, and retains all copyrights (which include the other relevant rights like the moral rights) therein. Please do not copy, share, or otherwise use the readme document unless that usage is permitted in the applicable law or in the Github Terms of Service. As for the use of the prompt documents, here are the conditions.
- You are allowed to add the verbatim version of each prompt document to a notebook of yours on NotebookLM to use the feature described in the document for yourself.
- You are allowed to modify each prompt document and add that modified version to a notebook of yours on NotebookLM to use the feature described in that version for yourself.
- I have not determined the policy for the other usages of the prompt documents yet. At the moment, please do not copy, share, or otherwise use them unless that usage is permitted in this section, in the applicable law, or in the Github Terms of Service. I am not planning to permit copying-and-pasting any prompt document in other materials (please instead share the URL of this project).

## Contact

- [My profile (@shun0t) on GitHub](https://www.github.com/shun0t)
- [My profile on LinkedIn](https://www.linkedin.com/in/shuntsukamoto)
- [My profile on Facebook](https://www.facebook.com/shun0t)
- I also have an account on some other socials.
