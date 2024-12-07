# Open-PLC-Project
yss OS를 사용한 오픈 소스/회로 PLC 프로젝트입니다.

중국의 lcsc에서 '전자 부품' + 'PCB' + 'SMT' 주문을 한번에 진행할 수 있는 자료를 모두 오픈할 계획입니다. 
누구나 PCB를 주문해서 거의 완성된 상태로 받아볼 수 있도록 할 계획입니다.
보드의 전체 기능이 yss OS 기반에서 제어 가능한 소스코드를 다운로드하여 필요한 동작을 구현하는 프로젝트입니다.

# 사용 프로그램
* 회로도/PCB : Kicad (<https://www.kicad.org/>)
* Compiler + IDE : gcc + Crossworks for ARM (<https://www.rowley.co.uk/arm/index.htm>)
* Office : Libreoffice (<https://www.libreoffice.org/>)

# Base Board
Base Board는 기본적인 소량의 디지털 I/O, 릴레이, AIN, AOUT을 갖출 계획입니다. 
부족한 기능은 외부에 보드를 추가해 CAN으로 서로 통신하며 기능을 보완하는 것을 계획하고 있습니다.

케이스 : <https://ko.aliexpress.com/item/1005003779239575.html?spm=a2g0o.order_list.order_list_main.5.185e140fnb0dcr&gatewayAdapt=glo2kor>

## 단자 구성
케이스는 총 40핀으로 구성되어 있습니다. 
핀맵은 아래와 같이 구성됩니다.

1. [전원] +8~24V (프리볼트)
2. [전원] GND
3. [통신] CANL
4. [통신] CANH
