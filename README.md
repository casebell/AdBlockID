[![git](https://img.shields.io/badge/Update%20via-GitHub%20Desktop-663399.svg?style=popout-square&logo=github)](https://gitforwindows.org)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/python-abp.svg?logo=python&style=popout-square)

# AdBlockID

Total rules: 14,388

AdblockID adalah filter tambahan untuk melengkapi [EasyList](https://github.com/easylist/easylist) dan [AdguardFilters](https://github.com/AdguardTeam/AdguardFilters) yang dirancang secara khusus untuk menghilangkan iklan (terutama iklan yang bermuatan konten dewasa) pada website di Indonesia.


## Manfaat Yang Anda Dapatkan
1. **No Iklan**: menghilangkan iklan, terutama iklan yang bermuatan konten dewasa.
2. **Block popads**.
3. **Block [crypto mining scripts](https://www.mycryptopedia.com/crypto-mining-scripts/)**.
4. **Speed you need:** mengurangi waktu pemuatan halaman hingga setengah dari waktu sebenarnya!
5. **Privacy:** dengan adanya annoyances blocking, ini `meningkatkan`  privacy.
6. **Saves expense:** mengurangi  `biaya` konsumsi data.
7. **Clean:**  no  `extra`  abracadabra!


## Cara Menggunakan
- Buka browser favorit Anda ([Chrome](https://www.google.com/chrome/), [Firefox](https://www.mozilla.org/firefox/), [Safari](http://www.apple.com/safari/), [Opera](http://www.opera.com/), ...)
- Install salah satu ekstensi dari berikut ini: [uBlock Origin](https://github.com/gorhill/uBlock#installation), [Nano Adblocker](https://github.com/NanoAdblocker/NanoCore#install-links), [AdGuard Browser extension](https://adguard.com/en/adguard-browser-extension/overview.html), [Adblock Plus](https://adblockplus.org), atau ekstensi ad blocker lainnya. (Secara pribadi Saya menggunakan uBlock Origin untuk keperluan testing filter ini)
- Anda dapat menggunakan filter AdBlockID dengan menambahkan alamat ini secara manual pada plugin adblock yang Anda gunakan.

   `https://raw.githubusercontent.com/realodix/AdBlockID/master/output/adblockid.txt`
   
   Tutorial spesifik cara memasang AdBlockID:
   - [uBlock Origin](https://github.com/realodix/AdBlockID/blob/master/tutorial/uBlock-import-filter.md)
   - [Nano Adblocker](https://github.com/realodix/AdBlockID/blob/master/tutorial/uBlock-import-filter.md)
   - [AdGuard Browser extension](https://github.com/realodix/AdBlockID/blob/master/tutorial/Adguard-import-filter.md)
   - [Adblock Plus](https://github.com/realodix/AdBlockID/blob/master/tutorial/Adblock-Plus-import-filter.md)
   - [Opera Ad Blocker](https://github.com/realodix/AdBlockID/blob/master/tutorial/Opera-AdBlocker-import-filter.md)


## Berkontribusi
Perkebangan iklan di web Indonesia begitu cepat, terutama web yang memajang iklan berkonten dewasa. Jika Anda menemukan web yang tidak terfilter oleh AdBlockID, jangan ragu untuk membuat [issue di sini](https://github.com/realodix/AdBlockID/issues) :D


## Generate File

### Persiapan
Untuk menyatukan semua file ke dalam sebuah file [adblockid.txt](https://raw.githubusercontent.com/realodix/AdBlockID/master/output/adblockid.txt), Anda membutuhkan:

* [Python (2.7 atau 3.5+)](https://www.python.org/downloads/).
* [pip](https://pypi.org/project/pip/).

Setelah semua sudah terinstall di komputer Anda, lalu jalankan perintah ini:

`$ pip install -e vendor/python-abp`

### Tools pendukung
* `FOP.py` untuk mengurutkan.
* `generate.py` untuk menyatukan.
* `validatehost.py` untuk memeriksa host apakah masih aktif atau tidak.
