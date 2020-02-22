# C_codeGeneratorUsingRNN
Use an **RNN** to generate C code.

We'll learn how to generate text using an RNN. Specifically, we'll use an RNN to generate C code. For those who're not familiar with C, it's a general purpose programming language like Python. But C was developed in the 70s. It is much much faster than Python. The numpy library is written in C because Python is very slow in linear matrix operations. The Linux operating system is written using C. And we'll use the Linux kernel code to train our RNN model.  
 
### Data source :https://github.com/torvalds/linux/tree/master/kernel   

### Platform used: https://www.nimblebox.ai/

We're going to build a C code generator by training an RNN on a huge corpus of C code (the linux kernel code). You can download the C code used as source text from the following link: https://github.com/torvalds/linux/tree/master/kernel  
You can find the code in this GitHub repository.     
Download the code and make sure that you gather all the C files present inside the folders of the kernel at one single place.
Create folder named "linux_kernel" to store the C-code downloaded from the github repo.

## Notebook Overview  
1. Preprocess data  
2. LSTM model  
3. Generate code  

### Conclusion :  
The model accuracy is approximately 69%. But accuracy is not a reliable metric in text generation. To really see how the model is performing, we need to generate the text and see it for ourselves. In the next segments, we'll generate the C code using the trained LSTM model.  
The code to generate the code is ready. Let's see the generated code in the jupyter notebook.

