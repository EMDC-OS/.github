# Research on Edge-Native Operating Systems for Edge Micro-Data-Centers

![test](./data/images/overview_en.png)

## Project Goal
본 연구는 엣지 디바이스로부터 전달되는 데이터 스트림의 지능 컴퓨팅 작업을 엣지-마이크로데이터센터에서 효과적으로 처리할 수 있도록 차세대 컴퓨팅 가속장치와 SCM의 특성을 반영한 새로운 운영체제 구조를 연구하고, 이를 구현하여 엣지-친화적 운영체제를 개발한다. 

## Repository Lists

| No. | Name | Description |
|:---:|:----:| ------------|
|1|[bidirectional-readahead](https://github.com/EMDC-OS/Bidirectional-Readahead)|양방향 readahead 코드
|2|[CorePartitioning](https://github.com/EMDC-OS/CorePartitioning)|I/O 성능향상을 위한 코어 파티셔닝 라이브러리 및 커널모듈|
|3|[CXL-AutoNUMA](https://github.com/EMDC-OS/CXL-AutoNUMA)|EMDC 환경에서 대규모 테넌트 지원을 위한 동적 핫 페이지 관리 기법 구현|
|4|[EMDC_llvm](https://github.com/arcs-skku/EMDC_llvm)|Intel DPC++기반의 컴파일러 유틸리티로 다종 이종가속기를 대상으로 팻 바이너리로 컴파일하고, dynamic binding/rebinding을 지원하는 구조로 변경하는 유틸리티|
|5|[gpu-faas](https://github.com/EMDC-OS/gpu-faas)|가속기 응용 실행에 있어 가속기 컨텍스트 공유를 통한 컨텍스트 초기화 시간 제거로 start-up latency를 최소화 하는 서버리스 컴퓨팅 플랫폼|
|6|[inference_profiler](https://github.com/EMDC-OS/inference_profiler)|NVIDIA Triton Inference Server를 사용한 추론 작업에서 추론 스택과 OS 커널의 전계층을 프로파일링 할 수 있는 프로파일러|
|7|[KuScale](https://github.com/sslab-konkuk/KuScale)|지능 컴퓨팅 작업을 효과적으로 처리할 수 있는 EMDC OS의 개발이며, 저지연성을 확보하며, 컴퓨팅 가속 장치(GPU)를 CPU와 대등하게 세밀한 제어가 가능한 스케줄러|
|8|[linux-autozg](https://github.com/jungyun-choi/linux-autozg)|F2FS의 동적 존 그룹 관리로 ZNS SSD에서 성능 최적화 기법|
|9|[mg-lru](https://github.com/EMDC-OS/mg-lru)|메모리 부족 환경에서 읽기 및 쓰기 작업을 수행할 때 발생하는 고지연 I/O 요청들의 커널 메모리 관리 계층을 분석할 수 있는 스크립트|
|10|[pm-aware-scheduler](https://github.com/EMDC-OS/pm-aware-scheduler)|NUMA 환경에서 SCM I/O를 인지하는 작업 동적 재배치 기법|
|11|[pm-opzero](https://github.com/EMDC-OS/pm-opzero)|DAX 파일시스템에서 페이지 캐시 제거로 인해 발생하는 데이터 초기화 (zero-out) 오버헤드가 제거된 파일시스템|
|12|[power-aware-trition](https://github.com/EMDC-OS/power-aware-triton)|NVIDIA Triton Inference Server를 기반으로 구현한 단일 GPU 노드에서 추론 에너지 소비 특성을 반영한 전력관리 기법|
|13|[remote-io](https://github.com/EMDC-OS/remote-io.git)|리눅스 커널에서 Remote-io 직접 접근 확장 모델|
|14|[remote-swap](https://github.com/EMDC-OS/remote-swap)|엣지 서버의 풍부한 저장소 자원을 활용한 모바일 시스템의 메모리 확장 및 응용프로그램 전환 성능 개선 코드|
|15|[severless-rewind](https://github.com/EMDC-OS/serverless-rewind)|서버리스 엣지 클라우드 환경에서 함수 실행 시 발생하는 보안문제를 해결하면서 동시에 실행 성능을 최적화한 기법|
|16|[usbip-COMPRESS](https://github.com/EMDC-OS/usbip-COMPRESS)|커널 계층 직접 송수신 기반 효율적 데이터 전송 구현|