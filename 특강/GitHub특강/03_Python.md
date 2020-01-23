# Python

## 모듈

- 모듈이란 것은 기존의 언어에서 따지자면 완전 다른 (이름.h + 이름.cpp)를 새롭게 삽입하는 느낌
- python이라는 통합된 IDE내부에 모듈을 설치해두면 import를 통해서 쉽게 이용할 수 있다

### 몇몇 함수들

```python
'이것은 {}이고, 저것은{}이다 '.format(인자1, 인자2)
```

- 위와 같이 쓰면 {}안에 인자가 들어가서 나오게된다

```python
변수 = f'이것은 {인자1}이고, 저것은{인자2}이다.'
```

- 좀 더 간단한 방식은 위와 같이 작성하면 어떤 인자가 어떤 위치에 들어가는지 쉽게 알 수 있다

## 예약어

- 예약어는 모두 30개가 있다
- 예약어는 상수 또는 변수 나 다른 식별자의 이름으로 사용 할 수 없다.
- 예약어는 모두 **소문자**이다.
- 예약어 표

| Keyword  | Keyword | Keyword |
| :------- | :------ | :------ |
| and      | exec    | not     |
| assert   | finally | or      |
| break    | for     | pass    |
| class    | from    | print   |
| continue | global  | raise   |
| def      | if      | return  |
| del      | import  | try     |
| elif     | in      | while   |
| else     | is      | with    |
| except   | lambda  | yield   |

- 위 예약어 왜에도 string 등 사용할 수 없는 단어들이 존재한다.
- 모든 예약어를 외울 수는 없으니 에러가 나면 확인 후 고치도록한다

## 크롤링

### selenium 

- 사용을 위해선 https://sites.google.com/a/chromium.org/chromedriver/ 에서 현재 사용하는 크롬에 맞는 드라이버 다운로드
- 경로는 어디에둬도 상관이 없지만 코드 상에서 경로 입력의 편의성을 위해 코드와 가까운 경로에 두는 것이 좋다

```bash
$> pip install selenium
```

- bash에 위와 같이 입력해서 selenium 설치
- 그 이후에 코드를 작성하면 된다 https://github.com/baw6114/PythonStudy 의 googlesearch.py 내용 참조

