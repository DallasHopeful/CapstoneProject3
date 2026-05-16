## Capstone Project 3

EG Capstone Project 3 focusing on Sequence-to-Sequence (seq2seq) modeling utilizing a BERT encoder-decoder architecture.

## 📁 Repository Structure

* `EG_Project_3_v4_finish.ipynb` - **Primary Jupyter Notebook containing the final model and execution workflows.**
* `Data/` - Directory designated for training and testing datasets.
* `outputs_seq2seq_bert_encoder_decoder/` - Directory for model output check-pointing and validation logs.
* `previous_versions/` - Directory holding older experimental versions and iterations of the project notebooks.
* `Project 3 Pitch Report.docx` - Pitch documentation outlining project objectives and approach.

## 🚀 Local Setup & Installation

To run this project locally, ensure your environment and files are structured according to the guidelines below.

### 1. File and Dataset Setup
The project notebooks are configured to fetch datasets using relative local paths. For successful local execution, you must structure the project directory as follows:

```text
CapstoneProject3/
├── EG_Project_3_v4_finish.ipynb
├── Data/
│   ├── [Place your data files here]

```

> ⚠️ **Important:** Make sure your dataset files are placed inside the `Data` folder within the project directory before attempting to execute cells in the Jupyter notebook.

### 2. Large Model Weights & Outputs (External Download)

Due to file size limitations on GitHub, the complete seq2seq outputs and the massive pre-trained/fine-tuned **BERT encoder/decoder save point files** are hosted externally.

* **Download Link:** [Google Drive Model Directory](https://drive.google.com/drive/folders/1k70rflzxNayxTmhdSETZ6O11DupISsUa?usp=share_link)

If you plan to perform local evaluation or resume training from a specific save point, download the required files from the Google Drive folder link above and place them into your local `outputs_seq2seq_bert_encoder_decoder/` folder.

## 🛠️ Usage

1. Open your terminal or command prompt.
2. Navigate to the project root directory.
3. Launch Jupyter Notebook or JupyterLab:
```bash
jupyter notebook

```


4. Open and execute `EG_Project_3_v4_finish.ipynb` to evaluate the final model architecture.

```

```
