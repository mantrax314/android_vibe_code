

# Reference
## LLM Inference guide in Android

https://ai.google.dev/edge/mediapipe/solutions/genai/llm_inference/android


## Hugginface documentation
https://huggingface.co/google/gemma-3n-E4B-it-litert-preview?clone=true

## Upload model to device

```
$ adb shell rm -r /data/local/tmp/llm/ # Remove any previously loaded models
$ adb shell mkdir -p /data/local/tmp/llm/
$ adb push output_path /data/local/tmp/llm/model_version.task

```