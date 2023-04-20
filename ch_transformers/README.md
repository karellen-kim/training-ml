## Transformer
* 2018년 6월: GPT, 최초의 사전 학습된(pretrained) Transformer 모델. 다양한 NLP 작업에 대한 미세 조정에 사용되었고 그 당시 많은 태스크에서 최고 성능을 달성
* 2018년 10월: BERT, 또 다른 대규모 사전 학습된 모델. 이 모델은 특히 고수준의 문장 요약을 제공하도록 설계되었습니다(다음 장에서 더 자세히 설명합니다!)
* 2019년 2월: GPT-2, 윤리적인 문제로 인해 즉시 공개되지 않은, 기존 GPT보다 규모가 더 크고 성능이 향상된 GPT 버전
* 2019년 10월: DistillBERT, 속도가 60% 더 빠르고 메모리 소비는 40% 줄였지만 여전히 BERT 성능의 97%를 유지하는 증류된(distilled) BERT 버전
* 2019년 10월: BART 및 T5, 원래 Transformer 모델과 동일한 아키텍처를 사용하는 두 개의 대규모 사전 학습 모델(순수 Transformer 아키텍처를 사용한 최초의 사전 학습 모델)
* 2020년 5월: GPT-3, 미세 조정 없이도 다양한 작업을 훌륭하게 수행할 수 있는 GPT-2의 더 큰 버전으로 제로샷 학습(zero-shot learning)이라고 함

## Encoder/Decoder
* 인코더 전용 모델 : 문장 분류, 개체명 인식과 같이 입력에 대한 분석 및 이해가 필요한 태스크
  ALBERT, BERT, DistilBERT, ELECTRA, RoBERTa
* 디코더 전용 모델 : 텍스트 생성 등과 같은 생성 태스크
  CTRL, GPT, GPT-2, Transformer XL
* 인코더-디코더 모델 혹은 시퀀스-투-시퀀스 모델 : 번역이나 요약과 같이 입력이 수반되는 생성 태스크
  BART, mBART, Marian, T5

