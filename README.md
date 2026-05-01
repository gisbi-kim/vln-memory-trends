# 3세대 VLN/Embodied 메모리 동향 분석

> 2026년 4월 기준, 최근 arXiv 논문 5편을 중심으로 정리한 VLN/Embodied 메모리 연구 서베이.

**🌐 Live:** https://gisbi-kim.github.io/vln-memory-trends/

---

## 한 줄 요약

VLN/Embodied 메모리 연구는 2026년을 기점으로 **"어떻게 표현할까"(1세대) → "어떻게 LLM과 붙일까"(2세대) → "어떻게 운영할까"(3세대)** 로 패러다임이 바뀌었다. 표현은 commodity가 됐고, 분리·반성·망각·적응의 **정책**이 새로운 전장이다.

## 세대 구분

| 세대 | 시기 | 핵심 질문 |
|---|---|---|
| 1세대 | 2023~2024 | 어떻게 표현할까 |
| 2세대 | 2025 | 어떻게 LLM/VLM과 붙일까 |
| 3세대 | **2026~** | 어떻게 운영할까 |

## 다루는 5편

| 논문 | 핵심 답변 |
|---|---|
| **HIMM** (2026.02) | 메모리를 episodic / semantic으로 분리하라 |
| **RAGNav** (2026.03) | Retrieval에 spatial 구조를 넣어라 |
| **TuKA** (2026.03) | 가중치를 Tucker로 분해해 환경별로 적응하라 |
| **MetaNav** (2026.04) | 메타인지로 자기 전략을 점검하라 |
| **H-EMV** (2026.04) | 사용자에 맞춰 선택적으로 잊어라 |

## 분석 구성

1. **큰 그림** — 세대 구분과 3세대의 정의
2. **연대기** — ChatGPT(2022) → ReMEmbR(2024) → 5편(2026)으로 이어진 흐름
3. **4가지 축** — 분리 / 메타인지 / 망각 / reranking
4. **4분면 요약** — Data·Weights × Storage-time·Query-time
5. **5가지 트렌드** — 인지과학, LM-as-controller, spatial 유지, real-world 평가, personalization vs generalization
6. **빈 자리** — 아직 덜 탐색된 영역

## References

- ReMEmbR (arXiv:2409.13682, ICRA 2025) — 2세대의 분기점
- HIMM (arXiv:2602.15513)
- RAGNav (arXiv:2603.03745)
- MetaNav (arXiv:2604.02318)
- H-EMV (arXiv:2604.11306)
- TuKA (arXiv:2603.14276, ICLR 2026)

## 로컬에서 보기

```bash
git clone https://github.com/gisbi-kim/vln-memory-trends.git
cd vln-memory-trends
# index.html을 브라우저로 열기 (별도 빌드 불필요)
```
