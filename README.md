# LAB1 Combinational Logic

서울시립대학교 전자전기컴퓨터공학부 LAB1 조합논리회로 실험 자료입니다.

## 실험 항목

1. AND/OR/XOR Logic Gate
2. Full Adder
3. 4-bit Adder
4. 4-bit Subtractor
5. 4-bit Comparator
6. 4:1 Multiplexer
7. 1:8 Demultiplexer
8. 8:3 Encoder
9. 3:8 Decoder
10. 7-Segment Decoder

## 환경

- Vivado 2026.1
- FPGA part: xc7s75fgga484-1
- Icarus Verilog / vvp 13.0 stable
- FPGA board: HBE-Combo II-DLD

## 디렉터리

- `circuits/`: Verilog RTL 및 XDC 핀 제약
- `evidence/videos/`: 실제 보드 동작 영상
- `evidence/photos/`: 실제 보드 사진
- `evidence/simulation/`: 사전 시뮬레이션 증빙
- `evidence/vivado/`: Vivado bitstream 생성 증빙
- `reports/`: 실험 전/후 보고서

실험 전 사전 시뮬레이션에서는 10개 회로 모두 자기검사 테스트벤치를 통과했으며, 실험 후 Vivado에서 합성·구현 및 bitstream 생성을 완료하고 실제 보드 동작을 촬영했습니다.
