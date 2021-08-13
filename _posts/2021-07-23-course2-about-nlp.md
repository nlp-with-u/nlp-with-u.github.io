---
layout: post
title: Course2. About NLP
subtitle: NLP에 대한 간략한 소개
gh-repo: nlp-with-u/nlp-with-u.github.io
gh-badge: [star, fork, follow]
tags: [git, github]
comments: true
---

NLP는 Natural Language Processing(자연어처리)의 약자로써 인간의 언어를 컴퓨터로 처리하고자 하는 모든 기법들을 아우릅니다. 이 페이지에서는 NLP 전반에 대해 잘 소개된 자료들을 공유하여 NLP를 공부하는 이들에게 간단한 가이드라인을 제공하고자 합니다.

{: .box-warning}
**Warning:** 여기에 있는 자료들이 최선/최신이 아닐 수 있습니다. 더 좋은 자료를 발견하면 공유 부탁드려요.

### 자연어처리 전반
* [딥 러닝을 이용한 자연어처리 입문](https://wikidocs.net/book/2155) : NLP 전반에 대해 잘 소개된 Wikidocs 페이지 (이론 & 코드)
* [nlp-tutorial 코드](https://github.com/graykode/nlp-tutorial) : word2vec부터 transformer까지 jupyter notebook으로 직접 실습해 볼 수 있는 repository

### 텍스트 전처리
* 텍스트 전처리(Text Preprocessing): 자연어처리에 있어 제일 기초적인 단계. 텍스트를 컴퓨터가 이해하기 좋은 형태로 잘 가공하는 과정 전반을 가리킨다. 언어에 따라 사용하는 기법이 크게 갈린다.
* [한국어 전처리를 위한 기법들](https://ebbnflow.tistory.com/246) : 간단한 코드와 설명이 곁들여진 블로그 포스트 (기초, 코드)

### 언어 모델
* 언어 모델(Language Model): 주어진 단어의 배열(=문장 or 텍스트)이 발생할 확률을 추정해주는 모델. 이를 이용해 여러 문장 중 어떤 문장이 사람이 보기에 더 그럴싸한 것인지 컴퓨터가 판단할 수 있다.
* 언어 생성 모델(Language Generation Model): 언어 모델은 주어진 단어 배열의 확률을 계산할 수 있으므로, 특정 텍스트 다음에 등장할 단어를 계산하는 것 역시 가능하다. 이를 통해 다음에 등장할 가능성이 높은 단어를 차례로 생성해 나가면 긴 문장을 생성하는 것도 가능한데, 이렇게 생성에 특화된 언어 모델을 언어 생성 모델이라고 한다. 최근 GPT 모델의 등장으로 많은 관심을 받고 있다.
* [언어 모델](https://ratsgo.github.io/from%20frequency%20to%20semantics/2017/09/16/LM/) : 이론적인 설명이 소개된 블로그 포스트 (기초, 이론)
* [위클리 NLP Week 29](https://jiho-ml.com/weekly-nlp-29/), [위클리 NLP Week 30](https://jiho-ml.com/weekly-nlp-30/) : 거대 언어 생성 모델 GPT-3에 대해 잘 설명된 글 (이론)

### 텍스트 분류
* 텍스트 분류(Text Classification): 주어진 텍스트가 정해진 카테고리 중 어디에 속하는지를 판단하는 작업. 고전적인 기계학습 분류기뿐만 아니라 RNN, CNN 등의 신경망을 사용한 분류기 등이 다양하게 사용된다. 특히 최근에는 BERT를 이용한 텍스트 분류가 많은 관심을 받고 있다.
* [RNN을 이용한 텍스트 분류](https://wikidocs.net/22891) : 코드 위주의 Wikidocs 페이지 (기초, 코드)
* [CNN을 이용한 한국어 문장 분류](http://docs.likejazz.com/cnn-text-classification-tf/) : 논문 소개와 코드 해설이 담긴 블로그 포스트 (심화, 이론 & 코드)

### 텍스트 군집화
* 텍스트 군집화(Text Clustering): 주어진 여러 개의 텍스트 중 비슷한 텍스트를 묶어주는 작업. 분류와는 달리 사람이 카테고리를 직접 지정해주지 않고, 입력한 데이터를 바탕으로 스스로 유사한 텍스트들을 묶어내는게 특징이다.
* (관련 자료들을 보충해주세요)

### 토큰 분류, 시퀀스 레이블링(태깅)
* 토큰 분류(Token Classification, Sequence Labeling, Sequence Tagging): 주어진 텍스트 내의 토큰(단어 혹은 형태소 등)들이 정해진 카테고리 중 어디에 속하는지 판단하는 작업. 전체 텍스트에 하나의 카테고리가 부여되는 텍스트 분류와는 달리 토큰 분류는 각 토큰별로 카테고리가 다르게 부여될 수 있다. 레이벨링 혹은 태깅이라고도 부른다. 이 부류에 속하는 작업 중 대표적인 것으로 품사 태깅(POS Tagging), 개체명 인식(Named Entity Recognition)과 형태소 분석(Morphological Analysis)이 있다.
* [시퀀스 레이블링](https://wikidocs.net/66108) : 시퀀스 레이블링 전반에 대한 Wikidocs 페이지 (이론 & 코드)
* [개체명 인식](https://wikidocs.net/30682) : 개체명 인식에 대한 간략한 소개와 코드 (기초, 이론 & 코드)
* [NER 개론과 NER 데이터셋 모음](https://stellarway.tistory.com/29) :
* [KoNLPy 형태소 분석 설명글](https://konlpy-ko.readthedocs.io/ko/v0.4.3/morph/) : 다양한 한국어 형태소 분석기에 대한 소개 (기초, 이론)

### 텍스트 요약
* 텍스트 요약(Text Summarization): 
* [BERT를 활용한 한국어 문서 추출요약 봇](https://velog.io/@raqoon886/KorBertSum-SummaryBot): 코드
* [자동 요약 기법의 연구 동향 정리](https://bab2min.tistory.com/625): 텍스트 요약 기법의 역사에 대해 간략하게 정리한 블로그 포스팅 (기초, 이론)
* [어텐션을 이용한 텍스트 요약](https://wikidocs.net/72820) : 생성 요약을 구현 코드 설명 (심화, 코드)

### 기계 번역
* 기계 번역(Machine Translation): 한 언어로 작성된 텍스트를 다른 언어로 번역하는 작업. 언어가 같더라도 문체를 바꾼다던가, 표준어를 방언으로 바꾸는 작업 역시 기계 번역의 하위 작업이라고 볼 수 있다. 최근 Transformers의 등장으로 성능이 크게 개선되며 많은 관심을 받고 있다.
* [시퀀스투시퀀스](https://wikidocs.net/65154)
* [신경망 번역 모델의 진화 과정](https://tech.kakaoenterprise.com/45) : 신경망 번역 모델의 연구 동향 소개 (기초, 이론)
* [위클리 NLP Week 22](https://jiho-ml.com/weekly-nlp-22/) : seq2seq 모델에 대한 간략한 이론 소개 (기초, 이론)
* [트랜스포머(Transformer)](https://ratsgo.github.io/nlpbook/docs/language_model/transformers/): 최근 기계 번역에 널리 쓰이는 Transformers의 구조를 설명한 블로그 포스트 (심화, 이론)
