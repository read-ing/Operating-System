### 프로세스
* 실행 중인 프로그램.
* 실행되면서 상태를 변경함. 
* 프로세스의 상태는 현재 활동에 의해 정의됨.
  * new
  * ready
  * running
  * wating
  * terminated
* 각 프로세스는 운영체제 내에서 자신의 프로세스 제어 블록(PCB, Process Control Blocck)에 의해 표현됨.
* 프로세스가 실행되지 않을 때는 ready queue에서 대기하게 됨.

### 스케줄링
* OS는 다양한 스케줄링 큐로부터 프로셋들을 선택해야 함.
* 장기 스케줄러(long term scheduler) : 어떤 프로세스를 ready queue에 넣을 것인지 결정
  * 이 스케줄링은 자원 할당 고려 사항, 특히 메인 메모리 관리에 의해 많은 영향 받음.
* 단기 스케줄러(short term scheduler) : CPU에게 어떤 프로세스를 할당할 것인지 결정

