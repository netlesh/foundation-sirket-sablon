# şirket sitesi şablon



- index
- Hakkımızda / kurumsal > tarihçe > ödüllerimiz > ik > sertifika
- Katalog / Medya
- Ürünler / Hizmetler / projeler
- İletişim

## kurulum

- [Git](https://gitforwindows.org/)

- [NodeJS](https://nodejs.org/en/download/)

- [Yarn](https://yarnpkg.com/en/docs/install#windows-stable)




Foundation CLI kurulumu:

```bash
yarn global add foundation
yarn global add gulp
yarn global add gulp-filelist

```

```bash
git clone https://github.com/netlesh/foundation-sirket-sablon sirketwww

```



Now `cd` to your project name and to start your project run 

```bash
foundation watch
```
Resimleri img/urunler klasörünün içine ürün guruplarına ait klasor olusturarak ekleyin
resimlerin büyük  boyutlarını "tam" klasörü içine, küçükleri "th" atın.
irfanview batch ile hızlı boyutlandırma yapabilirsiniz.

img/urunler içindeki resimlerin doğrudan ürün gurup sayfasına eklenmasi için
```bash
gulp data
```


To create compressed, production-ready assets, run `yarn run build`.
sourcemap DEVRE DIŞI BIRAKMAK İÇİN  
```bash
foundation build --production
```
