
# Aiffel AI Project
<img src="https://velog.velcdn.com/images/leejaejun/post/f28d0ac3-0ff7-4489-89f6-9a161bf4cc9d/ee.png" width="600px" height="310px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img><br/>
<br/><br/>[모두의 연구소](https://modulabs.co.kr/)
<br/><br/><br/><br/><br/>

## Integrated Development Environment
Python
* Object Oriented Programming
* Interpreter (Script)
* Dynamic Typing
* Platform Independent

<br/>Google Colab
* GPU : K80
* RAM : 32GB
* Runtime : 24 hours
* Background Execution: No
<br/><br/><br/><br/><br/>

## Curriculum

Hackathon
* Datathon
* Aiffelthon
<br/>

AI Basic
* AI Study
* NLP Study
* CV Study
<br/><br/><br/><br/><br/>

## Datathon
Korean Conversation EDA 
<br/><br/>[대화문 비교 분석(일상 대화 요약)](https://github.com/minseok0809/aiffel-ai-project/tree/main/korean-conversation-eda)

* Data : [AI HUB 한국어 대화 요약](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=116&topMenu=100&aihubDataSe=ty&dataSetSn=117)
* Json Parsing
* Text Normalization : Constraction. Stopword
* Tokenization : MeCab. Okt
* Visualization : LDA. Wordcloud. Folium
* Tokenizer Performance Evaluation : Cosine Similarity

<br/><br/><br/><br/><br/>
## Aiffelthon
Satelite Imagery Object Detection
<br/><br/>[FAIR1M 위성영상에서의 객체 인식 성능 개선](https://github.com/aiffelthon-SIAproject-GangNam-4/for-Public)

* Data : [FAIR1M2.0](https://arxiv.org/abs/2103.05569)
* Xml Parsing
* Baseline Model : MMRotate RoI Transformer
* Exploratory Data Analysis : Class Frequency. Image Size. Object Size
* Data Cleansing : Patch. Size Based Posted Filtering by GSD
* Data Augemntation : Patch. Hue/Brightness/Blur
* QGIS : Annotation File Converts to Geojson
* Evaluation Metric : FP/FN. Precision/Recall/F1-Score/AP. Mean Precision/Mean Recall/Mean F1-Score/mAP
* Further investigation : Semantic Segmentation

<br/><br/><br/><br/><br/>
## AI Study
|Number|Theme|Content|Library|Data|
|---|---|---|---|---|
|01|Classification|Decision Tree. Random Forest. Support Vector Classifier. SGD Classifier. Logistic Regression|sklearn|load_digits, wine, breast_cancer|
|02|Regression|Linear Regression|sklearn|load_diabetes. Forecast use of a city bikeshare system|
|03|Stock Price Forecasting|Time Series Decomposition|ARIMA. seasonal_decompose|Yahoo Finance : Samsung Electronics Co., Ltd. (005930.KS)|
|04|House Sale Prediction|Kaggle|sklearn. keras. tensorflow|House Sales in King County|
|05|Rock Siccsors Paper Classfier|Image Classfication|keras. tensorflow|Rock Scissors Paper Image|
|06|Lyric Bot|Text Generation|keras. tensorflow|Song_Lyrics|
|07|News Summary|Text Summarization (Abstractive and Extractive)|keras. tensorflow|news_summary_more|
|08|Mustache Sticker|Face Bounding Box. Landmark|OpenCV. dlib|CelebA. ibug 300-W|
|09|Film Review Sentimental Analysis|LSTM. Attention Mechanism. Transformer. Word2Vec|MeCab. gensim. keras. tensorflow|Naver sentiment movie corpus v1.0|
|10|Shallow focus|Semantic Image Segmentation|pixellib. OpenCV. torch|unsplash image. deeplabv3_xception_tf_dim_ordering_tf_kernels|
|11|Chatbot|Transformer|regex. hanspell. soynlp. keras. tensorflow|Chatbot data for Korean v1.0|
|12|Goods Info Search From Image|OCR. Web Crawling|keras_ocr. tesseract. OpenCV. selenium|Book Cover Image. Naver Book|
|13|Q&A : Machine Reading Comprehension|BERT|SentencePiece. keras. tensorflow|KorQuAD 1.0|
|14|Image Generator|DCGAN|imageio. pillow. OpenCV. keras. tensorflow|CIFAR-10|
|15|Recommender System|ALS|implicit. scipy|MovieLens 1M|
|16|Image-to-Image Translation|Pix2Pix|OpenCV. keras. tensorflow|Cityscapes|
|17|Session Based Recommendation|GRU|keras. tensorflow|MovieLens 1M|

<br/><br/><br/><br/>
## NLP Study
|Number|Theme|Content|Library|Data|
|---|---|---|---|---|
|02|Perplexity(PPL)|GPT-1|SentencePiece. MeCab. regex. torch. tensorflow|Korean Parallel Corpora. Naver sentiment movie corpus v1.0|
|04|Multiclass Text Classification|Naive Bayes Classifier. Linear Classifier. Support Vector Machine. Decision Tree. Ensemble Method. Nearest Neighbors. Neural Network Model. Dummy Classifier. DNN. 1D-CNN|sklearn. keras. tensorflow|Reuters-21578|
|06|WEAT(Word Embedding Association Test)|TfidfVectorizer. Word2Vec. Cosine Similarity|Okt. Word2Vec. sklearn|KOBIS Synopsis|
|08|Korean-English Translator|Seq2seq with Attention Mechanism|MeCab. regex. keras. tensorflow|Korean Parallel Corpora|
|10|Korean-English Translator|Transformer|SentencePiece. regex. keras. tensorflow|Korean Parallel Corpora|
|12|Chatbot|Data Augmentation : Word2Vec. Glove. FastText. BLEU Score. Transformer|MeCab. gensim. fasttext. nltk. PCA. regex. keras. tensorflow|Chatbot data for Korean v1.0|
|14|Pretrained Language Model|BERT|SentencePiece. regex. keras. tensorflow|kowiki|
|16|HuggingFace Custom Project|beomi/kcbert-base MLM. facebook/bart-large MNLI. google/electra-base-discriminator MNLI. distilbert-base-uncased MRPC|Keras Model . Huggingface Transformers Trainer. Pipeline|Korpora korean_petitions(청와대 국민청원). tensorflow_datasets(tfds.load('glue/mnli')). tensorflow_datasets(tfds.load('glue/mrpc'))|

<br/><br/><br/><br/>
## CV Study
|Number|Theme|Content|Library|Data|
|---|---|---|---|---|
|04|Data Augmentation|ResNet50. Flip Left Right. Audjust Brightness. Cutmix. Mixup|keras. tensorflow|Stanford Dogs Dataset|
|06|Object Detection|RetinaNet|OpenCV. pillow. tensorflow|KITTI-360|

<br/><br/><br/><br/>
