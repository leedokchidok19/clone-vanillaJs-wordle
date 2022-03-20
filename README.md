# 프로젝트
### 프로젝트명 : clone-vanillaJs-wordle
> javascript를 사용해서 wordle 게임 클론 코딩

# 게임 소개
> 5글자 단어를 입력해서 정답을 맞히는 게임

# 게임 규칙
1. 입력창에 단어를 입력
2. 정답 여부에 따른 입력창 색상 변경
    - 초록색 : 정답에 있는 글자이면서 위치까지 맞춘 글자
    - 노란색 : 정답에 있는 글자이지만 위치가 다른 글자
    - 회색 : 정답에 없는 글자

# 문제점
1. 변수에 저장된 답안만 사용
    - 배열로 저장된 여러 정답을 랜덤 호출로 수정
2. 문제/유저 답안 실제 단어인지 검사 안 함
3. 영어 이외 문자, 숫자 입력 가능
4. 입력 칸에 두 글자 이상 입력 가능(수정)
5. 두 번째 입력부터 색상 변경 안 된다(수정)

# 기능 개선
1. 답안 생성 기능
    - 날짜별 다른 답
    - 사전 등을 이용한 단어 사용
    - 단어 수 제한 5글자 혹은 글자 수에 맞는 입력 칸 숫자
2. 실제 단어 검사 기능
3. 단어 설명 기능
    - 단어 뜻 설명
    - 동일한 단어로 다른 나라 단어로 표기
4. 입력한 글자 키보드 자판 혹은 다른 방법으로 표시

# 참고
[JavaScript로 요즘 유행하는 Wordle 게임 만들기 (개쉬움)](https://www.youtube.com/watch?v=npvrAzxgTOQ)