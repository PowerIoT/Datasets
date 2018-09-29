# Datasets
Solarlogger, weather and cloud image datasets
* Epoch-time vs SumPac,  Epoch time dediğim (unix time)[https://tr.wikipedia.org/wiki/Unix_zaman] SumPac ise toplam üretilen ac güç.


## Solar-logger dataset
### Done
* 15.03.2018 - 22.08.2018 dataları tamam. Eksik dataları şu şekilde sınıflandırdım. 
  * 1-2 eksik data (14:00:00 ve 14:10:00 var 14:05:00 yok gibi)
  * 5-10 eksik data (eğer o gün bulutsuzsa kosinüse tamamladım.)
  * 10'dan daha fazla eksik: 11.06.2018 tarihinde bir buçuk saatlik bir kayıp var o günü komple sildim. 
  
 ## API Weather dataları
 * [Darksky API](https://darksky.net/forecast/40.7127,-74.0059/us12/en) adresini kullandım. Kullanıcı hesabını açtım. Data başına 10000 data noktası 1$. Datayı çekmeyle alakalı bir jupyter notebook hazırladım ihtiyaca göre çekilebilir. API key jupyter notebookta var. 
 * Şu anki datalarla ilgili bir sorun var. Kuruma mail attım. Bir daha bütün datayı çekmek gerekecek.
 
 ## Cloud Image
 * Örnek resimleri ekledim. Şu an düzenli çekemiyoruz hardware hazır olmadığından. Hardware konusunda ilerlediğimizde yine bu repoda depolarız.
