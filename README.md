## Sand-tray Playground

### Introduction
In this project, I aim to establish an online playground where users can explore their imagination and thoughts through a sand tray—a classic tool for psychological evaluation and therapy.

### Pipeline
When a user logs into the page, they see a blank canvas alongside categories of social and natural objects (e.g., a house, a flower). The user can fill the board with various objects of their choice. Then, a game agent generates a report interpreting the sand tray, simulating psychological therapy.

### Implementation
#### Object Detection – Computer Vision Model
1. Task Objective: Identify objects in the image, construct spatial relations, and provide a structured description of the sand tray.
2. Data: Names and locations of the miniatures on the canvas.
3. Model: Object detection architecture (e.g., R-CNN, YOLO, Detectron2), or pre-trained models via transfer learning from large datasets.

#### Interpreter – Natural Language Generation Model
1. Task Objective: Given a description of the sand tray, generate a psychological report.
2. Data: A textual description of the sand tray image, including the locations of objects.
3. Model: A pre-trained language model, further trained and fine-tuned for domain-specific purposes (i.e., a sand tray interpreter).

### Timeline
Set up interface (by 1/14) <br/>
Develop CV model pipeline (by 1/21) <br/>
Train language model (by 1/28) <br/>
Test
