# Prompt Engineering

## Simple
Zero-shot
- direct - write a poem about Glacier National Park

One-shot learning
- showing a model how to do a task once, then expecting the model to replicate it.

Few-shot learning
- multiple examples rather than one.

## Chain of Thought (CoT)
Lets think step by step.
time pressure can lead to errors.
Rather than just giving the answers like in x-shot learning, it gives the chain of thought of how to get to the answer.
Give explicit instructions - decompose instructions. give it the intermediate steps.
add "Let's think step by step" - 18% to 79% accuracy for a model

## Self Consistnecy Prompting
Sample multiple outputs from the modela nd select the most consistent answer
similar to bagging.

## ReAct
rag is what, ReAct is how
llm interacts with tools

