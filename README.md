# Gauge Plot Function

This Python code generates a gauge plot using Plotly to visualize a score on a scale from 'F' to 'A'. The score is mapped to specific ranges within the gauge.

![image](https://github.com/geocracio/plotly-custom-gauge-plot/assets/40581019/1bcfd10e-f454-4bc2-8074-841371a50d70)


## Prerequisites

Make sure you have the following libraries installed in your Python environment:
- `math`
- `numpy`
- `plotly`

## Usage

1. Import the necessary libraries:
    ```python
    import math
    import numpy as np
    import plotly.graph_objects as go
    ```

2. Define the `translate` function and the `gauge_plot` function from the provided code.

3. To create a gauge plot for a score, use the `gauge_plot` function:
    ```python
    # Replace 'your_score_value' with the desired score
    your_score_value = 750
    fig = gauge_plot(your_score_value)
    fig.show()
    ```

    Adjust the `your_score_value` variable to see the gauge plot for different scores.

## Function Explanation

The `gauge_plot` function takes a score value and generates a gauge plot using Plotly. It maps the score to specific ranges within the gauge and displays the corresponding position on the gauge needle.
