# Fooocus Version working with DoRA support.

Python embedded enviroment.

Release version:
https://github.com/elen07zz/fooocus/releases/download/release/Fooocus.7z


## Fooocus is an image generating software (based on Gradio ).

Fooocus presents a rethinking of image generator designs. The software is offline, open source, and free, while at the same time, similar to many online image generators like Midjourney, the manual tweaking is not needed, and users only need to focus on the prompts and images. Fooocus has also simplified the installation: between pressing "download" and generating the first image, the number of needed mouse clicks is strictly limited to less than 3. Minimal GPU memory requirement is 4GB (Nvidia).

Recently many fake websites exist on Google when you search “fooocus”. Do not trust those – here is the only official source of Fooocus.


### Features

 Below is a quick list using Midjourney's examples:
 -----------------------------------
| Midjourney 	| Fooocus | 
--------------------------
| High-quality text-to-image without needing much prompt engineering or parameter tuning. (Unknown method) 	| High-quality text-to-image without needing much prompt engineering or parameter tuning. (Fooocus has an offline GPT-2 based prompt processing engine and lots of sampling improvements so that results are always beautiful, no matter if your prompt is as short as “house in garden” or as long as 1000 words) | 
---------------------------------------------------------------------------------------
| V1 V2 V3 V4 	| Input Image -> Upscale or Variation -> Vary (Subtle) / Vary (Strong) | 
---------------------------------------------------------------------------------------
| U1 U2 U3 U4 	| Input Image -> Upscale or Variation -> Upscale (1.5x) / Upscale (2x) | 
--------------------------------------------------------------------------------------
| Inpaint / Up / Down / Left / Right (Pan) 	| Input Image -> Inpaint or Outpaint -> Inpaint / Up / Down / Left / Right (Fooocus uses its own inpaint algorithm and inpaint models so that results are more satisfying than all other software that uses standard SDXL inpaint method/model)
| Image Prompt 	| Input Image -> Image Prompt (Fooocus uses its own image prompt algorithm so that result quality and prompt understanding are more satisfying than all other software that uses standard SDXL methods like standard IP-Adapters or Revisions) | 
---------------------------------------------------
| --style 	| Advanced -> Style | 
-------------------------------------
| --stylize 	| Advanced -> Advanced -> Guidance | 
-----------------------------------------------------
| --niji 	| Multiple launchers: "run.bat", "run_anime.bat", and "run_realistic.bat".Fooocus support SDXL models on Civitai (You can google search “Civitai” if you do not know about it) | 
-----------------------------------------------
| --quality  	| Advanced -> Quality | 
-----------------------------------------
| --repeat 	| Advanced -> Image Number | 
------------------------------------------------------
| Multi Prompts (::) 	| Just use multiple lines of prompts | 
-----------------------------------------------------------------------
| Prompt Weights 	| You can use " I am (happy:1.5)".Fooocus uses A1111's reweighting algorithm so that results are better than ComfyUI if users directly copy prompts from Civitai. (Because if prompts are written in ComfyUI's reweighting, users are less likely to copy prompt texts as they prefer dragging files)To use embedding, you can use "(embedding:file_name:1.1)" | 
-------------------------------------------------
| --no 	| Advanced -> Negative Prompt | 
------------------------------------------------------------------------------
| --ar 	| Advanced -> Aspect Ratios | 
--------------------------------------------------------
| InsightFace 	| Input Image -> Image Prompt -> Advanced -> FaceSwap | 
---------------------------------------------------------
| Describe | Input Image -> Describe | 
-------------------------------------
