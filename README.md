# Lisanslı Güncelleme Yayını

Telefon Stok uygulaması yalnızca geçerli yıllık lisans varken güncelleme kontrolü yapar.

`version.json` dosyasını şu adrese yükleyin:

`https://raw.githubusercontent.com/technosef/ikizsoft-telefon-stok-updates/main/version.json`

Yeni paket yayımlarken:

1. `version` alanını uygulamadaki sürümden yüksek yapın.
2. `notes` alanına kullanıcıya gösterilecek değişiklikleri yazın.
3. `downloadUrl` alanına public güncelleme deposundaki GitHub Release kurulum EXE adresini yazın.
4. Güncelleme paketini o adrese yükleyin.

Uygulama yalnızca İkizSoft alan adı veya `github.com` Release indirme bağlantılarını kabul eder. Kaynak kod deposu private kalır. Bu yönetim klasörü müşteri ZIP paketine dahil edilmez.