# DMVAN
Interpretable Multimodal Sentiment Classification Using Deep Multi-View Attentive Network of Image and Text Data

## Article's Abstract:
Multimodal data can convey user emotions and feelings more effectively and interactively than unimodal content. Thus, multimodal sentiment analysis (MSA) research has recently acquired great significance as a field of study. However, most current approaches either acquire sentimental features independently for each modality or simply combine multiple modal features. Thus, semantic details pertinent to sentiment analysis and the relationship between visual and textual content are neglected. Furthermore, most available multimodal datasets are sentiment-annotated, although user emotions are usually rich and unlimited. Motivated by these observations, this paper proposes a novel deep multi-view attentive network (DMVAN) for robust multimodal sentiment and emotion classification. The DMVAN model has three phases: feature learning, attentive interaction learning, and cross-modal fusion learning. During the feature learning phase, visual features from a multi-view perspective (region and scene) and textual features from various levels of analysis (word, sentence, and document) are extracted to capture information effectively for accurate classification. In the attentive interaction learning phase, the image-text interaction learning mechanism is employed to enhance visual and textual information interaction by extracting sentimental and discriminative visual features and utilizing the textual information to guide the learning process of image features. Moreover, a cross-modal fusion learning module is developed to incorporate different features into a comprehensive framework that takes advantage of the complementary aspects of multiple modalities. Then, a multi-head attention mechanism is employed to extract and merge sufficient data from the intermediate features, thereby aiding in developing a robust joint representation. Finally, a multi-layer perceptron with multiple stacking-fully connected layers is used to deeply fuse the modal features, thereby enhancing sentiment classification performance. An interpretable multimodal sentiment classification model is further developed utilizing the local interpretable model-agnostic explanation model (LIME) to ensure the model’s explainability and strength. To perform a multimodal emotion classification, an image-text emotion dataset named Emotion-Getty (EMO-G) is constructed from Getty Images and labeled by distinct emotions. The proposed model is tested on three real-world datasets, attaining 99.801% accuracy on Binary_Getty (BG), 96.867% on Twitter, and 96.174% on the EMO-G dataset. These results show that the suggested model outperforms single-model techniques and current state-of-the-art methodologies based on model evaluation criteria.

![GA](https://github.com/cominsys/DMVAN/assets/44108907/0543d509-e538-4ef3-be94-0221aa972abe)


### Cite:
```bib
@ARTICLE{10227255,
  author={Al-Tameemi, Israa Khalaf Salman and Feizi-Derakhshi, Mohammad-Reza and Pashazadeh, Saeid and Asadpour, Mohammad},
  journal={IEEE Access}, 
  title={Interpretable Multimodal Sentiment Classification Using Deep Multi-View Attentive Network of Image and Text Data}, 
  year={2023},
  volume={11},
  pages={91060-91081},
  doi={10.1109/ACCESS.2023.3307716}}
