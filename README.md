# Distributed_Inference
Distributed Multi GPU Inference Engine ~ WORK IN PROGRESS

Traditional inference on large models can be slow, memory-intensive, and limited by single GPU constraints. 
This project solves these problems by:
Splitting models across multiple GPUs using layer-wise parallelism
Allowing multiple queries to be processed simultaneously (multi-query pipelining)
Implementing caching for repeated queries
Dynamically routing queries to small or large models based on input complexity
Supporting all MLP Structures
