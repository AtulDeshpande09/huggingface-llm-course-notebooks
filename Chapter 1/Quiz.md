## Quiz of Chapter 1

---
 1. Explore the Hub and look for the roberta-large-mnli checkpoint. What task does it perform? 

**Answer : ✅ Text classification**

--- 
 2. What will the following code return?<br>
```python
from transformers import pipeline

ner = pipeline("ner", grouped_entities=True)
ner("My name is Sylvain and I work at Hugging Face in Brooklyn.")
```
\
**Answer : ✅  It will return the words representing persons, organizations or locations.**

---
 3. What should replace … in this code sample?<br>
 ```python
from transformers import pipeline

filler = pipeline("fill-mask", model="bert-base-cased")
result = filler("...")
```
\
**Answer : ✅ This [MASK] has been waiting for you.**

---
 4. Why will this code fail?<br>
```python
from transformers import pipeline

classifier = pipeline("zero-shot-classification")
result = classifier("This is a course about the Transformers library")
```
\
**Answer : ✅ This pipeline requires that labels be given to classify this text.**

---
5. What does “transfer learning” mean?

**Answer : ✅ Transferring the knowledge of a pretrained model to a new model by initializing the second model with the first model's weights.**

---
 6. True or false? A language model usually does not need labels for its pretraining.

**Answer : ✅ True**

---
 7. Select the sentence that best describes the terms “model”, “architecture”, and “weights”.

**Answer : ✅  An architecture is a succession of mathematical functions to build a model and its weights are those functions parameters**

---
 8. Which of these types of models would you use for completing prompts with generated text?

**Answer : ✅ A decoder model**

---
 9. Which of those types of models would you use for summarizing texts?

**Answer : ✅ A sequence-to-sequence model**

---
 10. Which of these types of models would you use for classifying text inputs according to certain labels?

**Answer : ✅ An encoder model**

---
 11. What possible source can the bias observed in a model have?

**Answer : ✅ The data the model was trained on is biased.**

--- 
