# MT Evaluation Consistency Study (WMT 2021–2023)

This repository contains experiments investigating the **consistency of machine translation evaluation metrics** across different **domains** and **language pairs** using data from the WMT 2021, 2022, and 2023 Metrics Shared Tasks.

---

## 🌐 Project Goals

- Assess whether leading **MT evaluation metrics** (e.g., BLEU, COMET, BERTScore, MetricX-24) perform consistently across:
  - Different **language pairs**
  - Different **domains** (news, , , etc.)
- Compare metric performance with **human judgment** (DA/MQM correlation)
- Evaluate the **robustness and generalizability** of metrics over multiple years

---

## 📊 Selected Metrics

Metrics currently under evaluation:

- [x] COMET-22
- [x] COMET-KIWI
- [x] BLEURT-20
- [x] BERTScore
- [ ] xCOMET
- [ ] MetricX-24
- [ ] GPT-4 evaluator (if available)

See [`metrics/`](metrics/) for details on each.

---

## 📁 Repository Structure

```bash
MT_EvalMetri_Lab/
├── data/               # Raw and preprocessed WMT data
│   ├── wmt21/
│   ├── wmt22/
│   └── wmt23/
├── metrics/            # Scripts or wrappers for each metric
├── scripts/            # Data preprocessing and scoring scripts
├── notebooks/          # Jupyter notebooks for analysis and visualization
├── results/            # Output metric scores and comparison results
├── requirements.txt    # Python dependencies
└── README.md
