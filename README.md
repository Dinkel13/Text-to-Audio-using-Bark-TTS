# Text-to-Audio-using-Bark-TTS

# Bark  Text-to-Speech

## Overview
Bark Text-to-Speech is a Python-based solution that leverages the Bark text-to-speech engine to convert text into speech. This documentation provides a concise guide on how to set up and use Bark Text-to-Speech in your projects.


## Getting Started

### Prerequisites

Before you begin, ensure you have the following prerequisites:

Python 3.10
Bark Text-to-Speech API Key (obtain it from Bark TTS API)

Open a Python script or Jupyter Notebook where you want to use Bark Text-to-Speech.



## Installing all the dependency

Clone the repository:

```pip install git+https://github.com/suno-ai/bark.git```

Install Hugging Face Transformers library from main:

```pip install git+https://github.com/huggingface/transformers.git```

```pip install nltk```


```preload_models()```

Format a script and speaker lookup :

```
script = """ Put it in your choice"""
```

```nltk.download('punkt')```

```sentences = nltk.sent_tokenize(script)```


## Acknowledgments

Bark TTS for providing the text-to-speech engine.

The open-source community for creating and maintaining the libraries used in this project.
