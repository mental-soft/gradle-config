# Gradle config
Mental sistem için yapılacak uygulamalarda ortak gradle ayarları burada tutulacak.

Ayrıca her uygulamanın dependency leri burada tutulabilir.


## Gradle properties
 
Aşağıdaki kodları gradle.properties dosyasına ekleyin.

 
###### Jacoco
codeCoveragePercent=0.50
 
## Gitignore

Buradan projenin root klasöründe 
config klasörü oluşacak fakat o klasörü git repositorisine yüklemeye gerek yok.

<code> /config/ </code> ifadesini .gitignore dosyasına ekleyin. (varsa .dockerignore dosyasına da)



## örnek

* ui projeleri için kullanım: [example-ui](example-ui)
* api projeleri için kullanım: [example-api](example-api)
* diğer jar projeleri için kullanım: [example-jar](example-jar)