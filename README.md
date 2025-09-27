# -i21-1655-Ahmad-Akhtar-A1-CS452
DL ass-1


Network details: Architecture (VGG16/ResNet50 with heads), params (model.summary()), training settings (epochs=20+10, batch=32, Adam lr=0.001/1e-5, frozen then fine-tune), rationale: VGG for simplicity, ResNet for deeper residual learning.

Dataset splits: Train/Val/Test sizes, stratified on exp.

Training graphs, Performance measures , Performance comparison: Table from comparison_df, discuss continuous metrics (RMSE for error, CORR for linear relation, SAGR for sign match – useful in wild for polarity, CCC for overall agreement – best for wild as combines corr and mean diff).


 <img width="1145" height="211" alt="Screenshot 2025-09-27 233755" src="https://github.com/user-attachments/assets/8d476057-44cf-40a8-a830-9f3a92b6a67c" />
