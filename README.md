# Merlinx-Android-13-Adb-Sideload-Rom-Installation-Guide-

Redmi note 9 için ADB Sideload Yöntemiyle Rom Yükleme Rehberi

NOT: Bazı cihazlarda twrp yüklenmesi sonucu dokunmatik çalışmaması ve siyah ekran sorunları oluşmaktadır. Bu sorunları göze alarak twrp kurmayı deneyiniz.
Yapacağınız işlemlerde bütün sorumluluk size aittir. Oluşabilecek sorunlardan şahsım ve "TurkDevs.com" sorumlu tutulamaz.


Lütfen Başka Forumlarda Veya Platformlarda İznim Olmadan Paylaşmayınız.

Bu anlatım Redmi note 9 için android 13 project elixir, lineage os, crdroid vb.uyumlu romlarda çalışır.
(Android 12 vendor isteyen pixel experience ve pixelplus uı romlarında bu yöntem çalışmaz.)

Mıuı v12.5.4.0 sürümü vendor gereklidir.

https://xiaomifirmwareupdater.com/miui/merlin/stable/V12.5.4.0.RJOMIXM/

Miflash tool ile Mıuı v12.5.4.0 sürümünü yüklüyoruz. sonra aşağıdaki linkteki crdroid recovery dosyasını indiriyoruz ve recovery dosyasını ve kuracağınız custom rom dosyasını(project elixir) Minimal ADB and Fastboot aracının kurulu olduğu dizine atıyoruz.

ProjectElixir-3.4-merlinx-13.0-20221228-1840-OFFICIAL.zip dosyasını aşağıdaki linkten indiriyoruz.

https://www.pling.com/p/1813228/


Sonra telefonu fastboot moda alıyoruz ve aşağıdaki komutlarını yazıp entera basıyoruz.


...

fastboot flash recovery crdroid_recovery.img

...

