# **Linux Komutları**

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/35/Tux.svg" alt="Linux Tux" width="200"/>
</p>

## **Linux İşletim Sistemi Hakkında**

- Linux, **Unix benzeri** bir işletim sistemi olup, **açık kaynaklı** ve **topluluk tarafından geliştirilen** bir yapıya sahiptir. Linux, dünya çapında **bilgisayarlar**, **sunucular**, **mobil cihazlar** ve **gömülü cihazlar** gibi birçok platformda kullanılmaktadır.
- Linux, kullanıcılarına **özelleştirilebilir** ve **güçlü** bir ortam sunarak, geliştiriciler ve sistem yöneticileri için popüler bir tercihtir.

## Dosya ve Dizin İşlemleri

### 1.`ls` Komutu

**`ls`**, Linux ve Unix tabanlı işletim sistemlerinde kullanılan en yaygın komutlardan biridir. Bu komut, bulunduğunuz dizindeki dosya ve klasörlerin listesini görüntülemek için kullanılır. **`ls`** komutunun farklı seçenekler ile özelleştirilebilen güçlü bir kullanım yapısına sahiptir.

### Örnek Kullanım

Bulunduğunuz dizindeki dosya ve klasörleri listelemek için basitçe şu komutu kullanabilirsiniz:

```bash
ls
```
![görsel](/Resim%20linux/ls.png)

### 2.`pwd` Komutu

**`pwd`**, "print working directory" (geçerli dizini yazdır) ifadesinin kısaltmasıdır. Bu komut, terminalde şu an bulunduğunuz dizinin tam yolunu görüntüler. Kullanıcılar, özellikle dosya ve dizin yapıları arasında gezinirken, hangi dizinde olduklarını görmek için bu komutu kullanabilirler.

### Örnek Kullanım

Geçerli dizininizi öğrenmek için **`pwd`** komutunu çalıştırabilirsiniz:

```bash
pwd
```
![görsel](/Resim%20linux/pwd.png)

### 3.`cd` Komutu

**`cd`** (change directory), Linux'ta çalışma dizinini değiştirmek için kullanılan temel bir komuttur. Bu komut, dosya sistemi içinde hızlı ve kolay bir şekilde gezinmenizi sağlar.

### Örnek Kullanım

Bir dizine geçmek için **`cd`** komutunu şu şekilde kullanabilirsiniz:

```bash
cd Belgeler
```
![görsel](/Resim%20linux/cd.png)

### 4.`mkdir` Komutu

**`mkdir`** (make directory), Linux'ta yeni bir dizin oluşturmak için kullanılan bir komuttur. Bu komut, belirtilen adla bir veya birden fazla dizin oluşturmanıza olanak tanır.

### Örnek Kullanım

Aşağıdaki komut, **`Projeler`** adında bir dizin oluşturur:

```bash
mkdir Projeler
```
![görsel](/Resim%20linux/mkdir.png)

### 5.`rmdir` Komutu

**`rmdir`** (remove directory), boş dizinleri silmek için kullanılan bir komuttur. Bu komut, yalnızca içerisinde dosya veya alt dizin bulunmayan dizinleri kaldırabilir.

### Örnek Kullanım

Aşağıdaki komut, mevcut konumda bulunan **`EskiProje`** adındaki boş bir dizini siler:

```bash
rmdir EskiProje
```
![görsel](/Resim%20linux/rmdir.png)

### 6.`rm` Komutu

**`rm`** (remove), dosyaları ve dizinleri terminal üzerinden silmek için kullanılan güçlü bir komuttur.

### Örnek Kullanım

Bir dosyayı silmek için:

```bash
rm -r dosya.txt
```
![görsel](/Resim%20linux/rm/rm.png)
![görsel](/Resim%20linux/rm/rm1.png)
### 7.`cp` Komutu

**`cp`** (copy), dosya ve dizinleri bir yerden başka bir yere kopyalamak için kullanılan bir komuttur.

### Örnek Kullanım

Bir dosyayı başka bir konuma kopyalamak için:

```bash
cp dosya.txt /hedef/klasor/
```
![görsel](/Resim%20linux/cp.png)

### 8.`mv` Komutu

**`mv`** (move), dosya ve dizinleri taşımak veya yeniden adlandırmak için kullanılan bir komuttur.

### Örnek Kullanım

Bir dosyayı başka bir dizine taşımak için:

```bash
mv dosya.txt /hedef/klasor/
```
![görsel](/Resim%20linux/mv.png)

### 9.`touch` Komutu

**`touch`**, yeni bir dosya oluşturmak veya mevcut bir dosyanın son değiştirilme zamanını güncellemek için kullanılan bir komuttur.

### Örnek Kullanım

Bir dosya oluşturmak için:

```bash
touch dosya.txt
```
![görsel](/Resim%20linux/touch.png)

### 10.`tree` Komutu

**`tree`**, bir dizin yapısını hiyerarşik bir ağaç formatında görselleştirmek için kullanılan bir komuttur. Bu, dosya ve alt dizinleri daha net bir şekilde anlamanızı sağlar.

### Örnek Kullanım

Basit bir dizin ağacı oluşturmak için:

```bash
tree
```
![görsel](/Resim%20linux/tree.png)

## Dosya Görüntüleme ve Düzenleme
### 11.  `cat` Komutu

**`cat`** (concatenate), Linux'ta dosya içeriğini görüntülemek, birden fazla dosyanın içeriğini birleştirmek veya yeni dosyalar oluşturmak için kullanılan temel bir komuttur.

### Örnek Kullanım

Bir dosyanın içeriğini terminalde görüntülemek için:

```bash
cat dosya.txt
```
![görsel](/Resim%20linux/cat.png)

### 12.`more` Komutu

**`more`**, Linux'ta dosya içeriğini sayfa sayfa görüntülemek için kullanılan bir komuttur. Özellikle büyük dosyalarla çalışırken, tüm dosya içeriğini bir anda görmek yerine, daha rahat bir şekilde sayfa sayfa görüntüleme yapmanıza olanak sağlar.

### Örnek Kullanım

Bir dosyanın içeriğini sayfa sayfa görüntülemek için:

```bash
more dosya.txt
```
![görsel](/Resim%20linux/more.png)

### 13.`less` Komutu

**`less`**, Linux'ta büyük dosyaları veya uzun çıktıları daha rahat bir şekilde görüntülemek için kullanılan bir komuttur. `more` komutuna benzer şekilde, ancak daha fazla özellik sunar. **`less`** komutu ile dosya içeriğini sayfa sayfa görüntüleyebilir, ileri geri gezinebilir ve daha fazlasını yapabilirsiniz.

### Örnek Kullanım

Bir dosyanın içeriğini görüntülemek için:

```bash
less dosya.txt
```
### 14.`head` Komutu

**`head`** komutu, bir dosyanın baş kısmındaki ilk birkaç satırı hızlıca görüntülemek için kullanılan basit ama kullanışlı bir komuttur. Özellikle büyük dosyalarla çalışırken, sadece dosyanın başındaki bilgileri görmek istediğinizde bu komut oldukça işinize yarar.

### Örnek Kullanım

Varsayılan olarak, **`head`** komutu dosyanın ilk 10 satırını gösterir:

```bash
head dosya.txt
```
![görsel](/Resim%20linux/head.png)

### 15 `tail` Komutu

**`tail`** komutu, bir dosyanın son kısmındaki son satırları görüntülemek için kullanılır. Özellikle log dosyalarını izlerken veya son verileri kontrol ederken oldukça faydalıdır. **`tail`** komutu, dosyanın sonunda olan değişiklikleri hızlıca görmek için kullanılır.

### Örnek Kullanım

Varsayılan olarak **`tail`** komutu, dosyanın son 10 satırını gösterir:

```bash
tail dosya.txt
```
### 16.`nano` Komutu

**`nano`**, Linux'te kullanılan popüler bir metin düzenleyicisidir. Komut satırından çalışan ve dosya düzenleme işlemleri için oldukça basit ve kullanıcı dostu bir arayüz sunar. Özellikle hızlıca bir dosya düzenlemek gerektiğinde tercih edilir.

### Örnek Kullanım

**`nano`** komutunu bir dosya adıyla kullanarak bir dosyayı açabilirsiniz. Eğer dosya mevcutsa, içerik düzenlemeye başlarsınız; dosya yoksa, yeni bir dosya oluşturulur.

```bash
nano dosya.txt
```
![görsel](/Resim%20linux/nano.png)
### 17. `vim` Komutu

**`vim`**, Linux'te ve diğer Unix tabanlı işletim sistemlerinde kullanılan güçlü bir metin düzenleyicisidir. **`vim`**, **`vi`** metin düzenleyicisinin gelişmiş bir versiyonudur ve oldukça esnek ve güçlü özelliklere sahiptir. Ancak, **`vim`**'i öğrenmek biraz zaman alabilir çünkü oldukça fazla klavye kısayoluna ve modlara sahiptir.

### Örnek Kullanım

Bir dosyayı **`vim`** ile açmak için aşağıdaki komutu kullanabilirsiniz:

```bash
vim dosya.txt
```
![görsel](/Resim%20linux/vim.png)

### 18.`grep` Komutu

**`grep`** (Global Regular Expression Print), Linux ve diğer Unix tabanlı sistemlerde metin içeriği üzerinde arama yapmak için kullanılan güçlü bir komuttur. **`grep`**, belirli kelime veya ifadeleri dosyalarda veya çıktılarda aramak için kullanılır ve düzenli ifadeler (regular expressions) ile de uyumlu çalışabilir.

### Örnek Kullanım

Bir metin dosyasında belirli bir kelimeyi veya ifadeyi aramak için aşağıdaki komutu kullanabilirsiniz:

```bash
grep "kelime" dosya.txt
```
![görsel](/Resim%20linux/grep.png)

### 19.`wc` Komutu

**`wc`** (Word Count), bir dosyanın veya metin çıktısının kelime, satır ve karakter sayısını hızlıca öğrenmek için kullanılan bir Linux komutudur. Bu komut, dosyanın içeriğini analiz ederek çeşitli bilgileri döndürebilir ve özellikle metin dosyalarının boyutlarını kontrol etmek için kullanılır.

### Örnek Kullanım

```bash
wc  dosya.txt
```
![görsel](/Resim%20linux/wc.png)

### 20.`sort` Komutu

**`sort`** komutu, dosyalardaki verileri sıralamak için kullanılan güçlü bir araçtır. Varsayılan olarak, alfabetik sıralama yapar, ancak farklı seçeneklerle sayısal, ters ve özel sıralamalar yapabilirsiniz. Bu komut, verileri düzenlemek ve analiz etmek için sıklıkla kullanılır.

### Örnek Kullanım

Bir dosyadaki satırları alfabetik olarak sıralamak için **`sort`** komutunu kullanabilirsiniz:

```bash
sort dosya.txt
```
![görsel](/Resim%20linux/sort.png)


## Kullanıcı Yönetimi

### 21. `whoami` Komutu

**`whoami`** komutu, terminalde oturum açmış kullanıcıyı hızlı bir şekilde öğrenmek için kullanılır. Kullanıcı adı bilgisi, sistemde aktif olan oturumu belirten bir komut olarak oldukça faydalıdır.

### Örnek Kullanım

Terminalde şu komutu çalıştırarak, sistemdeki aktif kullanıcı adını öğrenebilirsiniz:

```bash
whoami
```
![görsel](/Resim%20linux/whoami.png)

### 22. `id` Komutu

**`id`** komutu, Linux ve Unix tabanlı sistemlerde oturum açmış kullanıcının kimlik bilgilerini, kullanıcı adı, kullanıcı ID'si (UID), grup adı ve grup ID'si (GID) gibi bilgileri gösterir. Ayrıca, kullanıcının ait olduğu grupların listesi de bu komutla elde edilebilir.

### Örnek Kullanım

Terminalde **`id`** komutunu çalıştırarak, sistemde oturum açmış kullanıcının kimlik bilgilerini öğrenebilirsiniz:

```bash
id
```
![görsel](/Resim%20linux/id.png)

### 23.`who` Komutu

**`who`** komutu, Linux ve Unix tabanlı sistemlerde, sisteme giriş yapmış olan kullanıcıları gösterir. Bu komut, oturum açan kullanıcıların adlarını, giriş tarihlerini, oturum açma terminalini ve oturum açma zamanlarını listeler. Sistem yöneticileri ve kullanıcılar için faydalı bir komut olup, aktif kullanıcılar hakkında bilgi verir.

### Örnek Kullanım

Terminalde **`who`** komutunu çalıştırarak, sisteme giriş yapmış tüm kullanıcıları görebilirsiniz:

```bash
who
```
![görsel](/Resim%20linux/who.png)

### 24. `adduser` Komutu

**`adduser`** komutu, Linux Mint ve diğer Debian tabanlı dağıtımlarda yeni bir kullanıcı hesabı oluşturmak için kullanılır. Bu komut, kullanıcıyı sistemdeki ilgili dosyalara ve dizinlere ekler, şifre belirler ve kullanıcıya bazı ek yapılandırmalar yapmanıza olanak tanır.

### Örnek Kullanım

Yeni bir kullanıcı oluşturmak için aşağıdaki komutu kullanabilirsiniz:

```bash
sudo adduser yeni_kullanici
```
![görsel](/Resim%20linux/adduser.png)

### 25.`passwd` Komutu

**`passwd`** komutu, Linux Mint ve diğer Linux dağıtımlarında kullanıcıların şifrelerini değiştirmek için kullanılır. Bu komut, hem mevcut bir kullanıcının şifresini değiştirmeye hem de yeni bir şifre belirlemeye olanak tanır.

### Örnek Kullanım

Bir kullanıcı, kendi şifresini değiştirmek için terminalde şu komutu kullanabilir:

```bash
passwd
```
![görsel](/Resim%20linux/passwd.png)

### 26.`su` Komutu

**`su`** (substitute user), Linux sistemlerinde başka bir kullanıcıya geçmek veya root (yönetici) yetkileriyle işlem yapmak için kullanılan bir komuttur. Bu komut, kullanıcıların belirli işlemleri daha yüksek yetkilerle gerçekleştirmelerine olanak tanır.

### Örnek Kullanım

Bir kullanıcı, sistemde root kullanıcısına geçiş yapmak için aşağıdaki komutu kullanabilir:

```bash
su
```
![görsel](/Resim%20linux/su.png)

### 27.`groups` Komutu

**`groups`** komutu, bir kullanıcının hangi gruplara ait olduğunu gösteren bir komuttur. Bu komut, özellikle kullanıcı yönetimi ve izinlerle ilgili işlemler yaparken faydalıdır. Linux sistemlerinde, her kullanıcı belirli gruplara ait olabilir ve bu gruplara ait izinlerle işlem yapar.

### Örnek Kullanım

Mevcut kullanıcı için ait olduğu grupları görmek amacıyla **`groups`** komutunu şu şekilde çalıştırabilirsiniz:

```bash
groups
```
![görsel](/Resim%20linux/groups.png)

### 28.`userdel` Komutu

**`userdel`** komutu, Linux sistemlerinde bir kullanıcıyı tamamen silmek için kullanılır. Bu komut, belirtilen kullanıcıyı sistemden kaldırır. Kullanıcı silindiğinde, kullanıcıya ait tüm dosyalar ve gruplar kaldırılabilir, ancak bu işlem öncesinde dikkatlice düşünülmelidir.

### Örnek Kullanım

Bir kullanıcıyı sistemden silmek için **`userdel`** komutunu şu şekilde kullanabilirsiniz:

```bash
sudo userdel kullanici_adi
```
![görsel](/Resim%20linux/userdel.png)

### 29.## `usermod` Komutu

**`usermod`** komutu, mevcut bir kullanıcıyı değiştirmek için kullanılır. Kullanıcı adı, grubunu, ev dizinini ve diğer hesap bilgilerini güncellemek için bu komut oldukça kullanışlıdır. Sistemdeki kullanıcılar üzerinde düzenlemeler yapmanıza olanak tanır.

### Örnek Kullanım

Bir kullanıcının adını değiştirmek için **`-l`** parametresini kullanabilirsiniz. Aşağıdaki komut, **`eski_ad`** adlı kullanıcının adını **`yeni_ad`** olarak değiştirir:

```bash
sudo usermod -l yeni_ad eski_ad
```
![görsel](/Resim%20linux/usermod.png)

## Sistem bilgileri

### 30.`uname` Komutu

**`uname`** komutu, Linux sistem hakkında temel bilgi sağlar. Çoğunlukla çekirdek adı, sürümü, işlemci mimarisi gibi bilgileri görmek için kullanılır. Bu komut, sistemin donanımı, yazılımı ve işletim sistemi hakkında bilgi edinmek için çok kullanışlıdır.

### Örnek Kullanım

`uname` komutu, işletim sistemi hakkında temel bilgileri gösterebilir. Aşağıdaki komut sadece işletim sistemi çekirdek adını görüntüler:

```bash
uname
```
![görsel](/Resim%20linux/uname.png)

### 31.`hostname` Komutu

**`hostname`** komutu, sistemin ağda tanımlı ismini görüntülemek ve değiştirmek için kullanılır. Bu komut, genellikle bir bilgisayarın ağ üzerindeki kimliğini tanımlayan ismi gösterir. Ayrıca, sistemin ağdaki tanınabilirliğini artırmak amacıyla hostname değiştirilebilir.

### Örnek Kullanım

Sadece **`hostname`** komutunu çalıştırarak sistemin mevcut ağ ismini öğrenebilirsiniz:

```bash
hostname
```
![görsel](/Resim%20linux/hostname.png)

### 32. `df` Komutu

**`df`** (disk free) komutu, sistemdeki dosya sistemlerinin kullanım durumunu gösterir. Bu komut, bağlı olan dosya sistemlerinin disk alanı kullanımını, toplam alanı ve boş alanı görüntülemenize olanak tanır.

### Örnek Kullanım

En basit şekilde **`df`** komutunu çalıştırarak, bağlı olan tüm dosya sistemlerinin disk kullanım bilgilerini görebilirsiniz:

```bash
df
```
![görsel](/Resim%20linux/df.png)

### 33.`du` Komutu

**`du`** (disk usage) komutu, bir dizin veya dosyanın disk üzerinde kapladığı alanı gösterir. Bu komut, özellikle büyük dosya ve dizinlerin yer kaplamasını incelemek için kullanılır.

### Örnek Kullanım

En basit haliyle **`du`** komutunu çalıştırarak, geçerli dizin ve alt dizinlerin disk kullanımını görebilirsiniz:

```bash
du
```

### 34.`top` Komutu

**`top`** komutu, sistemdeki işlemci kullanımını, bellek kullanımını ve diğer sistem kaynaklarını dinamik bir şekilde görüntülemek için kullanılır. Bu komut, sistemde çalışan işlemleri anlık olarak izleyebilmek için son derece faydalıdır.

### Örnek Kullanım

En basit haliyle **`top`** komutunu terminalde çalıştırarak, sistemdeki işlemler hakkında anlık bilgi alabilirsiniz:

```bash
top
```
![görsel](/Resim%20linux/top.png)


### 35.`htop` Komutu

**`htop`**, sistemdeki süreçleri ve kaynak kullanımını görsel olarak takip etmenizi sağlayan interaktif bir araçtır. **`top`** komutunun daha gelişmiş ve kullanıcı dostu bir versiyonudur. **`htop`**, işlemci, bellek, swap alanı ve diğer sistem kaynakları hakkında anlık bilgiler sağlar. Ayrıca, işlemleri sıralama, filtreleme ve sonlandırma gibi işlemleri kolayca yapmanıza olanak tanır.

### Örnek Kullanım

En basit haliyle **`htop`** komutunu terminalde çalıştırarak, sistemdeki işlemleri ve kaynak kullanımını görsel olarak izleyebilirsiniz:

```bash
htop
```
![görsel](/Resim%20linux/htop.png)

### 36. `ps` Komutu

**`ps`** komutu, Linux sistemlerinde çalışan işlemleri listelemek için kullanılır. Bu komut, sistemdeki aktif işlemlerin bilgilerini gösterir ve her bir işlem hakkında detaylı bilgi almanızı sağlar. **`ps`**, özellikle sistem yöneticilerinin ve geliştiricilerin, çalışan işlemleri izlemesi ve yönetmesi için temel bir araçtır.

### Örnek Kullanım

En basit haliyle, **`ps`** komutu yalnızca mevcut terminal oturumundaki işlemleri listeler:

```bash
ps
```
### 37.`free` Komutu

**`free`** komutu, Linux sistemlerinde bellek (RAM) kullanımını görmek için kullanılan basit ve etkili bir araçtır. Sistemdeki toplam, kullanılan ve boş bellek miktarını gösterir. Bu komut, özellikle sistem yöneticilerinin ve geliştiricilerin bellek kullanımını izlemeleri için oldukça faydalıdır.

### Örnek Kullanım

**`free`** komutunu herhangi bir ek parametre olmadan çalıştırdığınızda, sistemin genel bellek kullanımına dair temel bilgileri görüntüler:

```bash
free
```
![görsel](/Resim%20linux/free.png)

### 38.`uptime` Komutu

**`uptime`** komutu, Linux sisteminin ne kadar süredir çalıştığını gösteren basit bir araçtır. Sistemin başlatılmasından itibaren geçen süreyi, ayrıca sistem yükünü ve aktif kullanıcı sayısını hızlıca görüntülemenizi sağlar. Bu komut, özellikle sistem yöneticileri ve geliştiriciler için sistem durumu hakkında bilgi edinmek için kullanışlıdır.

### Örnek Kullanım



**`uptime`** komutunu terminalde çalıştırarak sistemin çalışma süresi hakkında bilgi alabilirsiniz:

```bash
uptime
```
![görsel](/Resim%20linux//uptime.png)

### 39.`dmesg` Komutu

**`dmesg`** komutu, Linux çekirdek mesajlarını görüntülemek için kullanılan güçlü bir araçtır. Bu komut, sistemdeki donanım ve çekirdek ile ilgili olayları, hata mesajlarını ve sistem başlatma işlemleri sırasında oluşan log kayıtlarını hızlı bir şekilde incelemenizi sağlar. **`dmesg`**, genellikle sistem hatalarını teşhis etmek, donanım sorunlarını gidermek ve çekirdek seviyesindeki logları kontrol etmek için kullanılır.

### Örnek Kullanım

**`dmesg`** komutunu terminalde çalıştırarak sistemin çekirdek mesajlarını görebilirsiniz:

```bash
dmesg
```
![görsel](/Resim%20linux/dmesg.png)

## Ağ ve İnternet
### 40. `ping` Komutu

**`ping`** komutu, ağ bağlantılarının doğruluğunu test etmek için kullanılan en temel ağ aracıdır. Bu komut, belirli bir hedefe ICMP (Internet Control Message Protocol) paketleri göndererek hedefin ulaşılabilirliğini ve yanıt süresini ölçer. Genellikle ağ bağlantı sorunlarını tespit etmek ve bir cihazın ağ üzerinde aktif olup olmadığını kontrol etmek için kullanılır.

### Örnek Kullanım

**`ping`** komutunu kullanarak bir IP adresine veya domaine ping atabilirsiniz. Örneğin, Google'a ping atmak için:

```bash
ping google.com
```
![görsel](/Resim%20linux/ping.png)

### 41.## `ifconfig` Komutu

**`ifconfig`** (Interface Configuration) komutu, ağ arabirimlerini (network interfaces) yönetmek ve yapılandırmak için kullanılan bir komuttur. Bu komut, ağ bağlantılarınız hakkında bilgi almanıza ve bu bağlantılar üzerinde değişiklikler yapmanıza olanak sağlar. Genellikle ağ adresi yapılandırmaları ve ağ arayüzü durumunu kontrol etmek için kullanılır.

### Örnek Kullanım

Ağ arayüzlerinin mevcut durumu hakkında bilgi almak için **`ifconfig`** komutunu şu şekilde çalıştırabilirsiniz:

```bash
ifconfig
```
![görsel](/Resim%20linux/ifconfig.png)

### 42. `ip a` Komutu

**`ip a`** komutu, Linux sistemlerde ağ arayüzlerini ve bu arayüzlere ait IP adreslerini görüntülemek için kullanılan bir komuttur. Bu komut, ağ arayüzlerinin detaylı bilgilerini sağlar ve özellikle ağ bağlantılarını yönetirken veya sorun giderme işlemlerinde kullanışlıdır.

### Örnek Kullanım

**`ip a`** komutunu çalıştırarak sistemdeki tüm ağ arayüzlerinin durumunu ve bu arayüzlere bağlı IP adreslerini görüntüleyebilirsiniz:

```bash
ip a
```
![görsel](/Resim%20linux/ip%20a.png)

### 43. `curl` Komutu

**`curl`** komutu, URL'ler üzerinden veri indirmek ve yüklemek için kullanılan güçlü bir komuttur. Genellikle HTTP, HTTPS, FTP gibi protokollerle veri iletimi yapmak için kullanılır. Bu komut, veri almak, göndermek veya bir URL üzerinden bilgi almak için yaygın olarak kullanılır.

### Örnek Kullanım

Bir URL'den içerik almak için **`curl`** komutunu şu şekilde kullanabilirsiniz:

```bash
curl https://www.example.com
```
### 44.## `wget` Komutu

**`wget`**, web üzerinde dosya indirmek için kullanılan güçlü ve çok yönlü bir komuttur. Çoğunlukla HTTP, HTTPS ve FTP protokollerini kullanarak dosyaları indirmenize olanak tanır. Ayrıca, arka planda çalışabilir ve internet bağlantınız kesilse bile indirme işlemini yeniden başlatabilirsiniz.

### Örnek Kullanım

Bir dosyayı bir URL'den indirmek için basitçe **`wget`** komutunu kullanabilirsiniz. Örneğin, **`example.txt`** dosyasını indirmek için şu komutu kullanabilirsiniz:

```bash
wget https://www.example.com/example.txt
```

### 45.`netstat` Komutu

**`netstat`**, ağ bağlantıları, yönlendirme tabloları, arayüz istatistikleri ve ağ protokollerine ilişkin bilgi sağlamak için kullanılan bir komuttur. Sistemdeki ağ bağlantılarını ve bunların durumlarını görmek için oldukça yararlı bir araçtır.

### Örnek Kullanım

Aktif ağ bağlantılarını görmek için **`netstat`** komutunu şu şekilde kullanabilirsiniz:

```bash
netstat
```
![görsel](/Resim%20linux/netstat.png)

### 46. `traceroute` Komutu

**`traceroute`**, bir hedef sunucuya ulaşana kadar geçen ağ yollarını ve bu yolların her birindeki gecikme sürelerini izlemek için kullanılan güçlü bir ağ teşhis aracıdır.

### Kullanım Senaryosu: Bir Web Sitesine Giden Ağ Yolunu İzlemek

Bir web sitesine olan ağ bağlantısının geçtiği yolları görmek için **`traceroute`** komutunu şu şekilde kullanabilirsiniz:

```bash
traceroute example.com
```

### 47. `ssh` Komutu

**`ssh`** (Secure Shell), uzak bir sunucuya güvenli bir şekilde bağlanmak için kullanılan bir protokoldür. Komut, şifreli bir bağlantı sağlar ve uzaktaki bir makine üzerinde komutlar çalıştırmanıza olanak tanır.

### Kullanım Senaryosu: Uzak Sunucuya Bağlanma

Bir sunucuya bağlanmak için şu komutu kullanabilirsiniz:

```bash
ssh username@remote-server
```

### 48. `scp` Komutu

**`scp`** (Secure Copy), SSH protokolünü kullanarak dosyaları güvenli bir şekilde bir sistemden diğerine kopyalamak için kullanılan bir komuttur. Yerel makineden uzak bir sunucuya, uzak bir sunucudan yerel makineye veya iki uzak sunucu arasında dosya transferi sağlar.

### Kullanım Senaryosu: Yerel Makineden Uzak Sunucuya Dosya Kopyalama

Aşağıdaki komut, yerel bir dosyayı uzak sunucuya kopyalar:

```bash
scp /path/to/local/file username@remote-server:/path/to/remote/directory
```
### 49.`ftp` Komutu

**`ftp`**, dosya aktarım protokolü (File Transfer Protocol) kullanarak bir sunucuya bağlanmak ve dosya transferi gerçekleştirmek için kullanılan bir komuttur. Basit bir istemci arayüzü sunar ve uzak sunucularda dosya yükleme, indirme, listeleme gibi işlemleri destekler.

### Kullanım Senaryosu: Bir FTP Sunucusuna Bağlanma

Aşağıdaki komut, belirli bir FTP sunucusuna bağlanmanızı sağlar:

```bash
ftp ftp.example.com
```
### 50. `tar` Komutu

**`tar`** (Tape Archive), dosyaları bir arşivde birleştirmek veya bir arşivi açmak için kullanılan bir komuttur. Yaygın olarak dosyaları sıkıştırmak veya sıkıştırılmış arşivleri açmak için kullanılır.

---

### Kullanım Senaryosu: Bir Dizini Sıkıştırılmış Arşiv Haline Getirme

Aşağıdaki komut, bir dizini **`.tar.gz`** formatında sıkıştırır:

```bash
tar -czvf archive-name.tar.gz directory-name/
```
## Sonuç

- Linux Mint'teki komutlar, sistem üzerinde hızlı, etkili ve esnek bir şekilde işlem yapmanızı sağlar. Bu rehberde incelediğiniz komutlar, dosya yönetiminden kullanıcı ayarlarına, ağ işlemlerinden sistem izlemeye kadar geniş bir yelpazede işlevler sunar.

- Bu bilgileri uygulayarak:

- Zamandan tasarruf edebilir,
- Sisteminizi daha iyi anlayabilir,
- Komut satırı becerilerinizi geliştirebilirsiniz.
- Unutmayın, Linux'un gücü detaylarda gizlidir! Deneme-yanılma yöntemiyle öğrenmekten çekinmeyin ve her komutta yeni bir şeyler keşfedin. 🎯

“En iyi kullanıcı, sistemini en iyi tanıyan kişidir.”
### İncelediğiniz için teşekkürler.

































