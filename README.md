# Resume Parser using Natural Language Processing
Welcome to an innovative Resume Parser project that leverages cutting-edge Artificial Intelligence techniques to automate the process of analyzing and extracting valuable information from resumes. This project harnesses the power of Natural Language Processing (NLP) and deep learning algorithms to assist recruiters in identifying ideal candidates quickly and efficiently.

## Project Overview:
In today's fast-paced recruiting landscape, time is of the essence. This Resume Parser is designed to be a game-changer for recruiters, enabling them to navigate through a vast pool of resumes and pinpoint exceptional candidates with precision. By utilizing advanced technologies, including NLP, Named Entity Recognition (NER), and Optical Character Recognition (OCR), a robust system has been created to handle even the most complex resumes.

## Key Features of the Resume Parser:

- Document Preprocessing: The initial step involves converting resumes into a standardized text format. This ensures uniformity of data, making it ready for analysis.

- Custom Named Entity Recognition (NER): Customization is taken to the next level by constructing a tailored NER model using SpaCy. This model is trained to recognize and categorize specific attributes within resumes, such as skills, experiences, and qualifications.

- Attribute Labeling: The NER model labels each piece of information within the resume, associating it with a relevant attribute. This offers recruiters a clear and organized view of candidates' qualifications.

- Parts of Speech Analysis: In addition to attribute labeling, the system analyzes the parts of speech within the resume text. This advanced feature enhances the parser's contextual understanding and enhances its capabilities.

- Multiclass Classification: To further assist recruiters, TF-IDF (Term Frequency-Inverse Document Frequency) and cosine similarity techniques are employed to build a multiclass classification model. This model ranks resumes based on their relevance to the job posting, ensuring that the most suitable candidates are prioritized.

## Dataset:
[Dataset Available at:](https://drive.google.com/drive/folders/1QDAFPLKGAJNWDsAD_SsCCsRokkyttL-s?usp=sharing)
Resume_train_data.txt/ Resume_train_data.pkl (pickle format to preserve the
data structure) and UpdatedResumeDataSet.csv and Alicia Clark Resume are used.
We will be using a database of around 200 entries in pickle format and 300
resume in csv format here to train our model and then load it to extract
information from any pdf/doc for the result testing.In this data, there are different
tuples in the form of dictionaries which assign labels (NER) to groups of tokens
which are contiguous. It provides a default model which can recognize a wide
range of named or numerical entities, which include company-name, location and
organization.
## Flowchart:
![image](https://user-images.githubusercontent.com/62128029/187261649-0924a67b-b204-47f6-90d3-5f6dd26cbde3.png)

## Conclusion:
In conclusion, this Resume Parser project is a game-changer for recruiters and HR professionals seeking to streamline the candidate selection process. By automating the parsing and classification of resumes, it empowers recruiters to channel their time and efforts towards engaging with the most promising candidates. 
