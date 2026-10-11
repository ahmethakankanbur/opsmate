# Hafta 0 — 11 Ekim 2026

## Bugün ne yaptım

- Çalışmalarda kullanmak üzere Multipass ile `lab-01` adlı bir sanal makine oluşturdum.
- Git kimliğimi ayarladım ve SSH anahtarımı GitHub hesabıma ekledim.
- `opsmate` deposunu açıp ilk commit'i gönderdim.

## Öğrendiğim üç komut

- `multipass snapshot` — sanal makinenin o anki durumunun görüntüsünü alır; bir şey bozulursa `multipass restore` ile bu ana dönülür.
- `git switch -c <dal>` — yeni bir dal oluşturur ve aynı anda o dala geçer.
- `dpkg --audit` — yarım kalmış ya da bozuk kurulu paketleri listeler; çıktı boşsa paket sistemi sağlamdır.
