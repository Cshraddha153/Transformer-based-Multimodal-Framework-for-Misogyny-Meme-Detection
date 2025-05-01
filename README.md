# Transformer based Multimodal Framework for Misogyny Meme Detection

This project focuses on detecting misogynistic content in Tamil and Malayalam memes using a multimodal approach. 
We extract image features using ViT (Vision Transformer) and text features using MuRIL, then fuse these features 
for classification. Both machine learning (ML) and deep learning (DL) models were trained for misogyny detection. 

# Sample Memes From dataset

![a4726f0a1647ede6649a6f862c71b78ef73c86ba](https://github.com/user-attachments/assets/a0e157d5-330b-4f22-b835-6e896d89875e)


![3fa765a1eb84776a1d76ad5fc93aeb7a6f694f59](https://github.com/user-attachments/assets/1f4fb2ff-6666-465b-aa40-55ad896ddfe5)


# Data distribution of Tamil
![63edf4f217080390931773234810af7342f42272](https://github.com/user-attachments/assets/45fb4475-2355-4006-87e6-9670edb39390)

# Data distribution of Malayalam
![46bbc1794d5d193559658a781de242e4528bb543](https://github.com/user-attachments/assets/c46e2a53-07f2-422a-a94e-1ac50b337c4d)


# Model Architecture

![07e0040ff156677da7cc97e5af6418fb0f7a2a46](https://github.com/user-attachments/assets/c475311b-c362-40cc-95c3-f100686012fe)


# Methodology
1. Image Feature Extraction: ViT (Vision Transformer)
2. Text Feature Extraction: XLM-Roberta
3. Feature Fusion: Combined visual and textual features for classification
   
# Models Used:
1. Machine Learning Models: KNN, SVM, Random Forest (RF), Naïve Bayes (NB)
2. Deep Learning Models: LSTM, GRU, Custom Multimodal Model (MMC)

# Confusion Matrix for Tamil data
![0c525eddd928ca3d04974cb96c0bca6c42d05d37](https://github.com/user-attachments/assets/89ffcd67-b69a-451f-a224-19bb2c5d420b)


# Confusion Matrix for Malayalam data
![a105eb00c3e2eeac73933babe660d79079532727](https://github.com/user-attachments/assets/ba3e1372-78b1-4e05-a7e6-ecfc58315b15)


# Rank List
### Team Name - MNLP
1. Tamil Rank list of Misogyny detection - [Tamil Rank list](https://github.com/user-attachments/files/19090596/Misogyny.shared.task.-.Tamil.Rank.list.pdf)

2. Malayalam Rank list of Misogyny detection - [Malayalam Rank list](https://github.com/user-attachments/files/19090593/Misogyny.shared.task.-.Malayalam.Rank.list.pdf)

   
# Citation

@inproceedings{chauhan-kumar-2025-mnlp-dravidianlangtech,
    title = "{MNLP}@{D}ravidian{L}ang{T}ech 2025: Transformer-based Multimodal Framework for Misogyny Meme Detection",
    author = "Chauhan, Shraddha  and
      Kumar, Abhinav",
    editor = "Chakravarthi, Bharathi Raja  and
      Priyadharshini, Ruba  and
      Madasamy, Anand Kumar  and
      Thavareesan, Sajeetha  and
      Sherly, Elizabeth  and
      Rajiakodi, Saranya  and
      Palani, Balasubramanian  and
      Subramanian, Malliga  and
      Cn, Subalalitha  and
      Chinnappa, Dhivya",
    booktitle = "Proceedings of the Fifth Workshop on Speech, Vision, and Language Technologies for Dravidian Languages",
    month = may,
    year = "2025",
    address = "Acoma, The Albuquerque Convention Center, Albuquerque, New Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.dravidianlangtech-1.43/",
    pages = "248--253",
    ISBN = "979-8-89176-228-2",
    abstract = "A meme is essentially an artefact of content- usually an amalgamation of a picture, text, or video-content that spreads like wildfire on the internet, usually shared for amusement, cultural expression, or commentary. They are very much similar to an inside joke or a cultural snapshot that reflects shared ideas, emotions, or social commentary, remodulated and reformed by communities. Some of them carry harmful content, such as misogyny. A misogynistic meme is social commentary that espouses negative stereotypes, prejudice, or hatred against women. The detection and addressing of such content will help make the online space inclusive and respectful. The work focuses on developing a multimodal approach for categorizing misogynistic and non-misogynistic memes through the use of pretrained XLM-RoBERTa to draw text features and Vision Transformer to draw image features. The combination of both text and images features are processed into a machine learning and deep learning model which have attained F1-scores 0.77 and 0.88, respectively Tamil and Malayalam for misogynist Meme Dataset."
}

