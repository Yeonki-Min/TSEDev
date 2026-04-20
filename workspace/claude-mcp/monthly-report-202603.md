# Monthly Report - 2026년 3월

## User Management 계정 목록

조회일시: 2026-04-20  
출처: CrowdStrike Falcon > Host setup and management > User management

| ID | 이름 | 생성일 | 마지막 접속일 |
|----|------|--------|--------------|
| insu-falcon@toss.im | insu falcon | Feb. 6, 2024 15:58:13 | Apr. 20, 2026 20:46:30 |
| jhhan@toss.im | 재현 한 | Feb. 5, 2024 14:30:20 | Feb. 23, 2026 16:40:37 |
| kantjo@toss.im | 민성 조 | Jul. 8, 2025 16:00:14 | Apr. 20, 2026 19:33:03 |

**총 계정 수: 3**

---

## Audit Log - Request Password Reset

조회일시: 2026-04-20  
출처: CrowdStrike Falcon > Audit Log > Falcon console (Time Range: Last 90 days)  
필터: Action = Request Password Reset

| 발생일시 | Action | Analyst | 대상 |
|----------|--------|---------|------|
| N/A | N/A | N/A | N/A |

**비고: 조회 기간(최근 90일) 내 "Request Password Reset" 이벤트 없음**

---

## 퇴사자 및 장기 미사용 계정 (Last login > 90일)

조회일시: 2026-04-20  
출처: CrowdStrike Falcon > Host setup and management > User management  
기준: 마지막 접속일로부터 90일 초과 계정

| ID | 이름 | 마지막 접속일 | 경과일수 |
|----|------|--------------|---------|
| N/A | N/A | N/A | N/A |

**비고: 전체 3개 계정 중 마지막 접속일 90일 초과 계정 없음**

| ID | 이름 | 마지막 접속일 | 경과일수 | 상태 |
|----|------|--------------|---------|------|
| insu-falcon@toss.im | insu falcon | Apr. 20, 2026 | 0일 | 정상 |
| jhhan@toss.im | 재현 한 | Feb. 23, 2026 | 56일 | 정상 |
| kantjo@toss.im | 민성 조 | Apr. 20, 2026 | 0일 | 정상 |

---

## IP Allowlist 등록 현황 (Status: On)

조회일시: 2026-04-20  
출처: CrowdStrike Falcon > Host setup and management > IP Allowlist Management

| IP 그룹명 | IP 주소/범위 | 설명 | Status |
|-----------|-------------|------|--------|
| N/A | N/A | N/A | N/A |

**비고: 등록된 IP 그룹 없음 (No IP groups yet)**

---

## API 계정 현황 (Created date > 90일)

조회일시: 2026-04-20  
출처: CrowdStrike Falcon > Support and resources > API clients and keys  
기준: 생성일로부터 90일 초과 API 클라이언트

| Client Name | Created date | Last Modified | Client ID | 경과일수 |
|-------------|-------------|---------------|-----------|---------|
| core-alerts | Aug. 14, 2024 14:13:54 | Aug. 14, 2024 14:48:41 | 8085befe32cb4b36a2a0441aecedf62a | 약 614일 |

**총 90일 초과 API 클라이언트: 1건**

---

## API 계정 현황 (Created date < 90일, 신규 생성)

조회일시: 2026-04-20  
출처: CrowdStrike Falcon > Support and resources > API clients and keys  
기준: 생성일로부터 90일 미만 신규 API 클라이언트 (2026-01-20 이후 생성)

| Client Name | Created date | Client ID | 경과일수 |
|-------------|-------------|-----------|---------|
| N/A | N/A | N/A | N/A |

**비고: 90일 이내 신규 생성 API 클라이언트 없음**

---

## 라이선스 사용량 (Sensor Subscription)

조회일시: 2026-04-20  
출처: CrowdStrike Falcon > Dashboards and reports > Billing > Sensor subscription licenses  
조회 기간: March 21, 2026 - April 18, 2026 (Last 4-Week)

| 항목 | 수량 |
|------|------|
| 계약수량 | 80 EA |
| Sensor Usage (사용량) | 140 EA |
| 초과/잔여 | **+60 EA 초과** |
| 사용률 | **175%** |

**비고: 계약수량(80EA) 대비 60EA 초과 사용 중 (사용률 175%)**

---

## OS별 호스트 & 센서 현황

조회일시: 2026-04-20  
출처: CrowdStrike Falcon > Host setup and management > Host management  
전체 호스트 수: **159대**

### Platform별 호스트 수

| Platform | 호스트 수 |
|----------|---------|
| Windows | 133 |
| Mac | 26 |
| **합계** | **159** |

### OS version별 호스트 수

| OS Version | 호스트 수 |
|------------|---------|
| Windows 11 | 112 |
| Sequoia (15) | 14 |
| Tahoe (26) | 12 |
| Windows Server 2016 | 8 |
| Windows 10 | 7 |
| Windows Server 2022 | 6 |
| **합계** | **159** |

### Sensor version별 호스트 수

| Sensor Version | 호스트 수 |
|---------------|---------|
| 7.35.20709.0 | 112 |
| 7.35.20704.0 | 21 |
| 7.33.20505.0 | 12 |
| 7.34.20610.0 | 8 |
| 7.33.20503.0 | 3 |
| 7.32.20403.0 | 1 |
| 7.32.20407.0 | 1 |
| 7.34.20604.0 | 1 |
| **합계** | **159** |

---

## Host Group 현황

조회일시: 2026-04-20  
출처: CrowdStrike Falcon > Host setup and management > Host groups  
전체 Host Group 수: **4개**

| Group Name | Group Type | Hosts Applied | 설명 | 생성자 | 생성일 |
|-----------|-----------|:------------:|------|--------|--------|
| AWS_VDI | Dynamic | 3 | AWS_VDI 사용자 | jhhan@toss.im | Feb. 24, 2025 |
| Windows_server | Dynamic | 11 | 윈도우 서버 그룹 | jhhan@toss.im | Feb. 14, 2024 |
| mac_os | Dynamic | 3 | Mac 사용자 | jhhan@toss.im | Feb. 24, 2025 |
| window_os | Dynamic | 81 | 윈도우 사용자 | jhhan@toss.im | Feb. 24, 2025 |

---

## Detection Top 5 (Triggering File)

조회일시: 2026-04-20  
출처: CrowdStrike Falcon > Endpoint security > Endpoint detections  
조회 기간: Last 90 days (323건)

| 순위 | Triggering File | 탐지 건수 |
|:---:|----------------|:-------:|
| 1 | setup.exe | 58 |
| 2 | LaunchAfterTricky 64.exe | 44 |
| 3 | AfterTricky64.exe | 36 |
| 4 | explorer.exe | 33 |
| 5 | AfterTricky.exe | 28 |

---

## Fusion Workflow - Execution Log

조회일시: 2026-04-20  
출처: CrowdStrike Falcon > Next-Gen SIEM > Workflows > Execution log

### Workflow 목록

| Workflow Name | Trigger | Actions |
|--------------|---------|---------|
| Crowdstrike detection | Detection > EPP Detection | Send Slack message |

**총 Workflow 수: 1개**

### Execution Status 현황

| Workflow Name | Execution Status | 건수 |
|--------------|-----------------|------|
| Crowdstrike detection | Completed | 325 |

**총 실행 건수: 325건 (Completed 100%)**
