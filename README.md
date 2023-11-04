# English-Turkish Idioms

This repository contains a collection of English-Turkish idioms with their literal translations, English equivalents, and examples. The idioms are presented in a table format with four rows: Turkish idiom, literal translation, English equivalent, and example.

## Table Format

**The table format used in this repository is as follows:**
- a single idiom table
- first tr is the turkish idiom. Second td of first tr is the idiom
- second tr is the literal translation. Second td of second tr is the literal translation
- third tr is the english equivalent. third tr has only one td. It contains explanation, example sentence and english equivalent sentence.
- fourth tr is the example

```html
<figure class="wp-block-table">
    <table border="1" cellspacing="0" width="100%">
        <tbody>
            <tr>
                <td rowspan="4">1</td>
                <td width="30%"><strong><span class="has-inline-color has-vivid-purple-color">Turkish</span></strong></td>
                <td><em>Zaman her şeyin ilacıdır.</em></td>
            </tr>
            <tr>
                <td><strong><span class="has-inline-color has-pale-cyan-blue-color">Literally</span></strong></td>
                <td>Time is the medicine of everything.</td>
            </tr>
            <tr>
                <td><strong><span class="has-inline-color has-vivid-cyan-blue-color">Equivalent in English</span></strong></td>
                <td>Time is the best medicine.</td>
            </tr>
            <tr>
                <td colspan="3">
                    As time passes, all the troubles we experience are forgotten or the sorrow we feel decreases.<br/><br/>
                    <u>Example:</u><br/><br/>
                    <em>Üzülme, bugünler de geçecek; zaman her şeyin ilacıdır.</em><br/><br/>
                    “Don’t worry, these days will be over, too; time is the best medicine.”
                </td>
            </tr>
        </tbody>
    </table>
</figure>
```
## Web Scraping

Bu projede, belirli bir web sitesinden veri çekmek için web scraping yöntemi kullanılmıştır. Web scraping, bir web sitesinin HTML içeriğini çekmek ve bu içerikten belirli bilgileri çıkarmak için kullanılan bir tekniktir.

Python dilinde, BeautifulSoup ve requests gibi kütüphaneler bu işlemi kolaylaştırır. İlk olarak, `requests.get(URL)` ile hedef web sitesine bir HTTP isteği gönderilir. Sunucu, web sayfasının HTML içeriğini döndürerek bu isteğe yanıt verir.

Ardından, BeautifulSoup kütüphanesi ile bu HTML içeriği parse edilir ve veri çıkarımı yapılır. BeautifulSoup, HTML içeriğini ağaç yapısına dönüştürerek, içerik üzerinde kolayca gezinme ve arama yapmayı sağlar.

Önemli Not: Web scraping yaparken, hedef web sitesinin kullanım şartlarına ve gizlilik politikasına dikkat etmek önemlidir. Eğer bir web sitesi scraping'i açıkça yasaklıyorsa, bu site üzerinde scraping işlemi yapmamalıyız. Ayrıca, scraping işlemi, bir web sitesinin kaynaklarını yoğun bir şekilde kullanabilir ve bu durum site sahibine zarar verebilir. Bu nedenle, scraping işlemlerini sorumlu ve etik bir şekilde gerçekleştirmeliyiz.
