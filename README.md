# Artificial Intelligence Engineer Nanodegree
## Intro to Natural Language Processing
# Project: Bookworm

A simple question-answering system built using IBM Watson's NLP services.

## Overview

In this project, I used IBM Watson's NLP Services to create a simple question-answering system. I used the Discovery service to pre-process a document collection and extract relevant information. I then used the Conversation service to build a natural language interface that can respond to questions.

## Prerequisites

1. Clone the repository and navigate to the downloaded folder.
    
    ``` 
        git clone https://github.com/udacity/aind2-dl.git
        cd aind2-dl
    ```

2. Obtain the necessary Python packages, and switch Keras backend to Tensorflow.  
    
    For __Mac/OSX__ or __Linux__:
    ```
        conda env create -f requirements/aind-dl-mac-linux.yml
        source activate aind-dl
        KERAS_BACKEND=tensorflow python -c "from keras import backend"
    ```

    For __Windows__:
    ```
        conda env create -f requirements/aind-dl-windows.yml
        activate aind-dl
        set KERAS_BACKEND=tensorflow
        python -c "from keras import backend"
    ```
    
3. Enjoy!


## Getting Started

Clone this repository to your local computer.

If you have the AIND Anaconda environment prepared, now is a good time to activate it.

Open the notebook `bookworm.ipynb` from a terminal using the following command:

```
jupyter notebook bookworm.ipynb
```

**Note**: You may have to install some packages (mentioned in the notebook). To do so, simply open another terminal and use pip.

### Additional Information
## IBM Watson Resources

- [Watson Developer Cloud](https://www.ibm.com/watson/developercloud/) [[GitHub](https://github.com/watson-developer-cloud/)]
  - [Starter Kits](https://www.ibm.com/watson/developercloud/starter-kits.html)
  - [Discovery service](https://www.ibm.com/watson/developercloud/doc/discovery/index.html)
  - [Conversation service](https://www.ibm.com/watson/developercloud/doc/conversation/index.html)

## Built With
## Authors
* **Udacity** - *Initial work* - [AIND-NLP-Bookworm](https://github.com/udacity/AIND-NLP-Bookworm)
* **Jonathan Sulivan**

## Acknowledgments
* Hackbright Academy
* Udacity

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. Please refer to [Udacity Terms of Service](https://www.udacity.com/legal) for further information.
