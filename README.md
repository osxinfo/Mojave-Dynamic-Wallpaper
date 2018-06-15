# Mojave-Dinamik-Duvarkağıdı

Duvar Kağıdı için 16 farklı aşama vardır.

Bu betik her 1,5 saatte duvar kağıdını değiştirir.

10.13.5 üzerinde denendi ve çalışmaktadır.Daha eski sürümlerde de çalışacaktır.


## Kurulum

1. Mojave klasörünü /Users/Shared içine kopyalayın.

```
/Users/Shared/Mojave
```

2. com.d3fault.mojavedynamicwallpaper.plist dosyasını ~/Library/LaunchAgents içine kopyalayın.
```
~/Library/LaunchAgents/com.d3fault.mojavedynamicwallpaper.plist
```

3. servisin sistem açılışı ile beraber çalıştırılmasını sağlamak için Terminal uygulamasını açın ve aşağıdaki komutu girin:
```
launchctl load -w ~/Library/LaunchAgents/com.d3fault.mojavedynamicwallpaper.plist
```


## Kaldırmak

1. Servisin çalıştırılmasını durudun
```
launchctl unload -w ~/Library/LaunchAgents/com.d3fault.mojavedynamicwallpaper.plist
```
2. Terminal kullanarak aşağıdaki dosyaları silin:
```
rm ~/Library/LaunchAgents/com.d3fault.mojavedynamicwallpaper.plist
rm -r "/Users/Shared/Mojave"
```
