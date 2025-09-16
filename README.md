# AndroidTool
MFC(C++) 기반으로 제작된 Windows용 Android Device 관리 툴입니다.  
ADB를 활용하여 연결된 단말기의 다양한 정보를 확인하고, 시스템 속성을 조회/수정하며, Wi-Fi/Proxy/루팅 여부 등 점검 기능을 제공합니다.

# 탭별 기능

## Device
<img width="986" height="793" alt="image" src="https://github.com/user-attachments/assets/7810ba60-9963-4f85-aa54-b7e42a7887ba" />

- 단말기 정보(연결된 단말기 정보)
- 제조사, 모델명, 안드로이드 버전, 빌드 버전, 루팅 여부, 개발자 옵션 여부, USB 디버깅 여부, SELinux
- WIFI SSID, WIFI IP, WIFI Proxy 상태
- CPU 정보, 메모리 정보
- 시스템 속성 설정
- CMD, ADB 콘솔 열기

## Proccess 
<img width="986" height="793" alt="image" src="https://github.com/user-attachments/assets/d97ad641-76f4-4205-b828-4c6e5724a170" />

- 현재 실행중인 앱 정보
- 메모리 덤프 기능(자동, 수동)

## Apps
<img width="986" height="793" alt="image" src="https://github.com/user-attachments/assets/c8c29142-64c1-4b3f-a2b9-12e23ab445e2" />

- 디렉터리 뷰어(파일 업/다운로드, 파일/폴더 CRUD, 권한 설정, 파일 시그니처 확인-파일 헤더 확인)
- 앱 추출 기능
- 화면 캡쳐 기능(화면 캡쳐, 저장경로 설정)

## Log 
<img width="986" height="793" alt="image" src="https://github.com/user-attachments/assets/c82d6f15-afaa-4ed3-be5f-42591b7f960e" />

- 작업 내역을 로그로 저장(SQLITE)

## Network
<img width="986" height="793" alt="image" src="https://github.com/user-attachments/assets/d7fe6ee4-20aa-4070-b032-c9b39e3ac016" />

- iptables 설정 기능(추가, 삭제, 수정)
  - python MITM 명령어 참고 가능
- 프록시 설정 기능

## Apktool
<img width="986" height="793" alt="image" src="https://github.com/user-attachments/assets/d09f7960-0d08-4023-aff9-1c479a57d4e7" />

- 디컴파일/컴파일
- 앱 사이닝

## Frida
<img width="986" height="793" alt="image" src="https://github.com/user-attachments/assets/50ab312d-b911-499d-b642-e7637b883e80" />

- 자주 사용하는 Frida 스크립트 저장 기능(SQLITE)
  
## 추후 기능 개발
- 라이브러리 미리 보기 기능
- ROOT CA 단말기에 설치 해주고 알아서 재부팅해주기
- DEX DUMP 기능.
