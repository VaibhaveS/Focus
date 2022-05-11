# Online meeting analyser for interviews using image processing and NLP
<a name="overview">

#### Overview

We provide an **online interview analyser** which can extract information related to online interviews from the **video and audio recording**. The system is designed to  analyse the emotions of the interviewees using image processing and deep learning techniques along with analysis on the audio of the interview using NLP and Machine learning techniques. Our system provides a detailed analysis of the interview. Companies can use the results from the system to judge the candidate.
 
#### Demo Link 
https://user-images.githubusercontent.com/71920164/167668306-678489f4-11c5-4ee3-8a24-1f64fb798731.mp4
 
#### Dataset Link
https://drive.google.com/file/d/1PH8WC63IqV0deTqNUHjxg2hr--zlkZJJ/view?usp=sharing

<a name="installation">
 
#### Installation

1. Clone this repository

```sh
$ git clone https://github.com/VaibhaveS/Focus.git
```

2. Change directory to that folder

```sh
$ cd Focus
```
  
3. Run the jupyter notebooks 
  
```sh
$ open them manually or use py -m Audio.ipynb and Process.ipynb
```
 
4. Enable Google cloud Speech-to-Text API 
 
 ```sh 
 https://console.cloud.google.com/
 ```

5. Open Homepage.html in the browser
 
<a name="features">

#### Features

- [x] Average response time of the interviewee
 <h5> The delta seconds for each question answer pair is calculated and added to a global sum to calculate the overall average response time of the interviewee.
 This allows the interviewer to gauge the interviewee in terms of how quick he is to think and answer questions i.e, decision making. </h5>
 
- [x] Bar chart signifying the count of each emotion
 
  <h5> A bar chart showing the average frequency of each emotion shown to get an overall idea of what emotion was displayed in response to the stimuli given, for example, a difficult question.  </h5>
 
- [x] Number of active speakers (in a normal interview setting it should be two, but may vary)
 
  <h5> Number of active speakers based on audio component of the meeting is found and displayed. </h5>
 
- [x] Number of questions asked
 
  <h5> From the numerous sentences from the audio transcript, questions that were asked are recognised and the count is returned. </h5>
 
- [x] Percentage of non-trivial questions
 
  <h5> From the questions asked, the number of non-interesting questions are found using TF/IDF and an existing dataset of both interesting and non-interesting questions. </h5>

 
- [x] Percentage of interesting questions
 
  <h5> From the questions asked, the number of interesting questions are found using TF/IDF and an existing dataset of both interesting and non-interesting questions. </h5>
 
<p align="center">
  <img src="https://github.com/VaibhaveS/Focus/blob/main/LOGO5.gif" style="margin:auto">
</p>
