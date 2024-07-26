# Audio Entailment: Assessing Deductive Reasoning for Audio Understanding
This repository contains CLE and ACE audio entailment datasets from [Audio Entailment: Assessing Deductive Reasoning for Audio Understanding](https://arxiv.org/abs/2407.18062). The data is provided in a .csv format. 
![image](https://github.com/user-attachments/assets/e24991c6-4db1-49e8-8bf6-5248fbbc7780)

## News
[Jul 24] Data is under review with a tentative release date of October 2024

## Structure
The .csv are located under `data` folder

    .
    ├── ...
    ├── data              
    │   ├── CLE         # Clotho Entailment
    │   ├── ACE         # AudioCaps Entailment
    └── ...

The original captions and the corresponding audio files for AudioCaps and Clotho can be found here: [AudioCaps](https://github.com/cdjkim/audiocaps), [Clotho](https://zenodo.org/record/4783391)

## Supervised leaderboard
The metric used is F1 score
|                        Model                       |    CLE   | 
|----------------------------------------------------|----------|
| [MS CLAP 23](https://github.com/microsoft/CLAP)    |  0.8336  | 
| [Pengi-enc](https://github.com/microsoft/Pengi)    |  0.7642  | 
| [LAION CLAP](https://github.com/LAION-AI/CLAP)     |  0.7445  | 
| [MS CLAP 22](https://github.com/microsoft/CLAP)    |  0.7118  | 

## Zero-Shot leaderboard
The metric used is F1 score
|                        Model                       |    ACE   |    CLE   |    Avg   |
|----------------------------------------------------|----------|----------|----------|
| [LAION CLAP](https://github.com/LAION-AI/CLAP)     |  0.5693  |  0.5161  |  0.5427  |
| [Qwen-AC](https://github.com/QwenLM/Qwen-Audio)    |  0.4975  |  0.4918  |  0.4946  |
| [MS CLAP 23](https://github.com/microsoft/CLAP)    |  0.4656  |  0.5159  |  0.4908  |
| [GAMA](https://github.com/Sreyan88/GAMA)           |  0.4534  |  0.4933  |  0.4734  |
| [SALMONN](https://github.com/bytedance/SALMONN)    |  0.4515  |  0.4826  |  0.4671  |
| [MS CLAP 22](https://github.com/microsoft/CLAP)    |  0.4332  |  0.4656  |  0.4494  |
| [GAMA-IT](https://github.com/Sreyan88/GAMA)        |  0.3433  |  0.3828  |  0.3631  |
| [LTU-AS](https://github.com/YuanGongND/ltu)        |  0.3420  |  0.3334  |  0.3377  |
| [Qwen-A](https://github.com/QwenLM/Qwen-Audio)     |  0.3117  |  0.3219  |  0.3168  |
| [Pengi-enc](https://github.com/microsoft/Pengi)    |  0.2888  |  0.3039  |  0.2964  |
| [Pengi-noenc](https://github.com/microsoft/Pengi)  |  0.2216  |  0.2045  |  0.2131  |

## Citation
```
@article{audioentail,
  title={Audio Entailment: Assessing Deductive Reasoning for Audio Understanding},
  author={Soham Deshmukh and Shuo Han and Hazim Bukhari and Benjamin Elizalde and Hannes Gamper and Rita Singh and Bhiksha Raj},
  journal={arXiv preprint arXiv:2407.18062},
  year={2024}
}
```

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.


## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
