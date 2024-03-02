AbstrActs is a benchmark dataset for abstractive multi-video captioning.
Abstractive multi-video captioning is the task that models describe information shared by multiple videos as much as possible.
In order to solve this task, models need to not only understand each video in detail but also have strong abstraction abilities to find commonalities among videos.


![task example](assets/task_example.jpg)

# Example

# JSONL Data Sample
```
{
    "caption":"a person is doing an exercise in a gym",
    "vatex_caption":"In a gym, a man uses heavy rope to do some training.",
    "videos":[
        {"video_id":"8Uy4XBJ20Ag_000005_000015","entailment":3,"confidence":3},
        {"video_id":"KeJRWZAEAxM_000031_000041","entailment":2,"confidence":3},
        {"video_id":"ae5-o3wtONA_000000_000010","entailment":5,"confidence":3},
        {"video_id":"sjbyEx20ou4_000000_000010","entailment":2,"confidence":2}
    ]
}
```
![Data Sample](assets/data_sample.jpg)

# Downloadable Features
VATEX video features (CLIP4Clip):  
https://lotus.kuee.kyoto-u.ac.jp/~r-takahashi/dataset/VATEX_CLIP4Clip.zip

VATEX caption features (fasttext):  
https://lotus.kuee.kyoto-u.ac.jp/~r-takahashi/dataset/VATEX_caption_features.zip

# Citation
If you find this dataset helpful, please cite our publication.

```
Rikito Takahashi, Hirokazu Kiyomaru, Chenhui Chu, Sadao Kurohashi.
Abstractive Multi-Video Captioning: Benchmark Dataset Construction and Extensive Evaluation.
In Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING), (2024.5).
```

# Acknowledgements
This work was supported by JSPS KAKENHI Grant Number JP23H03454 and Fujitsu.
