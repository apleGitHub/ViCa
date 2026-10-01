![Logo](/readme-files/vica-scaled.png "ViCa Logo")
### a vietnamese corpus for diffsinger
> yes i did make a logo. god forbid a girl has hobbies!
---
# \[ introduction \]
**NOTE**: i am not fluent in vietnamese (sorry ancestors) so pronunciation may seem off. this corpus serves as a way to cover all the phonemes and shouldn't be used as the only vietnamese corpus in your dataset (if there are any that are public to begin with). let's hope it isn't too scuffed! hopefully this can allow other public vietnamese corpuses to be created, i don't want to be the only one which in turn can fuck up a lot of pronunciations!

first diffsinger dataset heyyyy! i decided to make a pretty scuffed corpus for vietnamese support! i mainly recorded this since reclists are lowkey the best way to cover every phoneme under the bus but anygays! this is extremely scuffed but i hope this can be of help!

# \[ dataset info \]
461 .wav files

26 minutes and 42 seconds

denoised, dereverbed, and normalized

recorded at 16 bit 44.1k hz mono

labeled in .lab format

uses `vi` as its language code

# \[ phonemes \]
> examples and non-vietnamese approximation have been referenced from wikipedia

## non vocal phonemes
| use           | phoneme | description  |
| ------------- | :-----: | ------------ |
| silent stops  | pau     | pure silence |
| glottal stops | Q       | abrupt stops |

## initial consonant phonemes
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

## final consonant phonemes
| ipa | phoneme | example                   | non-viet. approximation           |
| --- | :-----: | ------------------------- | --------------------------------- |
| k̟   | CH      | cá**ch**          | te**ch**nical                         |
| k   | K       | á**c**, họ**c**  | pi**ck** |
| ɲ   | NH      | bì**nh**                    | o**ni**on                |
| ŋ   | NG      | trứ**ng**, chú**ng**            | lo**ng** |
| e   | N       | ba**n**, mì**n**, bê**n**, bố**n**, bú**n** | pi**n**, he**n**, pe**n** |
| m   | M       | thê**m**                  | l**e**d                           |
| p̚   | P       | tiế**p**           | clas**p**, but no audible release |
| t   | T       | xuấ**t**, chí**t**, mộ**t**         | pi**t**, hi**t**, cu**t** |
| j   | Y       | cá**i**, ta**y**, tu**i** | b**o**y                           |
| w   | W       | ta**o**, triệ**u**, đa**u**  | ho**w**                |

## vowel phonemes
| ipa | phoneme | example                            | non-viet. approximation           |
| --- | :-----: | ---------------------------------- | --------------------------------- |
| a   | a       | b**a**, m**a**i, c**a**o           | l**a**ugh, m**a**d                |
| ʌ   | ah      | **â**n                             | bal**a**nce                       |
| ɤ   | er      | b**ơ**                             | b**oo**k                          |
| e   | e       | v**ề**, c**â**y                    | d**a**y, s**ai**d (monophthongal) |
| ɛ   | eh      | x**e**                             | l**e**d                           |
| i   | i       | kh**i**, tu**y**                   | s**ea**t                          |
| o   | o       | c**ô**, s**â**u                    | 노래 / n**o**rae                  |
| ɔ   | ao      | c**ó**, x**oo**ng                  | **o**ff                           |
| ɯ   | eu      | t**ư**                             | glass**e**s, т**ы**               |
| u   | u       | r**u**, t**u**i                    | r**u**le                          |
| ə   | ax      | y**ê**u, ư**ớ**c, ư**a**, u**ô**ng | l**a**ugh, m**a**d                |

# \[ terms of use \]
\- you **are allowed** to use this dataset for multispeaker training of **svs models**

\- you **are allowed** to use this dataset for research purposes

\- you **are allowed** to use this dataset for training commercial svs models

\- you **are allowed** to use this dataset to train an svs model of this voice, but you **are not allowed** to release it

---
\- you **are not allowed** to redistribute the raw files of this dataset

\- you **are not allowed** to use this dataset for multispeaker training if your dataset contains vocalists that **haven't given you permission** for ai training

\- you **are not allowed** to run this dataset through any **svc technology** to morph it into other vocals

\- you **are not allowed** to use this dataset to train an **svc model**

# \[ credits \]
**aple**: creator, voice provider, labeling

**alex floarea**: name provider, labeling

# \[ license \]
ViCa © 2026 by aple is licensed under CC BY 4.0
