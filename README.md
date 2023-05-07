# Deep-Learning-Applications-with-GUI

List of FOSS Deep Learning (Desktop) Applications with GUI and/or CLI. Most Deep Learning models require a complicated setup and are not ready to use out of the box. At best there is a Colab or Jupiter notebook available, which is good for testing, but not for production use.

The software in this list is ready to use (CLI or GUI).

:camera_flash: NeRF 📃 Text 🎨 Image (generative) :notes: Audio 🎞️ Video frame interpolation 🖼️🎞️ Video upscaler 🖼️ Image/Video upscaling 🧩 Ready to use Plugins

# :camera_flash: 3D / NeRF: Neural Radiance Fields

https://github.com/NVlabs/instant-ngp#interactive-training-and-rendering

# 📃 Text

## Translation
https://github.com/argosopentech/argos-translate#installation
https://github.com/ymoslem/DesktopTranslator

## text-generation-webui

A gradio web UI for running Large Language Models like LLaMA, llama.cpp, GPT-J, Pythia, OPT, and GALACTICA.

Its goal is to become the AUTOMATIC1111/stable-diffusion-webui of text generation.

https://github.com/oobabooga/text-generation-webui

## Chat-Style LLM (Alpaca/Llama) (Chat GTP Clone)
https://github.com/antimatter15/alpaca.cpp
https://github.com/tatsu-lab/stanford_alpaca
https://github.com/tloen/alpaca-lora
(No UI but ready to use Installer for running from CLI)
Alpaca 7B model download (Model bin file size: 4017M)
curl -o ./models/ggml-alpaca-7b-q4.bin -C - https://ipfs.io/ipfs/QmUp1UGeQFDqJKvtjbSYPBiZZKRjLp8shVP9hT8ZB9Ynv1
curl -o ggml-alpaca-7b-q4.bin -C - https://gateway.estuary.tech/gw/ipfs/QmQ1bf2BTnYxq73MFJWu1B7bQ2UD6qG7D7YDCxhTndVkPC
curl -o ggml-alpaca-7b-q4.bin -C - https://cloudflare-ipfs.com/ipfs/QmQ1bf2BTnYxq73MFJWu1B7bQ2UD6qG7D7YDCxhTndVkPC
Read more here: https://medium.com/geekculture/writing-a-medium-article-using-ai-stanford-alpaca-running-on-your-local-pc-e025416a032a

## dalai

Run LLaMA and Alpaca on your computer.

https://github.com/cocktailpeanut/dalai

## GTP4All

Installs a native chat-client with auto-update functionality that runs on your desktop with the GPT4All-J model baked into it.

https://github.com/nomic-ai/gpt4all

## Gpt4All Web UI

This is a Flask web application that provides a chat UI for interacting with llamacpp based chatbots such as GPT4all, vicuna etc...

https://github.com/nomic-ai/gpt4all-ui

## AutoGPT GUI

A graphical user interface to AutoGPT

https://github.com/thecookingsenpai/autogpt-gui

# 🎨 Image (generative)

## Style2Paints

Style2paints V4 is the current best AI driven lineart **colorization tool**.

https://github.com/lllyasviel/style2paints

Source code not available for the latest release.

JavaScript, Python, Tensorflow

## NMKD Stable Diffusion GUI - AI Image Generator

https://github.com/n00mkrad/text2image-gui

https://nmkd.itch.io/t2i-gui

## stable-diffusion-ui

Easiest 1-click way to install and use Stable Diffusion on your own computer. Provides a browser UI for generating images from text prompts and images. Just enter your text prompt, and see the generated image

https://github.com/cmdr2/stable-diffusion-ui

## MochiDiffusion

This app uses Apple's Core ML Stable Diffusion implementation to achieve maximum performance and speed on Apple Silicon based Macs while reducing memory requirements.

https://github.com/godly-devotion/MochiDiffusion

## ComfyUI

This ui will let you design and execute advanced stable diffusion pipelines using a graph/nodes/flowchart based interface. For some workflow examples and see what ComfyUI can do you can check out:

https://github.com/comfyanonymous/ComfyUI

## OnnxDiffusersUI

Stable Diffusion on AMD graphics 

https://github.com/azuritecoin/OnnxDiffusersUI

## Diffusion Bee - Stable Diffusion GUI App for MacOS

https://github.com/divamgupta/diffusionbee-stable-diffusion-ui

## WebUI 

ready to use colab based notebooks with web ui

https://github.com/camenduru/stable-diffusion-webui-colab

## InvokeAI

 InvokeAI is a leading creative engine for Stable Diffusion models, empowering professionals, artists, and enthusiasts to generate and create visual media using the latest AI-driven technologies. The solution offers an industry leading WebUI, supports terminal use through a CLI, and serves as the foundation for multiple commercial products. 

https://github.com/invoke-ai/InvokeAI

## Lama Cleaner

A free and open-source inpainting tool powered by SOTA AI model.

https://github.com/Sanster/lama-cleaner

https://panicbyte.itch.io/lama-cleaner

## carefree-creator

 AI magics meet Infinite draw board. 

https://github.com/carefree0910/carefree-creator

## photoshot

An open-source AI avatar generator web app

https://github.com/shinework/photoshot

# :notes: Audio

## tacotron2-tts-GUI

GUI wrapper for synthesize. Allows CPU-only synthesis via a toggleable switch. Portable exe file is available (that runs on CPU only).

https://github.com/lokkelvin2/tacotron2-tts-GUI

## riffusion

Riffusion is an app for real-time music generation with stable diffusion.

https://github.com/riffusion/riffusion-app

## whisper-ui

Whisper is a general-purpose speech recognition model. It is trained on a large dataset of diverse audio and is also a multitasking model that can perform multilingual speech recognition, speech translation, and language identification.

This is a simple Streamlit UI for OpenAI's Whisper speech-to-text model. It let's you download and transcribe media from YouTube videos, playlists, or local files. You can then browse, filter, and search through your saved audio files.

https://github.com/hayabhay/whisper-ui for https://github.com/openai/whisper

https://grisk.itch.io/whisper-gui

## buzz 

GUI for whisper

https://github.com/chidiwilliams/buzz

## Ultimate Vocal Remover GUI v5.5.1

This application uses state-of-the-art source separation models to remove vocals from audio files. UVR's core developers trained all of the models provided in this package (except for the Demucs v3 and v4 4-stem models).

https://github.com/Anjok07/ultimatevocalremovergui

## SpleeterGUI

SpleeterGUI - Music source separation desktop app

Windows Desktop Front end for Spleeter - AI source separation

https://github.com/boy1dr/SpleeterGui

## SoftVC VITS Singing Voice Conversion Fork

https://github.com/34j/so-vits-svc-fork

# 🎞️ Video frame interpolation

## DAIN-App

The backbone of this project is a algorithm called DAIN. (https://github.com/baowenbo/DAIN)

https://github.com/BurguerJohn/Dain-App

https://grisk.itch.io/dain-app?download

## DAIN Vulkan GUI

AI-Powered video interpolater (eg. 30fps -> 60fps) for Vulkan devices. Based on dain-ncnn-vulkan and ffmpeg

https://github.com/Mar2ck/DAIN-Vulkan-GUI

## dain-ncnn-vulkan

ncnn implementation of DAIN, Depth-Aware Video Frame Interpolation.

https://github.com/nihui/dain-ncnn-vulkan

## Dain-App

https://github.com/BurguerJohn/Dain-App

## cain-ncnn-vulkan

Video Frame Interpolation

https://github.com/nihui/cain-ncnn-vulkan

## Flowframes

Flowframes is a simple but powerful app that utilizes AI frameworks to interpolate videos in order to increase their framerate with little to no noticable quality loss. (DAIN, CAIN, RIFE)

https://github.com/n00mkrad/flowframes

https://nmkd.itch.io/flowframes

# 🖼️🎞️ Video upscaler

## video2x

A lossless video/GIF/image upscaler achieved with waifu2x, Anime4K, SRMD and RealSR. Started in Hack the Valley 2, 2018. 
https://github.com/k4yt3x/video2x

# 🖼️ Image/Video upscaling

## Upscayl
Upscayl is a cross-platform application built with the Linux-first philosophy. This means that we prioritize Linux builds over others but that doesn't mean we'll break things for other OSes :) Makes use of Real-ESRGAN

https://github.com/upscayl/upscayl

## Anime4kSharp

https://github.com/shadow578/Anime4kSharp

## dandere2x-tremx

video compression 
https://github.com/Tremeschin/dandere2x-tremx

## Cupscale

Image Upscaling GUI based on ESRGAN - WORK IN PROGRESS

https://github.com/n00mkrad/cupscale

## IEU.Winforms

Windows only GUI for ESRGAN with additional features 
https://github.com/ptrsuder/IEU.Winforms

## NVIDIA-Ansel-AI-Enhancer

NVIDIA Upscaler, utilizes NVIDIA´s Ansel RTX. Requires latest drivers and a RTX GPU. Free, but not open source. 

https://github.com/dynamiquel/NVIDIA-Ansel-AI-Enhancer 

## RealSR

Real-World Super-Resolution via Kernel Estimation and Noise Injection 

https://github.com/jixiaozhong/RealSR

(https://github.com/nihui/RealSR)

## realsr-ncnn-vulkan

https://github.com/nihui/realsr-ncnn-vulkan

## Shell upscaler

https://github.com/n00mkrad/shell-upscaler

Acts as a GUI for esrgan-launcher.

## srmd-ncnn-vulkan

https://github.com/nihui/srmd-ncnn-vulkan

## VapourSynth-Super-Resolution-Helper

https://github.com/AlphaAtlas/VapourSynth-Super-Resolution-Helper

## Waifu2x-Extension-GUI

Photo/Video/GIF enlargement using machine learning

https://github.com/AaronFeng753/Waifu2x-Extension-GUI

C++, python, qt, caffe, ncnn_vulkan

AGPL-3.0 License

## waifu2x-ncnn-vulkan

https://github.com/nihui/waifu2x-ncnn-vulkan

# GAN / Style Transfer

## TorchRayLib

TorchRayLib++: A CMake based AI & generative art platform, integrating the rayib GUI and the PyTorch C++ Deep Learning Library.

https://github.com/QuantScientist/TorchRayLib

# :toolbox: DL Training GUI

## AIDeveloper

GUI-based software for training, evaluating and applying deep neural nets for image classification 

https://github.com/maikherbig/AIDeveloper

# 🧩 Ready to use Plugins

## vstSpleeter

audio source separation library vst plugin

https://github.com/gvne/vstSpleeter


---


## various apps (untested)

Paper2GUI is an AI desktop Application toolbox for everyone no matter your background with it being free and ready to use out of the box, already supporting 10+ AI models, covering the fields of speech synthesis, video frame filling, video overscoring, target detection, image stylization, OCR recognition, etc. Supporting Windows, Mac OS, Linux systems.

https://github.com/Baiyuetribe/paper2gui/blob/main/README_en.md

Free: https://www.nvidia.com/en-us/studio/canvas/
