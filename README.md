# sd-webui-colab

more info: https://rentry.co/nocrypt

<a target="_blank" href="https://colab.research.google.com/github/NoCrypt/sd-webui-colab/blob/main/sd_webui_colab.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

#
[![](https://i.ibb.co/R0RX65D/New-Project.webp)](https://colab.research.google.com/github/NoCrypt/sd-webui-colab/blob/main/sd_webui_colab.ipynb)

## Features:
- ~5 minutes startup time guaranteed.
- Booru tags suggestions included. (configurable)
- Supports hypernetworks (w/o fast-stable-diffusion)
- 3 server tunnels alternative to Gradio Server (No more big images causing stuck, hopefully)
- Output to google drive. Make your output permanent, no more anxiety from unknown colab's time limit. (imagine using a cell to zip lol)
- Load models from your drive, direct links, drive folders, drive links, and public/private hugging face.
- Batch count max. 200 (instead of 100)
- Custom UI config which added useful settings to quick settings, add a lot of negative prompts, default prompt, and much bigger prompt textarea
- UmiAI to help you generate character with random prompts
- XFormers to help increasing performance by 1.2x
- Easily upload your merged model to hugging face

## Models:
- Waifu Diffusion + VAE
- Stable Diffusion V1.5 + VAE
- Trinart + VAE
- Stable Diffusion Inpainting
- H Diffusion V17
- SD v1.4
- Anything v3 + VAE
- Elysium Anime V2 + WD VAE
- Gyokai



## Notes
- I will not include NovelAI to my colab due to legal reason.
- I'm no longer using fast-stable-diffusion as base because it have a very "hacky" approach to increase performance, thus making me relying on their code, AND need him to fix everytime A1111 breaks something which can take days.

---
### Model DL Colab

*Download models from torrents and drive in colab then distribute them to drive and hugging face*
https://colab.research.google.com/drive/1aQ5nXTfLWHhZi7GOfXteLKg5OT1X-aBZ?usp=sharing

---

### DEEPDANBOORU STRING
[![DEEPDANBOORU_STRING](https://i.imgur.com/DbDaAMi.png)](https://huggingface.co/spaces/NoCrypt/DeepDanbooru_string)

*My HF Space for img to booru tags*
https://huggingface.co/spaces/NoCrypt/DeepDanbooru_string

---

### Credits:
- [stable-diffusion](https://github.com/CompVis/stable-diffusion)
- [fast-stable-diffusion](https://github.com/TheLastBen/fast-stable-diffusion)
- [waifu-diffusion](https://huggingface.co/hakurei/waifu-diffusion)
- [stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)
- https://rentry.org/voldy
- https://rentry.org/sdupdates
- more credits in colab
