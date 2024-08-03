## Create Env
- mamba deactivate
- mamba env remove -n ov
- mamba create --name ov python=3.9 -y
- mamba activate ov
- python -m pip install --upgrade pip
- pip install openvino-dev[onnx,pytorch]==2022.3.0
- pip install -r requirements.txt

## Example
- python demo.py --prompt "A boy, Playing Guitar"

