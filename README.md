TUP! (Team UP!)
공모전 및 대외활동 팀 자동 매칭 플랫폼
TUP!은 대학생과 청년들이 공모전 준비 과정에서 겪는 '팀원 모집의 어려움'을 해결하기 위한 자동 매칭 플랫폼입니다. 사용자 데이터를 기반으로 한 최적의 팀 구성 알고리즘과 피드백 시스템을 통해 효율적인 협업 환경의 시작을 돕습니다.

1. 핵심 기능 (Key Features)
AutoTeamUp (자동 매칭 시스템): 사용자가 입력한 기술 스택, 희망 분야 등 프로필 정보를 바탕으로 알고리즘이 최적의 팀원을 자동 구성합니다.

팀 빌딩 피드백: 매칭된 팀원들 간의 정보를 확인한 후, 상호 동의 절차를 거쳐 팀 결성을 확정하는 프로세스를 제공합니다.

공모전 정보 큐레이션: 다양한 공모전 정보를 한눈에 확인하고, 해당 공모전에 즉시 팀 매칭 대기열로 진입할 수 있습니다.

사용자 시나리오 기반 UI/UX: 대기열 입장부터 팀 확정까지의 과정을 직관적인 Flow-Chart 기반으로 설계하여 사용자 편의성을 높였습니다.

2. 기술 스택 (Tech Stack)
Development
Front-end: React, CSS, JSX

Back-end: Django, Django REST Framework (DRF)

Database: MySQL, Django ORM

Infrastructure & DevOps
Container: Docker (각 서비스 컨테이너화 및 통합 관리)

CI/CD: GitHub Actions를 통한 코드 푸시 시 자동 테스트 및 배포 파이프라인 구축

3. 시스템 아키텍처 (System Architecture)
본 플랫폼은 서비스의 확장성과 관리 효율을 위해 계층별로 분리된 구조를 가집니다.

Service Layer: React 기반의 프론트엔드와 Django API 서버가 독립적으로 구동됩니다.

Infrastructure Layer: Docker 환경에서 인프라가 관리되며, GitHub을 통한 CI/CD 환경이 구축되어 있습니다.

Data Layer: MySQL을 활용하며, 관계형 데이터 모델링(ERD)을 통해 팀원 정보, 공모전 데이터, 매칭 대기열 등을 체계적으로 관리합니다.

4. 프로젝트 성과 및 기대 효과
의사결정 투명성: GitHub과 Notion을 활용하여 개발 과정의 기술적 의사결정을 기록하고 공유함으로써 체계적인 협업 환경을 유지했습니다.

자동화 기반 효율화: 수동 모집의 번거로움을 자동 매칭 알고리즘으로 대체하여 팀 구성에 소요되는 시간을 단축했습니다.
