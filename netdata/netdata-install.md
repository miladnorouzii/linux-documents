= نصب netdata =

== مرحله اول ==
برای نصب netdata کامند "wget -O /tmp/netdata-kickstart.sh <nowiki>https://my-netdata.io/kickstart.sh</nowiki> && sh /tmp/netdata-kickstart.sh" رو که سایت [https://learn.netdata.cloud/docs/installing/ netdatata] گفته رو در ترمینال اجرا میکنیم و صبر میکینم تا نصب بشه.


== مرحله دوم ==
پس از اینکه اسکریپت netdata نصب شد به مروگر خود میریم و با توجه به اینکه netdata پیشفرض در پورت 1999 قرار میگیره با نوشتن ip-server:1999 داشبورد netdata رو باز میکنیم.



```bash
sh /tmp/netdata-kickstart.sh
```