# Research Log

## Day 1
- Finalized project architecture.
- Compared AIR-RAG, PentaRAG, Enterprise QA paper.

---

## Experiment 1
Objective:
Compare Fixed Top-K vs Dynamic Top-K.

Dataset:
HR Policies (120 PDFs)

Results:
- Faithfulness: 0.81 → 0.89
- Latency: +12%
- Tokens: -18%

Conclusion:
Dynamic Top-K improves answer quality while reducing context size.

---

## Ideas

- Add query decomposition?
- Add adaptive chunk size?
- Try BGE reranker.