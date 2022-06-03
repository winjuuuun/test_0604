top 명령어는 현재 OS의 상태를 나타내주는 CLI 어플리케이션입니다. 메모리 사용량, CPU 사용량 등을 나타내주며 top를 실행하는 동안에는 주기적인 업데이트로 실시간에 근접한 내용을 보여줍니다. 리눅스에서 top 명령어를 실행하면 아래와 깉이 노출됩니다. 위에는 전체의 요약이 있으며 아래에는 각 프로세스마다 구체적인 내용을 포함하고 있습니다.요약 영역
![image](https://user-images.githubusercontent.com/106620115/171925625-2b8b6009-e11e-4b54-bf5e-be1aa94f9f75.png)
요약 영역은 top에서 상단에 위치하고 있습니다. 이 요약영역은 전체 프로세스가 OS에 대해서 리소스를 어느정도 차지하고 있는지를 알려줍니다. 요약 영역에 나타나는 대표적인 값은 시간, 유저, 로드 에버리지(Load Average), 테스크(Tasks), CPU, 메모리(memory)로 아래의 이미지를 보시면 각 영역에 대해 나태내느 값이 어디에 위치하는지 알 수 있습니다.
![image](https://user-images.githubusercontent.com/106620115/171925706-8bc6680a-b675-427f-99d1-2d276bcd8cad.png)
시스템 현재 시간, OS가 살아있는 시간, 유저 세션수(System time, uptime and user sessions)
이미지의 가장 왼쪽 위를 보시면 시스템 현재 시간, OS가 살아있는 시간, 그리고 유저의 세션수가 표시되는 영역이 있습니다. 가장 먼저 보이는 숫자가 시스템의 현재 시간입니다. 이 시간은 GMT 기준으로 표시됩니다. 위 예제 기준으로 GMT 16:58:55 이라는 것입니다. 이것은 한국시간으로 보면 +9를 한 00시 58분 55초와 동일합니다. 다음으로 표시되는 것이 OS가 얼마나 살아있는지 나타냅니다. days와 시간으로 표시되며 위 예제로보면 7일과 1시 15분 동안 서버가 살아있었다는 것을 알 수 있습니다. 그리고 다음 나타나는것이 현재 접속중인 유저 세션 수입니다.

좀 더 자세한 유저세션이 궁금하다면 who 명령어를 통해 알 수 있습니다.
![image](https://user-images.githubusercontent.com/106620115/171925811-17f89cd4-3d97-44b6-9748-ccf74348c7e3.png)
