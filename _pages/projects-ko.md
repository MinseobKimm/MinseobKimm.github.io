---
layout: archive
title: "프로젝트 설명"
permalink: /projects/ko/
author_profile: true
description: "Minseob Kim의 주요 프로젝트를 한국어로 소개합니다."
---

<p class="project-page-intro">
  주요 프로젝트의 목적과 설계 방향을 한국어로 정리한 페이지입니다.
</p>

<div class="project-grid project-grid--ko">
  <article class="project-card">
    <a href="https://github.com/MinseobKimm/paper-pilot">
      <img src="/images/projects/paper-pilot-attention.png" alt="Paper Pilot 리더 작업 화면" class="project-card__image" />
    </a>
    <div class="project-card__body">
      <p class="project-card__eyebrow">로컬 우선 연구 작업공간</p>
      <h2>Paper Pilot</h2>
      <p>
        Paper Pilot은 학술 PDF를 연구 흐름 안에서 읽기 위한 로컬 우선 Tauri 데스크톱 리더입니다.
        페이지 단위의 맥락을 유지하는 읽기 환경에 AI 번역, 로컬 RAG 기반 질의응답, 그림 설명,
        하이라이트, 요약, 인용 노트, 논문별 장기 기억을 결합했습니다. 논문을 가져오고, 문맥을
        놓치지 않은 채 읽고, 에이전트에게 질문하고, 유용한 결과를 원문 문서로 되돌려 저장하는
        연구 루프를 중심으로 설계했습니다.
      </p>
      <ul class="project-card__meta">
        <li>React + TypeScript + Tauri/Rust</li>
        <li>PDF.js 리더와 SQLite 기반 로컬 상태 관리</li>
        <li>BM25 스타일 검색과 교체 가능한 에이전트 브리지</li>
      </ul>
      <p><a href="https://github.com/MinseobKimm/paper-pilot">GitHub 저장소 보기</a></p>
    </div>
  </article>

  <article class="project-card">
    <a href="https://github.com/MinseobKimm/Locium">
      <img src="/images/projects/locium-knowledge-map.png" alt="Locium 지식 지도 화면" class="project-card__image" />
    </a>
    <div class="project-card__body">
      <p class="project-card__eyebrow">사람과 AI 에이전트를 위한 기억 시스템</p>
      <h2>Locium</h2>
      <p>
        Locium은 사람과 AI 에이전트를 위한 로컬 우선 기억 시스템입니다. 노트, 문서, 대화 기록,
        가져온 텍스트를 살펴볼 수 있는 작업공간으로 바꾸고, 사람이 읽기 쉬운 위키와 AI가 활용하기
        좋은 메모리 그래프를 함께 구성합니다. 출처를 추적할 수 있는 회상, 검토 큐, 되돌릴 수 있는
        상태 변경을 위한 append-only 저널을 통해 기억이 어디서 왔고 어떻게 바뀌었는지 확인할 수
        있도록 했습니다.
      </p>
      <ul class="project-card__meta">
        <li>React + Tauri 데스크톱 UI를 포함한 TypeScript 워크스페이스</li>
        <li>저널 기반 동기화 엔진과 위키/그래프 프로젝션</li>
        <li>출처와 최신성 신호를 제공하는 MCP 회상 도구</li>
      </ul>
      <p><a href="https://github.com/MinseobKimm/Locium">GitHub 저장소 보기</a></p>
    </div>
  </article>

  <article class="project-card">
    <a href="https://github.com/MinseobKimm/cf-workbench">
      <img src="/images/projects/cf-workbench-code.png" alt="CF Workbench Codeforces 연습 작업공간" class="project-card__image" />
    </a>
    <div class="project-card__body">
      <p class="project-card__eyebrow">로컬 경쟁 프로그래밍 워크벤치</p>
      <h2>CF Workbench</h2>
      <p>
        CF Workbench는 Codeforces 문제를 로컬에서 연습하기 위한 환경입니다. 문제를 가져오고,
        C++ 풀이 파일을 생성하며, 예제와 직접 만든 테스트를 실행하고, 개인 학습 진행 상황을
        추적할 수 있습니다. 문제 지문, 템플릿, 소스 파일, 테스트 케이스, 최근 제출 맥락을
        브라우저 기반 작업공간에 모으되, 대회 규칙의 경계를 지키는 방향으로 설계했습니다.
      </p>
      <ul class="project-card__meta">
        <li>Python 로컬 서버, 브라우저 기반 UI, Monaco editor</li>
        <li>토큰/공백 정리/완전 일치 비교 모드를 지원하는 C++ 컴파일 및 실행 파이프라인</li>
        <li>Codeforces API 연동과 선택적인 Chrome 확장 프로그램 워크플로</li>
      </ul>
      <p><a href="https://github.com/MinseobKimm/cf-workbench">GitHub 저장소 보기</a></p>
    </div>
  </article>
</div>

<div class="project-language-link">
  <a class="btn btn--inverse" href="/projects/">영문 프로젝트 페이지로 돌아가기</a>
</div>
