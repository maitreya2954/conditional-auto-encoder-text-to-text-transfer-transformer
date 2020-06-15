Code for CAE-T5

Requirements: 
* tensorflow==1.15.0
* tensorflow-text<2
* transformers==2.8.0
* kenlm==0.0.0
* t5==0.5.0
* tfds-nightly>=1.3.2.dev201912070105,<2.1.0.dev202003190105
* fasttext==0.9.2
* google-api-python-client==1.7.12 

To run on TPU: python main.py

--gin_file="objectives/denoise.gin"

