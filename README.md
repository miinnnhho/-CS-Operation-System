# 운영체제 
<면접을 위한 CS 전공지식 노트>(길벗, 2022)을 학습하고 개인 학습용으로 정리한 내용입니다.

# 23.04.06 작성😉

## 1.운영체제와 컴퓨터

#### CPU
- 쉽게 말 해 일꾼
* 제어장치(Control Unit)
  - 프로세스 조작 지시
* 레지스터
  - 임시기억장치
* 산술논리연산장치(ALU, Arithmetic Logic Unit)
  - 연산을 계산
  
#### DMA 컨트롤러
- cpu의 일을 보조

## 2.메모리
1. 레지스터
2. 캐시(L1, L2)
3. 주기억장치: RAM
4. 보조기억장치: HDD, SSD

#### 캐시
- 데이터를 미리 복사해 놓는 임시 저장소
(병목현상을 줄이기 위한 메모리)

#### 캐시히트, 캐시미스
- 캐시에서 원하는 값을 찾았다? => 캐시히트
- 없으면 주 메모리로 가서 찾아옴 => 캐시미스

#### 대표적인 캐시
1. 쿠키 : 만료기간이 있는 키값 저장소
2. 로컬 스토리지 : 만료기간 없는 키값 저장소(10MB까지 저장)
3. 세션 스토리지:  만료기간 없는 키값 저장소(5MB까지 저장)

# 23.04.12 추가 🥶
### 메모리 관리
#### 가상메모리
  - 스와핑
   => 하드디스크의 일부분을 메모리처럼 쓰는 것 -> 페이지 폴트가 안 일어난 것처럼 만듦.
#### 스레싱
   => 메모리의 페이지 폴트율이 높은 것 -> 심각한 성능 저하
 해결법: SSD로 변경, working set(작업 세트), PFF(Page Fault Frequency)
#### 메모리 할당
    * 연속 할당
      - 고정 분할 방식
      - 가변 분할 방식
    * 불연속 할당
      - 페이징
      - 세그멘테이션
      - 페이지드 세그멘테이션
#### 페이지 교체 알고리즘
    * 오프라인 알고리즘
    * FIFO
    * LRU
    * NUR
    * LFU
## 3. 프로세스와 스레드
  * 프로세스: 컴퓨터에서 실행되고 있는 프로그램
  * 
 


