##team-quiz-jihye

# 간단 보스몹 잡기 게임 요구사항 🙇‍♂️

## 필요한 패키지와 클래스 📁

1. main 패키지, game 패키지 생성
2. game 패키지 하단에 Soldier(용사) 클래스, Moster(몬스터) 클래스 생성

## 필요한 데이터와 메소드 😄

<game 패키지>

Soldier 클래스
1. soldierName(용사명) 데이터가 필요하다
2. weapon(무기) 데이터가 필요하다 
3. pet(펫) 데이터가 필요하다
4. hp(생명) 데이터가 필요하다
5. doSoldierOffensive메소드가 필요하다
 
Monster 클래스
1. monsterName(몬스터 이름)데이터가 필요하다.
2. offensivePower(공격력)데이터가 필요하다.
3. doMonsterOffensive 메소드가 필요하다.

<main 패키지>

Main 클래스
1. 메인 메소드 포함
2. 용사와 몬스터 객체 생성 후 게임 시작


## 요구사항 🌷
1. 용사의 이름을 입력받는다.
2. 용사는 무기를 선택한다. (초보자의 무기1, 초보자의 무기2 중 선택이며 15, 30의 공격력을 가진 무기가 랜덤으로 주어진다)
3. 용사는 펫을 선택한다. (1.고양이는 +5의 공격력을, 2.강아지는 +3의 공격력을 3.미선택은 +0의 공격력을 가진다.)
4. 용사의 초기 생명력은 200이다.
5. 몬스터는 몬스터1, 몬스터2, 보스몬스터가 있다.
6. 몬스터 1의 체력은 300, 공격력은 20이다.
7. 용사가 공격시, "(몬스터명)에게 (용사의 공격력과 펫의 공격력을 합친 값)데미지를 입혔습니다 ⚔️" 메세지를 출력한다.
8. 몬스터가 공격시, "(용사명)의 체력이 (남은 체력 값)이 남았습니다" 메세지를 출력한다.
9. 몬스터 1을 해치우면 용사의 체력은 +50, 공격력은 +10, 펫의 공격력은 +5가 된다.
10. 몬스터 2를 해치우면 "축하합니다!🎉  몬스터1을 해치웠습니다." 메시지를 출력한다.
11. 몬스터 1을 해치우면 용사의 체력은 +50, 공격력은 +10, 펫의 공격력은 +5가 된다. 
12. 변경된 공격력과 체력의 값을 출력한다.
13. 몬스터 2의 체력은 450, 공격력은 30이다.
14. 몬스터 2를 해치우면 용사의 체력은 +100, 공격력은 +20, 펫의 공격력은 + 10이 된다.
15. 몬스터 2를 해치우면 "축하합니다!🎉  몬스터2를 해치웠습니다." 메시지를 출력한다.
16. 보스몬스터의 체력은 700, 공격력은 50이다.
17. 보스몬스터를 해치우면 "축하합니다!🎉 보스 몬스터를 해치웠습니다. 평화가 찾아왔습니다 🌷" 메시지를 출력한다.
