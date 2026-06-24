# Data Files Guide / 数据文件说明

This project contains two different kinds of files. Do not confuse them.

## A. Protocol templates / future data dictionaries

These files define how a future study should record data. They are **not collected static-pause data**.

- `data_schema.csv` — future protocol data dictionary / field template.
- `stimulus_sheet_template.csv` — future sound-probe documentation template.
- `protocol_brief.md` / `protocol_brief_zh.md` — protocol brief drafts.
- `safety_flow.md` / `safety_flow_zh.md` — safety interaction flow drafts.

## B. Preliminary Pause-QDR data / actual derived preliminary data

These are the files to open if you want the preliminary 静坐 / pause data.

- `pause_qdr_preliminary_summary.csv` — anonymized derived numeric/categorical summary of the static-pause sessions.
- `pause_qdr_preliminary_dataset.md` — English interpretation and correct positioning of the Pause-QDR dataset.
- `pause_qdr_preliminary_dataset_zh.md` — Chinese interpretation and correct positioning of the Pause-QDR dataset.
- `pause_qdr_limitations.md` — limitations and correct use.
- `pause_qdr_codebook.md` — preliminary qualitative coding sketch.

## Important distinction

`data_schema.csv` is **not** the 静坐 data.

The actual static-pause preliminary summary is:

`pause_qdr_preliminary_summary.csv`
