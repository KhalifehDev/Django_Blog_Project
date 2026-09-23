# Django Blog Project

این پروژه یک وبلاگ ساده با Django است که به عنوان تمرین جلسات آموزشی Django ساخته شده است.

## امکانات پروژه

- ساخت مدل `Post`
- وضعیت پست‌ها به صورت `Draft` و `Published`
- مدیریت پست‌ها از طریق Django Admin
- نمایش لیست پست‌های منتشرشده
- نمایش صفحه جزئیات هر پست
- استفاده از `slug` در URL
- استفاده از Template Inheritance
- استفاده از Static Files و CSS
- ایجاد Migration برای مدل‌ها
- استفاده از Custom Manager برای پست‌های منتشرشده

## ساختار کلی پروژه

```text
Django_Blog_Project
│
├── blog
│   ├── migrations
│   ├── static
│   ├── templates
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
│
├── weblog
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── manage.py
├── requirements.txt
├── .gitignore
└── README.md
