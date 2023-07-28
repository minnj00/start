# Linux command 

> 리눅스 명령어들을 정리해봅시다.

- `pwd`(print working directory)
    - 현재 작업중인 경로를 출력

- `ls` (list)
    - 현재 폴더에 있는 파일, 폴더를 출력

    - `-a`(optional) : 숨김 처리된 파일, 폴더까지 출력

- `cd` (change directory)
    - 폴더 이동 (자동완성기능 활용하기 tab)

- `mkdir` (make directory)
    - 폴더 생성하기

- `touch`
    - 파일 생성하기

- `rm`(remove)
    - 파일 및 폴더 삭제
    - `-r` (optional) 폴더삭제를 위해 입력해야하는 옵션
    (폴더에서 앞에 . 이 붙으면 숨김처리가 된다.)

- `cd ..`
    - 상위 폴더로 이동

- `cd <폴더이름>`
    - <폴더이름>으로 이동
    
- ex) 
 터미널에서 <프로그래머스 폴더에서 swea 폴더 안의 있는 6220의 위치로 이동시키고 싶을 때>
 일단 상위 폴더로 이동 cd ..
 그 후 cd swea/6220 
 

- 터미널 algorithm 폴더에서 파로 두수의 곱 안의 파이선 실행하기
python programmers/두수의곱/sol.py
하지만 swea와 같이 input 과 같이 파이썬을 실행하는 경우는 이동하기 


- `tab` `tab` 
    - 똑같은 글자로 시작하는 폴더들이 다 나열됨

