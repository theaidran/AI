# Make me a summary text generation for Google Colab

This notebook uses [https://github.com/oobabooga/text-generation-webui](https://github.com/oobabooga/text-generation-webui)

▶⏩Run all the cells and a URL will appear at the bottom in around 5 minutes.🤞🐱‍👤 

Then, from the last cell choose the .txt file to be summarized and click the "Make summary" button.
Summarization will be automatically saved to your browser downloads directory.
The summary file will also be available in Colab /content directory.

On a free account, it is relatively slow and takes about 1 minute of work for 1k input words.
So in the case of 30k words, it will take about 30 minutes for summarization.

| Colab | Info
| --- | --- |
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/theaidran/AI/blob/main/make_me_summary_ui_4bit_textgen_gdrive.ipynb) | make_me_summary_ui_colab

## Parameters

* **save_logs_to_google_drive**: saves your chat logs, characters, and softprompts to Google Drive automatically, so that they will persist across sessions.
* **text_streaming**: streams the text output in real time instead of waiting for the full response to be completed.
* **load_in_8bit**: loads the model with 8-bit precision, reducing the GPU memory usage by half. This allows you to use the full 2048 prompt length without running out of memory, at a small accuracy and speed cost.
* **chat_language**: if different than English, activates automatic translation using Google Translate, allowing you to communicate with the bot in a different language.

## Updates
* Support of simple UI for testing LLMs. You can run a link within Colab's external HTTPs service.<br>
* check [README](https://github.com/theaidran/AI/blob/main/README.md) on github for Updates

## Credits

Based on the [original notebook by 81300](https://colab.research.google.com/github/81300/AI-Notebooks/blob/main/Colab-TextGen-GPU.ipynb).

Forked from [Philio](https://github.com/pcrii/Philo-Colab-Collection/blob/main/4bit_TextGen_Gdrive.ipynb).

Forked from [eucdee](https://github.com/eucdee/AI/blob/main/4bit_TextGen_Gdrive.ipynb).








