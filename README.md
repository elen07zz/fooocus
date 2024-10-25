# Fooocus Version working with DoRA support.

Python embedded enviroment.

Release version:
https://github.com/elen07zz/fooocus/releases/download/release/Fooocus.7z


## Fooocus is an image generating software (based on Gradio ).

Fooocus presents a rethinking of image generator designs. The software is offline, open source, and free, while at the same time, similar to many online image generators like Midjourney, the manual tweaking is not needed, and users only need to focus on the prompts and images. Fooocus has also simplified the installation: between pressing "download" and generating the first image, the number of needed mouse clicks is strictly limited to less than 3. Minimal GPU memory requirement is 4GB (Nvidia).

[1] David Holz, 2019.

Recently many fake websites exist on Google when you search “fooocus”. Do not trust those – here is the only official source of Fooocus.


All CMD Flags

 * entry_with_update.py  [-h] [--listen [IP]] [--port PORT]
 * [--disable-header-check [ORIGIN]]
 *  [--web-upload-size WEB_UPLOAD_SIZE]
                     * [--external-working-path PATH [PATH ...]]
                   *   [--output-path OUTPUT_PATH] [--temp-path TEMP_PATH]
                    *  [--cache-path CACHE_PATH] [--in-browser]
                    *  [--disable-in-browser] [--gpu-device-id DEVICE_ID]
                  *    [--async-cuda-allocation | --disable-async-cuda-allocation]
                 *     [--disable-attention-upcast] [--all-in-fp32 | --all-in-fp16]
                   *   [--unet-in-bf16 | --unet-in-fp16 | --unet-in-fp8-e4m3fn | --unet-in-fp8-e5m2]
                  *    [--vae-in-fp16 | --vae-in-fp32 | --vae-in-bf16]
                 *     [--clip-in-fp8-e4m3fn | --clip-in-fp8-e5m2 | --clip-in-fp16 | --clip-in-fp32]
                  *    [--directml [DIRECTML_DEVICE]] [--disable-ipex-hijack]
                  *    [--preview-option [none,auto,fast,taesd]]
                *      [--attention-split | --attention-quad | --attention-pytorch]
                *      [--disable-xformers]
                *      [--always-gpu | --always-high-vram | --always-normal-vram | 
                  *     --always-low-vram | --always-no-vram | --always-cpu]
               *       [--always-offload-from-vram] [--disable-server-log]
                 *     [--debug-mode] [--is-windows-embedded-python]
                  *    [--disable-server-info] [--share] [--preset PRESET]
                  *    [--language LANGUAGE] [--disable-offload-from-vram]
                 *     [--theme THEME] [--disable-image-log]  `
