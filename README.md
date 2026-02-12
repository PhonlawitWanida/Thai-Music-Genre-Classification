# Thai-Music-Genre-Classification
Audio classification project analyzing traditional Thai music identities. Utilizes Python and Librosa for feature extraction (MFCCs, Chroma) to train a Random Forest model.
💻 How to Run (Google Colab)
1. Inference (Predicting Genre)
Open notebooks/Run_on_web.ipynb in Google Colab.

Load the pre-trained model from the models/ folder.

Upload your .mp3 or .wav file.

Run the cells to see the predicted Thai Region.

2. Training a New Model
Open notebooks/Project_DE242_Music_Genre_Classification.ipynb.

Upload your dataset into the Dataset/ folder structure.

Run the pipeline to process audio, extract features, and retrain the Random Forest model.

🌐 Future Work & API Usage
Note regarding Web Interface: This repository currently provides the Backend Logic and API Endpoint (via Flask/Python).

It does not include a frontend HTML/CSS interface.

For Developers: You can consume the inference logic by sending an HTTP POST request with an audio file to the endpoint defined in Run_on_web.ipynb to build your own UI.
<img width="1483" height="584" alt="image" src="https://github.com/user-attachments/assets/5dc4610f-91b6-411a-bd1d-debfa32e30d9" />

<img width="1230" height="499" alt="image" src="https://github.com/user-attachments/assets/d5a5d387-6a57-4117-a3cd-a4426ae44fcc" />

