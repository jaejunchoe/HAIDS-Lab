## HAIDS Lab
This repository is a shared space for project conducted in collaboration with HAIDS Lab


## Expected Update Content
1. Analysis of the paper on [D-attn /  Interpretable Convolutional Neural Networks with Dual Local and Global Attention for Review Rating Prediction](https://dl.acm.org/doi/10.1145/3109859.3109890).
2. Unified preprocessing method for applying to three different models(DeepCoNN, Transnet, D-attn)
3. Modularization of each model
<br/>

## Updated Record
# 2025.01.03
`1) Dataset`<br/>
- **'Dataset/DeepCoNN & D-attn folder'**: Updated with the complete datasets (xlsx, json) for both DeepCoNN and D-attn, as well as the train (csv), valid (csv), and test (csv) files.
- **'Dataset/Transnet folder'**: Updated with the complete datasets (xlsx, json) for Transnet, along with the train, valid, and test (csv) files.
- **'Dataset folder'**: Updated with files required for preprocessing, including combined_word_emb(pkl), punctuation(txt), and stopword(txt).
- **Download glove.6B.50d(txt)**: The file glove.6B.50d(txt) is too large to upload to GitHub. You can download it from the following link and locate the file: <br/>
URL: [glove.6B.zip link](https://nlp.stanford.edu/data/glove.6B.zip)
<br/>

`2) Model`<br/>
- **'DeepCoNN & D-attn/DeepConn_and_D_attn_Preprocessing_Subscription_Boxes_Dataset.ipynb'**: Updated a shared preprocessing file for DeepCoNN and D-attn
- **'DeepCoNN & D-attn/Upload_ver02_DeepCoNN.ipynb'**, **'DeepCoNN & D-attn/Upload_ver02_D_attn_model.ipynb'**: Updated modeling files for DeepCoNN and D-attn:
- **Transnet/Transnet_Preprocessing_Subscription_Boxes_Dataset.ipynb**: Updated a preprocessing file for Transnet:
- **'Transnet/Upload_Transnet.ipynb'**: Updated a modeling file for Transnet:
<br/>


`3) Past Files Folder`<br/>
- **'Past files folder'**: All previously existing files have been moved to the 'Past files folder' to accommodate the updated versions. Files are categorized according to their respective models.
<br/>

`3) Visualized Framework`<br/>
'**Preprocessing Framework.md.'**: The Processing Framework for the datasets of DeepCoNN & D-attn and Transnet has been visualized and updated.
<br/>

# 2025.01.02
- Uploaded the **'D-attn/Upload_ver02_D_attn_model.ipynb'** file. <br/>
(The existing D-attn model, **'D-attn/Upload_D_attn_model.ipynb'**, has been moved to the **'Past files folder'**)

# 2024.12.27
- If you want to run the TransNets model, you should first execute the **'Transnet/Upload_preprocess'** file.

# 2024.12.26
- Uploaded the **'Dataset/train, valid, test.csv'** file. <br/>
(The files are not datasets actually derived from the **Upload_Unified_Preprocessing_Subscription Boxes Dataset.ipynb** file but are datasets intended for learning purposes to understand the data structure.)

# 2024.12.24
- Uploaded the **'Upload_Unified_Preprocessing_Subscription Boxes Dataset.ipynb'** file. <br/>
(The embedding process is not included yet. This process is expected to be updated.)

# 2024.12.23
- Uploaded the **'D-attn/Upload_D_attn_model.ipynb'** file. (Reference: [CNN-with-Dual-Local-and-Global-Attention](https://github.com/seongjunyun/CNN-with-Dual-Local-and-Global-Attention/tree/master?tab=readme-ov-file)) <br/>
- **Detailed explanations** regarding hyperparameter and the structure of the modal have been added. 

# 2024.12.21
 - Uploaded the **'DeepCoNN/Upload_DeepCoNN.ipynb'** and **'Transnet/Upload_Transnet'**, **'Transnet/Upload_preprocess'** file.

# 2024.12.20
 - Created a repositories.
