[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MiVO5zfB)
# 🐍 [2026-01] 나만의 파이썬 소프트웨어 개발 프로젝트

## 1. 시나리오 제목
* 봅슬레이 러너
<br>


## 2. 시나리오 (5~10줄)
* 이 프로그램은 '템플런'이라는 게임을 모티브로 만든 봅슬레이 게임입니다.
* 이 게임에는 여러 가지 능력을 가진 캐릭터를 선택할 수 있습니다. 인게임에서 얻은 코인을 이용하여 캐릭터의 능력치를 올릴 수 있습니다. 능력으로는 캐릭터마다 갖고 있는 썰매의 유틸성, 컨트를이 얼마나 부드러운지 혹은 자유자재로 가능 정도, 속도가 있습니다. 캐릭터를 선택한 후에는 게임을 진행할 수 있는 버튼이 있는데 그 버튼을 누르게 되면 봅슬레이를 타게 됩니다. 목표는 뒤에 쫓아오는 괴물에 대해서 얼마나 도망갈 수 있는지, 무작위로 나오는 장애물을 얼마나 피하면서 얼마나 멀리 봅슬레이에 탑승해 있을 수 있는지 경쟁하게 되는 것입니다. 또한 중간중간에 나오는 코인을 먹으며 캐릭터 구입 혹은 업그레이드를 할 수 있습니다. 괴물에 잡히는 조건은 일정 시간 안에 두 번 부딪히는 것입니다. 즉, 한 번 부딪히고 일정시간이 지나고 또 부딪힌다고 하여도 괴물에게 잡히지는 않습니다. 장애물을 피하는 방법은 점프, 슬라이드, 좌우 이동이 있습니다. 앞으로는 눈에 보이는 장애물이 있고, 좌우에서는 무작위로 장애물이 나올 것입니다. 게임이 끝나면 주행한 총거리와 얻은 코인이 나오고, 홈 화면으로 돌아가게 됩니다.

<br>


## 3. 예상 기능 및 메뉴 (최소 5개)
(예시)
1. 장애물이 무작위로 나오는 것 피하기
2. 캐릭터 종합 능력(ex.컨트롤, 속도, 유틸성)
3. 조종 등급 판정
4. 조종 키(점프, 슬라이드, 좌우 이동)
5. 기록 집계, 총 코인 개수
0. 게임 종료

<br>

# 🚀 [버전별 개발 일지 & AI 협업 기록]

## 🟦 [1차 과제: V1.0] 시나리오 기획
    
### **🤖 AI 파트너십 과정**
(예시)
 1. **내용 1 : 파이썬으로 가능한 것의 범위를 물어봄
    * **프롬프트 요약:** ""파이썬으로 3d 쿠키런을 만들 수 있어?"
    * **적용 내용:** 파이썬의 ursina 라이브러리를 검색해보라고 함. 더 검색해봤을때 한계를 느낌
      
 2. **내용 2 : 점수**
    * **프롬프트 요약:** "1차 과제 필수 요건(변수 5개, 자료형 3개 이상)을 충족하기 위한 캐릭터 초기 스탯 데이터 구조 모델링 논의"
    * **적용 내용:** 게임이 끝났을 때는 점수는 문자형으로, 코인은 정수형으로 바꾸어야 합니다.
    
### **📁 증빙 자료:**
![KakaoTalk_20260407_093031800_27](https://github.com/user-attachments/assets/d2b972a7-e324-46ee-98b2-184e752a75ec)
![KakaoTalk_20260407_093031800_26](https://github.com/user-attachments/assets/78a62bb4-ae00-43e0-9609-b5e0e56675a9)
![KakaoTalk_20260407_093031800_25](https://github.com/user-attachments/assets/859e7ab0-55bf-47d6-93f6-dc6526015b37)
![KakaoTalk_20260407_093031800_24](https://github.com/user-attachments/assets/5c8a9ca0-7587-4e56-8023-faafde1d45c5)
![KakaoTalk_20260407_093031800_23](https://github.com/user-attachments/assets/08199ed3-d3d2-4792-9dfb-2ca0e2b7653f)
![KakaoTalk_20260407_093031800_22](https://github.com/user-attachments/assets/8b087646-df1a-4fbb-a73e-56642709eb82)
![KakaoTalk_20260407_093031800_21](https://github.com/user-attachments/assets/aa259844-ec12-48cb-b232-128bb2e74b81)
![KakaoTalk_20260407_093031800_20](https://github.com/user-attachments/assets/f1f32137-8789-4e84-b19c-36374426c2f7)
![KakaoTalk_20260407_093031800_20](https://github.com/user-attachments/assets/603a46ce-c68e-4004-9b5a-94f61a5f8814)
![KakaoTalk_20260407_093031800_18](https://github.com/user-attachments/assets/3fcc5189-2666-4250-942f-4c39481fe451)
![KakaoTalk_20260407_093031800_17](https://github.com/user-attachments/assets/acb6441a-1153-4783-b2d9-eca728c4cae8)
![KakaoTalk_20260407_093031800_16](https://github.com/user-attachments/assets/bb62185d-bfa1-4b54-b2d9-19d0408febb8)
![KakaoTalk_20260407_093031800_15](https://github.com/user-attachments/assets/41384411-d7a1-4844-8ea3-96fa783fa4f4)
![KakaoTalk_20260407_093031800_14](https://github.com/user-attachments/assets/6ea44650-6a21-432b-8e44-39946285ed43)
![KakaoTalk_20260407_093031800_13](https://github.com/user-attachments/assets/aa449d6f-a4ee-4e7e-aa70-d742733c98b4)
![KakaoTalk_20260407_093031800_12](https://github.com/user-attachments/assets/8a961410-e74a-4e98-87ec-a47747c6437b)
![KakaoTalk_20260407_093031800_11](https://github.com/user-attachments/assets/abe857d0-57ba-4c42-a1bb-e201b061436d)
![KakaoTalk_20260407_093031800_10](https://github.com/user-attachments/assets/56436546-0ae2-4d71-9813-de69fd773e64)
![KakaoTalk_20260407_093031800_09](https://github.com/user-attachments/assets/f85be813-f6ca-43cb-93fb-d4999c7cfde0)
![KakaoTalk_20260407_093031800_08](https://github.com/user-attachments/assets/3d0f8a0e-1a67-4332-a2c6-38712804655d)
![KakaoTalk_20260407_093031800_07](https://github.com/user-attachments/assets/c89e68cb-9da5-4775-8b8e-d39de5d663c0)
![KakaoTalk_20260407_093031800_06](https://github.com/user-attachments/assets/fc706cee-caa9-4d4c-9261-63d3c1fa5789)
![KakaoTalk_20260407_093031800_05](https://github.com/user-attachments/assets/1a9f81ee-3e71-45c6-96d9-2e3f4fd17003)
![KakaoTalk_20260407_093031800_04](https://github.com/user-attachments/assets/08429933-614d-4e5e-903d-f76c238a9bd5)
![KakaoTalk_20260407_093031800_03](https://github.com/user-attachments/assets/eda8e1a6-d36a-4613-8819-2d86f989635a)
![KakaoTalk_20260407_093031800_02](https://github.com/user-attachments/assets/6e9eac18-7fde-460d-b2c4-794b1a855f7d)
![KakaoTalk_20260407_093031800_01](https://github.com/user-attachments/assets/a9c0ca1d-af30-43ac-966c-9bf4ba873424)
![KakaoTalk_20260407_093031800](https://github.com/user-attachments/assets/a0c6d131-a805-44cb-82a5-98457a5980e1)












<br>

## 🟩 [2차 과제: V1.0] 입출력 + 리스트 + 조건문 - 향후 작성 예정
### **✨2차 과제 내용:**
(예시)
  * 캐릭터와 장애물을 효율적으로 관리하기 위해 클래쓰를 구성하시 위해서 player 클래스와 Obstacle 클래스를 별도로 생성하고, 공통 속성은 상속을 통해 관리하며 코드의 재사용성을 높일 것
  * 파이선 random 모듈을 사용해서 장애물을 겹치지 않게 무작위로 나오기 위해서 리스트에 장애물 좌표를 저장하고 time.sleep 또는 프레임 단위로 random.choice를 호출하여 일정한 간격으로 장애물을 나타나도록 함
  * 캐릭터 좌표와 장애물 좌표가 만났을 때 게임 오버를 판정하는 수식을 정하기 위해 각 오브젝트의 히트박스 범위를 설정하고, 두 좌표의 특정 임계값 이하일 때 충돌로 판정하는 조건문을 적용할 것임
  * 실시간으로 올라가는 정수형 저무를 화면에 문장열로 예쁘게 표시하려면 score 변수를 매 프레임 업데이트하고, 출력시에는 f:score{score:05d}" 형식을 사용하여 5자리 숫자로 고정해 시각적 안정성을 높일 것.
    
### **🤖 AI 파트너십 과정**
(예시) 
1. **내용 1: 3D 환경에서의 충돌 판정 로직 최적화**
    * **프롬프트 요약:** "파이썬 Ursina 엔진에서 봅슬레이 캐릭터아 무작위로 생성되는 장애물 간의 거리 기반 충돌 감지를 어떻게 구현해야 가장 정확할까?"
    * **적용 내용:** 캐릭터와 장애물 사이의 벡터 거리를 계산하는 수식을 제안받아 적용하여 특히 장애물의 중심 좌표뿐만 아니라 히트박스 범위를 설정하여, 봅슬레이가 장애물 옆면에 스치기만 해도 충돌로 판정되는 세미한 로직을 완성함

2. **내용 2: 리스트를 활용한 무한 맵 생성 알고리즘**
    * **프롬프트 요약:** "템플런처럼 맵이 끝없이 이어지게 만들고 싶은데, 리스트에 도로 오브젝트를 담아서 재사용하는 효율적인 구조를 짜줘
    * **적용 내용:** 화면 뒤로 사라진 도로 오브젝트를 리스트에서 빼내어 다시 맨 앞으로 옮기는 '오브젝트 풀링' 개념을 제안받음. 이를 통해 메모리 낭비 없이 맵이 무한히 연결되는 시스템을 구축함
    
### **🛠️ Troubleshooting & 기술 회고:**
(예시) 
1. **문제 1: 장애물 위치가 겹쳐서 나오는 현상
    * **원인:** `random 함수로 좌표를 생성할 때, 이전 장애물의 위치값을 고려하지 않아 두 장애물이 한 곳에 겹쳐 생성됨
    * **해결:** `생성된 좌표를 리스트에 임시 저장하고, 다음 생성 시 최소 거리 간격을 검사하는 조건문을 추가하여 플레이어가 불가능한 상황을 방지하
2. **문제 2: 장애물 충돌 시 게임이 즉시 멈추지 않는 현상
    * **원인:** `충돌 판정 후 break나 상태 변수(Booleam) 처리가 누락되어 캐릭터가 장애물을 뚫고 계속 지나가는 현상이 발생됨
    * **해결:** is_alive = False 변수를 도입하고, 게임 루피 상단에서 이 상태를 체크하여 충돌 즉시 결과 창으로 전환되도록 로직을 수정함
3. **문제 3:** 키보드 입력 지연으로 인한 조작감 저하
   **원인:** input() 함수를 사용해 입력을 받으려다 보니 프로그램이 입력 대기 상태에 빠져 게임 프레임이 멈추는 문제 발생
   **해결:** 실시간 키 입력을 감지하는 라이브러리의 이벤트 처리 방식을 학습하여 딜레이 없는 실시간 조작을 구현함
     
### **📁 증빙 자료:**
<img width="1812" height="2176" alt="KakaoTalk_20260427_230420341_01" src="https://github.com/user-attachments/assets/38d2780f-e57e-424e-8658-fb10585d1fc3" />
<img width="1812" height="2176" alt="KakaoTalk_20260427_230420341_02" src="https://github.com/user-attachments/assets/afdf5887-6bbe-46aa-84b6-fd16f811c751" />
<img width="1812" height="2176" alt="KakaoTalk_20260427_230420341" src="https://github.com/user-attachments/assets/9a5241af-3027-414f-9a90-5307918a8aac" />
<img width="1812" height="2176" alt="KakaoTalk_20260427_230420341_03" src="https://github.com/user-attachments/assets/6448b113-517b-41e1-95d5-9b5df29737e0" />



<br>

## 🟨 [3차 과제: V3.0] 무한 루프와 메뉴 시스템 (반복문) - 향후 작성 예정
### **✨3차 과제 업데이트 내용:**
  * 내용.
    
### **🤖 AI 파트너십 과정**
 1. **내용 1**
    * **프롬프트 요약:**  ... 
    * **적용 내용:** ....
    
### **🛠️ Troubleshooting & 기술 회고:**
  1. **문제 1:** ...
     * **원인:** ...
     * **해결:** ..
     
### **📁 증빙 자료:**
  * [3차_AI협업캡처.pdf 첨부 완료] (첨부 후 링크)
  * [3차과제_실행결과.jpg]
<br>

### 🟥 [4차 과제: V4.0] 모듈화 및 데이터 확장 (배열과 함수) - 🌟최종 완성 -- 향후 작성 예정
### **✨4차 과제 업데이트 내용:**
  * 내용.
    
### **🤖 AI 파트너십 과정**
 1. **내용 1**
    * **프롬프트 요약:**  ... 
    * **적용 내용:** ....
    
### **🛠️ Troubleshooting & 기술 회고:**
  1. **문제 1:** ...
     * **원인:** ...
     * **해결:** ..
     
### **📁 증빙 자료:**
  * [4차_AI협업캡처.pdf 첨부 완료] (첨부 후 링크)
  * [4차과제_실행결과.jpg]
<br>
