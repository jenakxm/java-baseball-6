# 1주차 미션 - 숫자 야구

## 기능 요구사항 체크
- &#9745; 컴퓨터의 숫자 맞추기
	- 1에서 9까지 서로 다른 임의의 수 3개
    - 같은 수가 같은 자리에 있으면 스트라이크
    - 다른 자리에 있으면 볼
    - 같은 수가 전혀 없으면 낫싱
- &#9745; 맞추는 과정 반복
- &#9745;  게임 종료 후 다시 시작하거나 완전히 종료
- &#9745; 잘못된 값을 입력할 경우 `IllegalArgumentException`을 발생시킨 후 애플리케이션은 종료
    - 숫자 맞출 때 입력 오류 ➡️ 'qwe' , '1234'
