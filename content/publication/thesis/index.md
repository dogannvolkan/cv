---
title: 'Deep Learning Classification of Cognitive Workload Levels from EEG Wavelet Transform Images'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Volkan Dogan

date: '2023-10-02T:00:00:00Z'
doi: ''

abstract: Electroencephalogram (EEG) signals provide a non-invasive method to study cognitive processes. This study aimed to classify Multi-Attribute Task Battery (MATB) task difficulties based on wavelet transform images of EEG signals using deep learning models. An EEG dataset collected from 29 subjects while performing the MATB tasks of varying difficulties by Hinss et al. (2023) were transformed into wavelet images that can accommodate time-frequency information at the same time for further analysis. Three deep learning models, EfficientNet-B0, ResNet18, and ResNet50, were trained and tested on these images under different conditions, including pretrained and non-pretrained models, and using different optimizers. The models' performance was evaluated based on overall accuracy and accuracy by subject, EEG region, and task difficulty. The pretrained EfficientNet-B0 model achieved the highest overall accuracy (77.56%). However, the performance varied significantly across subjects and task difficulties, indicating limited generalizability. The model's accuracy was lower for medium tasks, suggesting difficulty in distinguishing between medium and other levels of difficulty. While deep learning models can achieve high accuracy in classifying MATB task difficulty based on EEG signals, their performance varies across individuals and task difficulties. Further research is needed to improve model generalizability, optimize performance across all task difficulties, and validate the models on larger and more diverse datasets.

# Summary. An optional shortened abstract.
summary: The study aimed to classify task difficulties using wavelet transform images of EEG signals and deep learning models. The EfficientNet-B0 model achieved the highest accuracy, but its performance varied significantly across individuals and task difficulties, indicating limited generalizability. The study suggests a need for further research to improve model generalizability, optimize performance, and validate the models on larger, more diverse datasets.

tags: [EEG, Deep Learning, Cognitive Workload, Wavelet Transform, Task Difficulty Classification]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: '' # to be added later on
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://open.metu.edu.tr/handle/11511/105413'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
