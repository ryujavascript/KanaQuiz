# KanaQuiz

Can you name the Romaji (English syllable) that matches the Hiragana/Katakana character ?

## Requirements

- Python 3.5+

## Usage

```bash
usage python kanaquiz.py <operation>
operations: 
    python kanaquiz.py {-h}     play hiragana only
    python kanaquiz.py {-k}     play katakana only
    python kanaquiz.py {-a}     play all kana quiz
    python kanaquiz.py {-d}     play dakuon quiz
    python kanaquiz.py {-t}     play trinity quiz
    python kanaquiz.py {-l}     list kanas with romaji
    python kanaquiz.py {-o}     list kanas only
    python kanaquiz.py {-q}     query performance history
```

## Tutorial

List all the hiragana/katakana characters and their romanized names:

```bash
python kanaquiz.py -l
```

Study/review kanas right inside your terminal: 

![](images/table.png)

When you are ready, take the hiragana quiz at first:

```bash
python kanaquiz.py -h
```

click enter to start the quiz:

```
[ よ ]  (1/46)
 ? {cursor}
```

Read the kana character in the square brackets `[ ]` and input its romanized name after the question mark `?` then press Enter to continue.

example:

![](images/quiz-1.png)

There will be a nice performance report after finished:

![](images/report.png)

Figure out which kana got the slowest response time (you are least likely to remember) and take time to practice.

The history reports can always be queried by:

```bash
python kanaquiz.py -q
```

Check the hiragana/katakana chart at any time if you can't remember them by:

```bash
python kanaquiz.py -l
```




## Credit

- Twitter: [@skywind3000](https://twitter.com/skywind3000)
