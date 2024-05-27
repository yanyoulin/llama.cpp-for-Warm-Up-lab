## Name : 林彥佑

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
  1. Google Colab and Google Drive:  
     I used my own Google Drive rather than school account initially, so I encountered like not enough space for downloading model.  
     So I decided to copy my code to school account and run again. Kinda stupid but ya, this is a problem I met.  
     And due to the mechanism of google colab, I need to connect to my drive everytime I change runtime type or I leave colab too long.  
     Sometime I forgot this and cause some error. And some commands also needed to run everytime I open colab, it's kinda annoying.  
  2. Set llama.cpp:  
     I follow github to set llama, but after I had done !make, I don't know what to do next.  
     The process of "make" to "./main" seems not write on github(or I didn't see it).  
     So I asked 曾若恩 for help, she send me this:https://medium.com/@AleNunezArroyo/run-google-gemma-llama-cpp-gguf-inference-in-google-colab-ecb1c03bc440  
     After learning this page, I solve my problem thanks to 曾若恩.  
  3. Unexecpted error:  
     As I mentioned from e-mail, maybe due to the mechanism of google colab, I found an unexpected error during runnig basic part in gpu:  
     ![image](https://github.com/yanyoulin/llama.cpp-for-Warm-Up-lab/blob/0ae4c1d346490280362ccc9d7c29cf8fed9029be/%E8%9E%A2%E5%B9%95%E6%93%B7%E5%8F%96%E7%95%AB%E9%9D%A2%202024-05-26%20002307.png)
* What you observed between CPU / GPU performance ?    
* Will quantization or smaller-parameters model impact model accuracy or inference throughput ? If so , what's the variation?



