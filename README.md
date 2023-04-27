LLM text generation notebook for Google Colab<br>
This notebook uses https://github.com/oobabooga/text-generation-webui to run conversational models in chat mode.

▶⏩Run all the cells and a public gradio URL will appear at the bottom in around 5 minutes.🤞🐱‍👤

Updates:<br>
*updated GPTQ to latest version for Vicuna 13b 1.1 support<br>
*added more interresting models to choose from<br>
-reeducator/vicuna-13b-free<br>
-TheBloke/vicuna-13B-1.1-GPTQ-4bit-128g<br>
-TheBloke/wizardLM-7B-GPTQ 0.46 tokens/s (need --model_type llama argument to launch, also manualy remove no-act-order model)<br>
-Aitrepreneur/wizardLM-7B-GPTQ-4bit-128g 0.46 tokens/s (need --model_type llama argument to launch)<br>
-gozfarb/oasst-llama13b-4bit-128g 1.62 tokens/s<br>
*added "print installed models" to installer (usefull for gdrive install)<br>
*set gdrive and save all to true (adds memory and fast start)<br>
