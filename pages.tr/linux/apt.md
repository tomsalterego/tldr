# apt

> Debian tabanlı dağıtımlar için paket yönetim aracı.
> Ubuntu 16.04 ve sonraki sürümlerde interaktif kullanıldığında `apt-get` için önerilen değiştirme.
> Daha fazla bilgi için: <https://manned.org/apt.8>.

- Kullanılabilir paket ve versiyonların listesini yenile (Bu komutu diğer `apt` komutlarından önce kullanmanız önerilir):

`sudo apt update`

- Belirli bir paketi arayın:

`apt search {{paket}}`

- Bir paketin bilgilerini gösterin:

`apt show {{paket}}`

- Bir paket kurun veya mevcut en son sürüme güncelleyin:

`sudo apt install {{paket}}`

- Bir paketi kaldırın (bunun için "purge" kullanmak, yapılandırma dosyalarını da kaldırır):

`sudo apt remove {{paket}}`

- Kurulu tüm paketleri mevcut en yeni sürümlerine yükseltin:

`sudo apt upgrade`

- Tüm paketleri listeleyin:

`apt list`

- Kurulu paketleri listeleyin:

`apt list --installed`
