# Llama2-on-CPU-Machine

# How to Run?

### Steps 1:

clone the repository

```bash
git clone https://github.com/pjluvi/Llama2-on-CPU-Machine.git
```
### Step 2:

Create a virtual environment

```bash
conda create -n cpullama python=3.8 -y
```
```bash
conda activate cpullama
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```


### Download the quantize model from the link provided in model folder & keep the model in the model directory:

```ini
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```