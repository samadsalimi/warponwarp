
# وارپ آن وارپ جدید

جیسون اصلاح شده با دریافت آیپی از کاربران  
با عرض سلام این پروژه همون پروژه فایل جیسون وارپ آن وارپ هیدیفای هست که برای راحتی کاربرانی که به اشتباه کپی و پیست میکنن در فایل جیسون ایجاد شده است.
این فایل یک فایل پایتون هست که با آیپی تمیز و اکانت های کلود فلر باز کار میکند حالا چجوری؟

![JSON](https://img.shields.io/badge/JSON-000000.svg?style=for-the-badge&logo=JSON&logoColor=white)

![Android](https://img.shields.io/badge/Android-34A853.svg?style=for-the-badge&logo=Android&logoColor=white)

![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)

![termux](https://img.shields.io/badge/Linux-FCC624.svg?style=for-the-badge&logo=Linux&logoColor=black)

![Windows](https://img.shields.io/badge/Windows-0078D4.svg?style=for-the-badge&logo=Windows&logoColor=white)

![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020.svg?style=for-the-badge&logo=Cloudflare&logoColor=white)

![Private](https://img.shields.io/badge/Private%20Internet%20Access-1E811F.svg?style=for-the-badge&logo=Private-Internet-Access&logoColor=white)



## مرحله اول
توی ترموکس اسکریپت های زیر رو اجرا کنید.
برای دریافت آیپی تمیز وارپ کد اسکریپت زیر رو در ترموکس اجرا کنید.

bash <(curl -Ls https://raw.githubusercontent.com/MiSaturo/WarpScanner/main/point/endip.sh

یکی از آیپی تمیز ها رو همراه با پورت کپی کنید و در جایی ذخیره کنید.

توجه : اگر اسکریپت بالا جواب نداد میتونید CRTL را با C کیبورد بگیرید و از اسکریپت زیر استفاده کنید.

bash <(curl -fsSL https://raw.githubusercontent.com/Ptechgithub/warp/main/endip/install.sh)

## مرحله دوم
کد دوم برای ساخت اکانت وارپ:

curl -sL "https://api.zeroteam.top/warp?format=sing-box" | grep -Eo --color=never '"2606:4700:[0-9a-f:]+/128"|"private_key":"[0-9a-zA-Z\/+]+="|"reserved":\[[0-9]+(,[0-9]+){2}\]'

این اسکریپت رو برای ساخت اکانت وارپ اجرا کنید. (حواستون باشه برای وارپ آن وارپ باید دو بار اجرا کنید چون به دوتا اکانت احتیاج داریم)

و نرم افزار مارو در pyroid 3 یا نرم افزار های دیگه پایتون اجرا میکنید و مقادیر لازم رو وارد میکنید و بهتون کد جیسون وارپ آن وارپ هیدیفای رو نرم افزار ما میده.

## نکات
IPV6 رو بدون دبل کوتیشن کپی کنید.

همچنین پرایوت کی ها هم بدون " کپی کنید.
alikayh
علی کِی اِچ

فیلم آموزشی نصب ابزار در ترموکس اندروید 


https://youtube.com/@Kayhgng?si=2un57BMUUgD_mj0a


# کد های مراحل کامل آیپی تمیز و اکانت های وارپ و نصب ابزار ما در ترموکس


    apt update
    apt upgrade
    bash <(curl -Ls [https://raw.githubusercontent.com/MiSaturo/WarpScanner/main/point/endip.sh](https://raw.githubusercontent.com/MiSaturo/WarpScanner/main/point/endip.sh)
    اگر کد بش بالا کار نکرد از بش پایین استفاده میکنیم
    bash <(curl -fsSL [https://raw.githubusercontent.com/Ptechgithub/warp/main/endip/install.sh](https://raw.githubusercontent.com/Ptechgithub/warp/main/endip/install.sh))
    curl -sL "[https://api.zeroteam.top/warp?format=sing-box](https://api.zeroteam.top/warp?format=sing-box)" | grep -Eo --color=never '"2606:4700:[0-9a-f:]+/128"|"private_key":"[0-9a-zA-Z/+]+="|"reserved":[[0-9]+(,[0-9]+){2}]'
    pkg install git
    git clone https://github.com/kayhgng/warponwarp.git
    pkg install python
    ls
    cd warponwarp
    python warponwarpkayh.py


