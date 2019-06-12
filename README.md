# DL40959-9798-Project
Required material for Deep Learning Course Project

Instructor: Mahdieh Soleymani

Course Page: [http://ce.sharif.edu/courses/97-98/2/ce959-1/](http://ce.sharif.edu/courses/97-98/2/ce959-1/)

## Prerequsites
* Distance
* nltk

```
pip3 install -r requirements.txt
```

## Usage

### For Evaluating BLEU Score
```shell
python3 Evaluation/bleu_score.py --target-formulas target.txt --predicted-formulas predicted.txt --ngram 5
```

### For Evaluating Edit Distance Accuracy

```shell
python3 Evaluation/edit_distance.py --target-formulas target.txt --predicted-formulas predicted.txt
```
