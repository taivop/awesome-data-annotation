# Awesome data annotation
A list of tools for annotating data, managing annotations, etc.

Contributing: I gladly accept additions to the lists below; please submit an issue or pull request with any updates.

***Just looking for a recommendation of the one best open source annotation tool?*** Me and several other people in industry and academia have independently found [**CVAT**](https://github.com/opencv/cvat) to be the best choice for Computer Vision tasks.

# Annotation tools
## Image / video
### Open source
* [Alp's labeling tool (ALT)](https://alpslabel.wordpress.com/2017/01/26/alt/) -- image
* [Annotorious](https://recogito.github.io/annotorious/)
* [boobs](https://github.com/drainingsun/boobs) -- image (rectangle)
* [Classifai](https://github.com/CertifaiAI/classifai)
* [COCO Annotator](https://github.com/jsbroks/coco-annotator) -- image
* [commacoloring](https://github.com/commaai/commacoloring) -- image segmentation
* [Computer Vision Annotation Tool (CVAT)](https://github.com/opencv/cvat) -- image/video segmentation, geometric shapes, keypoints
* [deeplabel](https://github.com/jveitchmichaelis/deeplabel) -- image
* [diffgram](https://github.com/diffgram/diffgram) -- image, video, text, data platform
* [dsgou/annotator](https://github.com/dsgou/annotator) -- video
* [Etiketai](https://github.com/aralroca/etiketai) -- image
* [Fast Image Annotation Tool (FIAT)](https://github.com/christopher5106/FastAnnotationTool) - image (rectangle)
* [Grid-Annotation-Tool](https://github.com/LukasBommes/Grid-Annotation-Tool) -- image (rectangle grids)
* [ilastik](https://github.com/ilastik/ilastik) -- image
* [imannotate](https://github.com/smileinnovation/imannotate) -- image
* [imglab](https://github.com/NaturalIntelligence/imglab) -- image (geometric shapes)
* [imagetagger](https://github.com/bit-bots/imagetagger) -- image; supports collaborative labelling
* [INCEpTION](https://github.com/inception-project/inception) -- text
* [LabelImg](https://github.com/tzutalin/labelImg) -- image
* [labelme](https://github.com/wkentaro/labelme) -- image/video (classification, polygon, geometric shapes)
* [labelml](https://github.com/bfortuner/labelml) -- image
* [LabelD](https://sweppner.github.io/labeld/) -- (web) image
* [Label Studio](https://github.com/heartexlabs/label-studio) -- image, audio, text
* [LEAR](https://lear.inrialpes.fr/people/klaeser/software_image_annotation) -- image segmentation
* [LOST](https://github.com/l3p-cv/lost)
* [Microsoft VoTT](https://github.com/Microsoft/VoTT) -- image/video (geometric shapes)
* [Pixano](https://pixano.cea.fr/) -- image/sequence (rectangle, polygon, polyline, keypoints, segmentation)
* [PixelAnnotationTool](https://github.com/abreheret/PixelAnnotationTool) -- image segmentation
* [react-image-annotation](https://github.com/Secretmapper/react-image-annotation) -- image (geometric shapes)
* [scalabel](https://github.com/scalabel/scalabel) -- image (bbox, tracking, segmentation), 3D 
* [Sloth](https://sloth.readthedocs.io/en/latest/) -- image/video (geometric shapes)
* [Tator](https://github.com/cvisionai/tator) -- video
* [Universal Data Tool](https://github.com/UniversalDataTool/universal-data-tool) -- image, video, PDF, text, audio
* [VATIC](http://www.cs.columbia.edu/~vondrick/vatic/), [VATIC.js](https://github.com/dbolkensteyn/vatic.js) -- video tracking
* [VGG Image Annotator (VIA)](http://www.robots.ox.ac.uk/~vgg/software/via/) -- image (polygons, geometric shapes)
* [ViPER-GT](http://viper-toolkit.sourceforge.net/products/gt/) -- video (classification, temporal segmentation, tracking)

### Commercial
* [Amazon Sagemaker Ground Truth](https://aws.amazon.com/sagemaker/groundtruth/)
* [DataTurks](https://dataturks.com/)
* [Figure Eight](https://www.figure-eight.com/)
* [Google AI Platform Data Labeling Service](https://cloud.google.com/ai-platform/data-labeling/docs)
* [Handl](https://handl.ai/)
* [Kili](https://kili-technology.com/)
* [Labelbox](https://www.labelbox.com/)
* [LinkedAI](https://linkedai.co/)
* [Oclavi](https://oclavi.com/)
* [Prodigy](https://prodi.gy/) -- image classification
* [RectLabel](https://rectlabel.com/) -- classification, bounding box, polygon, cubic bezier
* [SuperAnnotate](https://www.superannotate.com/)
* [Supervisely](https://supervise.ly/)
* [TrainingSet.ai](https://dashboard.trainingset.ai)

## Text
### Open source
* [Banksy](https://github.com/AboutGoods/Banksy-annotation-tool) -- NER, NEL, box
* [brat](http://brat.nlplab.org/)
* [doccano](https://github.com/chakki-works/doccano) -- NER, sentiment, translation
* [FoLiA Linguisitc Annotation Tool (Flat)](https://github.com/proycon/flat)
* [Hover](https://github.com/phurwicz/hover)
* [Label Studio](https://github.com/heartexlabs/label-studio) -- image, audio, text
* [Rubrix](https://github.com/recognai/rubrix) -- text
* [Universal Data Tool](https://github.com/UniversalDataTool/universal-data-tool) -- image, video, PDF, text, audio
* [WebAnno](https://webanno.github.io/webanno/)
* [YEDDA](https://github.com/jiesutd/YEDDA)

### Commercial
* [AnnoLab](https://annolab.ai/)
* [DataTurks](https://dataturks.com/)
* [Figure Eight](https://www.figure-eight.com/)
* [Kairntech](https://kairntech.com/) -- NER, classification, sentiment, knowledge-based
* [LightTag](https://www.lighttag.io/)
* [Prodigy](https://prodi.gy/) -- entity recognition, intent detection
* [TagTog](https://www.tagtog.net/)
* [UBIAI](https://ubiai.tools/)

## Multimodal / pointcloud
### Open source
* [3D-BAT](https://github.com/walzimmer/3d-bat) ([paper](https://arxiv.org/abs/1905.00525v1)) -- multimodal (image, pointcloud)
* [LATTE](https://github.com/bernwang/latte) -- pointcloud
* [Pixano](https://pixano.cea.fr/) -- multimodal (image, pointcloud)
* [springzfx/point-cloud-annotation-tool](https://github.com/springzfx/point-cloud-annotation-tool) -- pointcloud

## Components
UI and other components that can be integrated into other applications.
* [Pixano](https://github.com/pixano/pixano-elements/) -- Javascript annotation components for geometric shapes in image and pointcloud
* [react-image-annotate](https://github.com/waoai/react-image-annotate) -- React component for bounding boxes, points, and polygons

## Other
### Open source
* [dsgou/annotator](https://github.com/dsgou/annotator) -- video, audio, rosbag
* [Dumbris/trunklucator](https://github.com/Dumbris/trunklucator) -- interactive annotation from Python code
* [open-CRAVAT](https://github.com/KarchinLab/open-cravat) -- genomics
* [PCGR](https://github.com/sigven/pcgr) -- genomics
* [Label Studio](https://github.com/heartexlabs/label-studio) -- image, audio, text
* [Universal Data Tool](https://github.com/UniversalDataTool/universal-data-tool) -- image, video, PDF, text, audio

# Related lists
[awesome-dataset-tools](https://github.com/jsbroks/awesome-dataset-tools)

