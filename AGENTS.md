# AGENTS.md

本 repo（`115-programing`）為課程 115-1 電腦程式設計的程式碼庫，目前為空骨架：僅有 `README.md` 加上標準 Python `.gitignore`。

## 回應語言
- 所有回應一律使用繁體中文。

## Python 與套件管理
- 專案語言為 Python。
- 一律使用 conda 管理 Python 套件，不使用 `pip` / `venv` / `poetry` / `uv`。
- Conda 環境名稱為 `iem_python`；安裝、執行、驗證前先 `conda activate iem_python`（或以 `conda run -n iem_python` 執行）。

## 現況提醒
- 尚無原始碼、manifest（`pyproject.toml`、`requirements*.txt`、`environment.yml`）、lockfile 或 workspace 設定。
- 尚無 build、test、lint、formatter、typecheck、codegen、CI 或 task-runner 設定。勿預設有 `pytest`、`ruff`、`mypy`；使用前先確認實際加入的工具。
- 優先編輯既有檔案而非新建檔案；未經要求勿搭建文件、設定或範例目錄結構。
