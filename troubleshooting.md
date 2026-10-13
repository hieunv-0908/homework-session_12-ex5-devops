\# Báo Cáo Chẩn Đoán Và Khắc Phục Sự Cố Pipeline CI/CD



\- \*\*Thư mục bài tập:\*\* `homework/session\_12/ex5/`

\- \*\*Tệp kịch bản:\*\* `.github/workflows/broken-pipeline.yml`



\---



\## Sự cố 1: Gradle Wrapper thiếu quyền thực thi (Permission Denied)



\### 1. Phân tích Log lỗi

\- \*\*Hiện tượng:\*\* Tiến trình build dừng tại bước chạy `./gradlew bootJar` với mã thoát `126`.

\- \*\*Log chi tiết:\*\*

&#x20; ```text

&#x20; /home/runner/work/\_temp/xxx.sh: line 1: ./gradlew: Permission denied

&#x20; Error: Process completed with exit code 126.

