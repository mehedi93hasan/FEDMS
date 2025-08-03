<h1><b>Overview</b></h1>
FEDMS is an innovative adversarial defense framework designed specifically for network intrusion detection systems (NIDS). 
Our approach integrates nine heterogeneous detection models across three complementary categories with a sophisticated 
multi-dimensional confidence scoring mechanism that enables dynamic model selection based on real-time input characteristics and threat assessment.

<h1><b>Key Achievements</b></h1>

-96.8% accuracy on clean network traffic data

-75.5% average accuracy under strong adversarial attacks (16.6% improvement over state-of-the-art)

-12.4ms average processing latency suitable for enterprise deployment

-Real-time adaptation capabilities for evolving threat landscapes

<h1><b>System Architecture</b></h1> 
Main Framework Architecture
<div align="center">
  <img width="2563" height="1244" alt="fig 1_1 v8" src="https://github.com/user-attachments/assets/a504ec05-3441-491a-b317-38f52a7a39d1" />
  <br>
  <em>Figure 1: System architecture of our proposed adversarial defense framework showing the three-tier hierarchical structure integrating heterogeneous ensemble components, multi-dimensional confidence scoring, and dynamic selection mechanisms.</em>
</div>


<h1><b>Real-time Adaptation Framework</b></h1>  
<div align="center">
  <img width="1409" height="363" alt="fig 1_2 v3" src="https://github.com/user-attachments/assets/474acac1-ab0f-477f-af8f-4ae29d8beadc" />
  <br>
  <em>Figure 2: Real-time adaptation framework showing continuous system evolution through concept drift detection, threshold adaptation, model reweighting, and performance validation mechanisms.</em>
</div>

<h1><b>Installation</b></h1>  

<h2><b>Prerequisites </b></h2>  
 
Python 3.9.16+

CUDA 11.8+ (for GPU acceleration)

32GB RAM recommended for optimal performance

<h2><b>Quick Installation</b></h2> 

git clone https://github.com/mehedi93hasan/FEDMS.git

cd FEDMS

<h2><b>Quick Dependencies</b></h2> 
<br>

pip install tensorflow==2.13.0

pip install scikit-learn==1.3.0

pip install xgboost

pip install pyod==1.1.0

pip install numpy==1.24.3

pip install pandas==2.0.3

pip install matplotlib==3.7.2

pip install tqdm

pip install joblib

</br>

<h1><b>Citation</b></h1>  
bibtex@article{hasan2025amte, title={Ensemble-Based Adversarial Defense with Dynamic Model Selection for Intrusion Detection Systems}, author={Hasan, Md Mehedi and Islam, Rafiqul and Mamun, Quazi and Islam, Md Zahidul and Gao, Junbin}, journal={Research Article}, year={2025} }

