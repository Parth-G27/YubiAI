# Classification performance for yubilangdetect-e8-v1 on open-subtitles-v2018-100k-per-lang

- Dataset coverage (sentences in supported languages): 508349 (27.60%)
- **Aggregated accuracy: 95.81%**

<h2 id="supported-languages">Considered Languages for Evaluation (27)</h2>

hin (Hindi), ben (Bangla), guj (Gujarati), pan (Punjabi), mal (Malayalam), kan (Kannada), tam (Tamil), tel (Telugu), ori (Odia), mar (Marathi), asm (Assamese), nep (Nepali), urd (Urdu), eng (English), hin_Latn (Hindi (Latin)), ben_Latn (Bangla (Latin)), guj_Latn (Gujarati (Latin)), pan_Latn (Punjabi (Latin)), mal_Latn (Malayalam (Latin)), kan_Latn (Kannada (Latin)), tel_Latn (Telugu (Latin)), tam_Latn (Tamil (Latin)), mar_Latn (Marathi (Latin)), ori_Latn (Odia (Latin)), nep_Latn (Nepali (Latin)), urd_Latn (Urdu (Latin)), asm_Latn (Assamese (Latin))

<h2 id="metrics-per-language">Stats per language</h2>

|    | language_alpha3   | language   |   sentences_count |   precision |   recall |    f1 |    tp |   fp |     tn |    fn |
|---:|:------------------|:-----------|------------------:|------------:|---------:|------:|------:|-----:|-------:|------:|
|  1 | eng               | English    |             99932 |       0.994 |    0.948 | 0.967 | 94733 |  619 | 407798 |  5199 |
|  2 | mal               | Malayalam  |             99331 |       1.000 |    0.983 | 0.991 | 97621 |    1 | 409017 |  1710 |
|  3 | ben               | Bangla     |             98549 |       0.999 |    0.977 | 0.988 | 96297 |   68 | 409732 |  2252 |
|  4 | hin               | Hindi      |             97336 |       1.000 |    0.894 | 0.944 | 87040 |   35 | 410978 | 10296 |
|  5 | urd               | Urdu       |             45315 |       1.000 |    0.980 | 0.990 | 44424 |    6 | 463028 |   891 |
|  6 | tam               | Tamil      |             38761 |       1.000 |    0.987 | 0.993 | 38251 |   10 | 469578 |   510 |
|  7 | tel               | Telugu     |             29125 |       1.000 |    0.984 | 0.992 | 28664 |    1 | 479223 |   461 |