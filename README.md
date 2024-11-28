# Automatic_Piano_Evaluation_via_LLMs

### Idea
1. input, target 둘 다 올리고 10초(100개 인덱스) 단위로 청킹해서 평가 진행
  - 한번 진행(chatGPT-4o 기준)에 0.02 ~ 0.04$ 사용
2. 위 방법대로 하면서, score 파일을 함께 첨부해서 약간의 파인튜닝 느낌으로 정밀도 올리는 식으로 실험

### Abstract

### Result

### Usage
```
Automatic_Piano_Evaluation_via_LLM/
├── Automatic Piano Evaluation with ChatGPT.ipynb
├── Automatic Piano Evaluation using BERT.ipynb            
├── midi_data/     # Folder containing input and target files, such as midi and csv.
└── README.md              
```

#### Clone this repository and Install dependencies
1. Clone the repository: ```git clone https://github.com/PSLeon24/Automatic_Piano_Evaluation_via_LLM.git``` 
2. Install dependencies: ```pip install -r requirements.txt```

#### Dataset Preparation


### Citation

```
@inproceedings{Citation Key,
  title={Automatic_Piano_Evaluation_via_LLMs},
  author={So-Hyun Park, Yeong-Min Ko},
  booktitle={to be added.},
  year={2025}
}
```
