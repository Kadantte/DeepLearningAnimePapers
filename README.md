# DeepLearningAnimePapers
A list of papers and other resources on computer vision and deep learning with anime style images.
Contributions welcome!

## Contents
- [Anime Datasets](#anime-datasets)
- [Anime Papers](#anime-papers)
  - [Anime Colorization](#anime-colorization)
  - [Anime Face Recognition](#anime-face-recognition)
  - [Anime Generation](#anime-generation)
  - [Anime Inpainting](#anime-inpainting)
  - [Anime Image-to-Image Translation](#anime-image-to-image-translation)
  - [Anime Pose Estimation](#anime-pose-estimation)
  - [Anime Sketch Editing](#anime-sketch-editing)
  - [Anime Style Transfer](#anime-style-transfer)
  - [Anime Misc](#anime-misc)
  - [Anime Non-Deep Learning](#anime-non-deep-learning)
- [General Papers](#general-papers)
  - [Image Colorization](#image-colorization)
  - [Image Generation](#image-generation)
  - [Image Inpainting](#image-inpainting)
- [Other Repositories](#other-repositories)
  - [Anime Repositories](#anime-repositories)
  - [General Repositories](#general-repositories)

# Anime Datasets
- AnimeDrawingsDataset: 2000 anime/manga images with 2D pose annotations [[github]](https://github.com/dragonmeteor/AnimeDrawingsDataset) (Last updated June 10 2015)
- Manga109: 109 manga volumes from the 1970s to 2010s [[link]](http://www.manga109.org/en/)
- Nico-Illust: 400,000 images from Niconico Seiga and Niconico Shunga with metadata [[link]](https://nico-opendata.jp/en/seigadata/index.html)
- Danbooru2017: 2.9+ million images database from Danbooru with tags [[link]](https://www.gwern.net/Danbooru2017) (Last updated March 19 2018)
- Danbooru2018: 3.3+ million images database from Danbooru with tags [[link]](https://www.gwern.net/Danbooru2018) (Last updated April 04 2019)
- MyAnimeList Dataset: crawled data about 14k+ anime, 300k+ users, and 80+ million animelist records [[link]](https://www.kaggle.com/azathoth42/myanimelist) (Last Updated June 29 2018)

# Anime Papers
## Anime Colorization
- Into the Colorful World of Webtoons: Through the Lens of Neural Networks [[semanticscholar]](https://www.semanticscholar.org/paper/Into-the-Colorful-World-of-Webtoons-Through-the-Le-Cinarel-Zhang/341d3329284158ba729dad88bbb59470655a97f8) (2017)
- Style Transfer for Anime Sketches with Enhanced Residual U-net and Auxiliary Classifier GAN [[arXiv]](https://arxiv.org/abs/1706.03319) (June 11 2017)
- cGAN-based Manga Colorization Using a Single Training Image [[arXiv]](https://arxiv.org/abs/1706.06918) (June 21 2017)
- Automatic Colorization of Webtoons Using Deep Convolutional Neural Networks [[link]](https://doi.org/10371/141545) (February 2018)
- User-Guided Deep Anime Line Art Colorization with Conditional Adversarial Networks [[arXiv]](https://arxiv.org/abs/1808.03240v2) (August 10 2018)

## Anime Face Recognition
- A Multi-Label Convolutional Neural Network for Automatic Image Annotation [[link]](https://www.jstage.jst.go.jp/article/ipsjjip/23/6/23_767/_article) (July 5 2015)
- Disentangling Style and Content in Anime Illustrations [[arXiv]](https://arxiv.org/abs/1905.10742v2) (May 26, 2019)

## Anime Generation
- Towards the Automatic Anime Characters Creation with Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1708.05509) [[official implementation]](https://github.com/makegirlsmoe/makegirlsmoe_web) (August 18 2017)
- Full-body High-resolution Anime Generation with Progressive Structure-conditional Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1809.01890v1) (September 6 2018)
- StyleGAN trained on Danbooru2018 dataset [[very detailed description of everything]](https://www.gwern.net/Faces)

## Anime Image-to-Image Translation
- Improving Shape Deformation in Unsupervised Image-to-Image Translation [[arXiv]](https://arxiv.org/abs/1808.04325) (August 13 2018)
- Landmark Assisted CycleGAN for Cartoon Face Generation [[arXiv]](https://arxiv.org/abs/1907.01424v1) (July 2 2019)

## Anime Inpainting
- Joint Gap Detection and Inpainting of Line Drawings [[link]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Sasaki_Joint_Gap_Detection_CVPR_2017_paper.pdf) (2017)
- Decensoring Hentai with Deep Neural Networks https://github.com/deeppomf/DeepCreamPy (my project!) based on following Image Inpainting paper [[arXiv]](https://arxiv.org/abs/1804.07723)

## Anime Pose Estimation
- Pose Estimation of Anime/Manga Characters: A Case for Synthetic Data [[ACM]](https://dl.acm.org/citation.cfm?id=3011552) (December 4 2016)

## Anime Sketch Editing
- Sketch Simplification by Classifying Strokes [[IEEE]](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7899777) (December 4 2016)
- Mastering Sketching: Adversarial Augmentation for Structured Prediction [[Project page with paper link]](http://hi.cs.waseda.ac.jp/~esimo/en/research/sketch_master/) (January 18 2018) Note the version of this paper on arXiv is outdated.
- Real-Time Data-Driven Interactive Rough Sketch Inking [[Project page with paper link]](http://hi.cs.waseda.ac.jp/~esimo/en/research/inking/) (January 18 2018)

## Anime Style Transfer
- Style Transfer for Anime Sketches with Enhanced Residual U-net and Auxiliary Classifier GAN [[arXiv]](https://arxiv.org/abs/1706.03319v2) (June 11 2017)
- Anime Style Space Exploration Using Metric Learning and Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1805.07997v1) (May 21 2018)

## Anime Super Resolution
- Images Super Resolution [waifu2x - Image Super-Resolution for Anime-style art using Deep Convolutional Neural Networks](https://github.com/nagadomi/waifu2x), based on following paper [[arXiv]](https://arxiv.org/abs/1501.00092)

## Anime Misc
- Deep Extraction of Manga Structural Lines [[ACM]](https://dl.acm.org/citation.cfm?id=3073675) (July 2017)
- A Survey of Comics Research in Computer Science [[arXiv]](https://arxiv.org/abs/1804.05490) (April 16 2018)

## Anime Non-Deep Learning
- DrawFromDrawings: 2D Drawing Assistance via Stroke Interpolation with a Sketch Database [[PubMed]](https://www.ncbi.nlm.nih.gov/pubmed/27101610) (2016)
- Sketch-based Manga Retrieval using Manga109 Dataset [[SpringerLink]](https://link.springer.com/article/10.1007%2Fs11042-016-4020-z) (November 9 2016)
- Interactive Region Segmentation for Manga [[IEEE]](http://ieeexplore.ieee.org/document/7899993/) (December 4 2016)
- Face Detection and Face Recognition of Cartoon Characters Using Feature Extraction [[IIEEJ]](http://www.iieej.org/trans/IEVC/IEVC2012/PDF/4B-1.pdf) (2012)

# General Papers
## Image Colorization
- Real-Time User-Guided Image Colorization with Learned Deep Priors [[arXiv]](https://arxiv.org/abs/1705.02999) (May 8 2017)

## Image Generation
- StackGAN++: Realistic Image Synthesis with Stacked Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1710.10916) (October 19 2017) [[original pytorch implementation]](https://github.com/hanzhanggit/StackGAN-v2)
- Progressive Growing of GANs for Improved Quality, Stability, and Variation [[arXiv]](https://arxiv.org/abs/1710.10196) (October 27 2017) [[original theano/lasagne implementation]](https://github.com/tkarras/progressive_growing_of_gans)

## Image Inpainting
Title | Contributions | Shortcomings | Maximum Input Size | Code?
--- | --- | --- | --- | ---
Context Encoders: Feature Learning by Inpainting [[arXiv]](https://arxiv.org/abs/1604.07379) (April 25 2016) | <ul><li>First use of CNNs in image inpainting.</li><li>Utilizes an adversarial loss</li></ul> | <ul><li>Completed regions blurry.</li></ul> | 227 x 227 x 3 for random region and 128 x 128 x 3 for center region | [[official torch implementation]](https://github.com/pathak22/context-encoder)
Semantic Image Inpainting with Deep Generative Models [[arXiv]](https://arxiv.org/abs/1607.07539) (July 26 2016) | <ul><li>Missing content infered by searching for closest encoding of the corrupted image in the latent image manifold.</li></ul> | <ul><li>No end to end training.</li><li>IMHO, generating images is harder than inpainting images because with inpainting, there is always ground truth present. So converting inpainting to the harder problem of generating images might not be the way to go.</li></ul> | 64 x 64 x 3, arbitrary mask | [[tensorflow implementation]](https://github.com/bamos/dcgan-completion.tensorflow)
Globally and Locally Consistent Image Completion [[link]](http://hi.cs.waseda.ac.jp/~iizuka/projects/completion/en/) (2017) | <ul><li>Dilated convolutions</li><li>2 discriminators: one local discriminator for the completed region and one global discriminator for whole image</li></ul> | <ul><li>Long training time.</li><li>Poisson blending needed.</li><li>Complex training process. Completion network is trained, then the completion network is fixed and discriminators are trained, then finally both are trained.</li></ul> | 256 x 256 x 3 | [[official torch implementation. no training code]](https://github.com/satoshiiizuka/siggraph2017_inpainting) [[tensorflow implementation. missing gan loss]](https://github.com/tadax/glcic) [[tensorflow implementation. has UI]](https://github.com/shinseung428/GlobalLocalImageCompletion_TF)
Image Inpainting using Multi-Scale Feature Image Translation [[arXiv]](https://arxiv.org/abs/1711.08590) (November 23 2017) | <ul><li>2 stages: coarse prediction and refinement through feature based texture swapping</li><li>Framework can be adapted to multi-scale</li></ul> | | 256 x 256 x 3 input, arbitrary mask | Soon
Context-Aware Semantic Inpainting [[arXiv]](https://arxiv.org/abs/1712.07778) (December 21 2017) |
Light-weight pixel context encoders for image inpainting [[arXiv]](https://arxiv.org/abs/1801.05585) (January 17 2018)
High Resolution Face Completion with Multiple Controllable Attributes via Fully End-to-End Progressive Generative Adversarial Networks [[arXiv]](https://arxiv.org/abs/1801.07632v1) (January 23 2018) | <ul><li>Conditioned on facial attributes.</li><li>Progressive growing of GANs.</li><li>Three new losses: attribute, feature, and boundary.</li></ul> | <ul><li>Fails to learn low level skin features.</li><li>Long training time.</li></ul> | 1024 x 1024 x 3, arbitrary mask | Soon
Deep Structured Energy-Based Image Inpainting [[arXiv]](https://arxiv.org/abs/1801.07939) (January 24 2018) |
Image Inpainting for Irregular Holes Using Partial Convolutions [[arXiv]](https://arxiv.org/abs/1804.07723) (April 20 2018) | <ul><li>Introduces partial convolutions, which exclude information from the mask.</li><li>No post processing.</li></ul> | | 512 x 512 x 3, arbitrary mask |
Free-Form Image Inpainting with Gated Convolution [[arXiv]](https://arxiv.org/abs/1806.03589) (June 10 2018) | <ul><li>Utilizes gated convolutions.</li><li>State of the art inpainting for irregular masks.</li><li>No post processing.</li></ul> | | 512 x 512 x 3, arbitrary mask | Soon

# Other Repositories
## Anime Repositories
- none

## General Repositories
- [3D Machine Learning](https://github.com/timzhang642/3D-Machine-Learning)
- [Awesome Deep Vision](https://github.com/kjw0612/awesome-deep-vision)
