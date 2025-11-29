# Galatea Old Type 6u PCB

<br />

Geonworks에서 판매했던 Studio Kestra의 Galatea 구형 버전과 호환되는 a87 TKL 유니버셜 PCB입니다.

<br />

**Rendering**

![PCB Rendering Top View](/Asset/PCB_3D_Top.png)
![PCB Rendering Bottom View](/Asset/PCB_3D_Bottom.png)

<br />

**Prototype**

![PCB Prototype Top View](/Asset/PCB_Top.jpg)
![PCB Prototype Bottom View](/Asset/PCB_Bottom.jpg)

<br />

**Detail**

![PCB Prototype Top Detail View](/Asset/PCB_Top_Detail.jpg)
![PCB Prototype Bottom Detail View](/Asset/PCB_Bottom_Detail.jpg)

<br />

**Compatibility Test**

![Compatibility test of the USB-C port using the Frog TKL](/Asset/Test_Frog_TKL.jpg)

<br />
<br />

## Supported Layout

<br />

해당 PCB는 ISO 배열을 지원하지 않으며, 6.25u 대신 6u 하단열을 지원합니다.

<br />

![Supported Layout](/Asset/Supported_Layout.png)

<br />

또한 기존의 LED 인디케이터를 모두 버리고 Insert 키 위치에 캡스락 LED 인디케이터를 1개 배치하였습니다. 아래는 Vial의 탭댄스 기능을 활용한 인디케이터 테스트 영상입니다.

<br />

[LED_Indicator_with_Tap_Dance.webm](https://github.com/user-attachments/assets/71b8654c-97a3-42a6-80ce-c4df9c4b528a)

<br />
<br />

## Firmware

<br />

펌웨어는 QMK를 기반으로 Via와 Vial을 지원합니다. 펌웨어 소스코드와 Hex 파일은 [여기](/Firmware)에서 다운로드 받으실 수 있습니다.

<br />

```bash
├── Firmware/
│   ├── clein_galatea_old_type_rev_1_0_via.hex
│   └── clein_galatea_old_type_rev_1_0_vial.hex
└── README.md
```

<br />
<br />

## PCB Guide

<br />

PCB와 호환 보강판 제작에 관련된 가이드 도면은 [여기](/Guide)에서 다운로드 받으실 수 있습니다.

<br />

![PCB Guideline](/Guide/PCB_Guideline.png)
![PCB Outline](/Guide/PCB_Outline.png)
![Plate Guideline](/Guide/Plate_Guideline.png)

```bash
├── Guide/
│   ├── PCB_Guideline.dxf
│   ├── PCB_Outline.dxf
│   └── Plate_Guideline.dxf
└── README.md
```

<br />
<br />

## How to Order

<br />

해당 PCB의 프로토타입은 [PCBWay](https://pcbway.com)를 통해 제작되었습니다. 프로토타입 제작에 사용되는 파일들은 [여기](/Production)에서 다운로드 받으실 수 있습니다.

<br />

```bash
├── Production/
│   ├── Galatea_Old_Type_6u_PCB_BOM.csv
│   ├── Galatea_Old_Type_6u_PCB_BOM.xlsx
│   ├── Galatea_Old_Type_6u_PCB_Pos_JLCPCB.csv
│   ├── Galatea_Old_Type_6u_PCB_Pos.csv
│   └── Gerber.zip
└── README.md
```

<br />

아래는 적용된 옵션입니다.

![Options applied to the PCB prototype](/Asset/Prototype_Options.jpg)

<br />
<br />

## Licence

<br />

해당 프로젝트는 [ai03](https://github.com/ai03-2725) 님의 [KBD8X-MKII-PCB](https://github.com/ai03-2725/KBD8X-MKII-PCB) 프로젝트와 [Joe Scotto](https://github.com/joe-scotto) 님의 [ScottoKeebs](https://github.com/joe-scotto/scottokeebs) 프로젝트를 기반으로 만들어졌습니다. 해당 프로젝트를 활용한 수정, 복제, 배포 등의 활동은 저작자 표시와 함께 비영리적인 목적에 한해서만 가능하며, 라이선스 전문은 [여기](/LICENCE)에서 보실 수 있습니다.

<br />

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" /><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" /><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" /><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" />