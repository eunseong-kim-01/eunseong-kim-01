# 안녕하세요, 시스템 반도체 설계/검증 엔지니어를 꿈꾸는 김은성입니다.

<br>

### 👨‍💻 About Me
- 저는 **시스템 반도체 설계/검증 엔지니어**를 목표로 공부하고 있는 학생입니다.
- 현재 하만 세미콘 아카데미에서 RTL 설계부터 UVM을 활용한 기능 검증, SoC 플랫폼 통합설계까지 아우르는 실무 중심의 교육을 받고 있습니다.

<br>

### 🛠️ Tech Stack & Skills
#### Languages
![Verilog](https://img.shields.io/badge/Verilog-1E90FF?style=for-the-badge&logo=verilog&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-8A2BE2?style=for-the-badge)
![C/C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB_(Basic)-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)

#### EDA Tools & Verification
![Xilinx Vivado](https://img.shields.io/badge/Vivado-D95319?style=for-the-badge&logo=xilinx&logoColor=white)
![Synopsys Verdi](https://img.shields.io/badge/Synopsys_Verdi-522D80?style=for-the-badge)
![UVM](https://img.shields.io/badge/UVM-Verification-green?style=for-the-badge)
![Silvaco TCAD](https://img.shields.io/badge/Silvaco%20TCAD-D42E16?style=for-the-badge)

#### Hardware & Protocols
- **FPGA Boards**: `[Basys 3]`
- **Architectures**: `RISC-V (RV32I)`
- **Protocols**: `AMBA (AXI4, APB)`, `SPI`, `I2C`, `UART`, `VGA`
- **Sensors/Modules**: `OV7670 Camera`, `HC-SR04`, `DHT-11`

<br>

### 🚀 Featured Projects

#### 🖥️ SoC Design & Verification (SystemVerilog / UVM)
| Project | Description | Tech Stack | Link |
|---|---|---|---|
| **`⚡ RISC-V RV32I Multi-Cycle CPU & APB System`** | • **RV32I 명령어 집합**을 지원하는 Multi-Cycle CPU 설계<br>• **AMBA APB 프로토콜**을 구현하여 UART, FND 등 Peripheral 제어<br>• C 언어 기반 펌웨어를 ROM에 탑재하여 하드웨어/소프트웨어 통합 검증 수행 | `SystemVerilog` `RISC-V` `AMBA APB` `C` | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/eunseong-kim-01/RISC-V-RV32I-CPU-Multi-Cycle-AMBA-APB-Peripheral) |
| **`🔍 SoC Bus Protocol 설계 및 UVM 검증`** | • **AMBA AXI4, SPI, I2C** 통신 컨트롤러(Master/Slave) RTL 설계<br>• **UVM(Universal Verification Methodology)** 기반의 Testbench(Agent, Scoreboard 등) 구축<br>• SPI Loopback 테스트 및 I2C LED 제어를 통한 프로토콜 기능 검증 완료 | `SystemVerilog` `UVM` `AXI4` `SPI/I2C` | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/eunseong-kim-01/AMBAAXI-SPI-I2C-Design-SPI-UVM) |

#### 📹 FPGA & Embedded System
| Project | Description | Tech Stack | Link |
|---|---|---|---|
| **`🎮 FPGA 기반 실시간 영상 필터 & 인터랙티브 게임`** | • **OV7670 카메라** 입력 영상을 실시간 처리하는 **VGA Controller** 설계<br>• Line Buffer를 활용한 **Sobel, Gaussian, Cartoon 필터** 구현 (Memory 최적화)<br>• 실시간 색상 인식(Color Detection) 알고리즘을 적용한 **모션 인식 게임** 개발 | `SystemVerilog` `FPGA` `VGA` `Image Processing` | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/eunseong-kim-01/Real-time-VGA-Processing-Filter-Motion-Game) |
| **`⌚ 하이브리드 제어 디지털 시계 & 스톱워치`** | • FPGA 보드의 버튼과 PC의 UART 통신을 동시에 이용하여 제어하는 시스템<br>• UART RX/TX 모듈 설계 및 상태머신(FSM)을 이용한 제어 로직 구현 | `Verilog` `UART` `Vivado` | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/eunseong-kim-01/UART_Watch-Stopwatch) |
| **`⚙️ 다중 센서 통합 제어 시스템`** | • 초음파 거리 측정, 온습도 측정, 시계 기능을 통합한 FPGA 시스템<br>• 다중 센서 데이터 처리 및 디스플레이 제어 로직 설계 | `Verilog` `Sensors` `System Integration` | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/eunseong-kim-01/UART_WatchStopwatch_HC-SR04_DHT-11) |

#### 💻 Software & Others
| Project | Description | Tech Stack | Link |
|---|---|---|---|
| **`🍽️ 재료 맞춤형 레시피 추천 웹`** | • 웹 크롤링을 활용한 보유 재료 기반 요리 추천 및 맛집 정보 제공 서비스<br>• 데이터 수집 및 백엔드 로직 구현 | `Python` `Flask` `Selenium` | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/eunseong-kim-01/Ingredient-Recipe-Finder) |

<br>

### 🔬 Research Experience & Publications
#### [반도체 소자 연구실 (Semiconductor Device Lab)] (학부 연구생)
- **기간**: `2022.06 ~ 2023.11`
- **주요 연구 내용**: Silvaco TCAD 툴을 활용하여 차세대 반도체 소자인 **Silicon Biristor**의 온도 변화에 따른 전기적 특성을 시뮬레이션하고 분석했습니다.
- 이 경험을 통해 반도체 소자의 물리적 동작 원리에 대한 깊이 있는 이해를 갖추게 되었으며, 이는 RTL 설계 시 하드웨어의 물리적 제약(Timing, Power)을 고려하는 데 큰 도움이 되었습니다.

#### 📝 Publications
- **Temperature-Dependent Electrical Characteristics of Silicon Biristor**
  - **Eunseong Kim**, Doohyeok Lim
  - *Micromachines*, 2023
  - **(1st Author)**
  - [[Project Summary]](https://github.com/eunseong-kim-01/Temperature-Dependent-Electrical-Characteristics-of-Silicon-Biristor)
  - [[View Paper]](https://www.mdpi.com/2072-666X/14/12/2165)

<br>

### 🎓 Education & Experience
- **Harman Semicon Academy** (2025.07 ~ 2026.01 예정)
  - 반도체 설계 전문가 양성 과정 (Verilog/SystemVerilog, UVM, SoC Design)

- **[경기대학교] 반도체 공정 실습 (Semiconductor Fabrication Practice)**
  - **기간**: `2023.04 ~ 2023.06`
  - **내용**: 실제 Fab 환경에서 포토(Photo), 식각(Etch), 증착(Deposition), 이온 주입(Ion Implantation) 등 단위 공정을 직접 수행하며 Wafer 패터닝 실습
  - **배운 점**: 회로가 실제 칩으로 구현되는 과정을 이해하고, **공정 변수(Process Variation)**가 회로 성능에 미치는 영향을 고려하는 엔지니어링 시각 확보

- **경기대학교 (Kyonggi University)** (2020.03 ~ 2026.02 졸업예정)
  - 전자공학과 학사
  - **주요 수강 과목**: 회로이론, 디지털논리설계, 하드웨어설계, 임베디드시스템설계, 디지털신호처리, 반도체소자공학 등

<br>

### 📫 How to Reach Me
- **Email**: `sorii1028@naver.com`
