# LSM-Corpus-Alignment
<img width="1250" height="830" alt="image" src="https://github.com/user-attachments/assets/6d164c14-7a08-4eac-9c4e-ddadbbc39c56" />
This repository hosts the dataset and alignment resources developed as part of the master’s thesis **“Automatic Method for the Construction of Parallel Corpora in Mexican Sign Language and Spanish”**, conducted at *Universidad Autónoma de Coahuila (UAdeC)*.  
The project addresses one of the major gaps in sign-language research: the absence of **large, publicly accessible LSM–Spanish corpora**.  

The main goal of this project is to construct an automatically aligned corpus linking spoken Spanish segments with their corresponding LSM interpretations from televised programs.
The current version focuses on two key sources:
-Las Mañaneras (Mexico’s daily presidential conferences) - *approximately 120 hours of video*
-La UNAM Responde (educational program by the National Autonomous University of Mexico) (to be uploaded)
Although both programs include a much larger collection of recordings, this corpus contains a strategically selected subset. These videos were chosen through an optimization process to ensure maximum lexical and contextual diversity, following the methodology described in [paper_486.pdf](https://github.com/user-attachments/files/23011549/paper_486.pdf)


*Video Processing and Alignment*
Each video was automatically cropped to include only the interpreter’s square. In the folder Mañaneras, all files correspond exclusively to these cropped interpreter segments.
To ensure consistency, videos are renamed according to the original conference date. Each video also includes a corresponding .ass subtitle file with the same name, containing word-level timestamps generated with Whisper.
When downloaded together and placed in the same directory, the subtitles automatically synchronize with the audio, highlighting the spoken words in real time — as shown below:
<img width="708" height="679" alt="image" src="https://github.com/user-attachments/assets/c46fc1d7-2e96-4689-8e37-b31b87ff744f" />

