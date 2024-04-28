# Stock-price-prediction-with-financial-data-of-company
This project is a group project for ECSE 552 at McGill University.
Authors: 
  **Qingnan Li,
  Tony Xu,
  Manas Manoj Bedekar,
  Sansitha Panchadsaram**.
The project including dataset preparation and models implementation. The dataset of financial data of more than 2000 companies are in **"main.csv"**.
You can access the file with the given link here: **https://drive.google.com/file/d/1Um4BCBiIkHRkKhDcNJLuFKZDsjHcX5C_/view?usp=drive_link**
The jupyter notebook file **"MarketPredictor(1).ipynb"** has the code for data preprocessing and postprocessing, models implementation, models training, and models validation. We have investigated a comparative study on MLP, LSTM, LSTM with attention mechanism(AM), CNN_BiLSTM_AM, and Bi_LSTM.
In preprocessing of data, we only keep companies that have more than 80 quarters(80 samples), otherwise they are disgarrded. For those have 80 and more than 80 samples, we limit the number of samples to exactly 80 samples.
The jupyter notebook file **"Analysis (1)"** has the code to generate results including plot, tables, etc. In the very end, the plot of real vs. prediction has shown for one company with lowest error to demonstrate the performance of the model.
email at qingnan.li@mail.mcgill.ca for any concerns.
Have fun!
