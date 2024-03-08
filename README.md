# GIIAN_TEST_PJ

https://emfagroup.larksuite.com/docx/BWO3d4HEQooPgUxUDvounQbPsib

# 1. Quy trình phát triển trên source code trên GIT: Branch và các quy tắc:
    - master: là branch chính và không được code trên nhánh này. T sẽ là người check mà merge lên nhánh master
    - staging: là branch kiểm thử cuối cùng, là nhánh chung sau khi đã xong nhánh của mình.
    - dev: là branch phát triển dùng để  kiểm thử các chức năng trên các branch module (trừ master, staging)
    - level branch (cao -> thấp) : master->staging->dev
    - quy tắc commit code:
      - commit code có mesage rõ ràng liên quan đến tính năng để dễ truy vết
      - commit đúng branch hiện tại đang triển khai code
    - vấn đề hợp nhất branch sau khi hoàn thành một tính năng trên branch module:
      - bước 1: đẩy code lên branch dev hiện tại -> branch dev sẽ merge staging -> kiểm thử trên staging -> hoàn thành (pass) -> chuyển bước 2
      - bước 2: branch staging sẽ merge dev hiện tại -> kiểm thử trên staging -> hoàn thành (pass) -> chuyển bước 3
      - bước 3: branch master sẽ merge staging -> hoàn thành (pass) sẽ chuyển bước 4, có lỗi sẽ tạo branch hotfix cho dev đó từ master và tiến hành lại bước 3 cho đến khi pass
      - bước 4: có thể (nên) xóa branch dev
    * lưu ý: 
      - không code trên các branch master, staging. Pull và Push code đúng theo branch đang triển khai để hạn chế conflict source code
      - sau khi kiểm thử , hợp nhất và chạy ổn định trên master nên xóa các branch dev để  hạn chế sinh quá nhiều branch

# 2. Quy định trong code
    - spaces tab: 4
    - biến: tên theo Camelcase, tránh tối nghĩa (có thể viết dài)
    - tạo file code hoặc module: 
      - hạn chế phân mảnh file, module nếu chỉ thực hiện một vài chức năng, ít tương tác
