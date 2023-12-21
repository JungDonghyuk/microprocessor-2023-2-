# microprocessor-2023-2
마이크로프로세서응용시스템2023_2이태현장대호정동혁

# Maze game Generator
2023학년도 2학기 마이크로프로세서응용시스템 6조의 프로젝트입니다.

# Overall Logic
-시작점에 있는 공을 도착점에 옮기는 미로입니다.

-미로는 유니버셜 조인트 구조를 바탕으로 하여 판 전체를 조작하는 방식으로 공을 이동 시킵니다.

-미로의 16개 벽은 N초마다 한 번 씩 랜덤하게 오르내립니다.

-공이 시작점에 있는지, 시작점을 떠나 미로를 탐험하고 있는지, 도착점에 도달했는지는 조도센서를 바탕으로 파악합니다.

-공이 시작점을 떠났다고 판단하는 순간 7세그먼트로 카운팅을 시작하며 도착지점에 도착하는 순간 EEPROM에 기록을 저장합니다.

-새로운 기록이 찍히면, LCD에 그 기록을 표출하고, 예전 기록보다 느린 기록이면 Fail을 출력합니다.

# 완전한 완성을 하지는 못하였음. 

# 하드웨어의 문제,, 
-브레드보드을 치면 작동이 되고, 브레드보드을 치면 작동이 되지 않는 등, 브레드보드의 문제등이 있었고,
선들의 연결이 끊어지거나 절연이 제대로 되지 않는 문제들이 발생했습니다.

-sg90-hv 모터의 독특한 제어 특성 때문에 완벽한 왕복운동을 진행할 수 없다는 것이 문제였습니다.

-조도센서 문제를 해결하지 못함
