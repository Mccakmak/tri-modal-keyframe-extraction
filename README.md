# TriPSS: A Tri-Modal Keyframe Extraction Framework Using Perceptual, Structural, and Semantic Representations

## 📂 Directory Structure
```
Keyframe Extraction/
├── requirements.txt  # Includes libraries
├── main.py           # Runs the keyframe extraction as the main file
│
├── feature_extraction/                # Feature extraction modalities
│   ├── color_features/                # Color feature extraction content
│   │   └── color_feature_extraction.py  # Code for generating the color features
│   │
│   ├── image_features/                # Image feature extraction content
│   │   └── image_feature_extraction.py  # Code for generating the image features
│   │
│   ├── content_features/              # Content description feature extraction
│   │   ├── content_feature_extraction.py  # Generating content description features
│   │   └── content_embeddings.py         # Converting content descriptions to embeddings
│   │
│   └── cross_modal_features/           # Multi-modal fusion content
│       └── feature_level_fusion.py     # Fusion for color, image, and text features
│
├── clustering/                       # Clustering content
│   └── cluster_frames.py            # Clusters the frames
│
├── frame_selection/                 # Steps for keyframe selection
│   ├── candidate_frame_selection.py  # Finds candidate keyframes from clusters
│   └── keyframe_selection.py         # Selects final keyframes by filtering candidates
│
└── evaluation/                      # Evaluation of the framework
    └── TriPSS_evaluation.py         # Calculates F1 scores for evaluation datasets
```

## 📝 Description
This repository contains the implementation of **TriPSS: A Tri-Modal Keyframe Extraction Framework**, designed to extract keyframes from videos using perceptual, structural, and semantic representations. 

## 📚 Citation

If you use this work, please cite our paper:

@article{cakmak2025tripss,
  title={TriPSS: A Tri-Modal Keyframe Extraction Framework Using Perceptual, Structural, and Semantic Representations},
  author={Cakmak, Mert Can and Agarwal, Nitin and Poudel, Diwash},
  journal={arXiv preprint arXiv:2506.05395},
  year={2025}
}

ACM Reference Format:
Mert Can Cakmak, Nitin Agarwal, and Diwash Poudel. 2025. TriPSS: A Tri-
Modal Keyframe Extraction Framework Using Perceptual, Structural, and
Semantic Representations. In Proceedings of the ACM MM 2025 Workshop
on Multimedia Analytics with Multimodal Large Language Models (MA-LLM
’25), October 27–28, 2025, Dublin, Ireland. ACM, New York, NY, USA, 6 pages.
https://doi.org/10.1145/3746263.3757710
