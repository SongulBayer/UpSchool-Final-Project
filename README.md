# 🚀 UpSchool Full Stack Developer Bitirme Projesi

# ⚙️ Kullanılan Teknolojiler
* Asp .Net 7 ile Entity Framework Core
* Blazor
* CQRS Pattern
* Selenium
* SMTP
* CodeFirst yaklaşımı
* Clean Architecture

# Proje 6 Katmandan Oluşur:
* Domain
* Infrastructure 
* Application
* WebApi
* Wasm 
* Console

# 📝 Notlar
* Projede veritabanı olarak PostgreSql kullanılmıştır.
* Mailler her OrderEvent eklendiğinde gitmektedir.
* Projenin Front-End kısmı yakın zamanda eklenecektit.

# 📝 Projeyi Çalıştırmak İçin Gerekli Configurasyonlar
* FinalProject.WebApi projesi içerisindeki appsetting.json dosyası içerisinde gerekli düzenlemelerin yapılması gerekir.

` "ConnectionStrings": {
    "PostgreSQL": "User ID=***;Password=***;Host=***;Port=***;Database=UpSchoolProject;"
  }`
  
  * Projeyi çalıştırabilmek için Solution üzerinden Configure Startup Projects sekmesinden Multiple startup projects seçeneğini seçip FinalProject.WebApi, FinalProject.Console, FinalProject.Wasm projesini belirtilen sırada çalıştırmalısınız.




