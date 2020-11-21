Project 1 : Limation

Keypad Puzzle Script

Explanation

1. 숫자 입력 버튼을 통해 디스플레이에 숫자를 입력하고 M버튼을 통해 정답 확인
2. If문을 사용하여 미리 정해놓은 답과 입력한 답의 일치 여부를 확인
3. 정답 입력이 처음일 경우 bool값을 true로 설정하여 다음 이벤트 발생 준비
4. Invoke 함수를 사용하여 다음 스토리 자동 진행(2번째)
5. 퍼즐이 활성화 되어있을 때 TimeScale = 0되어 플레이어의 이동, 카메라 각도 이동 등이 불가능

Game Scene
![키패드 퍼즐](https://user-images.githubusercontent.com/74092254/99870512-fcf8d280-2c16-11eb-8ac2-a19ec3d70df8.png)
