# AIFFEL Campus Online 5th Code Peer Review Templete
- 코더 : 최한준
- 리뷰어 : 맹선재

# PRT(PeerReviewTemplate) 
각 항목을 스스로 확인하고 토의하여 작성한 코드에 적용합니다.

- [O] 코드가 정상적으로 동작하고 주어진 문제를 해결했나요?
  주어진 루브릭에 부합하게 동작 및 문제를 해결하였음
- [O] 주석을 보고 작성자의 코드가 이해되었나요?
  > 노드의 내용에 기반하였음으로 이해에 무리가 없었음
- [O] 코드가 에러를 유발할 가능성이 없나요?
  > 확인한 바로는 에러 발생 여지가 없다고 보임
- [O] 코드 작성자가 코드를 제대로 이해하고 작성했나요?
  > 결과물과 중간 직접 짜는 코드 부분들을 보아 코드에 대한 이해가 충분하다고 생각됨
- [O] 코드가 간결한가요?
  > 함수와 클래스를 활용하여 조립된 Transformer 모델 자체와 훈련 과정이 간결함

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
