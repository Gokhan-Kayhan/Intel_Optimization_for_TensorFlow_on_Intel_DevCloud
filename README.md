# Intel Optimization for TensorFlow on Intel DevCloud


## Intel Developer Cloud
Since I don't have suitable Intel Hardware, I have made all the test on Intel Developer Cloud. Registration and connection details can be found in [Intel Developer Cloud](sections/devcloud.md) section.

</br>


## Setting up the Kernel

To run our codes, we should set up a kernel. Details can be found [in this section.](sections/kernel.md)

</br>


## Run the code and Job Script

[This section](sections/job.md) explains ; running the codes and using the all capacity of the available computing resources on the DevCloud.

</br>

## Comparison of results

This [Jupyter Notebook](Intel_Optimized_vs_Default_TensorFlow.ipynb) contains the comparison of _"Default Tensorflow"_ and _"Intel Optimized TensorFlow(Intel Extension for Tensorflow package)"_ with different number of epochs and with various datasets.

|                               | Intel Optimized TensorFlow | Default TensorFlow |
|-------------------------------|----------------------------|--------------------|
| Normalized Data (10 Epochs)   | 10.90 seconds              | 30.77 seconds      |
| Normalized Data (20 Epochs)   | 22.87 seconds              | 66.84 seconds      |
|                               |                            |                    |
| Unnormalized Data (10 Epochs) | 50.57 seconds              | 73.14 seconds      |
| Unnormalized Data (20 Epochs) | 101.56 seconds             | 142.69 seconds     |

