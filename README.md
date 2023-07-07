<div dir=”rtl”>

# نصب پکیج با انسیبل

</div>
<div dir=”rtl”>

### توضیحات:
توی این پروژه خیلی ساده قصد دارم تا با استفاده از Ansible یک پکیج روی Remote Machin ها نصب کنیم، توی این پروژه فرقی نمیکنه که توزیع سیستم عامل Remote Machinها چی باشه (RedHat , Debian...)
</div>
<div dir=”rtl”>

### نحوه استفاده:
واسه استفاده از این playbook در قدم اول فایل hosts رو با دستور زیر باز کنید و آدرس IP یا HOSTNAME های سرورها یا Remote Machin های مورد نظر خود تون رو اضافه نمایید:
```

vi hosts
or
nano hosts
```

قدم دوم:
در دایرکتوری roles و در مسیر install-package > tasks فایل main.yml را باز کنید و نام پکیج های مد نظرتون رو وارد کنید:
```

vi roles/install-package/tasks/main.yml
```
حالا برای اجرای playbook دستور زیر رو اجرا کنید:
```

ansible-playbook playbook.yml
```
</div>
<div dir=”rtl”>

## با من در ارتباط باشید:


</div>

Project website:(https://github.com/alireza-fedora/install-package-with-ansible/)

Personal website:(https://fedorafans.com/author/alireza/)

Email: alireza.aghaee73@gmail.com

Linkdin: (https://www.linkedin.com/in/alireza-aghaie/)
