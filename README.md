# Datasets
A list of publicly available datasets (or available upon request) grouped not just by data type but also according to information related to the domain a trained model would be applicable.

The datasets are going to also be assigned tags related to their content on top of their current listing to facilitate searching. The list of tags is going to be available so that one can choose from the available tags and search.

Tags: Activity recognition, Object detection, Person detection, Posture recognition, Segmentation, Face recognition

## Speech

### Reading:
* **Common Voice:** A huge dataset crowdsourced by Mozilla with 1361 hours of audio, of which 1091 are validated and belonging to 18 different languages. Dataset was collected by volunteers speaking according to a script online and others validating the speech of others. The dataset also contains information about the gender or the accent in a language (e.g American English, England English, etc.) [[Link]](https://voice.mozilla.org/en/datasets)
* **LibriSpeech**: 1000 hours of read books (audiobooks) in English. [[Link]](http://www.openslr.org/12)
* **VCC Challenge 2016 dataset**: A cleaner version of the DAPS dataset. The data contains 20 speakers (10 male and 10 female), reading five excerpts each, about 13 minutes per speaker. The excerpts are read in 4 different recording settings (Raw, Clean Raw, Produced and Device). [[Link]](https://datashare.is.ed.ac.uk/handle/10283/2211)
* **ZeroSpeech2019**: The training data was recorded from 1 male and 1 female for 2 hours per talker and read text from 100 speakers with 10 minutes per speaker. There is also data contains also parallel utterances from a target voice and other voices. Lastly, the test set contains 15 speakers with about 2 minutes of speech per speaker. [[Link]](https://zerospeech.com/2019/index.html)
* **The Helsinki Prosody Corpus:** Basically LIbriTTS (cleaned part of LibriSpeech) annotated with high quality automatically generated annotations indicating the prominensce of prosody in speech. [[Link]](https://github.com/Helsinki-NLP/prosody)

### Pre-recorded speech replayed
* **The VOiCES Corpus**: Pre-recorded clean speech (from LibriSpeech) played and recorded again under realistic conditions from 12 different microphones. 120 hours of speech were recorded per mic (1440 hours in total). Audio was recorded with only the ambient room noise but also with a distractor adding noise on the foreground speech. The distractor was either TV noise, music being played or babble noise. [[Link]](https://voices18.github.io/downloads/ )

### Spoofed speech

#### Spoofed speech from TTS and VC
* **ASVspoof2015**: Genuine speech collected from 106 speakers (45 male and 61 female) and spoofed speech generated from the genuine data using different spoofing algorithms. The dataset was created for a challenge where the task was to discriminate genuine human speech from speech produced from text-to-speech (TTS) and voice conversion (VC). [[Link]](https://datashare.is.ed.ac.uk/handle/10283/853) 
#### Spoofed speech from recording genuine speech
* **ASVspoof2017v2:** A set of genuine speech recordings and spoofed ones. The genuine ones are a subset of the RedDots database which was collected by volunteers using Android Smartphones. Utterances correspond to 10 fixed phrases. The spoofed recordings were generated by recording genuine ones in a variety of environments and using different devices. [[Link]](https://datashare.is.ed.ac.uk/handle/10283/3055=) 

### Emotional Speech

#### Non-scripted
* **FAU Aibo Emotion Corpus**: 9 hours of 51 young (10-13 y/o) children interacting in German with a pet robot. 11 Emotion categories. 
 [[Link]](https://www5.cs.fau.de/de/mitarbeiter/steidl-stefan/fau-aibo-emotion-corpus/) 

#### Scripted
* **Interface ("Multimodal Analysis/Synthesis System for Human Interaction to Virtual and Augmented environments"):** Acted speech in Slovenian, English, Spanish and French. One male and one female actors per language except for two males and one female in English. About 4 hours per speaker. Currently (10/10/2019) only the Spanish recordings are available but the rest are to be published too.  [[Link]](http://universal.elra.info/product_info.php?cPath=37_39&products_id=62) 
* **The Sincere Apology Corpus (SinA-C):** English speech recorded from 15 male and 17 female, 20 to 60 year old people, 27 of them being native American and 5 from other nationalities but fluent in English. 24 of the people were actors while 12 were artists. The speakers were instructed to speak in four prosodic styles: i)monotonic, ii) pitch prominence, iii) fast speaking rate, iv) slow speaking rate.The dataset is annotated in terms of the sincerity perceived by listeners. [[Link]](https://zenodo.org/record/3241253#.XaA6CEYzZPY)

### Medical
* **VanDam Validation HomeBank Corpus:** About 7.5 hours of data selected from single-day recordings from the home-environment of 15 families with children that either develop or already have hearing problems. The children were 7-33 months old and the data was recording through a LENA system worn by the child. [[Link]](https://homebank.talkbank.org/access/Public/VanDam-Validation.html)
* **Parkinson Speech Dataset with Multiple Types of Sound Recordings Data Set**: Contains sound recordings from 20 people with Parkinson (14 males and 6 females) and 20 without (10 males and 10 females). [[Link]](https://archive.ics.uci.edu/ml/datasets/Parkinson+Speech+Dataset+with++Multiple+Types+of+Sound+Recordings#)
 
### Events in speech
* **SSPNet Vocalization Corpus**: Audio from 63 females and 57 males, unacquainted with each other, trying to solve the Winter Survival Task over phone. [[Link]](http://www.dcs.gla.ac.uk/vincia/?p=378)
* **SSPNet Conflict Corpus**: 1430 audioclips, 30 seconds each from 45 political debates televised in Switzerland. Data dedicated to detecting conflicts in speech, which are common in debates. [[Link]](http://www.dcs.gla.ac.uk/vincia/?p=270)
* **IBM Debate Speech Analysis Corpus:** Dataset made up from 3 separate datasets with good quality sound debates. The dataset is originally purposed for Automatic Speech Recognition. [[Link]](https://www.research.ibm.com/haifa/dept/vst/debating_data.shtml#Project)  

  
<br/><br/>  
<br/><br/>
  


## Computer Vision

### Images of people

#### Person detection
* **Stanford 40 Action Dataset**: The dataset contains images of humans performing 40 actions. Labels include bounding boxing for each image for 9532 images with 180-300 images per action class.   [[Link]](http://vision.stanford.edu/Datasets/40actions.html)  
[Activity recognition, Person detection, Object detection]

* **Inria Person dataset**: This dataset contains images of upright people in images and video as well as negative samples with no people inside. People with less than a specified height are not marked in the dataset (assuming they are not upright). The annotations are bounding boxes with the people but might contain mistakes especially when it comes to bounding boxes being a little bit inside or outside of the people. The dataset contains data from other sources such as the GRAZ01 dataset. [[Link]](http://www-old.emt.tugraz.at/~pinz/data/GRAZ_02/) [[Improved Dataset Link]](http://pascal.inrialpes.fr/data/human/)  
[Posture recognition, Person detection, Object detection]

* **People in Photo Albums (PIPA)**: The dataset consists over 60000 instances of ~2000 individuals collected from public Flickr photo albums. Only half of the images contain a frontal face and the dataset contains a lot of different poses, clothing styles, camera viewpoints, image resolutions and illumination settings. The annotations are bounding boxes around the heads of the people in the picture. If a crowd is present in a picture no more than 10 heads are marked. [[Link]](https://people.eecs.berkeley.edu/~nzhang/piper.html)  
[Face recognition, Person detection, Object detection]

* **Caltech Pedestrian Dataset**: Approximately 10 hours of 640x480 30Hz video taken from a vehicle driving through regular traffic in an urban environment. About 250,000 frames (in 137 approximately minute long segments) with a total of 350,000 bounding boxes and 2300 unique pedestrians were annotated. [[Link]](
http://www.vision.caltech.edu/Image_Datasets/CaltechPedestrians/)  
[Person detection, Object detection]

* **Daimler Pedestrian Detection Dataset**: The training set contains 15.560 pedestrian samples and 6744 additional full images not containing pedestrians for extracting negative samples. The test set contains an independent sequence with more than 21.790 images with 56.492 pedestrian labels, captured from a vehicle during a 27 min drive through urban traffic, at VGA resolution (640x480, uncompressed). Bounding boxes are provided. [[Link]](http://www.gavrila.net/Research/Pedestrian_Detection/Daimler_Pedestrian_Benchmark_D/Daimler_Mono_Ped__Detection_Be/daimler_mono_ped__detection_be.html)  
[Person detection, Object detection]

* **GM-ATCI Rear-view Pedestrian Dataset**:  In total, the dataset contains 250 clips with a total duration of 76 minutes and over 200K annotated pedestrian bounding boxes. The original dataset contains 15 filming sessions, each taken in a different day with different scenarios, with each session having multiple clips ranging from seconds to several minutes. Only the test set is available from this dataset which corresponds to 6 sets of clips. The data contains both "staged" and "in-the-wild" pedestrians in different urban locations.  Annotations include bounding boxes. [[Link]](https://sites.google.com/site/rearviewpeds1/)   
[Person detection, Object detection]
 


### Images of people/vehicles

* **GRAZ 01**: The dataset contains images with people and/or bikes as well as images with neither people or bikes. The dataset is originally annotated for image classification (detecting whether there is a person, bike or nothing in the picture) but also comes with pixel egmentation masks for 150 bike images. (https://lear.inrialpes.fr/people/marszalek/data/ig02/).[[Link]](http://www-old.emt.tugraz.at/~pinz/data/GRAZ_01/)  
[Person detection, Object detection]

* **GRAZ 02**: The dataset contains 365 images with bikes, 311 images with persons, 420 images with cars 
and 380 images not containing one of these objects. For 300 images of each category pixel segmentation masks are provided. There is also an improved version of the database with improved pixel segmentation masks. [[Link]](http://www-old.emt.tugraz.at/~pinz/data/GRAZ_02/) [[Improved Dataset Link]](http://lear.inrialpes.fr/people/marszalek/data/ig02/)  
[Person detection, Segmentation]





<br/><br/>
<br/><br/>
  
## Multimodal

### Interviews
* **VoxCeleb**: Large scale dataset consisting of 2000 hours of audiovisual data from interviews uploaded to YouTube with 7000+ speakers of which 1251 are celebrities. [[Link]](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/)

### Emotional speech
#### Scripted
* **Multimodal EmotionLines Dataset (MELD):** Dialogue data from the Friends TV series labelled with emotions such as Anger, Disgust, Sadness, etc. or a sentiment label (positive, negative or neutral).[[Link]](https://github.com/SenticNet/MELD)
#### Mixed scripted and non scripted
* **IEMOCAP**: Data from 10 actors, male and female having affective dyadic interactions in both improvised and scripted sessions. Comprises of 12 hours of audiovisual data with text along with the scripted data.  [[Link]](https://sail.usc.edu/iemocap/iemocap_release.htm)

### Medical
* **Dem@Care**: Audio-visual and physiological sensor data collected from lab and home experiments from Greek dementia patients. The dataset includes samples recorded during sleep and motion.  [[Link]](http://www.demcare.eu/results/datasets)
* **DAIC-WOZ**: About 50 hours of transcribed audio-visual data recorded from clinical interviews designed to support the diagnosis of anxiety, depression and PTSD. Part of the data was interviews conducted by a human controlled virtual interviewer.  [[Link]](
http://dcapswoz.ict.usc.edu/)

### Indoor noisy environment

#### Non-scripted
* **CHiME-5**: Audio data along with the transcriptions from 20 dinner parties (minimum 2 hours each) with two hosts and two guests each. The party members were all close friends and were instructed to act naturally. The transcriptions include annotations such as noise (when non-language noise is made), inaudible, laughter or reducted (removed for privacy reasons). [[Link]](http://spandh.dcs.shef.ac.uk/chime_challenge/CHiME5/data.html)



