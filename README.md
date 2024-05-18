# colab-depth-estimation
this is a cell of code used for the depth estimation

from transformers import pipeline

pipe = pipeline(task="depth-estimation", model="Intel/dpt-large")
result = pipe(image)
result["depth"]
