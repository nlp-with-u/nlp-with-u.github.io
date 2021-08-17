---
layout: post
title: Course3. 오픈소스 NLP 도구 소개
subtitle: 한국어 NLP를 위한 오픈소스 도구들 소개
gh-repo: nlp-with-u/nlp-with-u.github.io
gh-badge: [star, fork, follow]
tags: [git, github]
comments: true
---

NLP 작업은 보통 텍스트 전처리, 모델 구현/훈련, 훈련된 모델을 이용한 추론의 단계로 나뉘어집니다. 그리고 또 각 단계는 세부적으로 많은 작업들을 필요로 합니다. 다행히도 이 작업들 중 많은 것들은 오픈소스 라이브러리로 공유되고 있어서 새로운 NLP 작업을 진행할 때 이 모든 세부작업들을 처음부터 구현할 필요가 없습니다. 이 페이지에서는 유용한 오픈소스 NLP 도구들을 공유함으로써 NLP를 시작하는 이들에게 도움을 주고자 합니다.

### 한국어용 오픈소스 NLP 도구
* [KoNLPy](https://github.com/konlpy/konlpy): 한국어 정보처리를 위한 파이썬 패키지. 
  한국어 NLP에서 형태소 단위로 분리하는 데이터 전처리(토크나이징)에 많이 사용 ([한국어문서](https://konlpy.org/ko/latest/))
* [KoGPT2](https://github.com/SKT-AI/KoGPT2): 부족한 한국어 성능 극복을 위해 40GB 이상의 텍스트로 학습된 한국어 디코더 언어모델
* [KoBERT](https://github.com/SKTBrain/KoBERT)
* [Soynlp](https://github.com/lovit/soynlp)
* [Kiwi](https://github.com/bab2min/Kiwi)

- 한국어 말뭉치
  - [국립국어원 모두의 말뭉치](https://corpus.korean.go.kr/#none): 문어체와 구어체를 포함한 다양한 한국어 말뭉치
  - [네이버 쇼핑 제품 후기](https://github.com/bab2min/corpus/tree/master/sentiment): 네이버 쇼핑에서 제품별 후기를 별점과 함께 수집한 말뭉치
  - [네이버 뉴스 기사 수집](https://github.com/affjljoo3581/canrevan): 네이버 뉴스에서 기사 말뭉치를 수집하도록 도와주는 라이브러리
  - [네이버 영화 감상평](https://github.com/e9t/nsmc/): 네이버 영화 감상평 댓글 말뭉치

### 다국어용 오픈소스 NLP 도구
* [BERT](https://github.com/google-research/bert)
* [spaCy](https://github.com/explosion/spaCy)
* [Gensim](https://github.com/RaRe-Technologies/gensim)
* [NLTK](https://github.com/nltk/nltk) : 말뭉치, 토큰 생성, 형태소 분석, 품사 태깅 기능을 제공하는 자연어 처리 및 문서 분석용 파이썬 패키지.
* [OpenNLP](https://github.com/apache/opennlp)
* [PORORO](https://github.com/kakaobrain/pororo)
* [GPT-2](https://openai.com/blog/gpt-2-1-5b-release/) : OpenAI의 단방향 언어모델. 문장 생성에 최적화
* [Transformers](https://github.com/huggingface/transformers): State-of-the-art NLP 도구 모음 라이브러리(RoBERT,GPT,T5 등 pre-trained모델 제공)

### NLP 도구 사용법
* [KoNLPy](https://konlpy.org/ko/latest/#user-guide): KoNLPy 사용 가이드
* [Transformers](https://huggingface.co/transformers/#): Transformers 사용 가이드