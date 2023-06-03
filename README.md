LLM text generation notebook for Google Colab<br>
This notebook uses https://github.com/oobabooga/text-generation-webui to run conversational models in chat mode.

▶⏩Run all the cells and a public gradio URL will appear at the bottom in around 5 minutes.🤞🐱‍👤

**Added support of simple UI for testing LLMs. Instead of using Gradio and logging inputs into their servers, you can run a link within Colab's external HTTP service.
-Pickle tensors added as an option to download first, before Safetensors if both are available.
-AutoGPTQ used as defalut 

Updates:<br>
*updated GPTQ to latest version for Vicuna 13b 1.1 support<br>
*added "print installed models" to installer cell (usefull for gdrive install)<br>
*set gdrive and save all to true (adds memory and fast start)<br>
*added more interresting models to choose from<br>
- reeducator/vicuna-13b-free<br>
https://huggingface.co/reeducator/vicuna-13b-free<br>
- TheBloke/vicuna-13B-1.1-GPTQ-4bit-128g<br>
https://huggingface.co/TheBloke/vicuna-13B-1.1-GPTQ-4bit-128g</url><br>
- TheBloke/wizardLM-7B-GPTQ 0.46 tokens/s (need --model_type llama argument to launch, also manualy remove no-act-order model)<br>
https://huggingface.co/TheBloke/wizardLM-7B-GPTQ<br>
- Aitrepreneur/wizardLM-7B-GPTQ-4bit-128g 0.46 tokens/s (need --model_type llama argument to launch)<br>
https://huggingface.co/Aitrepreneur/wizardLM-7B-GPTQ-4bit-128g<br>
- gozfarb/oasst-llama13b-4bit-128g 1.62 tokens/s<br>
https://huggingface.co/gozfarb/oasst-llama13b-4bit-128g<br>
- catalpa/codecapybara-4bit-128g-gptq<br>
https://huggingface.co/catalpa/codecapybara-4bit-128g-gptq<br>
- mzedp/dolly-v2-12b-GPTQ-4bit-128g<br>
https://huggingface.co/mzedp/dolly-v2-12b-GPTQ-4bit-128g<br>
- autobots/pythia-12b-gptqv2-4bit<br>
https://huggingface.co/autobots/pythia-12b-gptqv2-4bit<br>
- TheBloke/medalpaca-13B-GPTQ-4bit<br>
https://huggingface.co/TheBloke/medalpaca-13B-GPTQ-4bit<br>
- TheBloke/gpt4-alpaca-lora-13B-GPTQ-4bit-128g<br>
https://huggingface.co/TheBloke/gpt4-alpaca-lora-13B-GPTQ-4bit-128g<br>
- catalpa/codecapybara-4bit-128g-gptq<br>
https://huggingface.co/catalpa/codecapybara-4bit-128g-gptq<br>




