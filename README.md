# SSCED: Single-Shot Crime Event Detector with Multi-View Surveillance Image Dataset

We introduce a novel benchmark dataset, which consists of crime event-based surveillance images with well-informed annotations. The dataset has crime videos and images categorized into 12 different categories, with a separate normal dataset extracted from scenes that ended five seconds before the crime, with a duration of 10 seconds. To evaluate the dataset, we narrowed down 13 categories to 6 (assault, robbery, swoon, kidnap, burglary, and normal) and conducted experiments on a total of 2,054,013 shuffled and randomly selected frames from the videos. We used four CNN models with a single transformer model for training and validation, with a smaller sub-dataset of 8,500 frames randomly extracted from each category video, totaling 51,000 frames. Despite a 1:40 ratio of the train-test split, the dataset performed well on common CNN models, while leaving some challenges for the Transformer model.

# Data
We collected surveillance dataset from AI Hub. As mentioned above, the dataset consists of 6 categories with total of 2,054,013 shuffled and randomly selected frames from the videos. There are 8,500 frames randomly extracted from each category video, totaling 51,000 frames for training and validation.

# - Examples of dataset
![swoon_2](https://user-images.githubusercontent.com/90234691/227839161-c87a23f5-093c-4c52-9c76-a9077977ece0.jpg)
![swoon_1](https://user-images.githubusercontent.com/90234691/227839177-d8f265ee-1fa9-40dc-b415-e265eb732616.jpg)
![robbery_2](https://user-images.githubusercontent.com/90234691/227839185-fe50e648-8006-48bb-9c23-2598243c6f6c.jpg)
![robbery_1](https://user-images.githubusercontent.com/90234691/227839187-a410112d-5072-465d-bf79-118b2fe8788b.jpg)
![normal_2](https://user-images.githubusercontent.com/90234691/227839194-9b190197-45fa-4c7e-b82f-1662ea8d0238.jpg)
![normal_1](https://user-images.githubusercontent.com/90234691/227839200-fa1b361a-a09f-401d-99f4-abfdfec5ac6f.jpg)
![kidnap_2](https://user-images.githubusercontent.com/90234691/227839202-b0b16f74-8aa7-4998-89fd-18455b896d2d.jpg)
![kidnap_1](https://user-images.githubusercontent.com/90234691/227839203-87329020-74cf-4521-b144-091082392001.jpg)
![burglary_2](https://user-images.githubusercontent.com/90234691/227839206-8b41ca6c-b620-4662-b83b-2eb02a415a2f.jpg)
![burglary_1](https://user-images.githubusercontent.com/90234691/227839209-341a5269-a023-4d3c-87b7-00fa6c774210.jpg)
![assault_2](https://user-images.githubusercontent.com/90234691/227839212-968c65eb-e617-4705-b8f4-760c2ac39739.jpg)
![assault_1](https://user-images.githubusercontent.com/90234691/227839218-d0288846-7258-4a64-bb85-5a691b71fb55.jpg)
