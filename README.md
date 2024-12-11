# cover_letter_chatbot

**A Samsung Electronics Cover Letter Crawler and ChatGPT Fine-Tuned Model**

---

## 프로젝트 개요

이 프로젝트는 ChatGPT 모델을 파인튜닝하여 “Yesable” 서비스에 활용하기 위한 모델을 개발한 작업이다. 이를 위해 삼성전자의 자기소개서 데이터를 크롤링하여 학습 데이터를 수집하였다.

---

## 프로젝트 세부사항

### 1. **Cover Letter Crawler**
- 삼성전자의 합격 자기소개서 데이터를 크롤링하여 학습 데이터를 구축하였다.
- 수집된 데이터는 Fine-Tuning 모델 학습에 활용되었다.

---

### 2. **Yesable Chat Bot 모델**
새롭게 개발된 **Yesable Chat Bot 모델**은 두 가지 주요 시스템으로 구성된다:

#### (1) **Chat_Bot 시스템**
- 일상적인 대화를 수행하며 사용자와 상호작용한다.
- 질문을 이해하고 대화를 확장하거나 되묻는 방식으로 작동한다.

#### **예시**:
<img width="746" alt="image" src="https://github.com/user-attachments/assets/69f0be13-a65a-496c-b8f5-6ad00ddb4a44">


#### (2) **Cover_Letter 시스템**
- 합격 자기소개서를 학습한 모델이다.
- 사용자의 질문에 기반하여 새로운 자기소개서를 작성한다.

#### **예시**:
<img width="743" alt="image" src="https://github.com/user-attachments/assets/03c668ea-0652-40f5-a980-bb4183cc6a03">
_아직 논리적인 자소서 작성까진 못하는 듯 하다..(더 많은 학습 필요)_

### 3. 사용 기술
- 프로그래밍 언어: Python
- 라이브러리 및 프레임워크:
  - BeautifulSoup: 데이터 크롤링
	-	OpenAI API: ChatGPT 모델 파인튜닝
-	모델: GPT 기반 파인튜닝
