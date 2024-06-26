# BA865 Face Recognition
**Group 8: Yu-Fang(Unice) Liao, Han Nga Chan, Yumeng Tang**

**The order to read our Jupyter notebooks:**


![Blank diagram](https://github.com/BA-865/BA865FaceRecognition_Group8_B1/assets/74975816/48525360-4b4d-4f28-b142-181624d38017)



We've divided our work into four notebooks. The first, **"BA865_Project_Introduction_&_Conclusion,"** covers our motivation, problem statement, data introduction, webscraping, and facial detection. It also addresses challenges, resolutions, conclusions, limitations, and next steps.


The next three notebooks each focus on specific model results. The first, **"CNN_Customized_ResNet18_ResNet50.ipynb,"** explores CNN implementations, including custom CNN, ResNet18, and ResNet50 modifications for face recognition. Output and report of this notebook can be found in the following links: 

- All Results: https://wandb.ai/unice-yfl/Team%20Project%20-%20Face%20Recognition%20/reports/CNN-ResNet18-ResNet50-All-Results--Vmlldzo3NzA0MDk4?accessToken=30pss2rl6u3bcc1oezr9zjb5xj3agde064626uedrqw2o3x0ack8k3b8rmqgxnef

- Comparison of #Classes (205 vs 105): https://wandb.ai/unice-yfl/Team%20Project%20-%20Face%20Recognition%20/reports/-Classes-Comparison-205-vs-105---Vmlldzo3NjkwNjM1?accessToken=patkv8aqt24a78xu96wott8qb1ylxnari64chzp3zyd00b3cbfy82fdhal4e5dgl

- Hyper Parameter Tuning of ResNet50 for Male Dataset: https://wandb.ai/unice-yfl/Team%20Project%20-%20Face%20Recognition%20/reports/Hyperparameter-Tuning-of-ResNet50-for-Male-Datasets--Vmlldzo3NjkwMzAy?accessToken=b2n05dh4xe1xlkm2nbk61xuodbfc2nb5yymghl43cvemaiqopq346vmnbk6iio1n  

- Hyper Parameter Tuning of ResNet50 for Female Dataset: https://api.wandb.ai/links/unice-yfl/8q6plstt

- Comparison of Female vs. Male: https://wandb.ai/unice-yfl/Team%20Project%20-%20Face%20Recognition%20/reports/Comparative-Performance-of-ResNet50-on-Female-vs-Male-Datasets--Vmlldzo3Njk3MjIw?accessToken=3rbkneqy7jli5uryht86uhybf8tlfd6bh962poyg1chanvpxm47rrikvxbj86wrx


The second notebook, **"ViT_Model.ipynb"** starts with logistic regression as a non-deep learning baseline, then delves into Vision Transformer models. It includes runs on 20 classes for both female and male celebrities, hyperparameter tuning, and experiments with 50 classes.


Finally, **"VGG_Model.ipynb"** details the VGG model implementation. This includes using the pre-trained VGG16 model, adjusting its layers, and tuning hyperparameters for varying class numbers (20, 50, and 105) to enhance accuracy.
