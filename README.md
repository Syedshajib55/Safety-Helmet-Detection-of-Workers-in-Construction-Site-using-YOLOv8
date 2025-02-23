Abstract—The safety of construction workers is a paramount
concern in the modern construction industry. A significant
proportion of injuries and fatalities on construction sites are
attributed to a lack of adherence to safety regulations, often
resulting from the non-utilization of Personal Protective Equipment (PPE) by workers. Additionally, effective monitoring of
construction areas by site supervisors can be challenging due
to the vastness and complexity of construction sites. Manual
monitoring, while a crucial aspect of construction safety management, is often hindered by time constraints and associated
costs. To address these challenges, the application of computer
vision and Convolutional Neural Network(CNN) techniques has
led to the development of automated helmet and jacket detection
systems. This research employs the YOLOv8 object detection
algorithm to explore the efficacy of safety helmet detection,
aiming to enhance the accuracy of automated safety helmet
detection systems. The YOLOv8 object detection algorithm is
a robust tool for recognizing objects in images. Our dataset
comprises a total of 4,200 images, including 4,000 images of hard
hats and jackets obtained from Kaggle [25], supplemented by
200 images depicting foggy, rainy, and nighttime conditions from
our custom collection sourced from the internet. The dataset
was meticulously divided into training, testing, and validation
sets, following a ratio of 60%, 20%, and 20%, respectively. The
experimental results revealed that the YOLOv8m architecture
achieved an accuracy of 92%, demonstrating its effectiveness
in detecting safety helmets under various lighting conditions,
including low-light environments. This performance highlights
the potential of the proposed approach for real-world applications
in construction site safety monitoring. This developed model
primarily focuses on detecting helmets and jackets in real-time
in adverse weather conditions such as rainy, foggy, and low-light
environments. It triggers an alarm if any workers are not wearing
their helmets and jackets. We have also discussed model training,
system structure, and performance measures.
