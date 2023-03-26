Scaffold-DbContext "Server=localhost;Database=BlogMVC;User Id=sa;Password=123;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models
Scaffold-DbContext "Server=localhost;Database=BlogMVC;User Id=sa;Password=123;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models -Force

Scaffold-DbContext "Server=localhost;Database=MyStock;Integrated Security=true;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir DataAccess

Scaffold-DbContext "Data Source=localhost; Initial Catalog=BlogMVC; Integrated Security=True; Encrypt=True; TrustServerCertificate=True;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models -Force

Set Identity SQLServer bằng tay :
https://thuthuat.taimienphi.vn/cach-tao-kiem-tra-va-thay-doi-cot-identity-tren-microsoft-sql-server-31618n.aspx

Scaffold-DbContext "Data Source=localhost; Initial Catalog=MyStock; Integrated Security=True; Encrypt=True; TrustServerCertificate=True;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir DataAccess -Force

dotnet ef dbcontext scaffold "Server=(local);Database=MyStock;Integrated Security=true;" Microsoft.EntityFrameworkCore.SqlServer --output-dir DataAccess

"server=localhost;Database=PE_Fall21B5;uid=sa;password=123"
Scaffold-DbContext "server=localhost;Database=PE_Fall21B5;uid=sa;password=123;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models

dotnet ef dbcontext scaffold "server=localhost;Database=ZaloApp;uid=sa;password=123;Integrated security = True;Encrypt=True; TrustServerCertificate=True;" Microsoft.EntityFrameworkCore.SqlServer --output-dir Models