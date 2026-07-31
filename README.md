# Tahmin Oyunu — Gizlilik Politikası

Bu depo yalnızca **Tahmin Oyunu**'nun gizlilik politikasını yayınlar.
Oyunun kaynak kodu burada değil.

Yayındaki adres: <https://bayramfurkankurucan.github.io/tahminoyunu-gizlilik/>

## Bu dosyalar elle düzenlenmez

`index.html` **üretilen** bir dosyadır. Kaynağı, oyunun kendi deposundaki
`web/PRIVACY.md`. Politika değiştiğinde oradan yeniden üretilir:

```bash
cd <oyun-deposu>/web
npm run privacy:site -- --out <bu-deponun-yolu>/index.html
```

Sonra buradan commit'lenip push'lanır.

İki kopyayı ayrı ayrı elle tutmak, biri güncellenip diğeri unutulduğunda
yayında eski politikanın kalması demek olurdu — ve mağazaya verilen adreste
yazan metin bağlayıcı olan.

## Yayın ayarı

GitHub → **Settings → Pages → Deploy from a branch → `main` / `(root)`**
