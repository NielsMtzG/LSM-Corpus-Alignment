# LSM-Corpus-Alignment
<img width="1250" height="830" alt="image" src="https://github.com/user-attachments/assets/6d164c14-7a08-4eac-9c4e-ddadbbc39c56" />
This repository hosts the dataset and alignment resources developed as part of the master’s thesis “Automatic Method for the Construction of Parallel Corpora in Mexican Sign Language and Spanish”, conducted at Universidad Autónoma de Coahuila (UAdeC).

The project addresses one of the major gaps in sign-language research: the absence of large, publicly accessible LSM–Spanish corpora.  

# Sources
The main goal of this project is to construct an automatically aligned corpus linking spoken Spanish segments with their corresponding LSM interpretations from televised programs.
The current version focuses on two key sources:
- Las Mañaneras (Mexico’s daily presidential conferences) - *approximately 120 hours of video*
- La UNAM Responde (educational program by the National Autonomous University of Mexico) - (to be uploaded)

Although both programs include a much larger collection of recordings, this corpus contains a strategically selected subset. These videos were chosen through an optimization process to ensure maximum lexical diversity, following the methodology described in [An Exact Optimization Approach for Text Filtering in the Context of Parallel SL Corpus Sub-sampling.pdf](https://github.com/user-attachments/files/23011549/paper_486.pdf)

# Corpus Structure (before fine alignment)

Each video was automatically cropped to include only the interpreter’s square.  In the drive **mananeras_signersquare** ([Mañaneras](https://1drv.ms/f/c/f33a3bbf75182183/ErG1XkBf_H9NtI0nunvE6akBax6pKDkMgvbxTgHxaLyLEw?e=UVam8K)), all files correspond exclusively to these cropped interpreter segments.

To ensure consistency, videos are renamed according to the original conference date. Each video also includes a corresponding .ass subtitle file with the same name, containing word-level timestamps generated with Whisper.

When downloaded together and placed in the same directory, the subtitles automatically synchronize with the audio, highlighting the spoken words in real time as shown below:

<p align="center">
  <img width="556" height="534" alt="Example of cropped interpreter frame with synchronized subtitles" src="https://github.com/user-attachments/assets/c937d608-2420-430f-b26f-e265eae6bcd7" />
</p>




