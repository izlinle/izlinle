# İzlinle
[![Dizipal Downloads](https://img.shields.io/github/downloads/izlinle/izlinle/total.svg?style=flat&label=Toplam%20İndirme)](https://github.com/dizipaltv/dizipal/releases)

> İzlinizle izliyorum.

Açık kaynak kodlu izlinle masaüstü uygulaması

## Nasıl İndirilir?

[Buradan](https://github.com/izlinle/izlinle/releases/latest) son sürüme ulaşabilirsiniz. Bu sayfaya gittiğinizde Assets başlığı altında yer alan .exe dosyasını indirip kurmanız yeterli olacaktır.

## Geliştiriciler için yükleme talimatları:

Kaynak kodlarıyla oynamak kendinize göre değiştirmeniz için birkaç bilgi sunacağım: Kullandığım,

| Kullanılan                   | Adı      | Sürüm   |
|------------------------------| -------- | ------- |
| Programlama Dili             | Nodejs   | 20.17.0 |
| Masaüstü Uygulama Yaratıcısı | Electron | 32.0.1  |
| Paket Yöneticisi             | Yarn     | 1.22.22   |

<br />

## Kaynak Kodlarını Nasıl İndiririm?
> [!IMPORTANT]      
> Bilgisayarınızda [git-scm](https://git-scm.com/)'in son sürümünün bulunması gerekmektedir.      
> ve de [Nodejs](https://nodejs.org)'in lts sürümünün sürümünün bulunması gerekmektedir.          

<br />

#### Bu depoyu klonlayarak başlayın

Github depomuzu klonlamak için aşağıdaki komutu terminalinize yapıştırınız.

```bash
git clone https://github.com/izlinle/izlinle.git
```

Şimdi indirilen deponun olduğu dizine girmeliyiz. Aşağıdaki komutları terminalinizde çalıştırınız.

```bash
cd izlinle
```

Bir sonraki adım ise gerekli bağımlılıkları indirmek olacaktır. Bu projenin ihtiyaç duyduğu bazı paketleri
indirmemiz gerekmektedir. Aşağıdaki komutları terminalinizde çalıştırınız.

```bash
yarn install
```

> npm kullanıyorsanız bu komutu çalıştırınız
```bash
npm run install
```

<br />

#### Projeyi dünya gözüyle görme zamanı

Evet gerekli herşeyin yüklenmesi, kurulmasının ardından artık projeyi başlatabiliriz.
Aşağıdaki komutları terminalinize yapıştırınız.

```bash
yarn start
```

<br />

#### Daha fazla komuta nasıl ulaşabilirim?
Evet daha birkaç komut daha mevcut bunları [package.json](package.json) içerisinde `"scripts"` altında bulabilirsiniz.
işte versiyon 0.3.1 için kullanılan komutlar
```
`dev`       : Geliştirme sürecinde yaptığımız değişiklikleri sıkıştırma olmadan görmek için kullanılan script komutudur,
minify      : Tüm kodlarımızı sıkıştıran komutdur,
start       : Uygulamamızı başlatır,
build       : Uygulamamızı paketler,
build-linux : Uygulamamızı linux a paketler,
build-mac   : Uygulamamızı macos a paketler,
build-win   : Uygulamamızı windows a paketler
```

<br /><br />

LICENSE : [MIT](LICENSE)
