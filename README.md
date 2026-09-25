![Logo](/readme-files/vica-scaled.png "ViCa Logo")
### a vietnamese corpus for diffsinger
> yes i did make a logo. god forbid a girl has hobbies!
---
# \[ introduction \]
**NOTE**: i am not fluent in vietnamese (sorry ancestors) so pronunciation may seem off. this corpus serves as a way to cover all the phonemes and shouldn't be used as the only vietnamese corpus in your dataset (if there are any that are public to begin with). additionally, this does not follow jani tran's vietnamese phoneme list, but follows a slightly edited version based on chezzie-chan's vietnamese vccv reclist. oh, did i mention that the corpus is reclist recordings? well now i did now. good luck!

first diffsinger dataset heyyyy! i decided to make a pretty scuffed corpus for vietnamese support! i mainly recorded this since reclists are lowkey the best way to cover every phoneme under the bus but anygays! this is extremely scuffed but i hope this can be of help!

# \[ dataset info \]
452 .wav files

26 minutes and 11 seconds

denoised and dereverbed

recorded at 16 bit 44.1k hz

labeled in .lab format

uses `vi` as its language code

# \[ phonemes \]
> based on chezzie-chan's vietnamese vccv reclist
>
> examples and non-vietnamese approximation have been referenced from wikipedia

## non vocal phonemes
| use           | phoneme | description  |
| ------------- | :-----: | ------------ |
| silent stops  | pau     | pure silence |
| glottal stops | Q       | abrupt stops |

## consonant phonemes
| ipa | phoneme | example            | non-viet. approximation               |
| --- | :-----: | ------------------ | ------------------------------------- |
| m   | m       | **m**ai            | **m**y                                |
| n   | n       | **n**am            | **n**o                                |
| ɲ   | nh      | **nh**à            | ca**ny**on, se**ñ**orita, **gn**occhi |
| ŋ   | ng      | **ng**âm, **ng**he | si**ng**er                            |
| p   | p       | **p**in            | s**p**ort                             |
| t   | t       | **t**ây            | s**t**op                              |
| tʰ  | th      | **th**ầy           | **t**op, **t**as**te**                |
| ʈʂ  | tr      | **tr**a            | **tr**end, but with tongue curled     |
| c   | ch      | **ch**è            | **ch**ange                            |
| k   | k       | **c**ô, **k**em    | s**c**an                              |
| ɓ   | b       | **b**a             | **b**ee with a gulp                   |
| ɗ   | d       | **đ**i             | **d**ay with a gulp                   |
| f   | ph      | **ph**ở            | **f**ight, **ph**oto                  |
| s   | x       | **x**a             | **s**o                                |
| ʂ   | s       | **s**áu            | **sh**ow, but with tongue curled      |
| x   | kh      | **kh**ô            | lo**ch**                              |
| h   | h       | **h**àng           | **h**igh                              |
| v   | v       | **v**ề             | **v**ictory                           |
| z/ʐ | z       | **d**a, **d**anh   | **z**ero                              |
| ɣ   | g       | **g**a, **gh**ế    | ami**g**o                             |
| l   | l       | **l**à             | **l**ow                               |
| j   | y       | **gi**à, **gi**ết  | **y**es                               |
| w   | w       | **o**anh, q**u**ốc | q**u**ick                             |

## vowel phonemes
| ipa | phoneme | example                  | non-viet. approximation           |
| --- | :-----: | ------------------------ | --------------------------------- |
| i   | i       | kh**i**, tu**y**         | s**ea**t                          |
| ɨ   | U       | t**ư**                   | glass**e**s, т**ы**               |
| u   | u       | r**u**, t**u**i          | r**u**le                          |
| e   | E       | v**ề**, c**â**y          | d**a**y, s**ai**d (monophthongal) |
| ɛ   | e       | x**e**                   | l**e**d                           |
| o   | O       | c**ô**, s**â**u          | st**o**ry                         |
| ɔ   | o       | c**ó**, x**oo**ng        | **o**ff                           |
| ə   | A       | **ă**n, m**a**y, c**a**u | c**u**t                           |
| a   | a       | b**a**, m**a**i, c**a**o | l**a**ugh, m**a**d                |

# \[ terms of use \]
\- you **are allowed** to use this dataset for multispeaker training of **svs models**

\- you **are allowed** to use this dataset for research purposes

\- you **are allowed** to use this dataset for training commercial svs models

\- you **are allowed** to use this dataset to train an svs model of this voice, but you **are not allowed** to release it

---

\- you **are not allowed** to use this dataset for multispeaker training if your dataset contains vocalists that **haven't given you permission** for ai training

\- you **are not allowed** to run this dataset through any **svc technology** to morph it into other vocals

\- you **are not allowed** to use this dataset to train an **svc model**

# \[ credits \]
**aple**: creator, voice provider, labeling

**alex floarea**: name provider, labeling

# \[ license \]
ViCa © 2026 by aple is licensed under CC BY 4.0
