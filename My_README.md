## Name : XXX

* About throughputs , please record the Tokens / Sec of Eval Time 

### Basic Challenge
| Throughputs (Tokens/sec) | CPU      | GPU      | 
| --------                 | -------- | -------- | 
| tinyllama-1.1b-chat-v0.3.Q4_K_M.gguf  | 9.15     | 16.46     |


### Medium Challenge
| Throughputs (Tokens/sec) | CPU      | GPU      | 
| --------                 | -------- | -------- | 
| tinyllama-1.1b-chat-v0.3.Q4_K_M.gguf  | 9.15     | 16.46     |
| TinyLlama-1.1B-Chat-v1.0-f16  | 4.84     | 10.5     |



### Advance Challenge
| Throughputs (Tokens/sec) | CPU      | GPU      | 
| --------                 | -------- | -------- | 
| tinyllama-1.1b-chat-v0.3.Q4_K_M.gguf  | 9.15    | 16.46   |
| TinyLlama-1.1B-Chat-v1.0-f16  | 4.84     | 10.5     |
| TinyLlama-1.1B-Chat-v1.0-Q8  | 6.49     | 12.68    |


### Advance Challenge

|                           | Accuracy  |
| --------                 | --------  |
| tinyllama-1.1b-chat-v0.3.Q4_K_M.gguf | 5/10     |
| TinyLlama-1.1B-Chat-v1.0-f16         | 6/10     |
| TinyLlama-1.1B-Chat-v1.0-Q8          | 5/10     |

### Questions
* What problems you encountered? How you solve it?  
  1.Google Colab and Google Drive:  
    [Tab]I used my own Google Drive rather than school account initially, so I encountered like not enough space for downloading model.  
    [tab]So I decided to copy my code to school account and run again. Kinda stupid but ya, this is a problem I met.  
    [tab]nd due to the mechanism of google colab, I need to connect to my drive everytime I change runtime type or I leave colab too long.  
    [tab]Sometime I forgot this and cause some error. And some commands also needed to run everytime I open colab, it's kinda annoying.  
  2.Set llama.cpp:
    
* What you observed between CPU / GPU performance ?    
* Will quantization or smaller-parameters model impact model accuracy or inference throughput ? If so , what's the variation?



