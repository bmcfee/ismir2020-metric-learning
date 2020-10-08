# ismir2020-metric-learning
ISMIR 2020 Tutorial for Metric Learning in MIR

- Jongpil Lee
- [Brian McFee](https://brianmcfee.net)
- Juhan Nam

# Using these materials

## Option 1: Google Colab

The easiest way to follow along with the coding session of the tutorial is to use Google Colab's notebook server.  This will require a Google account, but you will not need to install any software on your own machine.

For the first coding demo, follow this link: http://bit.ly/ml4mir-demo-1

To use the code, you will need to click the "Connect" button: 

![Colab Connect button](colab-connect.png)

After clicking this button and waiting a few seconds, you should have an active notebook instance.
You may observe a warning message because the notebook was developed by us (and not Google) -- that's normal.  As long as you trust us to write reasonable code, feel free to accept the warning and continue. :grin:

You can then work through the notebook by executing each cell with the "play" button or by hitting `Shift+Enter`.


## Option 2: Local conda environment

If you'd prefer to run the code on your own machine, take the following steps.

1. Clone this repository.
2. Install [miniconda](https://docs.conda.io/en/latest/miniconda.html).
3. Create a conda environment from the environment specification provided by `metriclearningmir.yml` in this repository.  This is done by executing the following command:

```
conda env create -f metriclearningmir.yml
```

4. Activate the environment: 
```
conda activate metriclearningmir
```

5. You should now be able to run the `Metric Learning Demo.ipynb` notebook in Jupyter:
```
jupyter "Metric Learning Demo.ipynb"
```
