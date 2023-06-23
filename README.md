**Hospital Activity Dataset**

The Hospital Activity Dataset is a valuable resource consisting of 5,770 images depicting 25 common activities observed within healthcare facilities. With each activity category containing between 180 and 396 images, this dataset serves as a comprehensive collection for the development and evaluation of computer vision models focused on activity recognition in hospital settings. Researchers and developers can leverage this dataset to train and assess algorithms that accurately identify and classify various actions in healthcare environments. The diverse range of images captures the nuances and complexities of different activities, enabling the creation of robust and efficient recognition systems. 

<p align="center">
<img width="640" alt="image" src="https://github.com/Wangmmstar/hospital-activity-dataset/assets/29313094/601c2aba-4fa3-43b6-b4e8-df38c97a6639">
</p>

The table below shows the activity description and statistics.

| Activity | Description | Shortened | Number of people | Count |
| --- | --- | --- | --- | --- |
| Measuring blood pressure | Medical staff is helping a patient to measure blood pressure. | Measuring | 2 | 250 |
| Comforting | Medical staff is comforting or expressing concern to patients. | Comforting | 2 and above | 189 |
| Carrying patients | Critically ill patients are being carried by first responders, doctors, or nurses. | Carrying | 2 and above | 231 |
| Consulting | Patients are consulting a professional doctor or nurse about their condition. | Consulting | 2 and above | 197 |
| Scanning | Doctors are helping patients with MRIs or full-body scans in large instruments. | Scanning | 1 and above | 220 |
| Doctor meeting | Doctors are having an in-person academic meeting around the table | Meeting | 2 and above | 203 |
| Analyzing samples | Doctors are analyzing blood or drug sample in the hospital laboratory analysis room. | Analyzing | 1 and above | 247 |
| Doctor sleeping | Doctors or first responders are temporarily sleeping and resting in the hospital. | Sleeping | 1 and above | 293 |
| Eating | Inpatients in wheelchairs or beds are eating. | Eating | 1 and 2 | 198 |
| Family visiting | Family members are visiting a patient who lying or sitting on the bed. | Visiting | 3 and above | 202 |
| Cleaning | Cleaning staff is disinfecting and clean within a hospital. | Cleaning | 1 and above | 262 |
| Patient sitting in a wheelchair | A patient is sitting alone in a wheelchair. | Wheelchair_1 | 1 | 253 |
| Patient sitting in a wheelchair with assistance | A patient is sitting in a wheelchair with an or multiple assistant or nurse next to it. | Wheelchair_2 | 2 and above | 202 |
| Infusing | A patient is being infused while lying or sitting on the bed. | Infusing | 1 and above | 165 |
| Injecting | A patient is being injected by a doctor. | Injecting | 2 and above | 197 |
| Lying in a bed | Patients are lying in the nursing bed. | Lying | 1 and above | 203 |
| Online meeting | A doctor or paramedic is meeting online using a computer. | O-meeting | 1 | 205 |
| Performing surgery | Doctors and nurses are performing surgery for a patient in a professional operating room. | Operating | 2 and above | 193 |
| Patient walking | A patient is walking alone in a hospital hallway or with one/couple of nursing staff. | Walking | 1 and above | 180 |
| Working in pharmacy | Doctors in pharmacy are sorting, helping clients, or recording. | Pharmacy | 1 and above | 248 |
| Sitting on a bed | Patients are sitting on the nursing bed. | Sitting | 1 | 194 |
| Discussing | A group of doctors or paramedics is standing together and discussing. | Discussing | 2 and above | 181 |
| Checking temperature | Nursing staff is using thermometer guns to measure the temperature of the patients. | Checking | 2 and above | 343 |
| Patient waiting | Patients are waiting in a waiting room or hallway for treatment or examination. | Waiting | 1 and above | 396 |
| Examining X-ray | Doctors are examining the X-ray pictures by himself/herself or with a colleague or nurse. | Examining | 1 and 2 | 318 |


We utilized the Barnes-Hut t-SNE algorithm to visualize raw image features in 2D space. t-SNE is a nonlinear dimensionality reduction technique that is useful for embedding high-dimensional data into a lower-dimensional space.

<p align="center">
<img width="647" alt="image" src="https://github.com/Wangmmstar/hospital-activity-dataset/assets/29313094/948b4aee-f970-4b75-9e22-c2f5bc825c7e">
</p>
