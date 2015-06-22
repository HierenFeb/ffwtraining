# ffwtraining
FFW training

1. Clone and rename *base* folder to *yourfolder*
2. Create sub task on intranet
*Work proccess*
* Chuyển trạng thái của task -> inprogress
* git branch (để liệt kê và kiểm tra xem mình đang ở branch nào)
* Tạo branch: IdTask_ten_task (đảm bảo là đang đứng ở branch master)
> > * git branch tenbranch 
> > * git checkout tenbranch
hoặc
> > * git checkout -b tenbranch
* Working
> > * git commit -a -m “[#IDtask] Viec da lam”
> > * git push -u origin tenbranch
* vào github tạo Pull request (cần chắc chắn là pull request đó là giữa branch mình đang làm với branch master)
* Vào redmine chuyển trạng thái task đang làm sang “needs review”, assign cho ng review và comment link của Pull request vừa tạo bên trên, logtime
