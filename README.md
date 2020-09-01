# GPT-2 based wikie simplifier 2020

#### Daniel Kharitonov, dkh@cs.stanford.edu

### Description:

This is a Wikipedia Simplifier project. It trains a generator on Simple English and attempts to use it to transform regular Wikipedia articles, for example:

```
Heracles' very existence proved at least one of Zeus' many illicit affairs, 
and Hera often conspired against Zeus' mortal offspring as revenge for her 
husband's infidelities.

(Flesch-Kinkaid score: 55.2)
```

can be transformed to:

```
Heracles' very existence proved at least one of Zeus' many illicit affairs, 
and Hera was crushed by the wrath when she had harboured those offspring of Zeus. 

(Flesch-Kinkaid score: 64.75)
```

The Rejection-Pass (RPF) architecture used in this project is shown below:
![alt text](https://github.com/volkfox/224n-final/blob/master/RPF.png "RPF architecture")

## Files:

This repositary contains the traning set and a Pyton notebook for a Wikipedia Simplifier.
Training dataset exceeds GitHub storage limit and can be downloaded from here:

Training set (53MB)
https://drive.google.com/open?id=1YEN3fJ2qG3wLvddBAOlkEZwvuXFrip9u

Full Simple Wikipedia snapshot (155MB)
https://drive.google.com/open?id=1YEN3fJ2qG3wLvddBAOlkEZwvuXFrip9u

[Python Notebook with Google Collab link](https://github.com/volkfox/224n-final/blob/master/RPF_CS224n.ipynb)

## Usage:

Upload the training set and go through a notebook to train and deploy your RPF simplifier instance.

Requires GPU 16GB+



