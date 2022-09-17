---
title: 'Fused Deep Neural Network based Transfer Learning in Occluded Face Classification and Person re-Identification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Prasanalakshmi B
  - Salem Alelyani
  - Mohammed Saleh Alsaqer

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'



date: '2022-05-15T07:52:15.206Z'
doi: 'https://doi.org/10.48550/arXiv.2205.07203'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *Archive*
publication_short: In *arXiv*

abstract: >-
  <p align="justify">

  Recent period of pandemic has brought person identification even with occluded face image a great importance with increased number of mask usage. This paper aims to recognize the occlusion of one of four types in face images. Various transfer learning methods were tested, and the results show that MobileNet V2 with Gated Recurrent Unit(GRU) performs better than any other Transfer Learning methods, with a perfect accuracy of 99% in classification of images as with or without occlusion and if with occlusion, then the type of occlusion. In parallel, identifying the Region of interest from the device captured image is done. This extracted Region of interest is utilised in face identification. Such a face identification process is done using the ResNet model with its Caffe implementation. To reduce the execution time, after the face occlusion type was recognized the person was searched to confirm their face image in the registered database. The face label of the person obtained from both simultaneous processes was verified for their matching score. If the matching score was above 90, the recognized label of the person was logged into a file with their name, type of mask, date, and time of recognition. MobileNetV2 is a lightweight framework which can also be used in embedded or IoT devices to perform real time detection and identification in suspicious areas of investigations using CCTV footages. When MobileNetV2 was combined with GRU, a reliable accuracy was obtained. The data provided in the paper belong to two categories, being either collected from Google Images for occlusion classification, face recognition, and facial landmarks, or collected in fieldwork. The motive behind this research is to identify and log person details which could serve surveillance activities in society-based e-governance.

  </p>

# Summary. An optional shortened abstract.
summary: 

tags: 
  - Occlusion detection
  - face recognition 
  - MobileNet V2
  - ResNet 
  - GRU

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2205.07203.pdf'
url_code: 'https://github.com/MohamedMohana/Face-Mask-Detection-and-Recognition'
url_dataset: 'https://drive.google.com/file/d/1imONpvavj1_mLGH1hekEXh16loWiJwwp/view?usp=sharing'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
  #- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: "" #example
---
