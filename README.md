# Embedded-System-Design with Open Source Software

## 2018년 봄학기 (Spring 2018)
## (오픈소스 기반 임베디드 시스템 설계 - 2018 1학기)

**소개**
> - 교수: 이정근 (jeonggun.lee (A) hallym.ac.kr, 033-248-2312)
> - 공동참여교수: 이덕영 (riverlike (a) hallym.ac.kr)
> - 조교: 민재홍 (woghd6811@hallym.ac.kr, BIT 연구실)

**무엇을 배우는가?**

> 본 수업에서는 학생들은 임베디드 시스템 설계에 대한 기초 이론을 배우고 간단한 임베디드 시스템 설계를 수행한다. 특히, 최근 임베디드 분야에서 빠른 프로토타입 제작에 많이 사용되고 있는 **아두이노**, **라즈베리파이**, 및 고성능 임베디드 시스템 **Jetson TK1** 보드를 이용하여 프로젝트를 진행하도록 한다. 아두이노는 최근에 큰 반향을 일으키고 있는 임베디드 오픈소스 플랫폼으로 다양한 자료와 함께 쉽게 원하는 시스템을 구축할 수 있어 인기가 많다. 라즈베리파이의 경우 보다 강력한 프로세싱 파워를 가지고 있으며, 리눅스 상에서 다양한 제어와 실습을 수행할 수 있어 효과적이다. 마지막으로 Nvidia의 Jetson Tk1 보드는 고성능 임베디드 보드로써 영상 처리와 같은 고속의 데이터 처리가 필요한 임베디드 응용에 효과적으로 사용될 수 있다. 따라서, 학생들은 필요한 요구 사항에 따라 선택적으로 구현 플랫폼을 선택하여 각자가 구현하고자 하는 임베디드 시스템을 구축할 수 있다.

**배우게 될 것~**
>  1. 임베디드 시스템 이론 (임베디드 시스템의 특징 및 장점, 임베디드 프로그래밍, 인터럽트, 디바이스 드라이버)습득
>  2. 다루기 쉬운 아두이노 부터 Jetson TK1 보드까지 실제 장치를 다룰수 있는 역량 습득
>
>      - **GPIO** 다루기 및 센서 활용, 고성능 임베디드 보드에서 **임베디드 병렬프로그래밍** 등
      
**요구사항**
> 과제 및 프로첵느는 반드시 **Github**를 통하여 제출:
> [초보자를 위한 Github 사용법](https://www.youtube.com/watch?v=JEY3X64gX4Q&t=0s)
> [![초보자를 위한 Github 사용법](http://img.youtube.com/vi/JEY3X64gX4Q/0.jpg)](https://www.youtube.com/watch?v=JEY3X64gX4Q&t=552s) 

**실습장비**
> - [Arduino Board](https://ko.wikipedia.org/wiki/%EC%95%84%EB%91%90%EC%9D%B4%EB%85%B8) (Control Oriented Computing)
> - [Raspberry Pi](https://ko.wikipedia.org/wiki/%EB%9D%BC%EC%A6%88%EB%B2%A0%EB%A6%AC_%ED%8C%8C%EC%9D%B4) Board
> - [Jetson TK1 Board](https://elinux.org/Jetson_TK1) (Data Processing Oriented Computing)

**이론 수업 스케줄 (Schedule)**
 1. 임베디드 시스템 설계 개요
    - 임베디드 시스템 개요
    - 아두이노 & 라즈베리파이 그리고 Jetson TK1 보드 소개
   
 2. [아두이노를 이용한 임베디드 설계 전략](https://github.com/jeonggunlee/Embedded-System-Design/blob/master/02_embedded_arduino.pdf)
    - 아두이노를 이용한 제어 / LED 제어 / SWITCH 사용 / 7 Segment
    - 가변 저항 읽기 / 조도 센서 읽기 / 모터 제어하기 / 적외선 / 블루투스 통신
  
 3. 아두이노를 이용한 IoT 노드 설계
 
 4. 임베디드 기초 이론 강의 1
    - 임베디드 시스템 핵심 이론
    
 5. 임베디드 기초 이론 강의 2
    - 임베디드 시스템 핵심 이론
    
 6. 임베디드 기초 이론 강의 3
    - 임베디드 시스템 핵심 이론
    
 7. Midterm Exam (중간고사)	
 
 8. 라즈베리 파이
    - GPIO 구동
    - sysfs의 직접 제어 및 Python을 이용한 제어
    - C 언어를 이용한 제어
    
 9. 라즈베리 파이
    - 디바이스 드라이버 1	 라즈베리 파이 실습
    
 10. 라즈베리 파이
    - 디바이스 드라이버 2
    - 병렬 프로그래밍: OpenMP 소개 1
    
 11. 라즈베리 파이
    - 병렬 프로그래밍: OpenMP 소개 2
    
 12. Jetson TK1 임베디드 GPIO: GPIO 제어를 통한 LED 깜빡이기 (PDF)
    - sysfs의 직접 제어 및 Python을 이용한 제어
    - C 언어를 이용한 제어
    - http://www.youtube.com/watch?v=SaIpz00lE84
    
 13. Parallel Programming on Jetson TK1: GPU Architecture & CUDA Programming
 
 14. Final Exam (기말 고사)	 프로젝트 진행
 
**유의사항**
> 실습 수업은 아두이노/Microcontroller/RaspberryPi 중심의 실습과 프로젝트 개발에 초점을 두고 진행.
> 충분한 개발 능력을 겸비한 학생은 Nvidia의 Jetson 보드를 활용한 프로젝트를 진행
>    - GPU에 기반한 머신러닝 코드 수행 가능
>
> 프로젝트는 2-3인 팀 프로젝트를 진행하며, 각 참여자는 자신의 역활에 대해서 분명히 규정하고 발표 시에 참여 부분에 대한 질문에 대답해야한다.

![alt text][uno]
![alt text][pi]
![alt text][jetson]

[uno]: https://github.com/jeonggunlee/Embedded-System-Design/blob/master/images/uno.jpg "Arduino Uno"
[pi]: https://github.com/jeonggunlee/Embedded-System-Design/blob/master/images/pi.png
[jetson]: https://github.com/jeonggunlee/Embedded-System-Design/blob/master/images/jetson.jpg
