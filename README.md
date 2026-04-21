


## [Linked White Paper](https://github.com/deep-model/Automatic_Speech_Recognition/blob/main/ASR_Report_M.Harper.pdf)
# AI-Driven Workflows for Automatic Speech Recognition with Nvidia NeMo toolkit for ASR

## [Veiw Project List](https://github.com/deep-model?tab=repositories)


<img width="900" height="600" alt="image" src="https://github.com/deep-model/Automatic_Speech_Recognition/blob/main/Abstract.png"/>


Abstract: AI-based  speech recognition is a 
rapidly growing field of research which has 
transformed the way humans interact not 
only with machines but with each other. 
Speech recognition is considered a 
technology that enables machines to 
understand and interpret human speech 
[1]. Also known as automatic speech 
recognition (ASR), computer speech 
recognition or speech-to-text, is a 
capability that enables a program to 
process human speech into a written 
format. While speech recognition is 
commonly 
confused 
with 
voice 
recognition, speech recognition focuses on 
the translation of speech from a verbal 
format to a text one whereas voice 
recognition just seeks to identify an 
individual user’s voice [6]. This report 
provides a summary introduction into 
speech recognition models and illustrates a 
basic ASR model with the lab practicum. 

<img align="left" width="600" height="800" src="https://github.com/deep-model/Automatic_Speech_Recognition/blob/main/figure%201.png">
Abstract: AI-based  speech recognition is a rapidly growing field of research which has transformed the way humans interact not 
only with machines but with each other. Speech recognition is considered a technology that enables machines to understand and interpret human speech 
[1]. Also known as automatic speech recognition (ASR), computer speech recognition or speech-to-text, is a capability that enables a program to 
process human speech into a written format. While speech recognition is commonly confused with voice recognition, speech recognition focuses on 
the translation of speech from a verbal format to a text one whereas voice recognition just seeks to identify an individual user’s voice [6]. This report 
provides a summary introduction into speech recognition models and illustrates a basic ASR model with the lab practicum.

<table>
  <tr>
    <td>Abstract: AI-based  speech recognition is a rapidly growing field of research which has transformed the way humans interact not 
only with machines but with each other. Speech recognition is considered a technology that enables machines to understand and interpret human speech 
[1]. Also known as automatic speech recognition (ASR), computer speech recognition or speech-to-text, is a capability that enables a program to 
process human speech into a written format. While speech recognition is commonly confused with voice recognition, speech recognition focuses on 
the translation of speech from a verbal format to a text one whereas voice recognition just seeks to identify an individual user’s voice [6]. This report 
provides a summary introduction into speech recognition models and illustrates a basic ASR model with the lab practicum.</td>
    <td><img width="6600" height="8400" alt="image" src="https://github.com/deep-model/Automatic_Speech_Recognition/blob/main/figure%201.png" alt="Description"></td>
  </tr>
</table>
<div>
  
  <img width="400" height="300" alt="image" src="https://github.com/deep-model/Automatic_Speech_Recognition/blob/main/figure%201.png" style="float: right; margin-left: 15px;">
  <p> Abstract: AI-based  speech recognition is a rapidly growing field of research which has transformed the way humans interact not 
only with machines but with each other. Speech recognition is considered a technology that enables machines to understand and interpret human speech 
[1]. Also known as automatic speech recognition (ASR), computer speech recognition or speech-to-text, is a capability that enables a program to 
process human speech into a written format. While speech recognition is commonly confused with voice recognition, speech recognition focuses on 
the translation of speech from a verbal format to a text one whereas voice recognition just seeks to identify an individual user’s voice [6]. This report 
provides a summary introduction into speech recognition models and illustrates a basic ASR model with the lab practicum. </p>
</div>
  
<p>  <p/>

<img width="400" height="300" alt="image" src="https://github.com/deep-model/Automatic_Speech_Recognition/blob/main/figure%201.png" />

</p>
<div style="display: grid; grid-template-columns: 1fr auto; gap: 20px;">
  <div>
    <p>Abstract: AI-based  speech recognition is a rapidly growing field of research which has transformed the way humans interact not 
only with machines but with each other. Speech recognition is considered a technology that enables machines to understand and interpret human speech 
[1]. Also known as automatic speech recognition (ASR), computer speech recognition or speech-to-text, is a capability that enables a program to 
process human speech into a written format. While speech recognition is commonly confused with voice recognition, speech recognition focuses on 
the translation of speech from a verbal format to a text one whereas voice recognition just seeks to identify an individual user’s voice [6]. This report 
provides a summary introduction into speech recognition models and illustrates a basic ASR model with the lab practicum.</p>
  </div>
  <img width="400" height="300" alt="image" src="https://github.com/deep-model/Automatic_Speech_Recognition/blob/main/figure%201.png" >
</div>

## Introduction 

Speech recognition refers to the technology that enables machines to understand and interpret human 
speech. This technology involves converting spoken language into text through a series of complex 
processes, including audio signal processing, feature extraction, and pattern recognition [1].  

Early development of speech recognition systems began in the early 1950s at Bell Laboratories. In 1952, a 
pioneering system named "Audrey" was developed. This innovative creation, a testament to the early days 
of speech recognition, demonstrated remarkable capabilities. Audrey could accurately recognize spoken 
digits, from zero to nine, with an impressive accuracy rate exceeding 90%. The system was trained on the 
voice of its developer, HK David, showcasing the early limitations of speech recognition technology that 
relied on specific voices and limited vocabularies [6]. 

Building upon the foundation laid by Audrey, researchers continued to push the boundaries of speech 
recognition technology. In 1962, IBM introduced the "Shoebox," a significant step forward in the field. This 
innovative machine demonstrated the ability to recognize a vocabulary of 16 spoken English words, 
marking a substantial increase in the scope of speech recognition capabilities. Simultaneously, Soviet 
scientists made remarkable progress in developing algorithms capable of recognizing over 200 words, 
further expanding the potential applications of speech recognition technology. These advancements in the 
1960s laid the groundwork for future developments and demonstrated the growing potential of speech 
recognition as a tool for human-computer interaction [4]. 

Today, deep learning models combined with cloud computing have largely reinvigorated the advanced 
field of text-to-speech technology. Cloud-based platforms offer scalable solutions for processing large 
volumes of data, enabling the development of more sophisticated and accurate models. Additionally, the 
availability of vast amounts of data has fueled the development of deep learning techniques, which have 
significantly improved the quality of machine generated and synthesized speech. These innovations have 
made speech recognition technology more accessible and versatile, finding applications in various 
domains, including virtual assistants, language learning, and accessibility tools [4]. 

Even today, speech recognition is a complex field within computer science, which involves converting 
spoken language into written text. Overall, speech recognition (SR) is a complex field involving linguistics, 
mathematics, and statistics. Speech recognizers consist of components like speech input, feature 
extraction, feature vectors, a decoder, and word output [6]. 

### Components of Speech Recognition: 
<p ## Audio Signal Processing: /p> The first step in speech recognition is capturing the audio signal using 
microphones. The audio is then processed to remove noise and enhance the clarity of the speech 
signal. 
 
Feature Extraction: The processed audio signal is analyzed to extract key features, such as pitch, 
tone, and frequency. These features are crucial for distinguishing different sounds and phonemes 
in the speech. 

Pattern Recognition: The extracted features are then compared against a database of known 
patterns (e.g., phonemes, words, and phrases). The system uses these patterns to interpret the 
spoken words and convert them into text. 

Language Modeling: Language models help improve the accuracy of speech recognition by 
predicting the likelihood of certain words or phrases occurring in a given context. These models 
are trained on large datasets of text and speech to understand the structure and grammar of the 
language. 

### Speech Recognition Model Accuracy and Word Error Rate (WER) 
The decoder uses acoustic models, pronunciation dictionaries, and language models to determine the 
appropriate output.  Accuracy is measured by word error rate (WER). Factors like pronunciation, accent, 
pitch, volume, and background noise affect WER and is one of the primary challenges in speech recognition 
along with spoken language accents and semantics. The goal is to achieve human parity in WER. Research 
suggests a WER of around 4% is possible, but replication has been difficult. It requires a sophisticated 
combination of linguistics, mathematics, and statistics to achieve high accuracy [1, 6].  

### AI Driven Speech Recognition 
Artificial intelligence has revolutionized speech recognition (SR) by addressing the limitations of traditional 
rule-based systems, which were often constrained by predefined patterns and struggled to adapt to 
variations in accents, dialects, and speech patterns. AI-driven systems, powered by deep learning models 
and natural language processing techniques, have overcome these challenges, enabling more accurate, 
versatile, and user-friendly speech recognition capabilities. As a result, AI-based systems have 
revolutionized speech recognition by addressing the limitations of traditional rule-based systems, which 
were often constrained by predefined patterns and struggled to adapt to variations in accents, dialects, 
and speech patterns. These AI-driven systems, powered by deep learning models and natural language 
processing techniques, have overcome these challenges, enabling more accurate, versatile, and user
friendly speech recognition capabilities [1]. 

Deep learning models, and in particular neural networks, have been instrumental in improving the 
accuracy and adaptability of speech recognition systems. These models can learn from vast amounts of 
data, allowing them to recognize a wider range of speech patterns, accents, and dialects. By leveraging the 
power of deep learning, AI-driven systems can effectively capture the nuances of human speech, making 
them more robust and reliable in diverse environments [1]. 

Moreover, the integration of natural language processing (NLP) techniques has significantly enhanced the 
ability of speech recognition systems to understand the context and meaning behind spoken words. NLP 
algorithms can analyze the semantic and syntactic structure of language, allowing systems to not only 
transcribe speech but also comprehend the intent and context of the utterance. This capability enables 
more natural and intuitive interactions, as systems can respond appropriately to user queries and 
commands, even in complex or ambiguous situations [1]. 

### Examples of AI-Driven Enhancements in Speech Recognition [1]: 

Deep Learning and Neural Networks: AI-driven systems use deep learning models to improve accuracy 
and adaptability, allowing them to recognize a wider range of speech patterns and accents. 

Natural Language Processing (NLP): AI integrates NLP techniques to understand the context and 
meaning behind spoken words, enabling more natural and intuitive interactions. 

Real-time Adaptation: AI enables systems to adapt to individual users over time, improving their ability 
to recognize specific speech patterns and preferences. 
Multilingual Support: AI has significantly improved the ability of speech recognition systems to support 
multiple languages and dialects. 
Overall these AI aided enhancements are enbling the development of more accurate, versatile, and user
friendly speech recognition systems with a wider range of applications, thereby, transforming the way we 
interact with technology now and in the future. 

### Applications in AI Enhanced Speech Recognition: Transforming Industries 

Artificial intelligence has significantly advanced speech recognition (SR) technology, enabling a wide range 
of application across various industries. By leveraging the power of AI, speech recognition systems have 
become more accurate, efficient, and versatile, transforming the way we interact with machines [1]. 
One of the most notable impacts of AI-driven speech recognition is in the healthcare sector. 

AI-powered systems can automatically transcribe medical dictation, reducing the administrative burden on healthcare 
providers and improving the accuracy of medical records. This enables doctors and other healthcare 
professionals to focus more on patient care and less on time-consuming documentation tasks [1]. 

In the customer service industry, AI-powered speech recognition has revolutionized the way businesses 
interact with their customers. Virtual assistants and chatbots powered by AI can understand and respond 
to customer queries in real time, providing immediate assistance without the need for human 
intervention. This improves customer satisfaction and reduces wait times, leading to more efficient and 
effective customer service operations. 

The automotive industry has also benefited significantly from AI-driven speech recognition. Voice
controlled systems in vehicles allow drivers to control navigation, make phone calls, and adjust settings 
using their voice, reducing distractions and promoting safer driving. By minimizing the need for manual 
interaction with in-car systems, speech recognition technology enhances the overall driving experience. 

### Example Applications of AI-Driven SR Systems [1]: 

Healthcare: AI-powered speech recognition automates medical transcription, reducing administrative 
burdens and improving the accuracy of medical records. 

Customer Service: Virtual assistants and chatbots powered by AI enhance customer service efficiency, 
reduce wait times, and improve overall customer experiences.

Automotive Industry: Voice-controlled systems in vehicles, enabled by speech recognition, contribute 
to safer driving experiences by minimizing distractions. 

Education: AI-driven speech recognition tools make education more accessible, facilitating language 
learning and providing support for students with disabilities. 

Entertainment: Voice-controlled gaming, virtual reality, and content search enhance user experiences, 
making entertainment more interactive and engaging. 

The recent developments in AI-driven speech recognition is transforming industries by enabling more 
natural and intuitive human-computer interactions. This technology improves accuracy, efficiency, and 
accessibility, opening up new possibilities for innovation in various fields and continues to advance the 
field of speech recognition and tis applications[1]. 

### Speech-to-Text with Deep Learning 

Deep learning neural network based speech recognition (SR) systems address limitations of traditional 
rule-based systems, which are often constrained by predefined patterns and struggle to adapt to variations 
in accents, dialects, and speech patterns. Moreover, AI-driven systems, powered by deep learning models 
and natural language processing techniques, have overcome these challenges, enabling more accurate, 
versatile, and user-friendly speech recognition capabilities. Additionally, this is a critical advancement in 
the field of natural language processing (NLP) which has revolutionized how we convert spoken language 
into text [1]. 

The following items include the process steps of converting speech to text, all of which can be efficiently 
handled by deep learning models [1]:  

Audio Input Processing: The first step is to process the incoming audio signal, which typically 
involves splitting the audio into small segments or "slices." These segments might be as short as 
20 milliseconds, as shown in the diagram on the slide.  

Feature Extraction: Each audio slice is then transformed into a set of features that can be 
processed by the neural network. Common features include Mel-frequency cepstral coefficients 
(MFCCs) and spectrograms, which represent the frequency and intensity of the audio signal over 
time.  

Modeling Sequential Data: Speech is inherently sequential, meaning the order of the audio slices 
matters. Deep learning models, particularly those designed for sequential data, are used to 
capture this temporal relationship. The model processes each slice in the context of previous slices 
to maintain the continuity of speech. 

Prediction of Phonemes or Words: As the model processes each audio slice, it generates a 
probability distribution over possible phonemes or words. The model's current state, influenced 
by previous audio slices, guides the prediction for the current slice. 

Decoding the Output: The final step involves decoding the sequence of predicted phonemes or 
words into coherent text. This might involve additional processing, such as using language models 
to improve the grammaticality and coherence of the output. 

An important feature of any Deep Learning Model is the architecture utilized for the neural network. 
Although many, there a few prominent models more commonly used for SR and speech-to-text purposes. 

These include the following deep learning models [1]: 

Recurrent Neural Networks (RNNs): RNNs are designed to handle sequential data by maintaining 
a hidden state that is passed from one time step to the next. This makes them suitable for speech 
recognition, where the sequence of sounds is crucial.  

Long Short-Term Memory (LSTMs): A form of RNN that includes special gates to control the flow 
of information, allowing them to maintain long-term dependencies. This helps in handling 
sequences where context from earlier in the sequence is important.  

Transformers: Transformers rely on self-attention mechanisms to process sequences in parallel, 
rather than sequentially. This allows for more efficient computation and the ability to capture long
range dependencies more effectively.  

Speech-to-Text  Speaker Diarization 
Speaker diarization is a technique used to identify and separate the speech of different speakers in an 
audio recording. By analyzing the audio stream, the system can determine who spoke at what time, 
providing valuable information for applications like transcription, analysis, or indexing. In addition, This 
technique is especially useful in scenarios with multiple speakers, such as meetings, interviews, or 
broadcast news, where distinguishing between different speakers is crucial for accurate understanding and 
analysis of the content [1]. 

The primary purpose of speaker diarization is to enhance transcription, understanding, and usefuleness of 
audio data by detecting, identifying, and separating speakers. This enhances transcription, provides better 
speaker-specific analysis, and improved interaction with the data [1]. 

Speaker diarization has various practical applications, including [1]: 

Improved Transcription: In transcription settings, diarization provides valuable information by labeling 
the speech of different speakers, making transcripts more understandable and useful. 

Meeting Analysis: Diarization tools can track participation, identify dominant speakers, and analyze 
the content of each speaker's speech, aiding in meeting summarization and understanding group 
dynamics. 

Audio Indexing: For large datasets of audio or video content, diarization helps index data by speaker, 
facilitating easier searching and retrieval of information. 

Enhanced User Experience: In voice-activated systems, diarization can improve the user experience by 
distinguishing between different users and responding appropriately based on the speaker's identity. 

These applications demonstrate the versatility and value of speaker diarization in various domains, from 
transcription to meeting analysis and user experience enhancement. 

### Generalized Inference with Deep Learning SR models 

Deep learning models have significantly outperformed traditional methods in speech recognition due to 
their ability to capture and model complex patterns in speech data. Unlike traditional methods, which rely 
on handcrafted features and statistical models, deep learning models can automatically learn relevant 
features from raw audio data, leading to more accurate and robust recognition [1]. 

### Noise Robustness Filtering in SR 

Deep learning methods utilized for SR enable the ability to handle and process variability in speech data. 
Traditional methods struggled to cope with variations in accents, speaking styles, and noisy environments, 
often leading to degraded performance. Deep learning models, on the other hand, can learn to generalize 
across these variations, making them more adaptable to different speech inputs. This robustness is 
particularly important in real-world applications where speech data can be noisy or non-standard [1]. 

Moreover, noise is typically a challenging barrier with speech recognition systems which limits accurate 
transcription and understanding of speech. 

A few challenges include the following [1]: 

Variety of Sound Sources – Unwanted sounds or noise can come from many varying sources 
including background sound, traffice, industrial machinery, and even environmental factors such 
as rain and wind. 

Signal Degradation – Noise can appear in form of sound signal transform quality which translates 
into incorrect feature extraction. 

Overlapping Speech – Constructive and destructive interference can occur when multiple people 
are speaking simultaneously in similar frequency rnages. This creates an overlapping effect and is 
challenging to filter out unwanted noisy interference in the wanted sound. 

Variability in Noise Levels – Varying noise levels can change rapidly within the same invironment 
or across different environments requireing speech recognition systems to adapt quickly and 
effectively to maintain accuracy. 

There are several prominent methods utilized to improve noise reduction and noise robustness within 
speech recogniton systems including [1]: 

Noise Reduction Algorithms – Algorithms designed to filter out noise from the audio signal before 
it is processed by the speech recognition system. Common methods include spectral subtraction, 
Weiner filtering, and adaptive filtering. 

Data Augmentation – This method involves artificially creating cariations in the training data to 
improve the model’s ability to generalize to different noise conditions. 
Training with Noisy Data – The objective of traning with noisy audio samples is to train the model 
to distinguish between noise and speech. 

In addition, it is not uncommon for multiple combinations of the above methods to be utilized to train and 
fine-tune noise-robust automatic speech recognition systems. Moreover, recent research  has 
demonstrated significant progress by creating noisy training models with the use of data augmentation to 
create and embed the noisy audio files, combined with the use of adaptive filtering algoorithms [1, 5].  

Noisy audio files were generated by adding noist to original audio with a particular signal-to-noise ratio 
(SNR) which is the ratio between signal and noise [5]. The higher the SNR the better signal quality as 
illustrated in the the formula below where convolution was utilized to add or embed the noisy signals into 
the original signal [5]. 

<img width="900" height="600" alt="image" src="https://github.com/deep-model/Automatic_Speech_Recognition/blob/main/eq%205.png"/>

The graphs below in the figure indicate a significant reduction in % WER in both monolingual and 
multilingual models.  

<img width="900" height="600" alt="image" src="https://github.com/deep-model/Automatic_Speech_Recognition/blob/main/Abstract.png"/>
### Figure 2 – Results of ASR model trained with noise embedded augmented audio data set combined with [5]. 

### Training SR Models 

Training of deep learning models can be performed end-to-end, meaning the entire process from audio 
input to text output is optimized simultaneously. This contrasts with traditional methods, which often 
required separate models for different stages of the process (e.g., feature extraction, pattern recognition). 
End-to-end training simplifies the development pipeline, allowing for faster iteration and improvement of 
speech recognition systems [1].   

In addition, training models on noisy data  can have a significant effect on accuracy and usefullness of ASR 
models.  Unfortunately, there is a limited amount of noisy data for training even for the high-resource 
languages that have a large speech corpora. However, as other have demonstrated, training with data 
augmented data sets embedded with noise can is one possible solution to creating or generating noisy 
data sets to significantly reduce word error rates exhibited with inferential models [1,5]. 
Fortunately, there is now a few prominent noise-robust or noisy audio training sets for use in existing 
training data sets including [1]: 

DeepSpeech – Developed by Mozilla, DeepSpeech is an open-source speech recognitioin model 
that incorporates noise robustness techniques into the training set. 

Google’s ASR (Automatic Speech Recognition) System – Google ASR is used in well know ASR 
models such as Google Assistant and Google Translate and is known for its ability to dunction well 
in noisy environments. 

Kaldi ASR – An open-sourced toolkit that is widely used in academic and industrial research which 
includes nose-robust feratures for training models in noisy environments. 

NeMo (Neural Modules) ASR - Is an open-sourced NVIDIA end-to-end ASR toolkit for developing 
conversational AI models. Lab 6 utilizes this toolkit specifically to fine-tune a pre-trained model to 
improve noise robustness, and demonstrate the efficient way to train for various noisy conditions 
[7]. 

###  End-to-End ASR Models 
End-to-end Automatic Speech Recognition (ASR) models represent a significant advancement over 
traditional methods. Unlike traditional systems that break down the process into multiple steps, end-to
end models directly map raw audio inputs to text outputs, streamlining the entire process. This integration 
leads to improved accuracy and efficiency, as the model can learn to optimize all aspects of the task 
simultaneously [1]. 

In addition, end-to-end ASR models simplify speech recognition pipeline by eliminating 
the need for multiple or separate models by utilizing the following techniques: 

End-to-end ASR models offer several advantages over traditional methods, including [1]: 

Direct Mapping: By directly mapping raw audio to text, end-to-end models eliminate the need for 
intermediate representations, simplifying the system and allowing for simultaneous optimization. 

Unified Model Architecture: The use of a single neural network architecture streamlines the process 
and reduces complexity. 
Reduced Dependency on Handcrafted Features: End-to-end models can learn relevant features 
directly from raw audio data, reducing reliance on handcrafted features like MFCCs. 

Simplified Training Process: The integrated approach eliminates the need for training and fine-tuning 
multiple separate components, leading to faster development and deployment. 

Improved Performance: End-to-end models often achieve better recognition accuracy and are more 
robust to variations in speech and background noise. 

### Scalability in SR models 

Finally, deep learning models are highly scalable and can be adapted to different languages, dialects, and 
domains with relative ease. This flexibility is essential for building speech recognition systems that can be 
deployed in various contexts and cater to diverse user needs. By leveraging the power of deep learning, 
speech recognition systems can be made more accessible and inclusive, breaking down language barriers 
and enabling communication across different cultures [1]. 

Improved Accuracy: Deep learning models, especially those using architectures like LSTMs and 
transformers, can capture more complex patterns in speech data, leading to higher accuracy in 
recognition and transcription. 

Handling Variability: Deep learning models are more robust to variations in accents, speaking styles, 
and noisy environments, making them more adaptable to different speech inputs.

End-to-End Training: Deep learning models can be trained end-to-end, simplifying the development 
process and allowing for faster iteration and improvement. 

Scalability and Flexibility: Deep learning models are highly scalable and can be adapted to different 
languages, dialects, and domains with relative ease. 

These advantages have enabled AI-driven speech recognition systems to achieve remarkable accuracy and 
versatility, transforming the way we interact with technology. 

### Project – Speech Recognition with End-to-End ASR 

Code Reference: Google Colab. (n.d.). 
https://colab.research.google.com/github/NVIDIA/NeMo/blob/stable/tutorials/asr/ASR_with_NeMo.ipy
nb [8] 

### The process for the Transformer Classification: 

Step 1 – Load the Python Libraries huggingface_hub and NeMo toolkit ASR from Github 
Step 2 – Create Path to data directory   
Step 3 – Load AN4 Dataset  
Step 4 – Convert to .wav Audio Files 
Step 5 – Verify Dataset Loaded & Converted (display audio waveform) 
Step 6 – Install NeMo ASR Toolkit 
Step 7 – Insantiate QuartzNet ASR Model 
Step 8 – Create Training/Evaluation Manifest of Metadata/Descriptions 
Step 9 – Load YAML Model Parameter Configurations 
Step 10 – Train Model with PyTorch Lightning 
Step 11 – Inference 








This repository hosts a **GitHub Pages–optimized version** of the ASR Report by **Matthew Harper**.

## 📄 Live Document
👉 View the report here: [**GitHub Pages site**](https://github.com/deep-model/Automatic_Speech_Recognition/blob/main/ASR_Report_M.Harper.pdf)

## 📂 Repository Structure
```
main/
 ├── ASR_Report_M.Harper.pdf
 ├── speech_recognition.py

docs/
 ├── index.md        # Main rendered document
 ├── page_merged.svg # Visual pages 1–15 (vector)
```

## 🛠️ Formats Provided
- Markdown (semantic, searchable)
- SVG (high-fidelity visual reference)

## 🚀 Deployment
This site is deployed using **GitHub Pages** from the `/docs` directory.











