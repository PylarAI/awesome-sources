# awesome-sources
Awesome Sources

 - [Explaining LoRA Learning Settings Using Kohya_ss for Stable Diffusion Understanding by Anyone
](https://github.com/FurkanGozukara/Stable-Diffusion/blob/main/Tutorials/How-To-Do-Kohya-SDXL-LoRA-Training-With-Weak-Low-VRAM-GPUs.md)
 - [Minute of setting video Lora](https://youtu.be/sBFGitIvD2A?t=2262)
 - [Very Interesting discussion about config .json files for Lora](https://github.com/kohya-ss/sd-scripts/issues/661)

When it asks:

```
Already up to date.
venv "C:\Python311\Scripts\Python.exe"
Python 3.10.9 (tags/v3.10.9:1dd9be6, Dec  6 2022, 20:01:21) [MSC v.1934 64 bit (AMD64)]
Version: v1.5.1
Commit hash: 68f336bd994bed5442ad95bad6b6ad5564a5409a
Traceback (most recent call last):
  File "D:\PylarSoft\stable-diffusion-webui\launch.py", line 39, in <module>
    main()
  File "D:\PylarSoft\stable-diffusion-webui\launch.py", line 30, in main
    prepare_environment()
  File "D:\PylarSoft\stable-diffusion-webui\modules\launch_utils.py", line 314, in prepare_environment
    raise RuntimeError(
RuntimeError: Torch is not able to use GPU; add --skip-torch-cuda-test to COMMANDLINE_ARGS variable to disable this check
Press any key to continue . . .
```

Solution is run the install base file of [AUTOMATIC1111/stable-diffusion-webui - file: run.bat inside the zip file sd.webui.zip
](https://github.com/AUTOMATIC1111/stable-diffusion-webui)

```
Python 3.10.6 (tags/v3.10.6:9c7b4bd, Aug  1 2022, 21:53:49) [MSC v.1932 64 bit (AMD64)]
Commit hash: 48a15821de768fea76e66f26df83df3fddf18f4b
Installing torch and torchvision
Looking in indexes: https://pypi.org/simple, https://download.pytorch.org/whl/cu117
Collecting torch==1.13.1+cu117
  Downloading https://download.pytorch.org/whl/cu117/torch-1.13.1%2Bcu117-cp310-cp310-win_amd64.whl (2255.4 MB)
     ━━━━━━━━━━━━━━━╺━━━━━━━━━━━━━━━━━━━━━━━━ 0.9/2.3 GB 108.8 MB/s eta 0:00:13
```

