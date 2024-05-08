This project consists of python file for a Text Summarizer using Transformer based model T5.

The dataset used consists of a csv file which has the following columns:

Author 

date 

headlines

read_more

text

ctext

The columns Text and ctext are used.
The text contains the complete news text.
The Ctext contains the summary of that news in the corresponding row.


**Model and Architecture**

•	The project utilizes the T5 (Text-To-Text Transfer Transformer) model, a Transformer-based architecture specifically designed for text generation tasks.

•	Fine-tuning is performed on the pre-trained T5 model using transfer learning techniques to adapt it to the text summarization task.


**Training and Evaluation**

•	The dataset is split into training and testing sets, with appropriate data loaders created using PyTorch Lightning.

•	During training, the model is optimized using the AdamW optimizer with a specified learning rate.


The model is trained and then tested on user text for which it generates the summary.


