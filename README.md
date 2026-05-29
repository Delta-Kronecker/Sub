# چند نکته مهم

در شرایط فعلی کانفیگ ها را در دسته های بیشتر از 100 عدد تست(real delay) نکنید چرا که همگی رد می شوند

<<<<<<< Updated upstream
اگر نتایح مطلوبی نگرفتید:
1. کلاینت خودتون رو بروز کنید
2. از یک کلاینت جایگزین استفاده کنید من [Throne](https://github.com/throneproj/Throne/releases/tag/1.1.4) را پیشنهاد می کنم در این برنامه می توانید تعداد تست همزمان کانفیگ و حداکثر زمان انتظار برای پاسخگویی را تایین کنید مقادیر 100 و 10,000(دقت کنید باید به هزار ثانیه وارد کنید) مناسب هستند، اگر امار کانفیگ های سالم پایین بود انها را 50 و 20,000 قرار دهید
=======
## در شرایط فعلی کانفیگ ها را در دسته های بیشتر از 100 عدد تست(real dealy) نکنید چرا که همگی رد می شوند

>>>>>>> Stashed changes

کانفیگ های sni را نمی توانید به شکل معمول استفاده کنید برای اموزش یا سرچ کنید یا اموزش من را از این لینک مشاهده کنید
[https://youtu.be/AcI7JdFCcjs](https://youtu.be/AcI7JdFCcjs)

برای استفاده صرف از تلگرام نیازی به اعمال system proxy یا tun mode نیست، سرعت اتصال را با این کار پایین نیاورد فقط کانفیگ را انتخاب کنید( روی ان کلیک و اینتر بزنید) سپس تلگرام را با پروکسی به برنامه متصل کنید یعنی به این موارد وصل شوید، برای v2rayN :
[https://t.me/socks?server=127.0.0.1&port=10808](https://t.me/socks?server=127.0.0.1&port=10808)
یا برای Throne:
[https://t.me/socks?server=127.0.0.1&port=2080](https://t.me/socks?server=127.0.0.1&port=2080)

در چنل تلگرام برای اطلاع از بقیه پروژه ها عوض شود:
[t.me/DeltaKroneckerGithub](https://t.me/DeltaKroneckerGithub)

<<<<<<< Updated upstream
و مهم تر از همه خواهشا هر پروژه ای که این روز ها ذره ای مفید بوده براتون رو حتما یه استار بدید حتی اگه یک ساعت درگیر ثبت نام سایت باشید، این کار مهمی هست که باید انجام بدیم چرا که انگیزه بزرگی برای توسعه دهنده خواهد بود و نتیجه ای انگیره هم دسترسی راحت تر و با کیفیت تر مردم ایران به اینترنت ازاد خواهد بود

جاوید ایران
=======
| Protocol | Count | Link |
|---|---|---|
| All | 510 | [all_configs.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/all_configs.txt) |
| VLESS | 260 | [vless.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/protocols/vless.txt) |
| VMESS | 34 | [vmess.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/protocols/vmess.txt) |
| SS | 143 | [ss.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/protocols/ss.txt) |
| TROJAN | 73 | [trojan.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/protocols/trojan.txt) |

---

## SNI

| Protocol | Count | Link |
|---|---|---|
| All | 510 | [all_configs_sni.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/sni/all_configs_sni.txt) |
| VLESS | 260 | [vless_sni.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/sni/protocols/vless_sni.txt) |
| VMESS | 34 | [vmess_sni.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/sni/protocols/vmess_sni.txt) |
| SS | 143 | [ss_sni.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/sni/protocols/ss_sni.txt) |
| TROJAN | 73 | [trojan_sni.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/sni/protocols/trojan_sni.txt) |

---

##V2ray Batches

| Batch | Count | Link |
|---|---|---|
| 001 | 500 | [batch_001.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/batches/v2ray/batch_001.txt) |
| 002 | 10 | [batch_002.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/batches/v2ray/batch_002.txt) |

## SNI Batches

| Batch | Count | Link |
|---|---|---|
| 001 | 500 | [batch_001.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/batches/sni_v2ray/batch_001.txt) |
| 002 | 10 | [batch_002.txt](https://github.com/Delta-Kronecker/V2ray-Config/raw/refs/heads/main/config/batches/sni_v2ray/batch_002.txt) |

## Statistics

| Protocol | Tested | Valid | Pass% |
|---|---|---|---|
| VLESS | 2192 | 260 | 11.9% |
| VMESS | 467 | 34 | 7.3% |
| SS | 304 | 143 | 47.0% |
| TROJAN | 245 | 73 | 29.8% |
| SSR | 10 | 0 | 0.0% |
| TUIC | 1 | 0 | 0.0% |
| **Total** | **3219** | **510** | **15.8%** |

| Metric | Value |
|---|---|
| Fetched | 4970 |
| Unique | 3219 |
| Valid | 510 |
| Time | 130.85s |

---

>>>>>>> Stashed changes
