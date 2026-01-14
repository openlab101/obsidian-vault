
```mermaid
graph LR
    %% 전체 흐름 좌->우
    
    %% 1단계: 유입
    subgraph Stage1 [1. 유입 단계 - Acquisition]
        direction TB
        S1_Action("TO DO (해야 할 것)<br/>• 메타/SA 광고 소재 A/B 테스트<br/>• SEO 키워드 최적화 작업<br/>• 바이럴 콘텐츠 발행")
        S1_Refine("DELETE (정리 대상)<br/>• 성과 낮은 과거 광고 소재 OFF<br/>• 중복된 UTM 파라미터 통일")
        S1_Data("DATA (수집 데이터)<br/>• CAC 유입비용<br/>• CTR 클릭률<br/>• ROAS 광고수익률<br/>• 세션 당 페이지뷰")
        S1_Clean("CLEAN (데이터 정제)<br/>• UTM 소스 매체명 표준화<br/>• 봇 트래픽 필터링")
        S1_Docs("DOCS (기록 방법)<br/>• 03_Growth_Log 실험일지<br/>• 01_Data_Taxonomy 정의서")
        
        S1_Action --> S1_Refine --> S1_Data --> S1_Clean --> S1_Docs
    end

    %% 2단계: 활성화
    subgraph Stage2 [2. 활성화 단계 - Activation]
        direction TB
        S2_Action("TO DO (해야 할 것)<br/>• 상세페이지 GIF 영상 배치<br/>• 회원가입 간소화 UX 개선<br/>• 이탈 감지 팝업 설치")
        S2_Refine("DELETE (정리 대상)<br/>• 로딩 속도 저하 이미지 압축<br/>• 불필요한 회원가입 필드")
        S2_Data("DATA (수집 데이터)<br/>• Bounce Rate 이탈률<br/>• Avg. Time 체류시간<br/>• Scroll Depth 스크롤 깊이<br/>• 상세페이지 조회수")
        S2_Clean("CLEAN (데이터 정제)<br/>• 체류시간 0초 세션 제외<br/>• 스크롤 중복 카운트 제거")
        S2_Docs("DOCS (기록 방법)<br/>• 03_Growth_Log UX실험<br/>• 히트맵 분석 결과")
        
        S2_Action --> S2_Refine --> S2_Data --> S2_Clean --> S2_Docs
    end

    %% 3단계: 구매
    subgraph Stage3 [3. 구매 단계 - Revenue]
        direction TB
        S3_Action("TO DO (해야 할 것)<br/>• 결제 버튼 시인성 강화<br/>• 장바구니 리마인드 메시지<br/>• 크로스셀링 상품 추천")
        S3_Refine("DELETE (정리 대상)<br/>• 복잡한 결제 주소 입력 단계<br/>• 품절 상품 노출 로직")
        S3_Data("DATA (수집 데이터)<br/>• CVR 구매전환률<br/>• AOV 객단가<br/>• 장바구니 포기율<br/>• 결제 단계별 이탈률")
        S3_Clean("CLEAN (데이터 정제)<br/>• 테스트 결제 취소 건 제외<br/>• 실결제 vs PG사 데이터 대조")
        S3_Docs("DOCS (기록 방법)<br/>• 04_Automation_Ops 매출집계<br/>• 일일 주간 매출 리포트")
        
        S3_Action --> S3_Refine --> S3_Data --> S3_Clean --> S3_Docs
    end

    %% 4단계: 재구매
    subgraph Stage4 [4. 재구매 단계 - Retention]
        direction TB
        S4_Action("TO DO (해야 할 것)<br/>• CRM 시나리오 설계<br/>• 리뷰 작성 자동 유도<br/>• VIP 등급 혜택 알림")
        S4_Refine("DELETE (정리 대상)<br/>• 오픈율 낮은 CRM 문구<br/>• 휴면 고객 데이터 분리")
        S4_Data("DATA (수집 데이터)<br/>• LTV 고객생애가치<br/>• 재구매율 및 재방문율<br/>• 리뷰 작성률<br/>• Churn Rate 이탈률")
        S4_Clean("CLEAN (데이터 정제)<br/>• 수신거부 유저 필터링<br/>• 중복 고객 DB 통합")
        S4_Docs("DOCS (기록 방법)<br/>• 02_CRM_Logic 세그먼트<br/>• 고객 인터뷰 VOC 기록")
        
        S4_Action --> S4_Refine --> S4_Data --> S4_Clean --> S4_Docs
    end

    %% 연결
    Stage1 --> Stage2 --> Stage3 --> Stage4

    %% 스타일 정의 (심플하게)
    classDef box fill:#fff,stroke:#333,stroke-width:1px,color:#000,rx:5,ry:5,text-align:left;
    class S1_Action,S1_Refine,S1_Data,S1_Clean,S1_Docs box;
    class S2_Action,S2_Refine,S2_Data,S2_Clean,S2_Docs box;
    class S3_Action,S3_Refine,S3_Data,S3_Clean,S3_Docs box;
    class S4_Action,S4_Refine,S4_Data,S4_Clean,S4_Docs box;
```


1 단계 : 유입 => 2 단계 : 활성화 => 3 단계 : 구매 => 4 단계 : 재구매

----
### 📂 관련 문서 바로가기

- [[01_Data_Taxonomy|📊 데이터 정의서 열기]]
- [[02_CRM_Logic|💌 CRM 시나리오 열기]]
- [[03_Growth_Log|⚗️ 그로스 실험 일지 열기]]
- [[04_Automation_Ops|🤖 자동화 성과 열기]]


[[바이트몰_광고 퍼널.canvas|바이트몰_광고 퍼널]]
[[바이트 50M 전략.canvas|바이트 50M 전략]]
