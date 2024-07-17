# Generative Image AI

Research into generative image models such as diffusion models and variational autoencoders.

## Environment Setup

> Right now the only executable code is the notebooks in `experiments`.

To set up on MacOS or Linux:

```sh
git clone https://github.com/DL4DS/gen_image_ai.git
cd gen_image_ai

# Check if you have a recent version of python
python3 --version

# Create a virtual environment
python3 -m venv .venv

# activate the virtual environment
source .venv/bin/activate

# install the requirements
pip install -r requirements.txt
```