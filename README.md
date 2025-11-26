# Hugging Face Practical Project

This project provides sample practical implementations and experiments with the Hugging Face Transformers library. It covers model loading, fine-tuning, and working with datasets and the Hugging Face hub.

## Features

- Loading datasets and models from Hugging Face
- Guidance on caching and environment setup
- Fine-tuning transformer models on custom data

## Requirements

- Python 3.8+
- Hugging Face Transformers
- PyTorch
- numpy
- pyyaml
- packaging
- regex

## Virtual Environment Setup

It is recommended to use a virtual environment to manage dependencies and avoid conflicts.

### Using `venv` (Standard Python)

```bash
# Create a new virtual environment named 'venv'
python -m venv venv

# Activate the virtual environment

# On Windows:
venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate

# Upgrade pip
pip install --upgrade pip
```

### Using `conda`

```bash
conda create -n <venv> python=<version>
conda activate <venv>
```

## Installing Requirements

Install the required Python packages:

```bash
pip install numpy transformers transformers[torch] pyyaml packaging regex accelerate>=0.26.0
```

## Usage

Clone the repository and run the provided notebooks or scripts:

```bash
git clone https://github.com/Anurag0798/Hugging-Face-Practical.git

cd Hugging-Face-Practical
```

## Example Warning

If you encounter a warning about symlinks and the cache, you can safely ignore it. Refer to the [Hugging Face documentation](https://huggingface.co/docs/huggingface_hub/how-to-cache#limitations) for more information.

## License

This project is licensed under the MIT License. Please read it for more details.