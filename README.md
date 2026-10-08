# KPI.Web
Bản web hóa phần mềm Quản lý KPI C# WinForms hiện tại.

## Chạy local
1. Cài .NET 8 SDK.
2. Sửa `appsettings.json` với SQL Server của bạn.
3. Chạy `dotnet restore` rồi `dotnet run`.

## GitHub
Upload toàn bộ thư mục này lên repository GitHub. GitHub dùng để lưu source; để website chạy công khai cần triển khai ASP.NET Core lên một dịch vụ hosting (Azure App Service, Render, Railway, VPS...).

## CSDL
Giữ database `QuanLyKPI` hiện tại. Không đưa mật khẩu SQL Server hoặc chuỗi kết nối thật lên GitHub. Khi deploy, cấu hình connection string bằng biến môi trường/secret của hosting.
