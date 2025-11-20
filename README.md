# Comfyui-Android-Install-Termux-Simplified
I simplify the process of installing comfyui on android caus most people only use native ai or don't want to wait almost an hour to install it on termix like myself over the years I've cluttered the main comfyui install guide so this one is for fast quick up and running version most packages are included by comfyui manager




apt update && apt upgrade -y && apt install python3 python3-pip python3-venv git ffmpeg -y && python3 -m venv comfyui-env && source comfyui-env/bin/activate && git clone https://github.com/comfyanonymous/ComfyUI.git && cd ComfyUI && pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu && pip install -r requirements.txt && cd custom_nodes && git clone https://github.com/ltdrdata/ComfyUI-Manager.git
cd ..
