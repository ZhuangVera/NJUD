# Introduction of NJUD -- Nanjing University Speech Command Dataset

## Abstract
This dataset was collected by the VLSI Laboratory at the School of Electronic Science and Engineering, Nanjing University. The data sources were randomly selected students within the laboratory. The aim is to augment localized Chinese user data on the basis of the GSCD Google dataset. It can be used for tasks such as fine-tuning or transfer learning in keyword spotting (KWS).

## Dataset Description
- Sampling frequency：48kHz(from DJI mic)
- Speaker number：eight speakers，from 001 to 008
- Each speaker repeated each keyword 30 times, with utterances spaced at 3-second intervals.  
- Each recording is named using the convention: postset_speakerid_keywordid_num  
    - Example: For speaker 3 saying the keyword "happy," the file is named: Postset_003_013.wav

Here are the keywords and their corresponding codes. All keywords are from the Google Speech Commands dataset.

| Keyword      | Keyword-to-code|  Keyword   | Keyword-to-code|
|--------------|----------------|------------|--------------- |
| backward     | 001            | bed        | 002            |
| bird         | 003            | cat        | 004            |
| dog          | 005            | down       | 006            |
| eight        | 007            | five       | 008            |
| follow       | 009            | forward    | 010            |
| four         | 011            | go         | 012            |
| happy        | 013            | house      | 014            |
| learn        | 015            | left       | 016            |
| marvin       | 017            | nine       | 018            |
| no           | 019            | off        | 020            |
| on           | 021            | one        | 022            |
| right        | 023            | seven      | 024            |
| sheila       | 025            | six        | 026            |
| stop         | 027            | three      | 028            |
| tree         | 029            | two        | 030            |
| up           | 031            | visual     | 032            |
| wow          | 033            | yes        | 034            |
| zero         | 035            |            |                |

## File Description
The files are organized and stored according to the speaker ID, located under `dataset_kws_vlsi/00x`. Each audio file contains multiple repetitions of a specific keyword spoken by a given speaker. The utterances are spaced approximately 3 seconds apart, allowing for segmentation and extraction of individual repetitions.
