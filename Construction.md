Základní koncept konstrukce hangáru vychází z krychlovitého tvaru s rozevírající se vrchní částí a s veškerou elektronikou a výpočetní technikou umístěnou pod přistávací plochou. Mechanický design tak můžeme rozdělit na tři části a to základnu, střední část [Landing pad] a dveře

                            Obrázek : Model kompletní konstrukce hangáru

### 3.1 Použitý materiál
Při výběru materiálu na jednotlivé části mechanického designu bylo důležité splňovat stanovené kriteria potřebných vlastností (váha, pevnost), jednoduché manipulace s materiálem a nízké ceny. 

Stěžejním a nejvíce využitým materiálem je hliník v podobě stavebnivobého systému hliníkových profilů 30x30 B8, jenž je využit na kostru konstrukce. Díky modulárnosti těchto systémů jsme byli schopni vytvořit obrys o přesně stanovených rozměrech s možností snadné úpravy. Profily jsou k sobě uchyceny pomocí úhelníků a kladívkových šroubů.

                            Obrázek : Model obrysu konstrukce
                            
Dalším výrazným prvkem jsou stěny hangáru. Pro námi navrhnutý prototyp zařízení jsme využili desky o tloušťce 4 mm z plexiskla bílé barvy na míru nařezané za pomoci laseru. Zvažovali jsem také dřevěnou překližku či dibond, ale kvůli nevhodným parametrům jako je příliš vysoká cena či váha jsme využili plexisklo. Díky zmíněné modulárnosti stavebnicového systému profilů jsou veškeré desky vsunuty do drážek přiléhajících profilů a upevněny tak na místě. 

Využitým materiálem v části landing padu na přistávací plochu a na uchycení elektroniky jsou voděodolné dřevěné překližky. Zde byla překližka použita kvůli své pevnosti a jednoduchému opracování dřeva, což bylo nutné pro vytvoření přesných zářezů na přistávací ploše.

Velké zastoupení má také glykolem modifikovaný polyethylentereftalát (PET-G), jenž byl použit díky své poměrně vysoké odolnosti jakožto stěžejní materiál modelů získaných pomocí 3D tisku.

Značné zastoupení mají i nejrůznější slitiny kovů jakožto ocel, či mosaz v podobě využitých tyčí, šroubů a matic.

### 3.2 Základna hangáru 
Základna hangráu je mechanicky nejjednodušší částí. Jedná se o zakrytovaný kvádrovitý objekt, vněmž jsou umístěny záložní baterie s možností připojení ke stěžejní střední části landing padu. K landing padu se základna uchytí za pomoci závitových tyčí umístěných v každém rohovém profilu. Pro veškeré stěny konsturkce bylo využito plexisklo zasunuté do drážek profilů.

### 3.3 Střední část hangáru - "Landing pad"
V hlavní operační jednotce celého zařízení se skrývá přistávací plocha společně s nabíjecím mechanismem dronu a elektronikou. Pro stěny konstrukce bylo stejně jako u základny využito plexisklo. Pro vrchní a spodní stranu je však použita překližka kvůli vyšší pevnosti a jednoduché úpravě v podobě využití frézy na přesné zážezy. Na spodní překližkovou desku je uchycena veškerá elektronika. Horní deska slouží jako přistávací plocha pro dron. 

Dron je schopen přistát s přesností do 10 cm, proto je nutný mechanismus zarovnání dronu, jenž jej vystředí a zajistí tak spolehlivé nabíjení společně s bezpečnou dráhou vzletu.

                          Obrázek : Model landing padu

#### 3.3.1 Mechanismus zarovnání dronu
Každá část mechanismu je provedena 4x. Na každou stranu přistávací plochy jednou. Mechanismus je ovládán za pomoci motorů GA12-N20 - 12 V s převodovkou. Tyto motory jsou za pomoci šroubů uchyceny ze spodní části přistávací plochy na MODEL 1, jenž slouží jakožto vyztužení středu plochy. Na ose motoru je nasazen MODEL 2, jenž pohybuje s ozubeným řemenem. Řemen je přichycen k profilu za pomoci MODEL 3. Stěžejní částí je MODEL 4, jenž se za pomoci ozubeného řemene rozpohybovaného motorem pohybuje po kolejnici uchycené do MODEL 3. Všechny použité motory se pohybují vždy ve stejný okamžik. 

### 3.4 Dveře
Nejvýše položenou částí hangáru jsou dveře. Jedná se o pohyblivý mechanismus s účelem zakrytí dronu a jeho ochraně před nepříznivými jevy okolí a následným otevřením a uvolněním letové dráhy. Dveře jsou zakryty za pomoci desek plexiskla, kvůli nízké hmotnosti a rezistivitě vůči vodě. Pohyb je uskutečněn čtyřmi zpřevodovanými krokovými motory z řady NEMA 17 v zapojení se závitovými tyčemi. Dvě protější hrany figurují pro dveře jakožto osy otáčení a nachází se zde kovové panty.

#### 3.4.1 Mechanismus pohybu dveří (+ Výpočty??)
Použitým krokovým motorem pro pohyb dveří je NEMA 17 s jmenovitým proudem 1,68 A a napětím o hodnotě 2,8 V. Tento motor je zpřevodován planetovou převodovkou v poměru 50,9:1 a výsledný kroutící moment tak dosahuje velikosti o 6 Nm. (viz sekce 4).

Motor je, za pomoci kovového držáku, šrouby uchycen přímo do profilu. Na osu motoru je pomocí redukce pevně přichycena ocelová trapézová závitová tyč o velikosti závitu M8. Tato tyč je podpůrně upevněna k profilu za pomoci MODEL 5, aby nedošlo k jejímu zdeformování při zatížení. Na tyči je navinuta mosazná matice odpovídajících parametrů s připevněným MODEL 6. Tento model slouží jakožto redukce k připevnění tyče k MODEL 7. MODEL 7 figuruje jako jezdec po kolejnici tvořené z hliníkové tyče o průměru M10. Kolejnice je do profilu uchycena za pomoci MODEL 8. Mechanismus je použit celkem 4x. Pro každou stranu dveří jednou.

Při souběžné rotaci krokových motorů na každé straně dveří začne stoupat matice společně s MODEL 6 vzhůru a pomocí uchycení ke kolejnici tak odláčet dveře směrem vzhůru. Při zadání invertovaného příkazu krokovým motorům se začné trapézová tyč otáčet opačným směrem a dveře se zavřou.

### 3.5 Modely
Obrázek: MODEL 1 - Hvězdice k zachycení motorů

Obrázek: MODEL 2 - Ozubené kolo

Obrázek: MODEL 3 - Uchycení ozubeného řemene do profilu

Obrázek: MODEL 4 - Vystřeďovací model

Obrázek: MODEL 5 - Uchycení tyče do profilu

Obrázek: MODEL 6 - Model na matici

Obrázek: MODEL 7 - Jezdec na kolejnici

Obrázek: MODEL 8 - Uchycení kolejnice do profilu



