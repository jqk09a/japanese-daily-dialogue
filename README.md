# Japanese-Daily-Dialogue

**Japanese Daily Dialogue (in Japanese, 日本語日常対話コーパス)** is a high-quality multi-turn dialogue dataset.
The dataset consists of daily conversations on five topics, all written in standard Japanese using basic vocabulary and word order. All data were manually created and processed.



## Statistics

| Topic | # of dialogue | # of utterance |
| --- | ---: | ---: |
| Dailylife | 1,070 | 8,462 |
| School | 1,058 | 8,197 |
| Travel | 1,021 | 8,459 |
| Health | 1,061 | 8,344 |
| Entertainment | 1,051 | 8,318 |
| Total | 5,261 | 41,780 |



## Data Format


```json
{
    "topic_id": 3,
    "topic_name": "Travel",
    "dialogue_id": 611,
    "dialogue_length": 8,
    "utterances": [
        {
            "turn_num": 1,
            "speaker": "A",
            "utterance": "おはようございます。高原の朝は冷えますね。"
        },
        {
            "turn_num": 2,
            "speaker": "B",
            "utterance": "おはようございます。本当ですね。羽織るものが欲しいです。"
        },
        ,,,
        {
            "turn_num": 8,
            "speaker": "B",
            "utterance": "ロッジのオーナーに聞いてみましょう。"
        }
    ]
}   
```


## Reference
For more details, please refer to the following paper:
```
@InProceedings{akama2023jdd,
  title = {{日本語日常対話コーパスの構築}},
  author = {赤間 怜奈 and 磯部 順子 and 鈴木 潤 and 乾 健太郎},
  booktitle = {言語処理学会 第29回年次大会 発表論文集},
  pages = {108--113},
  year = {2023};
  url = {https://www.anlp.jp/proceedings/annual_meeting/2023/pdf_dir/H1-1.pdf}
}
```

## Copyright
All copyright of this dataset belongs to our research group.
The dataset is only for research purposes. It is accessible to commercial companies for research and evaluation, but it may not be utilized as a service, such as a chatbot or any other similar application.
The dataset may not be distributed to others. 

## License

Japanese Dialy Dialogue dataset is licensed under a
[Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License][cc-by-nc-nd].

[![CC BY-NC-ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]

[cc-by-nc-nd]: http://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png
[cc-by-nc-nd-shield]: https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg
