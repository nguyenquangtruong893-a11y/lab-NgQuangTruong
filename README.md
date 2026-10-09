# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup

Prerequisites: Python 3.10+, Git.

```bash
git clone [https://github.com/nguyenquangtruong893-a11y/lab-NgQuangTruong.git](https://github.com/nguyenquangtruong893-a11y/lab-NgQuangTruong.git)
cd lab-NgQuangTruong
python -m venv .venv
# Windows PowerShell: .venv\Scripts\Activate.ps1
# macOS / Linux / Git Bash: source .venv/bin/activate
pip install -r requirements.txt
pip install -e .

## Run

python -m assistant "where is the IT helpdesk?"

## Test

pytest -q

## Project structure

src/ : Mã nguồn chính của trợ lý ảo.

tests/ : Các bài kiểm thử tự động (unit tests).

data/ : Dữ liệu mẫu (ví dụ: offices.csv).

docs/ : Tài liệu và các báo cáo bài tập lab.

scripts/ : Các tập lệnh hỗ trợ (như check_env.py).

.gitignore : Các file và thư mục bị bỏ qua bởi Git.
