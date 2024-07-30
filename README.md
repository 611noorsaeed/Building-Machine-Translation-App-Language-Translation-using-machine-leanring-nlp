# Building-Machine-Translation-App-Language-Translation-using-machine-leanring-nlp


Language Translation
Language translation is the process of converting text or speech from one language to another while preserving its meaning and context. This involves using linguistic and computational techniques to interpret the source language and generate the equivalent content in the target language. Modern translation methods often employ machine learning models and neural networks for accuracy and fluency.

We have two problems
First Problem: Language Detection
The first problem is to know how you can detect language for particular data. In this case, you can use a simple python package called langdetect.

supports 55 languages

af, ar, bg, bn, ca, cs, cy, da, de, el, en, es, et, fa, fi, fr, gu, he, hi, hr, hu, id, it, ja, kn, ko, lt, lv, mk, ml, mr, ne, nl, no, pa, pl, pt, ro, ru, sk, sl, so, sq, sv, sw, ta, te, th, tl, tr, uk, ur, vi, zh-cn, zh-tw

pip install langdetect

Second Problem: Language Translation
The second problem you need to solve is to translate a text from one language to the language of your choice. In this case, you will use another useful python package called google_trans_new.

google_trans_new is a free and unlimited python package that implemented Google Translate API and It also performs auto language detection.

Install google_trans_new

but it has some issues so we will use alternatives....

pip install googletrans==4.0.0-rc1
