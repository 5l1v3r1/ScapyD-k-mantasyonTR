## Sniffing işlemi 

* Bu işlem için <b>sniff()</b> fonksiyonunu kullanacağız.

## Fonksiyonun detayları - Alabileceği parametreler

* <b>prn</b>     = yakalanan paketlerin gönderileceği fonksiyon
* <b>count</b>   = yakalanacak paket sayısı
* <b>iface</b>   = sniff işleinde kullanılacak interface
* <b>filter</b>  = sniff işleminde kullanmak istediğiniz filtreler
* <b>offline</b> = daha önce yakaladığını bir pcap dosyasını okuyabilirsiniz.
* <b>timeout</b> = sniff işlemi için zaman sınırlaması

### Örnekler
sniff(iface='eth0', filter='arp',count=5)

sniff(iface='wlan0', count=7, prn=Beacon)

sniff(offline='cypm.pcap', prn=Analiz)
