# AWS Cloud Practitioner Essentials (CLF-C02) 학습 및 정리 프로젝트

이 프로젝트는 AWS Cloud Practitioner Essentials 공식 강의를 수강하며 배운 내용을 자유롭게 메모하고 정리한 프로젝트입니다.

---

## 강의 목차 및 로드맵
AWS Certified Cloud Practitioner(CLF-C02) 시험 범위를 포괄하는 총 13개의 핵심 모듈로 구성되어 있습니다. 각 노트 파일은 notes/ 폴더 내에 생성되어 있습니다.

1. [Module 1: Introduction to AWS](notes/01_introduction_to_aws.md) - 완료
2. [Module 2: Compute in the Cloud](notes/02_compute_in_the_cloud.md) - 완료
3. [Module 3: 추가 컴퓨팅 서비스](notes/03_additional_compute.md)
4. [Module 4: 글로벌 시장 진출](notes/04_going_global.md)
5. [Module 5: 네트워킹](notes/05_networking.md)
6. [Module 6: 스토리지](notes/06_storage.md)
7. [Module 7: 데이터베이스](notes/07_databases.md)
8. [Module 8: AI/ML 및 데이터 분석](notes/08_ai_ml_data_analytics.md)
9. [Module 9: 보안](notes/09_security.md)
10. [Module 10: AWS 클라우드에서의 모니터링, 규정 준수, 거버넌스](notes/10_monitoring_compliance_governance.md)
11. [Module 11: 요금 및 지원](notes/11_pricing_and_support.md)
12. [Module 12: AWS 클라우드로 마이그레이션](notes/12_migration.md)
13. [Module 13: Well-Architected 솔루션](notes/13_well_architected_solutions.md)

---

## 가독성을 높이는 마크다운 작성 팁

마크다운 기본 문법 외에도 아래 팁을 활용하여 가독성을 극대화해 보세요.

### 1. 접기/펼치기 (Toggle) 효과
긴 내용이나 세부 설명 등을 접어두고 싶을 때 사용하면 유용합니다.
```html
<details>
<summary>상세 설명 보기 (클릭)</summary>

이곳에 숨겨질 내용을 작성합니다.
- 핵심 포인트 기록

</details>
```

### 2. 깔끔한 인용구(Blockquote)로 중요 요약 강조
강의 내용 중 반드시 기억해야 할 핵심 원칙이나 힌트는 `>` 기호를 사용하여 강조 처리합니다.
> 중요: AWS 공동 책임 모델에서 클라우드 자체의 보안(Security of the Cloud)은 AWS의 책임이고, 클라우드 안에서의 보안(Security in the Cloud)은 고객의 책임입니다.

### 3. 테이블(Table) 활용하기
서로 대조되는 서비스 종류나 개념을 분류할 때 테이블을 활용합니다.
| 서비스명 | 데이터 타입 | 주요 특징 |
| :--- | :--- | :--- |
| Amazon S3 | 객체(Object) | 무제한 저장 가능, 정적 웹 호스팅 |
| Amazon EBS | block(Block) | EC2 인스턴스에 장착하는 가상 하드디스크 |
| Amazon RDS | 관계형(RDBMS) | 복잡한 쿼리 지원, 관리형 데이터베이스 |

### 4. 텍스트 하이라이트
* 본문 작성 중 중요한 키워드는 \`\` (백틱)을 씌워 `highlight` 하거나 **굵게** 표현하여 한눈에 들어오게 강조합니다.

---

## 시작하기

1. **Active Workspace 설정**: 이 폴더(/Users/choi/Developer/aws-cloud-practitioner-notes)를 작업 영역으로 지정하여 필기를 진행합니다.
2. **템플릿 활용**: templates/velog_template.md 파일의 형식을 참고하여 공부한 강의 노트를 기록합니다.
3. **노트 작성**: 강의 모듈을 수강하면서 notes/ 디렉토리 하위 파일들에 강의 메모를 누적하며 복습을 진행합니다.
