# BTVN Session8_Ex2
## 1. Giới thiệu 
- **phân tích :** về sự khác nhau giữa get-childitem và select-string 
## 2. Phân tích
- Vấn đề của bạn An là nhầm lẫn giữa việc tìm file và lọc file và trường hợp này  là bạn đang muốn lọc file
## 3.Câu lệnh 
**so sánh:**
- Power shell: Get-childitem -Path "." | Select-String access.log "error"
- Git Bash: Find . -name "." | grep -i "error" access.log  
