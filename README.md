---

# Question Generator Project

This project generates short answer questions and multiple-choice questions (MCQs) from a given context using the answer provided.

## Files and Notebooks

- **train.ipynb**: Contains the code for fine-tuning the T5 base model to generate questions.
- **Load_model.ipynb**: Loads the trained model from the drive and uses it to generate short answer questions or MCQs, depending on the need. This notebook also utilizes Streamlit for deployment.

## Instructions to Run the Project

1. **Download the Trained Model**:
   - Download the trained model and tokenizer from [this Google Drive link](https://drive.google.com/drive/folders/11uzZVjyk8cZB12IFIJUMQ6JYc-VBm650?usp=drive_link) and save them in your drive.

2. **Load the Model**:
   - Connect the notebook to your drive and load the model.

3. **Ngrok Authentication**:
   - Replace the ngrok authentication key with your token. (You need an ngrok account for this).

4. **Run the Streamlit App**:
   - Click on the generated URL to view the Streamlit app.

---
