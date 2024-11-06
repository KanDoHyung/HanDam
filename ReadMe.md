# 🍳 여행한담

삼성 청년 소프트웨어 아카데미 11기 특화 프로젝트

## 📚 목차

- [🍳 여행한담](#-여행한담)
  - [📚 목차](#-목차)
  - [🗓️ 프로젝트 개요](#️-프로젝트-개요)
    - [진행 기간](#진행-기간)
    - [팀 구성](#팀-구성)
  - [📢 서비스 소개](#-서비스-소개)
  - [🥳 서비스 설계](#-서비스-설계)
    - [기술 스택](#기술-스택)
    - [ERD](#erd)
    - [Wireframe](#wireframe)
    - [Architecture](#architecture)
    - [Docs](#docs)
  - [🤗 기능 소개](#-기능-소개)
    - [여행 성향 진단](#여행-성향-진단)
    - [맞춤 및 지역별 여행지 추천정보](#맞춤-및-지역별-여행지-추천정보)
    - [다른 사용자의 피드 검색 기능](#다른-사용자의-피드-검색-기능)
    - [사용자의 데이터 기반 여행계획 작성기능](#사용자의-데이터-기반-여행계획-작성기능)
    - [동행 구인](#동행-구인)
    - [마이페이지](#마이페이지)
  - [🚩핵심 기능](#핵심-기능)
  - [😆 느낀점](#-느낀점)

## 🗓️ 프로젝트 개요

### 진행 기간

- 2024.08.26 ~ 2024.10.11 (7주)

### 팀 구성


| 고도연 | 강동형 | 고충원 | 김민주 | 유재광 | 이상민 |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :-------------------------------------------------------------: | :-------------------------------------------------------------: |
| <img src="https://avatars.githubusercontent.com/u/156388715?v=4" width="100" height="100"> | <img src="https://avatars.githubusercontent.com/u/156388917?v=4" width="100" height="100"> | <img src="https://avatars.githubusercontent.com/u/156388848?v=4" width="100" height="100"> | <img src="https://avatars.githubusercontent.com/u/87603324?v=4" width="100" height="100"> | <img src="https://avatars.githubusercontent.com/u/65598179?v=4" width="100" height="100"> | <img src="https://avatars.githubusercontent.com/u/134148399?v=4" width="100" height="100"> |
| PM, FE | FE | FE | BE, Infra, AI | BE | BE |

## 📢 서비스 소개

[📎 서비스 소개 UCC](https://youtube.com/shorts/xfRjP9bi9n4)

 **"여행한담"** 은 여행일정을 짜는데 도움을 주는 웹서비스입니다. 여행계획을 구성할 때, 정보의 과부화, 시간 소모 등 사용자의 피로를 덜어주기 위해 개발되었습니다. 가벼운 성향테스트를 통해 내 여행 성향을 파악할 수 있고, 다른 사용자의 피드 게시물을 보고 좋아요와 댓글 등의 소통을 할 수 있는 SNS 기능을 겸하고 있습니다. 좋아요를 누른 피드 데이터를 기반으로 사용하기 쉬운 여행 계획 수립 및 자동맞춤 여행일정 수립 기능을 보유하고 있습니다.

## 🥳 서비스 설계

### 기술 스택

|               | Front                                   | Back                                     | AI                       |
| ------------- | --------------------------------------- | ---------------------------------------- | ------------------------ |
| **Language**  |    JavaScript(ES6+), TypeScript        |            Java17                         |          python          |
| **IDE**       |       Visual Studio Code             |             IntelliJ                        |        Jupyter Lab       |
| **Framework** |         React, Vite                   | Spring Boot, Fast API, Spark | Pytorch, fastAPI               |
| **Library**   | intersection-observer, daum-postcode, sweetalert2, tailwind, storybook    ||  transformers, diffusers, boto |   

| DB           |               CI/CD              |        Tools         |
| :----------- |  :-----------------------------: | :------------------: |
| MySQL, Hadoop, Redis, Elasticsearch | Jenkins, Docker, Dockerhub, Mattermost | GitLab, Jira, Notion, RestDoc |

### ERD

![ERD](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbiTDvs%2FbtsJ2uIzU9k%2F1pkZZWV6hMqXEmzdyayx30%2Fimg.png)

### Wireframe

[📎 Figma Link](https://www.figma.com/design/CCGP6nyPBqx6LpUE4uEP3M/%ED%94%8C%EB%A1%9C%EC%9A%B0%EC%B0%A8%ED%8A%B8?node-id=19-2&node-type=canvas&t=spQ9HQoCBojIyKx0-0)

![화면설계](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FvIZvK%2FbtsJ0et1JBG%2Fb7MOijr6SrEI9Y6DaysykK%2Fimg.png)

### Architecture

![아키텍쳐 구성도](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbNFwpM%2FbtsJ17Aae4V%2FCKp290W72UZNlrfqi5jxH1%2Fimg.png)

### Docs

[📎 API](https://versed-dragonfly-804.notion.site/API-f13725999d6049449807479bf6f0dddd)  
[📎 기능 정의서](https://versed-dragonfly-804.notion.site/9a8edc1bf92f406fb69b82e39a47a72f?pvs=4)

## 🤗 기능 소개
### 여행 성향 진단

<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbdX5jc%2FbtsJ0dIRkZi%2FLZUNeTkxldO1LXycXion5k%2Fimg.png" width="300" height="500"> | <img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fb7HPhB%2FbtsJ102mgX5%2F29tjb6ZAS1DwrMWpfPnFA1%2Fimg.png" width="300" height="500">
<br>
<ul>
<li>
  간단한 진단 문항을 통해 사용자의 성향을 진단하고 진단 결과에 따라 16가지 결과물을 사용자에게 보여줍니다. <li>진단 과정에서 사용자에게 입력을 받아 사용자의 좋아요 데이터 기본값을 설정하도록 합니다.
</ul>

### 맞춤 및 지역별 여행지 추천정보
<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2F9xjc2%2FbtsJ2mqqAbH%2FZQ0RFiaJw3UCc8PHpBs8g1%2Fimg.png" width="500" height="250"> | <img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2F7gg2O%2FbtsJ1GC5sNQ%2FWjdcKNW11XxsX3G3UXXhc1%2Fimg.png" width="500" height="250">
<li>맞춤여행지들이 추천되고, 핫플여행지, 지역별 여행지, 축제 정보등을 표시합니다.
</li>

### 다른 사용자의 피드 검색 기능
<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FpUasD%2FbtsJ3a4g4i6%2FNJKj48q16olfBKvwD2OQ01%2Fimg.png" width="500" height="250"> | <img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2F9rBwM%2FbtsJ178slZS%2FTDDXJf7eQcQBg8TdAFL5a1%2Fimg.png" width="400" height="150">
<br>
<ul>
  <li>탐색페이지에서 자신의 여행유형과 좋아요한 피드들을 기준으로 여행지가 추천됩니다.
  <li>이 탐색페이지는 자신과 비슷한 유형의 사용자가 좋아요한 피드위주로 추천됩니다.
  <li>사용자 검색 후 팔로우 기능을 할 수 있고, 피드검색도 가능합니다.
</ul>

### 사용자의 데이터 기반 여행계획 작성기능
<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2F1N8ax%2FbtsJ1e8i8M9%2FbjOt08UVFRbRPyxnV276U0%2Fimg.png" width="500" height="250"> | <img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fbgy4tb%2FbtsJ2QSJUuN%2FSyKPzZWvz0OK1kb2b0dtQ0%2Fimg.png" width="500" height="250">
<ul>
  <li>자신이 좋아요 한 데이터들은 여행 계획 페이지에서 클러스터링을 거쳐 군집화됩니다.
  <li>군집화 된 목록을 누르면 해당좋아요를 포함해서 자동으로 일정을 생성합니다.
  <li>장소를 검색하여 일정에 가고싶은 곳을 추가하여 수정할 수 있습니다.
  <li>하단 바에서 군집 중심에서 주변 장소들을 추천해줍니다.
  <li>여행일정을 저장되고 일정 상세페이지를 확인할 수 있습니다.
</ul>

### 동행 구인
<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbHhLb0%2FbtsJ2Xxt6CB%2FSY1sIeZoZwG94EjzRDj5kk%2Fimg.png" width="500" height="250">
<ul>
  <li>동행 구인글들을 확인할 수 있고 제 일정을 공유하면 동행 구인글을 작성할 수 있습니다.
  <li>게시된 게시물을 클릭하면 다른 사용자의 여행일정이 보입니다.
</ul>

### 마이페이지
<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FcwulPj%2FbtsJ28ZOO5I%2FdV0wH2AFcUdcZKSg1Xfc3k%2Fimg.png" width="500" height="320">
<li>
마이페이지에는 제가 작성한 피드, 좋아요목록 동행 게시글, 포토카드등을 확인할 수 있습니다.
</li>

## 🚩핵심 기능

<ol>
  <li>Kafka, Hadoop, Spark를 통한 주기적인 피드 추천 적용
    <ul>
      <li>배치 처리: Cron을 활용하여 정기적인 배치 처리로 피드 추천 시스템을 실행합니다.</li>
      <li>협업 필터링: 사용자 기반 협업 필터링을 적용하며, 좋아요 이벤트에 시간 가중치와 사용자 특성을 반영하여 추천 품질을 향상시켰습니다.</li>
      <li>추천 캐싱: 추천된 피드는 Redis에 캐싱되어, 빠른 응답성을 위해 TTL을 적용하고 있습니다.</li>
    </ul>
  </li>
  <li>Kafka를 통한 최근 활동 사용자 수집
    <ul>
      <li>추천 최적화: 최근에 활동한 사용자만을 대상으로 추천 피드를 생성하여, 불필요한 계산을 줄이고 효율적인 추천 기능을 제공합니다.</li>
    </ul>
  </li>
  <li>WebSocket을 활용한 실시간 채팅
    <ul>
      <li>Stomp 프로토콜을 사용하여 안정적이고 실시간성 높은 채팅 서비스를 구현했습니다.</li>
    </ul>
  </li>
  <li>ElasticSearch를 활용한 빠른 피드 검색
    <ul>
      <li>거리 기반 검색: ElasticSearch를 활용해 거리 기반의 가까운 피드를 빠르게 검색할 수 있습니다.</li>
      <li>데이터 동기화: Partial Update를 통해 DB와 ElasticSearch 간의 데이터 동기화를 유지하고, 서버 실행 시 전체 데이터 동기화를 수행합니다.</li>
    </ul>
  </li>
  <li>동시성 제어
    <ul>
      <li>동시 요청 처리 개선: 동시 요청자 100명 기준으로, 요청 실패율을 28%에서 0%로 감소시키는 데 성공했습니다.</li>
      <li>부하 테스트: Locust를 사용하여 서버 부하 테스트를 수행하고 최적화를 진행했습니다.</li>
    </ul>
  </li>
  <li>포토카드 생성
    <ul>
      <li>BLIP image captioning, OWL-ViT zero-shot object detection, Pix2Pix image to image translation 모델을 활용해 사용자들이 올린 피드 이미지로 고유한 포토카드를 생성할 수 있도록 기능을 구현했습니다.</li>
    </ul>
  </li>
  <li>MSA 구조의 CI/CD 파이프라인 구축
    <ul>
      <li>독립적 파이프라인: 각 서버별로 독립적인 CI/CD 파이프라인을 구축하여 개발과 배포의 효율성을 극대화했습니다.</li>
      <li>자동 알림: 배포 성공 시 MM 알람을 통해 팀원들에게 자동으로 공지하여 생산성을 향상시켰습니다.</li>
    </ul>
  </li>
  <li>네트워크 처리 요청 장치 적용
    <ul>
      <li>토큰 버킷 알고리즘: Spring Cloud Gateway에 토큰 버킷 알고리즘을 적용하여 네트워크 요청 처리를 효율적으로 관리하고 있습니다.</li>
    </ul>
  </li>
  <li>실시간 좋아요 데이터 스트리밍 파이프라인 설계
    <ul>
      <li>Spark Streaming을 활용해 실시간으로 좋아요 데이터를 스트리밍 처리하여 최신 데이터를 반영합니다.</li>
    </ul>
  </li>
  <li>군집화 알고리즘 적용
    <ul>
      <li>DBSCAN 알고리즘을 사용해 사용자 좋아요 데이터를 군집화하여, 비슷한 성향의 사용자를 묶고 그에 맞춘 피드 추천을 제공합니다.</li>
      <li>데이터 캐싱: 캐시 미스와 히트 개념을 도입하여 데이터 조회 속도를 높였습니다.</li>
    </ul>
  </li>
</ol>

## 😆 느낀점

<table>
  <tr>
    <th rowspan="3">Front</th>
    <td>고도연</td>
    <td>
        <strong>[페이지 간 상태 전달]</strong><br>
        React Router의 <code>useLocation</code>과 <code>state</code>를 사용해 페이지 이동 시 상태를 전달하고, 필요한 데이터를 정확하게 받아오는 방법을 익혔습니다. 이 과정에서 상태 관리를 적절히 사용하는 것이 중요함을 다시 확인했습니다.
        <br><br>
        <strong>[FormData 직렬화와 Blob 사용]</strong><br>
        FormData 직렬화와 Blob 사용에 대해선, JSON 데이터를 서버로 전송할 때 정확한 데이터 형식 지정의 필요성을 깨달았습니다. JSON 데이터를 Blob으로 변환해 <code>application/json</code> 타입을 지정함으로써 서버와의 통신에서 발생할 수 있는 오류를 방지할 수 있었습니다.
        <br><br>
        <strong>[데이터 갱신과 리렌더링]</strong><br>
        POST 요청 후 GET 요청을 통해 데이터를 갱신하는 과정에서 컴포넌트가 의도한 대로 리렌더링되지 않는 문제를 해결했습니다. 이를 위해 <code>useEffect</code>와 상태 변화를 감지하는 <code>reload</code> prop을 활용해 데이터를 새로 불러오는 방식을 채택했으며, 리렌더링의 트리거를 명확히 정의하는 것이 유지보수에 용이하다는 것을 느꼈습니다.
        <br><br>
        <strong>[React 컴포넌트 재사용과 리렌더링]</strong><br>
        React가 탭 전환 시 성능 최적화를 위해 컴포넌트를 재사용하는 방식에 대해 이해하게 되었습니다. 기본적으로 컴포넌트가 언마운트되지 않는 특성을 활용하는 방법을 익혔고, 필요에 따라 <code>key</code> 속성을 변경해 특정 탭 전환 시 컴포넌트를 리마운트하는 방법도 배웠습니다. React의 최적화 원리를 이해함으로써 적절한 시점에 리렌더링을 제어하는 능력이 향상되었습니다.
        <br><br>
        이 경험을 통해, 문제를 해결하기 위해선 React의 기본 동작과 상태 관리에 대한 이해가 필수적임을 다시 한번 깨달았습니다. 이를 통해 더 나은 사용자 경험을 제공하는 방법을 찾을 수 있었습니다.
    </td>

    
  </tr>
  <tr>
    <td>강동형</td>
    <td>
    새로운 기능을 많이 배워보려고 노력했고, 한 층 더 개발자로 성장했습니다. 그러면서 필요하지 않은 기능을 사용하는 것은 프로젝트가 무거워질 뿐이라 프로젝트도 최적화와 같은 다이어트가 필요하다는 것을 알게되는 과정이었습니다.<br>
    CSS와 업무관련 갈등이 조금 있었습니다. 맡은 업무를 수행했는데 사용하지 않은 경우도 종종 있었고, 디자인 측면에서도 서로 추구하는 바가 달라 조율하는데 작은 소음이 있었습니다.<br>
    프로젝트를 작성할때, 이번에는 상태관리 변수를 적극적으로 활용하지 않았습니다. 프로젝트가 규모가 조금 작고, PropsDrilling의 깊이도 낮아서 괜찮았지만, 다음에는 적극적으로 활용해야 겠다고 느꼈습니다.<br>
    시작할때는 최대한 깔끔하게 프로젝트를 작성해야 겠다고 생각했지만, URL이 바뀌지 않으면서 페이지 렌더링을 바꾸려고 하다보니 분기처리 과정에서 코드가 길어지고 가독성이 떨어졌습니다. 프로젝트의 막바지 즘에 따로 컴포넌트를 내부에서 분리해서 본 코드의 길이를 줄이는 방법을 사용했었는데, 다음 프로젝트에서는 이 방법을 일찌감치 사용해서 훨씬 클린한 코드를 작성하는 것을 목표로 하고 싶습니다.
    </td>
  </tr>
    <tr>
    <td>
     고충원
    </td>
    <td>
    이번 프로젝트에서 가장 중요하게 생각했던 점은 팀원들과의 협업 능력이었습니다. 이전 프로젝트에서는 첫 팀 프로젝트였기 때문에 팀원들과의 협업과 커뮤니케이션이 부족했고, 
    서로의 의견을 조율하고 각자의 코드를 이해하며 하나의 결과물을 만들어가는 과정이 쉽지 않았습니다.
    <br>
    그래서 이번 프로젝트에서는 소통을 더욱 강화해 팀원들과 의견을 잘 조율하기 위해 노력했습니다. 이를 위해 세 가지 방안을 실천했습니다.
    <br>
    첫째, 코드 리뷰 문화와 코딩컨벤션을 적극적으로 활용했습니다. 
    코드 리뷰를 통해 서로의 코드를 이해하고, 개선할 수 있는 피드백을 주고받으면서 코드 품질을 높일 수 있었습니다. <br>
    특히, 팀원들과 코딩 컨벤션을 정하고 이를 지키기 위해 노력했습니다. 
    이를 통해 팀원 간의 코드 스타일을 통일하고, 코드의 일관성을 유지할 수 있었습니다. 
    코드 리뷰 과정에서는 각자의 로직을 파악하며, 사전에 오류를 발견하고 수정함으로써 더욱 견고한 코드를 작성할 수 있었습니다.
    <br>
    둘째, 스토리북(Storybook)을 사용하여 컴포넌트 단위로 UI를 독립적으로 개발하고 테스트할 수 있었습니다. 
    팀원들과 UI 변경 사항을 쉽게 공유하고, 즉각적으로 피드백을 받아 반영할 수 있어 개발 속도와 품질을 동시에 향상시킬 수 있었습니다.
    <br>
    셋째, 프로젝트 초기에 파일 구조를 잘 설계하기위해 노력했습니다. 
    이전 프로젝트에서는 자바스크립트를 사용했지만, 이번 프로젝트에서는 타입스크립트를 도입해 더 견고하고 효율적인 파일 구조를 설계했습니다. 
    타입스크립트를 활용한 덕분에 코드의 안정성과 가독성이 크게 향상되었고, 코드 작성 시 타입 오류를 사전에 방지할 수 있었습니다. 
    이러한 구조적 설계 덕분에 프로젝트 관리가 수월해졌습니다.
    <br>
    이번 프로젝트에서 쌓은 협업 경험과 기술적인 성장 덕분에, 앞으로 더 복잡하고 큰 프로젝트에서도 팀원들과 원활하게 소통하며, 
    견고한 코드를 작성할 수 있는 개발자가 될 자신감을 얻었습니다. 이 경험은 저의 개발자로서의 성장에 큰 자산이 될 것입니다.</td>
  </tr>

  <tr>
    <th rowspan="3">Back</th>
    <td>김민주</td>
    <td>
    [MSA 아키텍처와 CI/CD 구축을 통한 개발 경험]<br>
    이번 프로젝트에서 MSA(Microservice Architecture) 아키텍처 기반의 애플리케이션을 개발하며 Jenkins와 Docker를 활용하여 CI/CD 파이프라인을 구축하였습니다. 이를 통해 CI/CD의 편리함을 확실히 깨닫게 되었고, 개발 및 배포 과정에서 큰 도움을 받았습니다. 특히 애자일(Agile) 개발 방법론을 적용하는 과정에서 CI/CD는 필수적인 요소임을 체감했습니다.
    <br>
    <br>
    [CI/CD의 효과]<br>
    CI/CD를 구축한 덕분에 코드의 변경이나 새로운 기능 추가가 매우 유연하고 간단해졌습니다. 수동 배포에서 발생할 수 있는 오류를 줄이고, 새로운 기능을 신속하게 배포할 수 있었습니다. 이는 개발 속도 향상뿐만 아니라, 다양한 테스트 자동화를 통해 코드의 품질을 유지하는 데에도 큰 도움이 되었습니다. 특히 개발 도중 새로운 방향으로 프로젝트의 목표를 수정하거나 기능을 추가해야 할 때에도 큰 어려움 없이 유연하게 대응할 수 있었습니다.
    <br>
    <br>
    [코드 컨벤션의 중요성]<br>
    이번 프로젝트에서는 작성한 클래스 파일의 양이 이전 프로젝트에 비해 훨씬 많았지만, 팀원들과 코드 컨벤션을 잘 지켜가며 협업한 덕분에 코드 관리가 수월했습니다. 통일된 코드 스타일 덕분에 다른 팀원이 작성한 코드를 이해하는 데 혼동이 없었고, 이로 인해 협업 과정에서 발생할 수 있는 문제를 최소화할 수 있었습니다. 이를 통해 코드 컨벤션의 중요성을 다시 한 번 깨닫게 되었습니다.
    <br>
    <br>
    [AI 모델 적용에서의 도전과 해결]<br>
    특히 포토카드 기능에서는 객체 탐지(Object Detection) 모델을 활용해야 했는데, 학습하지 않은 객체를 탐지하지 못하는 문제가 발생했습니다. 이러한 문제는 'zero-shot object detection'과 'image captioning' 기법을 활용하여 어느 정도 해결할 수 있었습니다. 이 과정에서 AI 모델의 한계를 파악하고, AI 기술을 어떻게 활용하면 문제를 해결할 수 있는지에 대해 깊이 고민하게 되었습니다. AI 모델에서 발생할 수 있는 문제를 다른 AI 기술로 해결하는 경험은 매우 인상 깊었으며, AI에 대한 더 깊은 지식이 다양한 문제 해결에 도움될 수 있음을 느꼈습니다.
    <br>
    <br>
    [결론]<br>
    이번 프로젝트를 통해 CI/CD의 중요성과 AI 기술을 프로젝트에 적용하는 과정에서의 도전과 해결 방식을 배우게 되었습니다. 또한, 팀원들과의 원활한 협업을 위해 코드 컨벤션을 지키는 것이 얼마나 중요한지 다시금 깨달을 수 있었습니다. 이러한 경험은 앞으로의 개발 과정에서 많은 도움이 될 것으로 생각됩니다.
    </td>
  </tr>
  <tr>
    <td>유재광</td>
    <td>
    프로젝트를 진행하면서 에러 핸들링과 테스트의 중요성을 깊이 느꼈습니다. 안정적인 시스템을 구축하기 위해서는 철저한 에러 관리와 체계적인 테스트가 필수적임을 깨달았습니다. 
    <br>
    또한 협업, 최적화, 그리고 시간 관리의 중요성도 크게 인식하게 되었습니다. 팀원들과의 원활한 소통과 역할 분담을 통해 효율적으로 문제를 해결할 수 있었으며, 성능 최적화를 통해 시스템의 효율성을 높이는 방법을 학습했습니다. 
    <br>
    더불어, 마감일을 준수하기 위해 체계적인 시간 관리가 프로젝트의 성공에 결정적인 역할을 한다는 점을 느꼈습니다. 이러한 경험들은 앞으로의 프로젝트에서도 많은 도움이 될 것 같습니다.</td>
  </tr>

  <tr>
    <td>이상민</td>
    <td>
    </td>
  </tr>
</table>
