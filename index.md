---
layout: homepage
title: 홈
---

<style>
    @media screen and (orientation: landscape) {
        .buttons {
            flex-direction: row;
            justify-content: space-between;
        }
        
        .buttons button {
            width: 240px;
        }
    }

    @media screen and (orientation: portrait) {
        .buttons {
            flex-direction: column;
        }

        .buttons button {
            width: 100%;
            margin: 6px auto;
        }
    }
    
    .buttons {
        display: inline-flex;
        width: 100%;

        margin-top: 24px;
    }

    .buttons button {
        font-family: "Galmuri7", "GalmuriMono7", "Noto Sans", "Twemoji Mozilla", "Noto Emoji", Arial, Helvetica, sans-serif;

        height: 160px;
    
        background-color: #fcfcfc;
        background-size: cover;
        background-position: center;

        border: 4px solid #9088ff;
        border-radius: 8px;
    }

    .home-globallaw {
        background-image: url("assets/img/buttons/home-globallaw.png");
    }

    .home-worlds {
        background-image: url("assets/img/buttons/home-worlds.png");
    }

    .home-characters {
        background-image: url("assets/img/buttons/home-characters.png");
    }
</style>

# ARCASPAI: Universe Guidebook

**아르카스페이: 세계관 가이드북**에 오신 것을 환영합니다.

- [구 사이트](https://arcaspai.notion.site/ARCASPAI-Universe-Guidebook-2978e3302cae817fa3c9eb88d7c00ce8)는 페이지 이전 완료로부터 한 달 후에 비공개로 전환됩니다.
    - 페이지 이전 완료: <time datetime="2026-05-26">2026년 5월 26일</time>
    - 구 사이트 비공개 전환(예정): <time datetime="2026-06-26">2026년 6월 26일</time>

<div class="buttons">
    <a href="/universe/global-law">
        <button class="home-globallaw">
            전역 법칙
        </button>
    </a>
    <a href="/universe/worlds">
        <button class="home-worlds">
            세계관
        </button>
    </a>
    <a href="/universe/characters">
        <button class="home-characters">
            캐릭터
        </button>
    </a>
</div>
