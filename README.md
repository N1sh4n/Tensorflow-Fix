# Tensorflow-Fix

!pip install --extra-index-url https://pypi.nvidia.com tensorrt-bindings==8.6.1 tensorrt-libs==8.6.1
!pip install -U tensorflow[and-cuda]==2.15.0
import tensorflow as tf; print(tf.__version__); print(tf.config.list_physical_devices('GPU'))
