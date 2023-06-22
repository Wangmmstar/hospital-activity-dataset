**Hospital Activity Dataset**

The construction of the hospital activity dataset is composed of two steps that are image downloading and data cleaning. We selected 25 common activities that occur in healthcare facilities, each of which has unique implications for robotic disinfection. Images were initially downloaded from Getty and Shutterstock, two stock photography websites with extensive image libraries. Each image comes with a textual description, written by the image's creator, that aligns with its visual content. Using relevant search terms, we obtained approximately 1,000 images corresponding to each hospital activity of interest. The dataset was then refined through a verification process, during which mislabeled images were either deleted or reassigned to their appropriate categories. We also eliminated images of poor quality, such as those that were blurry or didn't clearly depict the specified human activity. Despite these eliminations, our dataset still boasts significant diversity in terms of background, human pose, and appearance within each category. To ensure dataset quality, the finalized set of images underwent additional review by a separate human labeler. The final dataset comprises 180 to 396 images per class, with a total of 5,770 images collected. 


| Activity | Description | Shortened | Number of people | Count |
| --- | --- | --- | --- | --- |
| Measuring blood pressure | Medical staff is helping a patient to measure blood pressure. | Measuring | 2 | 250 |
| Comforting | Medical staff is comforting or expressing concern to patients. | Comforting | 2 and above | 189 |
| Carrying patients | Critically ill patients are being carried by first responders, doctors, or nurses. | Carrying | 2 and above | 231 |
| Consulting | Patients are consulting a professional doctor or nurse about their condition. | Consulting | 2 and above | 197 |
| Scanning | Doctors are helping patients with MRIs or full-body scans in large instruments. | Scanning | 1 and above | 220 |
| Doctor meeting | Doctors are having an in-person academic meeting around the table | Meeting | 2 and above | 203 |
| Analyzing samples | Doctors are analyzing blood or drug sample in hospital laboratory analysis room. | Analyzing | 1 and above | 247 |
| Doctor sleeping | Doctors or first responders are temporarily sleeping and resting in the hospital. | Sleeping | 1 and above | 293 |
| Eating | Inpatients in wheelchairs or beds are eating. | Eating | 1 and 2 | 198 |
| Family visiting | Family members are visiting a patient who lying or sitting on the bed. | Visiting | 3 and above | 202 |
| Cleaning | Cleaning staff is disinfecting and cleaning within a hospital. | Cleaning | 1 and above | 262 |
| Patient sitting in a wheelchair | A patient is sitting alone in a wheelchair. | Wheelchair_1 | 1 | 253 |
| Patient sitting in a wheelchair with assistance | A patient is sitting in a wheelchair with an or multiple assistant or nurse next to it. | Wheelchair_2 | 2 and above | 202 |
| Infusing | A patient is being infused while lying or sitting on the bed. | Infusing | 1 and above | 165 |
| Injecting | A patient is being injected by a doctor. | Injecting | 2 and above | 197 |
| Lying in a bed | Patients are lying in the nursing bed. | Lying | 1 and above | 203 |
| Online meeting | A doctor or paramedic is meeting online using a computer. | O-meeting | 1 | 205 |
| Performing surgery | Doctors and nurses are performing surgery for a patient in a professional operating room. | Operating | 2 and above | 193 |
| Patient walking | A patient is walking alone in hospital hallway or with one/couple of nursing staff. | Walking | 1 and above | 180 |
| Working in pharmacy | Doctors in pharmacy are sorting, helping clients, or recording. | Pharmacy | 1 and above | 248 |
| Sitting on a bed | Patients are sitting on the nursing bed. | Sitting | 1 | 194 |
| Discussing | A group of doctors or paramedics is standing together and discussing. | Discussing | 2 and above | 181 |
| Checking temperature | Nursing staff is using thermometer guns to measure the temperature of the patients. | Checking | 2 and above | 343 |
| Patient waiting | Patients are waiting in a waiting room or hallway for treatment or examination. | Waiting | 1 and above | 396 |
| Examining x-ray | Doctors are examining the X-ray pictures by himself/herself or with a colleague or nurse. | Examining | 1 and 2 | 318 |


<img width="640" alt="image" src="https://github.com/Wangmmstar/hospital-activity-dataset/assets/29313094/601c2aba-4fa3-43b6-b4e8-df38c97a6639">

We utilized the Barnes-Hut t-SNE algorithm is adopted to visualize raw image features in 2D space. t-SNE is a nonlinear dimensionality reduction technique that is useful for embedding high-dimensional data into a lower-dimensional space.

<img width="647" alt="image" src="https://github.com/Wangmmstar/hospital-activity-dataset/assets/29313094/948b4aee-f970-4b75-9e22-c2f5bc825c7e">

