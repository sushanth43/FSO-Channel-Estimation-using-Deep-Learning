# FSO-Channel-Estimation-using-Deep-Learning
FSO Channel Estimation using Deep Learning
🚀 Deep Learning-Based Channel Estimation in Free-Space Optical (FSO) Communication 🚀

I’m thrilled to share my current project where I’m exploring how Bidirectional LSTM models can be used to estimate channel gain in Free-Space Optical (FSO) communication systems — a field that blends wireless communication theory, optical impairments, and AI.

📌 Objective:
To develop a deep learning model that can predict the true channel gain (h_true) in FSO systems affected by:

🌫️ Weak atmospheric turbulence (Log-normal fading)

🎯 Pointing error (due to jitter)

🌥️ Visibility-based atmospheric loss (Kim's model)

These channel conditions are dynamic, and accurate estimation is crucial for calculating:

📉 Bit Error Rate (BER)

⚠️ Outage Probability

🛠️ What I’ve Done So Far:
🔹 Simulated a dataset of received signals under varying turbulence, pointing errors, and visibility.

🔹 Built a Bidirectional LSTM model trained to estimate average channel gain over a time window.

🔹 Evaluated the model against traditional estimators:

Maximum Likelihood Estimator (MLE)

Minimum Mean Square Error (MMSE)

Blind Estimator

🔹 Computed BER and outage performance using the predicted channel estimates.


🔧 Still working on improving outage probability estimation, particularly in aligning the LSTM-based results with theoretical (Meijer G-function) and traditional estimators.

🧠 The model’s performance is close — but still needs enhancement to consistently outperform conventional methods under all channel conditions.

📊 Analysis So Far:
R² Score: 0.99
Outage probabilities benchmarked with Meijer G-function model
