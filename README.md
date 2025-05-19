# LLM as a Judge 
This exercise is to create LLM as a judge. It will evaluate and compare responses from two other AI models. 

Model A: gpt-4o-mini \n
Model B: Gemini-2.0-flash \n
Model C (Judge) : GPT-4.1






###Workflow is as below 

          +-------------------+          +-------------------+
          |                   |          |                   |
 Input ---> Model A (Responder)          Model B (Responder) | <--- Input
          |                   |          |                   |
          +-------------------+          +-------------------+
                    |                             |
                    |                             |
                    +-----------+ +---------------+
                                V V
                           +---------------------+
                           |    Model C (Judge)  |
                           |  Compares A vs. B   |
                           +---------------------+
                                    |
                                    V
                             +-----------------+
                             |   Evaluation    |
                             |(Which is better)|
                             |                 |
                             +-----------------+

