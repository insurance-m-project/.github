> 2024 메리츠화재 인턴십 프로젝트
# 보험 서류 청구 자동화 시스템
## Ethereum Smart Contract & DApp
**'독감'** 보험 서류 청구 시, 총 9 단계의 프로세스를 2 단계로 줄일 수 있는 **스마트 컨트랙트** 기반 이더리움 네트워크 구성

## As-is & To-be
### As-is
```
1. 진료비 영수증, 진료비 세부산정내역을 병원에서 환자가 직접 발급
2. 메리츠화재 앱에서 보험금 청구 메뉴 접속
3. 로그인
4. 청구유형 선택
5. 치료받을 분 선택
6. 필수약관 동의 선택
7. 청구 정보 입력 선택 (사고유형, 사고일자, 진단 및 청구 내용, 이메일 등 입력)
8. 입금 계좌정보 (청구 대행서비스, 의료급여 수급권자 여부 선택)
9. 보험금에 필요한 서류 전송 (진료비 계산 영수증, 진료비 세부 내역서 등을 카메라로 촬영하여 전송)
```

### To-be
```
1. 보험 서류 청구 자동화 동의
2. 병원에서 DApp에 직접 접속하여 독감 보험금 접수 버튼 클릭
```


## Project Architecture
<details>
<summary>Project Architecture</summary>
  
![architect img](https://github.com/insurance-m-project/.github/assets/90203250/dfc2cef3-d31b-446d-af03-9b4f4fa94ac8)
</details>

## Project Flow
<details>
<summary>Project Flow</summary>
  
![copy](https://github.com/insurance-m-project/.github/assets/90203250/cc6dd77a-a6a0-4dda-b40f-36e7ded99f27)
</details>

<br> 

## Design
<img width="744" alt="스크린샷 2024-04-21 오후 10 42 41" src="https://github.com/insurance-m-project/.github/assets/90203250/af82d6a6-7a4f-4122-a509-fa89795633cb">

## Member
|[서재혁](https://github.com/twg0)|[장채은](https://github.com/chaerlo127)|
|:---:|:---:|
|<img src="https://github.com/twg0.png" width="180" height="180" >|<img src="https://github.com/chaerlo127.png" width="180" height="180" >|
| **Ethreum Network** <br> **비즈니스 솔리디티 로직** <br> **메리츠화재 DApp(이벤트)**   | **Ethreum Network** <br> **비즈니스/로깅 솔리디티 로직** <br> **병원/로깅 DApp** | 
