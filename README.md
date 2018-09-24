## Distributed deep learning with Keras on Spark
<p align="center">
  <img src="https://i.imgur.com/JarVo2A.png" title="Spark with Keras">
</p>

#### There are many distributed deep learning frameworks, but only this one worked for me so far
and only with some fixing

1. Fix workers.py by adding add_history to SequentialWorker class
2. Run the model
