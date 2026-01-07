<img width="1705" height="744" alt="custom_datasets_examples" src="https://github.com/user-attachments/assets/603054da-7fed-44b9-b883-242384f4d2e2" />

# Learning from What is Already Out There: Few-shot Sign Language Recognition with Online Dictionaries

#### [Maty Bohacek](https://www.matybohacek.com) and [Marek Hruz](https://scholar.google.com/citations?user=f7M7JgQAAAAJ)

Today's sign language recognition models require large training corpora of laboratory-like videos, whose collection involves an extensive workforce and financial resources. As a result, only a handful of such systems are publicly available, not to mention their limited localization capabilities for less-populated sign languages. Utilizing online text-to-video dictionaries, which inherently hold annotated data of various attributes and sign languages, and training models in a few-shot fashion hence poses a promising path for the democratization of this technology. In this work, we collect and open-source the UWB-SL-Wild few-shot dataset, the first of its kind training resource consisting of dictionary-scraped videos. This dataset represents the actual distribution and characteristics of available online sign language data. We select glosses that directly overlap with the already existing datasets WLASL100 and ASLLVD and share their class mappings to allow for transfer learning experiments. Apart from providing baseline results on a pose-based architecture, we introduce a novel approach to training sign language recognition models in a few-shot scenario, resulting in state-of-the-art results on ASLLVD-Skeleton and ASLLVD-Skeleton-20 datasets with top-1 accuracy of 30.97 % and 95.45 %, respectively.

> [Data]() — [Paper](https://arxiv.org/abs/2301.03769) — [Contact us](mailto:maty@stanford.edu)
>
> *Pre-print. Under review.*

<br>

- The dataset is distributed via [Hugging Face]().
- To reproduce experiments using the SPOTER architecture, see [this GitHub repo](https://github.com/maty-bohacek/spoter).
- We provide a mapping of classes from our dataset to [WLASL](https://dxli94.github.io/WLASL/) and [ASLLVD](https://www.bu.edu/asllrp/av/dai-asllvd.html). Refer to the respective publications if you wish to obtain their data as well.
