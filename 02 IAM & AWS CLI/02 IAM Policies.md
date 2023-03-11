# IAM Policies 

Người dùng được kế thừa police từ groups

# IAM policies Structure
<img width="485" alt="image" src="https://user-images.githubusercontent.com/54473576/224479001-f8980dfe-2c95-48ca-8771-733274c2955a.png">

- Version: policy language version
- Id: Nhận biết policies (optional)
- Statement: 1 hoặc nhiều statement (required)
  - Sid: mã định danh cho statement (optional)
  - Effect: ảnh hưởng của statement `allow` hoặc `deny`
  - Principal: user/role/account mà policy được áp dụng
  - Action: danh sách các action mà policy `allow` hoặc `deny`
  - Resource: danh sách các resource mà action được áp dụng
