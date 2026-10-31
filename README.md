# Samet Erhan Sarı

I am a final-year electrical engineering student at Yıldız Technical University in Istanbul. My work is anchored in control and system modelling, and I use that core to move between power electronics, energy systems, flight dynamics, industrial automation and embedded software. Most of the projects here started as a question about how something actually behaves, and I kept building, simulating or measuring until I could answer it.

Older commits appear under the name Nikolai Andrew, which is also me.

## Research

Two research projects are being prepared as preprints, so their code is not public yet.

- **Hydrogen-integrated microgrid energy management.** A TÜBİTAK 2209-A funded project on a microgrid with wind, solar, battery storage and a hydrogen chain of electrolyzer, storage and fuel cell, coordinated by a three-layer energy management system. The controller was validated from model-in-the-loop through software-in-the-loop to processor-in-the-loop on an STM32G431RB.
- **Model predictive control for renewable-powered HVAC.** An MPC-based HVAC and energy management framework that can be configured for different applications such as greenhouses, cold storage and offices. It runs on two decades of location-based weather data and includes a battery degradation model.

## Experience

- **Siemens Energy**, Control and Digitalization intern, working with the Omnivise T3000 DCS, HMI development and lab commissioning
- **Turkish Technic**, Avionics Engineering intern, studying the lateral-directional dynamics of the RCAM benchmark aircraft, which I later extended into RCAM-Flight-Dynamics
- **Esen-El Engineering**, intern on MV and LV substation work for a university campus project

## Selected projects

| Project | Area | What it is |
|---|---|---|
| [RCAM-Flight-Dynamics](https://github.com/1337leets/RCAM-Flight-Dynamics) | Flight control | Nonlinear 6-DOF model of the GARTEUR RCAM aircraft with trim, linearization, modal analysis and a gain-scheduled yaw damper in plain MATLAB |
| [Simulink-Grid-Tied-Battery-VSC-Inverter](https://github.com/1337leets/Simulink-Grid-Tied-Battery-VSC-Inverter) | Power electronics and control | A 10 kW grid-tied battery inverter built up step by step from an open-loop bridge to an SRF-PLL and dq current control |
| [TL494-Buck-Converter-LTspice](https://github.com/1337leets/TL494-Buck-Converter-LTspice) | Power electronics | A 12 V to 5 V breadboard buck converter whose protection circuits were each checked in simulation against the fault they are meant to handle |
| [PMDC-Motor-PID-Control-Modbus-HMI-OpenPLC](https://github.com/1337leets/PMDC-Motor-PID-Control-Modbus-HMI-OpenPLC) | Industrial automation | A motor speed loop in Structured Text on OpenPLC with a Modbus to REST bridge and a live web HMI for tuning |
| [Cell-Tower-Locator](https://github.com/1337leets/Cell-Tower-Locator) | Estimation | Locating LTE base stations from timing advance and GPS logs collected on a phone, compared against OpenCellID |
| [Volts](https://github.com/1337leets/Volts) | Software | A terminal puzzle game in C and ncurses that solves each circuit with real DC and AC equations as you swap parts |

## Other work

**Power electronics and circuits**
[ELM-3071 controlled rectifier](https://github.com/1337leets/ELM-3071-PSIM-Single-Phase-Controlled-Rectifier),
[ELM-3182 buck-boost converter](https://github.com/1337leets/ELM-3182-PSIM-Buck-Boost-Converter),
[PSIM square wave to sine filter](https://github.com/1337leets/PSIM-Square-Wave-Sine-Filter),
[PMDC motor PI control in ngspice](https://github.com/1337leets/PMDC-Motor-PI-Control-ngspice),
[ELM-4040 alternative energy models](https://github.com/1337leets/ELM-4040-Alternative-Energy-Simulink)

**Digital design**
[VHDL seven-segment driver](https://github.com/1337leets/VHDL-7Seg-Driver),
[ELM-2042 flash ADC](https://github.com/1337leets/ELM-2042-Flash-ADC),
[ELM-3091 inverse traffic light](https://github.com/1337leets/ELM-3091-Inverse-Traffic-Light),
[mod-10 up/down counter](https://github.com/1337leets/Proteus-Mod10-Sync-Up-Down-Counter),
[ELM-4070 Arduino calculator](https://github.com/1337leets/ELM-4070-Arduino-Calculator-FSM),
[Logisim ALU and shifter](https://github.com/1337leets/Logisim-ALU-Shifter),
[Logisim PWM](https://github.com/1337leets/Logisim-Selective-PWM-3bit),
[Logisim traffic light FSM](https://github.com/1337leets/Logisim-Traffic-Light-FSM),
[Logisim piano](https://github.com/1337leets/Logisim-Piano)

**Automation**
[OpenPLC assembly line with fault detection](https://github.com/1337leets/Automated-Assembly-Line-Control-System-OpenPLC)

**Systems, security and low-level programming**
[BareScan](https://github.com/1337leets/BareScan),
[PhantomDiary](https://github.com/1337leets/PhantomDiary),
[x86 Assembly Blackjack](https://github.com/1337leets/x86Assembly-Blackjack),
[Win32 Minesweeper in C](https://github.com/1337leets/C-Win32-Minesweeper-GUI),
[ELM-2080 C programming](https://github.com/1337leets/elm2080-c-programming),
[Windows event sounds](https://github.com/1337leets/Windows-Startup-Shutdown-Login-Logout-Sound)

**Android, Termux and sensors**
[Wi-Fi wardriving logger](https://github.com/1337leets/WiFi-Wardriving-Logger),
[GPS speedometer](https://github.com/1337leets/Termux-GPS-Speedometer),
[VibDet](https://github.com/1337leets/VibDet),
[IEEE Xplore tracker](https://github.com/1337leets/IEEEXplore-Tracker),
[SoX multitrack](https://github.com/1337leets/SoX-Multitrack),
[Python DSP synth](https://github.com/1337leets/Python-DSP-Synth),
[Termux scripts](https://github.com/1337leets/Termux-Scripts),
and several Tasker profiles

## Tools

MATLAB, Simulink and Simscape, LTspice, PSIM, ngspice, Proteus, STM32CubeIDE, OpenPLC (IEC 61131-3), Omnivise T3000, VHDL with GHDL, Logisim, C, Python and Bash.
