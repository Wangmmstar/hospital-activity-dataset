**Hospital Activity Dataset**

The construction of the hospital activity dataset is composed of two steps that are image downloading and data cleaning. We selected 25 common activities that occur in healthcare facilities, each of which has unique implications for robotic disinfection. Images were initially downloaded from Getty and Shutterstock, two stock photography websites with extensive image libraries. Each image comes with a textual description, written by the image's creator, that aligns with its visual content. Using relevant search terms, we obtained approximately 1,000 images corresponding to each hospital activity of interest. The dataset was then refined through a verification process, during which mislabeled images were either deleted or reassigned to their appropriate categories. We also eliminated images of poor quality, such as those that were blurry or didn't clearly depict the specified human activity. Despite these eliminations, our dataset still boasts significant diversity in terms of background, human pose, and appearance within each category. To ensure dataset quality, the finalized set of images underwent additional review by a separate human labeler. The final dataset comprises 180 to 396 images per class, with a total of 5,770 images collected. 

<img width="640" alt="image" src="https://github.com/Wangmmstar/hospital-activity-dataset/assets/29313094/601c2aba-4fa3-43b6-b4e8-df38c97a6639">

We utilized the Barnes-Hut t-SNE algorithm is adopted to visualize raw image features in 2D space. t-SNE is a nonlinear dimensionality reduction technique that is useful for embedding high-dimensional data into a lower-dimensional space.

<img width="647" alt="image" src="https://github.com/Wangmmstar/hospital-activity-dataset/assets/29313094/948b4aee-f970-4b75-9e22-c2f5bc825c7e">

