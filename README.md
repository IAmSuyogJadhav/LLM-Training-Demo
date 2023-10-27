# Setup Instructions

1. Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html).

2. Create a conda environment with the required packages:

    ```bash
    conda env create -f environment.yml
    ```

3. Activate the environment:

    ```bash
    conda activate llm-demo
    ```


# Running the demo

Follow the instructions inside the [01. Getting Started](01.%20Getting%20Started.ipynb) notebook for instructions on how to run pretrained models from Hugging Face.


Follow the instructions inside the [02. Training and Scaling](02.%20Training%20and%20Scaling.ipynb) notebook for instructions on how to train your own models and scale them up using deepspeed.

# Notes

You may need to change the `CUDA_VISIBLE_DEVICES` environment variable to select the GPU(s) you want to use. The value set for it inside the notebooks is for a DGX-1 system with 8 GPUs. If you are using a different system, you may need to change it accordingly.

# License

This project is licensed under the GNU/GPLv3 License - see the [LICENSE](LICENSE) file for details.

# Issues

Please report any issues you find in the [Issues](/issues) section of this repository.
