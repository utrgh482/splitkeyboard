# dnerd zmk-config (1호 PCB용)

- build.yaml : nice_nano_v2 + dnerd_left / dnerd_right / settings_reset
- config/boards/shields/dnerd/ : 쉴드 정의(매트릭스 핀, 키맵, 유선 스플릿)
- .github/workflows/build.yml : 푸시하면 GitHub Actions가 uf2를 만들어 줌

핀: cols D4 D5 D6 D7 D8 D9 D10 (오른쪽 +D16), rows D21 D20 D19 D18 D15 D14,
UART TX=D1(실크 006) RX=D0(실크 008). 왼쪽이 central(USB 꽂는 쪽).
