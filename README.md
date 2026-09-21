# BE MY HUNTER — Xogot / Godot

서림, 2050. 3D 생활권 배경과 도트 캐릭터를 결합한 네이티브 2.5D RPG.

- [브라우저에서 플레이](https://snow72730321-star.github.io/be-my-hunter/)
- [Xogot 프로젝트 다운로드](./BMH_Xogot_Play.zip)
- [소스 프로젝트](./BMH_Xogot_Source.zip)
- [실제 Godot 검사와 빌드 기록](https://github.com/snow72730321-star/be-my-hunter/actions/workflows/xogot.yml)

Xogot에서는 ZIP을 파일 앱에서 풀고 `project.godot`를 가져와 실행하세요. 가로 화면 기준입니다. 외부 AI API나 별도 게임 서버는 필요하지 않습니다.

새로하기 / 이어하기 / 설정, 성인 캐릭터 외형·포인트 특성 선택, 직접 이동·대시·상호작용, 슬롯·합·코인 전투, 무기별 모션과 VFX, 정신력·흐트러짐, 애니메이션으로 펼쳐지는 헌터 디바이스, 세이브를 제공합니다.

현재 범위는 **첫 서림 생활권 시제품**입니다. 모든 장이 완성된 오픈월드가 아닙니다. 프롤로그와 1장 관련 구조·의료·대피·공략의 상태를 구현했습니다. 2장 이후·펫·옥션·전체 성장 체계는 이번 네이티브 버전에 포함되지 않습니다. 자세한 구현/참조 데이터/미검증 구분은 프로젝트의 `README.md`와 `docs/VALIDATION.md`에 있습니다.

Godot 4.4.1에서 규칙 22개와 실제 렌더링 시나리오를 실행합니다. 실제 iPhone Xogot 장치 검증은 아직 별도입니다. 캐릭터와 타이틀은 BMH용 생성형 원본 시제품 에셋이며, 건물과 적은 기본 3D 모델입니다. Limbus Company의 이미지·음원·캐릭터 파일을 사용하지 않습니다.

0.2 GDevelop 버전과 그 저장 형식은 별도로 남습니다. 0.3은 GDScript와 native scene graph로 다시 만들었습니다.
