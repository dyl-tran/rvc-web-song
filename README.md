<h1 align="center">RVC-WebUI-Song</h1>
<div align="center">
<p>

[`liujing04/Retrieval-based-Voice-Conversion-WebUI`](https://github.com/liujing04/Retrieval-based-Voice-Conversion-WebUI) reconstruction project

</p>
</div>

---

<div align="center">
<p>

[日本語](README-ja.md) | [English](README.md)

</p>
</div>

<br >

# Launch

## Windows
Double click `webui-user.bat` to start the webui.

## Linux or Mac
Run `webui.sh` to start the webui.

<br >

# How to use:

## Put model files in .\models\checkpoints then refresh and choose a model

## Use the Gradio web user interface and copy the path of the vocals of chosen song in Source Audio box

## Copy the path of Faiss index that look like ```added_IVF208_Flat_nprobe_4.index``` under the Faiss index file path box

## Copy the path of Big NPY that look like ```total_fea.npy``` under Big NPY file path box

## Click infer

```
Tested environment: Windows 10, Python 3.10.9, torch 2.0.0+cu118
```

<br >

# Troubleshooting

## `error: Microsoft Visual C++ 14.0 or greater is required.`

Microsoft C++ Build Tools must be installed.

### Step 1: Download the installer
[Download](https://visualstudio.microsoft.com/ja/thank-you-downloading-visual-studio/?sku=BuildTools&rel=16)

### Step 2: Install `C++ Build Tools`
Run the installer and select `C++ Build Tools` in the `Workloads` tab.

<br >

# Credits
- [`liujing04/Retrieval-based-Voice-Conversion-WebUI`](https://github.com/liujing04/Retrieval-based-Voice-Conversion-WebUI)
- [`teftef6220/Voice_Separation_and_Selection`](https://github.com/teftef6220/Voice_Separation_and_Selection)
