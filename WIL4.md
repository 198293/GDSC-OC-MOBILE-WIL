# Week4

[https://www.notion.so/Week4-4e92c8b320bc452ab127aa0ce4ca2709?pvs=4](https://www.notion.so/Week4-4e92c8b320bc452ab127aa0ce4ca2709)

[https://www.figma.com/proto/0wEP8Q4cD1qY4qYPQNnby2/4%EC%A3%BC%EC%B0%A8-%EC%8A%A4%ED%84%B0%EB%94%94?node-id=1-105&scaling=contain&page-id=0%3A1](https://www.figma.com/proto/0wEP8Q4cD1qY4qYPQNnby2/4%EC%A3%BC%EC%B0%A8-%EC%8A%A4%ED%84%B0%EB%94%94?node-id=1-105&scaling=contain&page-id=0%3A1)

## 쉬운 플러터 3강 + **Flutter 로 웹툰 앱 만들기**

### Scaffold

→ Scaffold 위젯을 이용하면 레이아웃을 더 쉽게 만들 수 있다.

→ screen 구성에 적절한 구조를 제공한다.

### Margin

→ 마진 : 바깥여백

→ 바깥 여백을 주고 싶다면 margin이라는 파라미터를 사용한다

- **`margin: EdgeInsets.all(20)`**

→ 전체적으로 바깥 여백 20

- **`margin: EdgeInsets.fromLTRB(left, top, right, bottem)`**

→ 박스의 원하는 부분에 일부 여백을 준다

### Decoration

→ decoration 이외의 다른 데코레이션을 주고 싶다면 사용한다.

- **박스에 테두리 주는 법**

decorarion: BoxDecoration(

border: border.all(color: Colors.black))

### **Padding**

→ 패딩 :  안쪽 여백

→ 안쪽 여백을 주고 싶다면 padding이라는 파라미터를 사용한다.

### **추가 정보**

- **?의 의미**
    
    → 있을 수도 없을 수도 있다는 뜻
    
- `appbar, body, bottomNavigationBar` **파라미터를 이  용하면 상, 중, 하로 나눠줄 수 있다.**
- `mainAxisAlignment`
    
    → 아이콘 정렬 가능
    
- Container는 무겁기 때문에 `SizedBox`로 대체할 수 있다
