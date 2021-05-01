# Class4-Statistics-Week15
## Seaborn kütüphanesi içerisinde bulunan tittanic datasını kullanarak
```
# pip install seaborn
# seaborn kutuphanesini ustteki kod ile yukluyoruz
import seaborn as sns
tips = sns.load_dataset('titanic')
df = tips.copy()
print(df.head())
#kodlar araciligi ile titanic datasini yukluyoruz
```


## Titanic datasında bulunan,
### Değişkenlerin veri türlerini yazınız
- Nicel verileri describe methodu ile inceleyiniz ve verileri ortalaması, standart sapması ve çeyrekliklerine bakarak aykırılık olup olmadığını ve normal dağılıp dağılmadığı konusunda yorumda bulunun.
- Nitel verilerin dtypelarıını kategorik yapın. Sıralanabilecek kategorik değişkenlerin sıralı olarak belirleyiniz. Sıralanmış kategorik verilerin sıralaması doğru değilse sıralamayı uygun hale getirin.
- sex ve class değişkenlerini Label Encoder  veya Dummies yöntemiyle sayısal verierle dönüştürünüz.
- age ve fare değişkenlerinin normalliklerini inceleyiniz

## Hipotez Testleri:

### H0 hipotezi Titanik kazasında insanlarin sosyo ekonomik siniflari hayatta kalma oranlarına herhangi bir etkisi yoktur
### H1 hipotezi Titanik kazasında insanlarin sosyo ekonomik siniflari hayatta kalma oranlarına herhangi bir etkisi vardır.

### Hipotez test asamalrinin tamamini yukarda önerilen hipotez icin uygulayınız ve hipotezi dogrulayiniz.
