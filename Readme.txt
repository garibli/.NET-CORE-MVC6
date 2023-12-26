Şimdi projeyi lokalnize kurduğunuzda yapmanız gerekenleri tek tek listeleyeceğiz size.
Öncelikle postgresql kurmanız gerekiyor.
Daha sonrasında size listesini vereceğim. Paketleri uygulamanıza eklemeniz gerekiyor.
Bunun ardından. Eğer temiz kurulum yapmak istiyorsanız, bu dosyaları klasörlerin oluşturup. Dosyaların, klasörlerin oluşturduktan sonra migratelerini yapıp sonra controllerlarını ve viewlarını oluşturup benim size verdiğim dosyadaki gibi düzenlemeniz gerekiyor.
Ardından data klasörü içerisindeki seeddata adlı dosyanın içerisinde belirtilen alanları doldurmanız gerekiyor.
Benim size tavsiyem bir kaç tane migrate yapmanız bu migrate leri yaptıktan sonra da projeyi yavaş yavaş commit etmeniz.

Paketler:
6.0.25

Microsoft.AspNetCore.Authentication.JwtBearer
Microsoft.AspNetCore.Identity.EntityFrameworkCore
Microsoft.AspNetCore.Identity.UI
Microsoft.EntityFrameworkCore.Design
Microsoft.EntityFrameworkCore.Sqlite
Microsoft.EntityFrameworkCore.SqlServer
Microsoft.EntityFrameworkCore.Tools


Microsoft.VisualStudio.Web.CodeGeneration.Design – 6.0.16
Npgsql.EntityFrameworkCore.PostgreSQL – 6.0.22

Appsettings.json:

Database bağlantısı sağlanacak.


SeedData:

Mail adresinizi ve ad soyad bilgisi girmeyi unutmayın. Admin kullanıcısını burada oluşturacaksınız.
