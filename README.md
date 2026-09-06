# BeyondMoment Chain — Web

BeyondMoment의 순간 기록 웹 UI (정적 사이트, GitHub Pages 배포)

지갑(MetaMask)을 연결해 순간을 글로 남기면, Sepolia 테스트넷의 BeyondMoments
컨트랙트에 영구히 기록됩니다. 이 저장소에는 UI만 있고, 실제 스마트 컨트랙트
소스 코드와 배포 도구는 별도의 프라이빗 저장소에서 관리합니다.

- `index.html` — 지갑 연결, 순간 기록/조회 UI
- `abi.json` — 컨트랙트와 통신하기 위한 인터페이스 정의 (구현 코드 아님)
- `config.js` — 배포된 컨트랙트 주소 및 네트워크 설정
