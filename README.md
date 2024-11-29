# Automatic_Piano_Evaluation_via_LLMs

### Idea
1. input, target 둘 다 올리고 10초(100개 인덱스) 단위로 청킹해서 평가 진행
  - 한번 진행(chatGPT-4o 기준)에 0.02 ~ 0.04$ 사용
2. 위 방법대로 하면서, score 파일을 함께 첨부해서 약간의 파인튜닝 느낌으로 정밀도 올리는 식으로 실험
3. 청크의 평균보다 각 청크의 점수를 활용해서 점수대별 가중치를 적용해서 평균내는게 좋을 것 같기도?

### Abstract
This study introduces a novel expert system designed to evaluate piano performances using advanced LLMs, such as ChatGPT-4o, providing detailed feedback on musical accuracy, similarity, consistency, and alignment with target music score. The system analyzes performance data chunked into 10-second intervals, focusing on key evaluation criteria, including note accuracy, dynamic similarity, dynamic change consistency, accent accuracy, articulation similarity, rhythm similarity, and pedaling accuracy. Leveraging advanced Large Language Models, the system ensures comprehensive and precise feedback for each chunk, culminating in an overall evaluation that highlights strengths, weaknesses, and actionable suggestions for improvement.
Proposed structured prompt methodology ensures the alignment of feedback with pedagogical objectives, enabling performers to target specific areas for refinement.
The experimental results demonstrate the system's potential as an effective tool for music educators and learners, providing objective, automated performance evaluation that supplements traditional instruction methods. By bridging computational precision with pedagogical value, this study contributes to the growing field of AI-assisted education, specifically in the domain of piano performance evaluation. Future work aims to expand the system’s application to broader musical genres and instruments, further enhancing its educational impact.

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
