# Tímaverkefni 3

> Verkefni 5. Samspil leturs, litavals 

> Verkefni 6. Myndvinnsla og myndnotkun

### Hannið vefsíðu samkvæmt kröfulýsingu hér að neðan

- Þema vefsíðunnar er **HAUST**
- Veljið myndefni úr myndabankanum **[PXHERE](https://pxhere.com/)**
  - Leitið (_search: autumn_) og veljið myndir sem eru viðeigandi
  - Notið vefsíðuna sem er hér: **[Haustlýsing](index.html)**
- vefsíðan á að vera með forsíðumynd í ` picture `
- Í ` main ` koma tveir dálkar 
	1. dálkur með texta (haustlýsing).  
	2. dálkur með mynd sem er með **gegnsæjum bakgrunni**, myndatexta og texta


### Leturval og tenglar

-  Tengið (_link_) leturgerð að eigin vali frá [Google Fonts](https://fonts.google.com/) 
-  Fjórir tenglar eru í efnisyfirliti sem vísa á aðrar vefsíður. Þegar búið er að smella á tengil í fær hann annan lit
- Efnisyfirlit `nav a:link` er með öðru stílsniði en `a:link`

### Litaval

- **Haustlitir**. Litaval bakgrunns og texta á að vera í samræmi við myndefni og umfjöllun vefsíðunnar
- Efnisyfirlit (_nav_) og neðanmálsgreinar (_footer_) eiga að vera aðgreint frá meginmálstexta (_main_) með bakgrunnslit

### Skipulag (_Mobile up layout_)

1.  Forsíðumynd í `picture` taginu hleðst í réttri stærð í vafra eftir skjástærð, myndina á að fjölfalda í eftirfarandi stærðum. 
    -   Farsímar (lóðrétt): 0rem - 37.5rem
	-   Farsímar (lárétt): 37.5rem
	- Spjaldtölvur 48rem
    - Fartölvur 60rem
	- Borðtölvur 80rem
2.  Myndir aðlagast skjástærðum eftir viðmiðum
	- 0 - 47rem, allt efni vefsíðu í einum dálki
	- 48rem, Í ` main ` eru 2 dálkar 
    - ` footer ` 3 dálkar, nafn nemanda, heimildaskrá og námsefni 

#### Mynd í hliðardálk

* Myndin á að vera með gagnsæjum grunni og vistuð í **webp eða .png** formati

* Auðveld leið til að maska út bakgrunn úr mynd í _Photopea_
    1. Í valslá efst veljið _"Layer"_, í valglugga veljið _"Raster mask"_ -> _"Reveal all"_
    2. slá inn **F** á lyklaborðið, þá birtist innsláttargluggi
    3. skrifið **remove** og forritið býður upp á _Remove bg_, veljið það
    4. Smellið á _"Enter/Return"_ og eftir nokkrar sekúndur er forritið búið að hreinsa bakgrunninn úr myndinni <br>(skoðið _"alpha"_ lagið í Layers valglugganum)
		* þessi aðferð er aðgengileg í Pro útgáfu :( eða horfið á 20 sek auglýsingu áður en algoriþminn fer af stað

#### Fyrirsöfn í _header

* Stillið fyrirsögnina ofaná forsíðumyndina með því að setja -mínus gildi á `header h1 { magin-bottom:  }` 
* Til að tryggja að fyrirsögni sé ofaná myndinni þarf gildi í `z-index` að vera hærra en á forsíðumyndinni 

> Athugið að það á <u>ekki<u> að nota **Rockitt** letrið eða litasamsetninguna úr æfingaverkefni 6.
---

### Námsmat  15%

-   2% Letur og litaval 
	-	Leturgerð sótt af Google fonts
	-	Mismunandi bakgrunnslitur í _header, main og footer_
-   1% Tenglar í efnisyfirliti hafa annan lit eftir að búið er að smella á þá
-   4% Rétt stærð fosíðumyndar eftir skjástærðum (_picture_)
	-   Farsímar (lóðrétt): 0 - 37.5rem
	-   Farsímar (lárétt): 37.5rem
	-   Spjaldtölvur: 48rem 
	-   Fartölvur: 60rem 
    -   Borðtölvur: 80rem 
-   2% Mynd í hliðardálk með gagnsæjum grunni (_transparent_)
-   1% Fyrirsögn er ofaná forsíðumyndinni
- 5% Æfingaverkefni

---

### Verkefnaskil

-   Skilið öllum myndum, html síðu, stílsíðu og æfingaverkefnum í verkefni 6 í Innu í **.zip** skrá

*Gangi þér vel* 👍
