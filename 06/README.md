# AIFFEL Campus Online 5th Code Peer Review Templete
- 코더 : 박혜원
- 리뷰어 : 최철웅


# PRT(PeerReviewTemplate) 
각 항목을 스스로 확인하고 토의하여 작성한 코드에 적용합니다.

- [X] 코드가 정상적으로 동작하고 주어진 문제를 해결했나요?
  - Word2Vec을 통해 단어 표현을 학습하고 단어 유사도가 잘 반영되었는지 확인함
  - 편향성을 수치화 및 시각화를 수행하고 분석함
- [X] 주석을 보고 작성자의 코드가 이해되었나요?
  - 주석이 각 코드 블럭에서 수행하는 내용을 잘 설명하였다
- [X] 코드가 에러를 유발할 가능성이 없나요?
  - 코드 실행 결과 에러가 발생하지 않음
  - 코드 내용에도 예외가 발생할 부분이 없음
- [X] 코드 작성자가 코드를 제대로 이해하고 작성했나요?
  - 마크다운을 통해 코드가 수행하는 작업에 대한 내용을 설명하고 있음
- [X] 코드가 간결한가요?
  - 불필요한 반복이나 실행되지 않는 코드가 존재하지 않음

# 예시
1. 코드의 작동 방식을 주석으로 기록합니다.
2. 코드의 작동 방식에 대한 개선 방법을 주석으로 기록합니다.
3. 참고한 링크 및 ChatGPT 프롬프트 명령어가 있다면 주석으로 남겨주세요.
```python
# 사칙 연산 계산기
class calculator:
    # 예) init의 역할과 각 매서드의 의미를 서술
    def __init__(self, first, second):
        self.first = first
        self.second = second
    
    # 예) 덧셈과 연산 작동 방식에 대한 서술
    def add(self):
        result = self.first + self.second
        return result

a = float(input('첫번째 값을 입력하세요.')) 
b = float(input('두번째 값을 입력하세요.')) 
c = calculator(a, b)
print('덧셈', c.add()) 
```

# 참고 링크 및 코드 개선
```python
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
