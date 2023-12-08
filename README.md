# AppleGameAI

https://www.gamesaien.com/game/fruit_box_a/
사과게임을 스스로 하는 인공지능을 만들어봐요

1. 사과게임 사이트에서 사과이미지를 캡쳐
2. 17 * 10으로 쪼개서 총 170개의 이미지를 각각 저장
3. 미리 1~9까지 사과이미지를 저장해두고 opencv의 matchTemplate함수로 가장 비슷한 숫자로 저장
4. 이차원배열을 만들고 브루트포스로 탐색하며 10이 되는 조합찾은 후 드래그
5. 찾은 조합은 0으로 바꿔서 다음 탐색에 반영

추후 할것들:
1. 강화학습 시켜보기
2. 조금 더 효울적인 알고리즘 찾기

  -> 미리 조합 쌍을 찾아두고 BFS탐색으로 최선의 방법을 찾기?
  
  -> 조합들 중 9, 8, 7과 같이 성가신 조합을 우선순위큐에 넣어서 정렬 후 하나씩 조지기?


