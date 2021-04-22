# ventory

source : https://github.com/ventoy/Ventoy

부팅 USB를 제작하지 않고 ISO 파일을 그냥 복사하면 부팅되는 기능을 제공하는 프로그램
윈도우, 리눅스 등 다양한 운영체제를 한 개의 USB에 넣어서 필요할때 부팅에 사용할 수 있는 기능 제공

# 사용법


1) 터미널 (Ctrl + Alt + T)을 열고 `sudo ventory` 명령을 실행하면 아래와 같은 화면이 브라우저에 나타납니다.
```
sudo ventory
```

![ventory](docs/img.png)

2) USB를 삽입하고 장치를 선택한 후 `설치` 버튼을 누르면 설치 완료. ( USB의 모든 내용이 삭제됩니다.)

3) 제작이 완료된 USB를 한 번 뺐다가 다시 삽입하면 `VTOYEFI` 와 `Ventory` 2개의 파티션이 보이고 `Ventory` 파티션에 원하는 ISO 파일을 복사하기만 끝.

4) USB로 부팅하면 해당 ISO 이미지를 선택할 수 있는 메뉴가 나온다.


![ventory](https://camo.githubusercontent.com/0280fc6415276f7940c16341aa4c484a3a7a4ba85bb0e9f71e877a01707198c6/68747470733a2f2f7777772e76656e746f792e6e65742f7374617469632f696d672f73637265656e2f73637265656e5f756566692e706e67)

