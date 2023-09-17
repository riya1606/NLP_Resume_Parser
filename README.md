# Resume Parser using Natural Language Processing
<p>
Artificial Intelligence has recently been used to automate resume parsing
which deciphers various resumes using an NLP (Natural Language
Processing) engine. It is important for recruiters as it may locate excellent
candidates with a perfect match in qualifications, talents, and experience in
a similar industry.
</p>

<hr>

<p>
Resume Parser is notable for interpreting and screening the most complex
resumes utilizing deep learning algorithms combined with NLP, NER, and
OCR to interpret and screen the most complex resumes. We will preprocess the data by converting
the document into text and build a custom NER model to train the data on it
using SpaCy which labels data based on the attribute and displays the text
alongside the label. Our project also shows variety of other information like
parts of speech making the resume parser even more powerful than before.
We will be using TF-IDF and cosine similarity to build this multiclass
classification model and rank the resume giving employers the flexibility to
see all the highranked resume on top and making their way from there to
the bottom.
</p>

<hr>

## [Dataset Available at:](https://drive.google.com/drive/folders/1QDAFPLKGAJNWDsAD_SsCCsRokkyttL-s?usp=sharing)
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
