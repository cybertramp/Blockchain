# Blockchain
My blockchain studies pages.

## Bitcoin 처리 흐름

1. 트랜잭션 발행(전자서명 첨부)

2. 참가자 전원에게 브로드캐스트

3. 트랜잭션을 받은자는 전자서명 확인 후 블록을 생성하기 위한 해답을 찾기 시작

4. 첫 조건을 만족하는 해답을 발견한 자는 생성한 블록을 전체 브로드캐스트

5. 블록을 받은 노드는 정당한 블록인지 검증
검증: (블록+해답)의 해시로 확인, 맞으면 수신한 블록을 자신의 블록체인에 추가

### 대표적인 블록체인 기반 기술

- Bitcoin core

흔히 말하는 Bitcoin 레퍼런스를 구현한 것

- Ethereum

Dapps 구축 플랫폼, 스마트 컨트랙트

- Hyperledger Fabric

성능과 신뢰성 향상을 위한 고유의 합의 알고리즘, MSP(신원) 관리 기능, Linux Foundation

- Corda

R3 주도, 금융 DLT, 합의 형성에 초점, 참가자 전원이 데이터를 공유하지는 않음

### 블록체인 기술 구성 요소

- SmartContract

- Digital signature, Hash

- Consensus Algorithm

### 블록체인 분류

- Public

- Consortium

- Private

### P2P형 시스템 분류

- Pure P2P

노드 탐색 알고리즘 필요

- Hybrid P2P

인덱스 서버를 통해 노드 탐색(노드 탐색 알고리즘 필요 X)


