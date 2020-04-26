# Project Title

DSC160 Data Science and the Arts - Midterm Project Repository - Spring 2020

Project Team Members: 
- Firstname Lastname1, name1@ucsd.edu
- Firstname Lastname2, name2@ucsd.edu
- Firstname Lastname3, name3@ucsd.edu
- Rakesh Senthilvelan, rsenthil@ucsd.edu
- Praveen Nair, prnair@ucsd.edu

## Abstract

(10 points) 

For the project proposal, please write a short abstract addressing the questions below. You should replace the entire contents of this section with one to two paragraphs addressing the following:

- What is the data set that you are going to analyze?
- What is your research question? 
- What is your hypothesis about the results? 
- What features of the data will you use to address your question? 
- What techniques and software tools will you use to extract these features?
- What analytic techniques will you use?
- What forms will your results take? (graphs, charts, images, sonification, Wordles, etc)
- How are you expanding on topics we have covered in class? 
- Why is it interesting? (personally, culturally, politically, other)

For this project, we are going to analyze a broad group of influential hip-hop songs from the 1970s to today. The goal of the project is to cluster hip-hop songs based on a variety of audio features to quantify their similarities and differences, and to determine whether popular terms for classifying hip hop (based on factors like period, geography, and subgenre) are visible in these audio features. Our hypothesis is that artists and songs that share these sorts of qualitative similarities will also be considered more similar in audio analysis, but also that stylistic groupings (such as soul rap and trap music) will be stronger than identity-based groupings (for example, East vs. West Coast).

In order to conduct this analysis, we will use the Python package librosa, which will allow us to extract features such as mel-frequency cepstral coefficients (MFCC’s), chroma features, zero crossing rate, and other spectral features. Then, using a dimensionality reduction technique such as PCA, we can use the package sklearn to cluster and classify our data based on the extracted features. The results of this clustering should be available as graphs based on the dimensional reduction, within which we can make distinctions for different clusters. This project expands on the feature extraction we did in class by harnessing the domain knowledge we have about hip-hop classification and history to determine whether the sorts of classifications that listeners of hip-hop make have an underlying basis in measurable audio features. This analysis is also valuable in that it provides a quantitative way to understand high-level trends in hip-hop from its inception until today, and to also understand what previously unrecognized similarities there might be between works that we would previously not associate together.


## Data

(10 points) 

This section will describe your data and its origins. Each item should contain a name of the data source, a link to the source, and any necessary background information such as:
- What is your cultural data source? 
- When was it made? 
- Who created the works? 
- Is it digital native, or is it some kind of scan, recording, photo, etc., of an analog form? 

## Code

(20 points)

This section will link to the various code for your project (stored within this repository). Your code should be executable on datahub, should we choose to replicate your result. This includes code for: 

- data acquisition/scraping
- cleaning
- analysis
- generating results. 

Link each of your notebooks or .py files within this section, and provide a brief explanation of what the code does. Reading this section we should have a sense of how to run your code.

## Results

(30 points) 

This section will contain links to documentation of your results. This can include figures, sound files, videos, bitmaps, as appropriate to your domain of analysis. Each result should include a brief textual description, and all should be listed below: 

- image files (`.jpg`, `.png` or whatever else is appropriate)
- audio files (`.wav`, `.mp3`)
- written text as `.pdf`

## Discussion

(30 points, three to five paragraphs)

The first paragraph should be a short summary describing your results.

The subsequent paragraphs could address questions including:
- Why is this culturally relevant?
- How does your computational approach differ from the traditional art historical, musicological, manuel/subjective approach to analyzing your cultural subject? 
- How do you think the original artists/musicians would respond to this type of analysis? Would it change/inform their practice in some way?
- How do your results relate to broader social, cultural, economic political, etc., issues? 
- In what future directions could you expand this work?

## Team Roles

Provide an account of individual members and their efforts/contributions to the specific tasks you accomplished.

## Technical Notes and Dependencies

Any implementation details or notes we need to repeat your work. 
- Additional libraries you are using for this project
- Does this code require other pip packages, software, etc?
- Does this code need to run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

References to any papers, techniques, repositories you used:
- Papers
- Repositories
- Blog posts
