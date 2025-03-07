# fast-huyuan-low-vram

## 1. Setup ComfyUI-Windows Portable (skip if already done)

There is a portable standalone build for Windows that should run on Nvidia GPUs or your CPU only on the [releases page](https://github.com/comfyanonymous/ComfyUI/releases).

### [Direct link to download](https://github.com/comfyanonymous/ComfyUI/releases/latest/download/ComfyUI_windows_portable_nvidia.7z)

Simply download, extract with [7-Zip](https://7-zip.org) and run.

If you have trouble extracting it, right-click the file -> properties -> unblock

GitHub page [ComfyUI](https://github.com/comfyanonymous/ComfyUI?tab=readme-ov-file)

### Recommended to install ComfyUI-Manage
**ComfyUI-Manager** is an extension designed to enhance the usability of [ComfyUI](https://github.com/comfyanonymous/ComfyUI). It offers management functions to **install, remove, disable, and enable** various custom nodes of ComfyUI. Furthermore, this extension provides a hub feature and convenience functions to access a wide range of information within ComfyUI.

To install ComfyUI-Manager in addition to an existing installation of ComfyUI, you can follow the following steps:

1. goto `ComfyUI/custom_nodes` dir in terminal(cmd)
2. `git clone https://github.com/ltdrdata/ComfyUI-Manager comfyui-manager`
3. Restart ComfyUI
There are other methods for installation Visit [GitHub repo](https://github.com/ltdrdata/ComfyUI-Manager/tree/main)

## 2. Download and load the workflow

The workflow is given in the repo [HunyuanVideoGGUF4GB.json](https://github.com/Arshadshemilk/fast-huyuan-low-vram/edit/main/HunyuanVideoGGUF4GB.json)

Load the workflow in ComfyUI

Download the missing nodes
Using the Manager:
1. Open ComfyUI and click the "Manager" button. 
2. Click "Install Custom Node" and search for the desired node. 
3. Restart ComfyUI.
   
Manually:
1. Open a terminal or command prompt. 
2. Navigate to the custom_nodes folder. 
3. Use Git to clone the repository of the desired custom node. 
4. Example: git clone https://github.com/example/comfyui-node.git. 
5. Restart ComfyUI. 
