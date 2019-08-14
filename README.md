# stagnation-data
### 1、About this Study

Almost all users have ever experienced poor responsiveness with Android phones, in particular Application Not Responding (ANR) and System Not Responding (SNR) which have a direct, disrupting impact on user experience. Unfortunately, there is little visibility into their actual prevalence, characteristics, and root causes. In this paper, we make an indepth study of ANR and SNR at scale in the wild, based on fine-grained system-level crowdsourced data from 30,000 Android phones. We find that ANR and SNR happen prevalently to all our studied 15 models of phones, while better hardware does not seem to relieve the problem. In contrast, as Android evolves from version 7.0 to 9.0, there are fewer ANR but more SNR events. In addition, we uncover the multifold root causes of ANR and SNR, and pinpoint the largest one as the pathology of Android’s implementation of write amplification mitigation (WAM). We design a practical
approach to eliminating this root cause; after real deployment, it reduces almost all (>99%) ANR and SNR caused by WAM while only decreasing 3% of the data write speed.

### 2、Code and Raw Data Download

our paper has been submitted to MobiCom2020

#### Code

#### Raw Data

### 3、Contact

limingliang0527@gmail.com

linhao16@mails.tsinghua.edu.cn
