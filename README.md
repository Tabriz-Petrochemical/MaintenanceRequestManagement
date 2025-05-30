# سیستم مدیریت درخواست‌های تعمیرات (Maintenance Request Management System)

سیستم مدیریت درخواست‌های تعمیرات به کارمندان این امکان را می‌دهد تا درخواست‌های تعمیراتی برای دستگاه‌ها یا تجهیزات خود ارسال کنند. این درخواست‌ها توسط تیم فنی بررسی می‌شود و وضعیت آن‌ها تغییر می‌کند (در حال بررسی، در حال انجام، تکمیل شده). سیستم همچنین امکان ارسال ایمیل‌های اطلاع‌رسانی به کارمندان و تیم فنی پس از هر تغییر وضعیت را فراهم می‌آورد.

این پروژه با استفاده از **.NET Core MVC** و **Entity Framework Core** برای دسترسی به پایگاه داده **SQL Server** پیاده‌سازی شده است.

## ویژگی‌ها

- **ارسال درخواست‌های تعمیراتی**: کارمندان می‌توانند درخواست‌های تعمیراتی برای دستگاه‌ها و تجهیزات خود ارسال کنند.
- **بررسی درخواست‌ها توسط تیم فنی**: تیم فنی درخواست‌ها را بررسی کرده و وضعیت آن‌ها را تغییر می‌دهد (در حال بررسی، در حال انجام، تکمیل شده).
- **ارسال پیامک به کارمند و تیم فنی**: پس از هر تغییر وضعیت در درخواست‌ها، پیامک های اطلاع‌رسانی به کارمند مربوطه و تیم فنی ارسال می‌شود.
- **امکان جستجو و فیلتر درخواست‌ها**: سیستم قابلیت جستجو و فیلتر درخواست‌ها بر اساس وضعیت، تاریخ، دستگاه و سایر معیارها را دارا می‌باشد.

## تکنولوژی‌ها

- **.NET Core 8 MVC**
- **Entity Framework Core** (EF Core)
- **SQL Server**
- **SMTP** برای ارسال ایمیل‌ها
- **Bootstrap 5** برای طراحی واکنش‌گرا
- **JavaScript** برای تعاملات کاربری

## پیش‌نیازها

قبل از شروع استفاده از این پروژه، اطمینان حاصل کنید که موارد زیر نصب و پیکربندی شده‌اند:

- **.NET Core SDK 8**
- **SQL Server** (میتونید از نسخه‌های SQL Server Express هم استفاده کنید)
- **Visual Studio** (برای توسعه و اجرای پروژه) یا **VS Code**

## نصب و راه‌اندازی

### 1. کلون کردن پروژه

برای شروع، پروژه را از GitHub کلون کنید:

```bash
git clone https://github.com/Tabriz-Petrochemical/MaintenanceRequestManagement.git
