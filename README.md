# SchoolHelperChatbot-Gemma2B-Finetuning
open LLM 모델 Gemma-2B-it 모델을 학교 정보 데이터셋으로 파인튜닝 시켜, 학교 정보를 알려주는 챗봇을 만드는 프로젝트.
 --- 
### 프로젝트 구성
Base LLM model:  <a href="https://huggingface.co/google/gemma-2b-it">google/gemma-2b-it</a>
Fine Tuning Datasets: <a href="https://huggingface.co/datasets/taeseo06/SchoolHelperChatbot-dataset">taeseo06/SchoolHelperChatbot-dataset</a> (자체제작)
Fine-tuned model: <a href="https://huggingface.co/taeseo06/SchoolHelperChatbot-Gemma2B-Finetuning">ttaeseo06/SchoolHelperChatbot-Gemma2B-Finetuning</a> (학교 안내 챗봇)

파인튜닝 방법론: PEFT-LoRA




---
### 발표

1) 응용프로그래밍 실습 -발표자료
[발표자료.pdf](https://github.com/Taeseo06/SchoolHelperChatbot-Gemma2B-Finetuning/blob/main/%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C/30407%E1%84%86%E1%85%AE%E1%86%AB%E1%84%90%E1%85%A2%E1%84%89%E1%85%A5-%E1%84%8B%E1%85%B3%E1%86%BC%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%91%E1%85%B3%E1%84%85%E1%85%A9%E1%84%80%E1%85%B3%E1%84%85%E1%85%A2%E1%84%86%E1%85%B5%E1%86%BC%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD.pdf)
![[Pasted image 20240615115449.png]]

2) 발표 시 사용했던 시연 사이트
	* 프롬프트 토큰화1: https://platform.openai.com/tokenizer
	* 프롬프트 토큰화2: https://tiktokenizer.vercel.app/?model=gpt-4
	* Word2Vec Embedding Projector: https://projector.tensorflow.org/
