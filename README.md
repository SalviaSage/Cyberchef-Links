# Cyberchef-Links
*This repository has specific links to Cyberchef converters for doing specific tasks.*

__URL Decoder (commas, parentheses and apostrophes):__  
https://gchq.github.io/CyberChef/#recipe=Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%5C%27%27%7D%2C%27%2527%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%2C%27%7D%2C%27%252C%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Extended%20%28%5C%5Cn%2C%20%5C%5Ct%2C%20%5C%5Cx...%29%27%2C%27string%27:%27%28%27%7D%2C%27%2528%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Extended%20%28%5C%5Cn%2C%20%5C%5Ct%2C%20%5C%5Cx...%29%27%2C%27string%27:%27%29%27%7D%2C%27%2529%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29

__String Reverser:__  
https://gchq.github.io/CyberChef/#recipe=Reverse('Character')

__String to Windows Registry Hex Converter:__  
https://gchq.github.io/CyberChef/#recipe=Find_/_Replace%28%7B'option':'Extended%20(%5C%5Cn,%20%5C%5Ct,%20%5C%5Cx...)','string':'%5C%5Cn'%7D,'%5C%5Cr%5C%5Cn',true,false,true,false%29Encode_text%28'UTF-16LE%20(1200)'%29Find_/_Replace(%7B'option':'Regex','string':'%5E'%7D,'%5C%5Cxff%5C%5Cxfe',true,false,true,false/disabled)Find_/_Replace(%7B'option':'Regex','string':'$'%7D,'%5C%5C0%5C%5C0',true,false,true,false/disabled)To_Hex('Comma')

__Windows Registry Hex to String Converter:__  
https://gchq.github.io/CyberChef/#recipe=From_Hex('Comma')Decode_text%28'UTF-16LE%20(1200)'%29

__String to Hex Converter:__
https://gchq.github.io/CyberChef/#recipe=To_Hex('Space',0)

__Hex to String Converter:__
https://gchq.github.io/CyberChef/#recipe=From_Hex('Auto')

__Single Byte Hex to Double Byte Hex Converter:__  
https://gchq.github.io/CyberChef/#recipe=From_Hex%28%27Auto%27%29Find_/_Replace%28%7B%27option%27:%27Extended%20%28%5C%5Cn%2C%20%5C%5Ct%2C%20%5C%5Cx...%29%27%2C%27string%27:%27%5C%5Cn%27%7D%2C%27%5C%5Cr%5C%5Cn%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Encode_text%28%27UTF-16LE%20%281200%29%27%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%5E%27%7D%2C%27%5C%5Cxff%5C%5Cxfe%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27$%27%7D%2C%27%5C%5C0%5C%5C0%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse/disabled%29To_Hex%28%27Comma%27%2C0%29

__Double Byte Hex to Single Byte Hex Converter:__  
https://regexr.com/59hev

__Number Westernizer:__  
(converts number graphemes of all other writing systems to ours, like ٠١٢٣٤٥٦٧٨٩ becomes 0123456789)  
INSERT LINK

__Devanagri to TPA Transliterator ( WIP, 2020-08-03 ):__  
https://gchq.github.io/CyberChef/#recipe=Comment%28%27Devanagari%20Transliterator%20%28%20WIP%20%29%5Cn%5CnNote%201:%20Word%20final%20consonants%20are%20not%20transliterated%20with%20a%20succeding%20vowel%27%29Comment%28%27COMBINING%20DIACRITICS%20%28%20ANUSVARA%20%29%20%E0%A4%83%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Comment%28%27COMBINING%20DIACRITICS%20%28%20VISARGA%20%29%20%E0%A4%83%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Comment%28%27BASE%20LETTERS%20%28%20VOCOIDS%20%29%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%85%27%7D%2C%27a%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%87%27%7D%2C%27%C9%A9%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%89%27%7D%2C%27u%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%8F%27%7D%2C%27e%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%93%27%7D%2C%27o%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%94%27%7D%2C%27%C9%94%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%90%27%7D%2C%27%E1%B4%87%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Comment%28%27BASE%20LETTERS%20%28%20CONTOIDS%20-%20NON%20ASPIRATED%20%29%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%95%27%7D%2C%27ka%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%9A%27%7D%2C%27%CA%86a%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%9F%27%7D%2C%27%CA%88%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%A4%27%7D%2C%27%E1%B4%9Ba%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%AA%27%7D%2C%27pa%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%97%27%7D%2C%27ga%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%9C%27%7D%2C%27%CA%93a%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%A1%27%7D%2C%27%C9%96a%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Comment%28%27Word%20final%20contoids%20%28non-aspirated%29%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Comment%28%27Word%20final%20contoids%20%28aspirated%29%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Comment%28%27COMBINED%20LETTERS%20%28%20CONSONANT%20CLUSTERS%20%29%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Comment%28%27PUNCTUATION%20MARKS%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%BD%27%7D%2C%27%CB%90%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A5%A4%27%7D%2C%27%EF%BD%A1%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A5%A5%27%7D%2C%27%EF%BD%A1%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Extended%20%28%5C%5Cn%2C%20%5C%5Ct%2C%20%5C%5Cx...%29%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Comment%28%27Sindhi%20Implosive%20Letters%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A5%BB%27%7D%2C%27%C9%A1%EF%BF%ACa%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A5%BC%27%7D%2C%27%C8%B7%EF%BF%ACa%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Comment%28%27Foreign%20letters%20and%20sounds%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A5%B9%27%7D%2C%27%CA%92a%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Comment%28%27Below%20are%20word%20by%20word%20transliterators%20as%20opposed%20to%20letter%20by%20letter%2C%20here%2C%20words%20that%20have%20irregular%20pronunciations%20are%20listed.%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%AC%E0%A4%B9%E0%A5%81%E0%A4%A4%27%7D%2C%27boho%E1%B4%9B%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse/disabled%29&input=4KSG4KSm4KS/IOCkruClh%2BCkgiDgpKrgpLDgpK7gpYfgpLbgpY3gpLXgpLAg4KSo4KWHIOCkhuCkleCkvuCktiDgpJTgpLAg4KSq4KWD4KSl4KWN4KS14KWAIOCkleClgCDgpLjgpYPgpLfgpY3gpJ/gpL8g4KSV4KWACuCklOCksCDgpKrgpYPgpKXgpY3gpLXgpYAg4KSs4KWH4KSh4KWM4KSyIOCklOCksCDgpLjgpYHgpKjgpLjgpL7gpKgg4KSq4KWc4KWAIOCkpeClgDsg4KSU4KSwIOCkl%2BCkueCksOClhyDgpJzgpLIg4KSV4KWHIOCkiuCkquCksCDgpIXgpKjgpY3gpKfgpL/gpK/gpL7gpLDgpL4g4KSl4KS%2BOiDgpKTgpKXgpL4g4KSq4KSw4KSu4KWH4KS24KWN4KS14KSwIOCkleCkviDgpIbgpKTgpY3gpK7gpL4g4KSc4KSyIOCkleClhyDgpIrgpKrgpLAg4KSu4KSj4KWN4KSh4KSy4KS%2B4KSk4KS%2BIOCkpeCkvuClpArgpKTgpKwg4KSq4KSw4KSu4KWH4KS24KWN4KS14KSwIOCkqOClhyDgpJXgpLngpL4sIOCkieCknOCkv%2BCkr%2BCkvuCksuCkviDgpLngpYs6IOCkpOCliyDgpIngpJzgpL/gpK/gpL7gpLLgpL4g4KS54KWLIOCkl%2BCkr%2BCkvuClpArgpJTgpLAg4KSq4KSw4KSu4KWH4KS24KWN4KS14KSwIOCkqOClhyDgpIngpJzgpL/gpK/gpL7gpLLgpYcg4KSV4KWLIOCkpuClh%2BCkluCkviDgpJXgpL8g4KSF4KSa4KWN4KSb4KS%2BIOCkueCliDsg4KSU4KSwIOCkquCksOCkruClh%2BCktuCljeCkteCksCDgpKjgpYcg4KSJ4KSc4KS/4KSv4KS%2B4KSy4KWHIOCkleCliyDgpIXgpKjgpY3gpKfgpL/gpK/gpL7gpLDgpYcg4KS44KWHIOCkheCksuCklyDgpJXgpL/gpK/gpL7gpaQK4KSU4KSwIOCkquCksOCkruClh%2BCktuCljeCkteCksCDgpKjgpYcg4KSJ4KSc4KS/4KSv4KS%2B4KSy4KWHIOCkleCliyDgpKbgpL/gpKgg4KSU4KSwIOCkheCkqOCljeCkp%2BCkv%2BCkr%2BCkvuCksOClhyDgpJXgpYsg4KSw4KS%2B4KSkIOCkleCkueCkvuClpCDgpKTgpKXgpL4g4KS44KS%2B4KSC4KSdIOCkueClgeCkiCDgpKvgpL/gpLAg4KSt4KWL4KSwIOCkueClgeCkhuClpCDgpIfgpLgg4KSq4KWN4KSw4KSV4KS%2B4KSwIOCkquCkueCkv%2BCksuCkviDgpKbgpL/gpKgg4KS54KWLIOCkl%2BCkr%2BCkvuClpQrgpKvgpL/gpLAg4KSq4KSw4KSu4KWH4KS24KWN4KS14KSwIOCkqOClhyDgpJXgpLngpL4sIOCknOCksiDgpJXgpYcg4KSs4KWA4KSaIOCkj%2BCklSDgpJDgpLjgpL4g4KSF4KSo4KWN4KSk4KSwIOCkueCliyDgpJXgpL8g4KSc4KSyIOCkpuCliyDgpK3gpL7gpJcg4KS54KWLIOCknOCkvuCkj%2BClpArgpKTgpKwg4KSq4KSw4KSu4KWH4KS24KWN4KS14KSwIOCkqOClhyDgpI/gpJUg4KSF4KSo4KWN4KSk4KSwIOCkleCksOCkleClhyDgpIngpLjgpJXgpYcg4KSo4KWA4KSa4KWHIOCkleClhyDgpJzgpLIg4KSU4KSwIOCkieCkuOCkleClhyDgpIrgpKrgpLAg4KSV4KWHIOCknOCksiDgpJXgpYsg4KSF4KSy4KSXIOCkheCksuCklyDgpJXgpL/gpK/gpL47IOCklOCksCDgpLXgpYjgpLjgpL4g4KS54KWAIOCkueCliyDgpJfgpK/gpL7gpaQK4KSU4KSwIOCkquCksOCkruClh%2BCktuCljeCkteCksCDgpKjgpYcg4KSJ4KS4IOCkheCkqOCljeCkpOCksCDgpJXgpYsg4KSG4KSV4KS%2B4KS2IOCkleCkueCkvuClpCDgpKTgpKXgpL4g4KS44KS%2B4KSC4KSdIOCkueClgeCkiCDgpKvgpL/gpLAg4KSt4KWL4KSwIOCkueClgeCkhuClpCDgpIfgpLgg4KSq4KWN4KSw4KSV4KS%2B4KSwIOCkpuClguCkuOCksOCkviDgpKbgpL/gpKgg4KS54KWLIOCkl%2BCkr%2BCkvuClpQrgpKvgpL/gpLAg4KSq4KSw4KSu4KWH4KS24KWN4KS14KSwIOCkqOClhyDgpJXgpLngpL4sIOCkhuCkleCkvuCktiDgpJXgpYcg4KSo4KWA4KSa4KWHIOCkleCkviDgpJzgpLIg4KSP4KSVIOCkuOCljeCkpeCkvuCkqCDgpK7gpYfgpIIg4KSH4KSV4KSf4KWN4KSg4KS%2BIOCkueCliyDgpJzgpL7gpI8g4KSU4KSwIOCkuOClguCkluClgCDgpK3gpYLgpK7gpL8g4KSm4KS/4KSW4KS%2B4KSIIOCkpuClhzsg4KSU4KSwIOCkteCliOCkuOCkviDgpLngpYAg4KS54KWLIOCkl%2BCkr%2BCkvuClpArgpJTgpLAg4KSq4KSw4KSu4KWH4KS24KWN4KS14KSwIOCkqOClhyDgpLjgpYLgpJbgpYAg4KSt4KWC4KSu4KS/IOCkleCliyDgpKrgpYPgpKXgpY3gpLXgpYAg4KSV4KS54KS%2BOyDgpKTgpKXgpL4g4KSc4KWLIOCknOCksiDgpIfgpJXgpJ/gpY3gpKDgpL4g4KS54KWB4KSGIOCkieCkuOCkleCliyDgpIngpLjgpKjgpYcg4KS44KSu4KWB4KSm4KWN4KSwIOCkleCkueCkvjog4KSU4KSwIOCkquCksOCkruClh%2BCktuCljeCkteCksCDgpKjgpYcg4KSm4KWH4KSW4KS%2BIOCkleCkvyDgpIXgpJrgpY3gpJvgpL4g4KS54KWI4KWkCuCkq%2BCkv%2BCksCDgpKrgpLDgpK7gpYfgpLbgpY3gpLXgpLAg4KSo4KWHIOCkleCkueCkviwg4KSq4KWD4KSl4KWN4KS14KWAIOCkuOClhyDgpLngpLDgpYAg4KSY4KS%2B4KS4LCDgpKTgpKXgpL4g4KSs4KWA4KScIOCkteCkvuCksuClhyDgpJvgpYvgpJ/gpYcg4KSb4KWL4KSf4KWHIOCkquClh%2BClnCwg4KSU4KSwIOCkq%2BCksuCkpuCkvuCkiCDgpLXgpYPgpJXgpY3gpLcg4KSt4KWAIOCknOCkv%2BCkqOCkleClhyDgpKzgpYDgpJwg4KSJ4KSo4KWN4KS54KWAIOCkruClh%2BCkgiDgpI/gpJUg4KSP4KSVIOCkleClgCDgpJzgpL7gpKTgpL8g4KSV4KWHIOCkheCkqOClgeCkuOCkvuCksCDgpLngpYvgpKTgpYcg4KS54KWI4KSCIOCkquClg%2BCkpeCljeCkteClgCDgpKrgpLAg4KSJ4KSX4KWH4KSCOyDgpJTgpLAg4KS14KWI4KS44KS%2BIOCkueClgCDgpLngpYsg4KSX4KSv4KS%2B4KWkCuCkpOCliyDgpKrgpYPgpKXgpY3gpLXgpYAg4KS44KWHIOCkueCksOClgCDgpJjgpL7gpLgsIOCklOCksCDgpJvgpYvgpJ/gpYcg4KSb4KWL4KSf4KWHIOCkquClh%2BClnCDgpJzgpL/gpKgg4KSu4KWH4KSCIOCkheCkquCkqOClgCDgpIXgpKrgpKjgpYAg4KSc4KS%2B4KSk4KS/IOCkleClhyDgpIXgpKjgpYHgpLjgpL7gpLAg4KSs4KWA4KScIOCkueCli%2BCkpOCkviDgpLngpYgsIOCklOCksCDgpKvgpLLgpKbgpL7gpIgg4KS14KWD4KSV4KWN4KS3IOCknOCkv%2BCkqOCkleClhyDgpKzgpYDgpJwg4KSP4KSVIOCkj%2BCklSDgpJXgpYAg4KSc4KS%2B4KSk4KS/IOCkleClhyDgpIXgpKjgpYHgpLjgpL7gpLAg4KSJ4KSo4KWN4KS54KWAIOCkruClh%2BCkgiDgpLngpYvgpKTgpYcg4KS54KWI4KSCIOCkieCkl%2BClhzsg4KSU4KSwIOCkquCksOCkruClh%2BCktuCljeCkteCksCDgpKjgpYcg4KSm4KWH4KSW4KS%2BIOCkleCkvyDgpIXgpJrgpY3gpJvgpL4g4KS54KWI4KWkCuCkpOCkpeCkviDgpLjgpL7gpILgpJ0g4KS54KWB4KSIIOCkq%2BCkv%2BCksCDgpK3gpYvgpLAg4KS54KWB4KSG4KWkIOCkh%2BCkuCDgpKrgpY3gpLDgpJXgpL7gpLAg4KSk4KWA4KS44KSw4KS%2BIOCkpuCkv%2BCkqCDgpLngpYsg4KSX4KSv4KS%2B4KWlCuCkq%2BCkv%2BCksCDgpKrgpLDgpK7gpYfgpLbgpY3gpLXgpLAg4KSo4KWHIOCkleCkueCkviwg4KSm4KS/4KSoIOCkleCliyDgpLDgpL7gpKQg4KS44KWHIOCkheCksuCklyDgpJXgpLDgpKjgpYcg4KSV4KWHIOCksuCkv%2BCkr%2BClhyDgpIbgpJXgpL7gpLYg4KSV4KWHIOCkheCkqOCljeCkpOCksCDgpK7gpYfgpIIg4KSc4KWN4KSv4KWL4KSk4KS/4KSv4KS%2B4KSCIOCkueCli%2BCkgjsg4KSU4KSwIOCkteClhyDgpJrgpL/gpKjgpY3gpLngpYvgpIIsIOCklOCksCDgpKjgpL/gpK/gpKQg4KS44KSu4KSv4KWL4KSCLCDgpJTgpLAg4KSm4KS/4KSo4KWL4KSCLCDgpJTgpLAg4KS14KSw4KWN4KS34KWL4KSCIOCkleClhyDgpJXgpL7gpLDgpKMg4KS54KWL4KSC4KWkCuCklOCksCDgpLXgpYcg4KSc4KWN4KSv4KWL4KSk4KS/4KSv4KS%2B4KSCIOCkhuCkleCkvuCktiDgpJXgpYcg4KSF4KSo4KWN4KSk4KSwIOCkruClh%2BCkgiDgpKrgpYPgpKXgpY3gpLXgpYAg4KSq4KSwIOCkquCljeCksOCkleCkvuCktiDgpKbgpYfgpKjgpYcg4KS14KS%2B4KSy4KWAIOCkreClgCDgpKDgpLngpLDgpYfgpII7IOCklOCksCDgpLXgpYjgpLjgpL4g4KS54KWAIOCkueCliyDgpJfgpK/gpL7gpaQK4KSk4KSsIOCkquCksOCkruClh%2BCktuCljeCkteCksCDgpKjgpYcg4KSm4KWLIOCkrOClnOClgCDgpJzgpY3gpK/gpYvgpKTgpL/gpK/gpL7gpIIg4KSs4KSo4KS%2B4KSI4KSCOyDgpIngpKgg4KSu4KWH4KSCIOCkuOClhyDgpKzgpZzgpYAg4KSc4KWN4KSv4KWL4KSk4KS/IOCkleCliyDgpKbgpL/gpKgg4KSq4KSwIOCkquCljeCksOCkreClgeCkpOCkviDgpJXgpLDgpKjgpYcg4KSV4KWHIOCksuCkv%2BCkr%2BClhywg4KSU4KSwIOCkm%2BCli%2BCkn%2BClgCDgpJzgpY3gpK/gpYvgpKTgpL8g4KSV4KWLIOCksOCkvuCkpCDgpKrgpLAg4KSq4KWN4KSw4KSt4KWB4KSk4KS%2BIOCkleCksOCkqOClhyDgpJXgpYcg4KSy4KS/4KSv4KWHIOCkrOCkqOCkvuCkr%2BCkvjog4KSU4KSwIOCkpOCkvuCksOCkvuCkl%2BCkoyDgpJXgpYsg4KSt4KWAIOCkrOCkqOCkvuCkr%2BCkvuClpArgpKrgpLDgpK7gpYfgpLbgpY3gpLXgpLAg4KSo4KWHIOCkieCkqCDgpJXgpYsg4KSG4KSV4KS%2B4KS2IOCkleClhyDgpIXgpKjgpY3gpKTgpLAg4KSu4KWH4KSCIOCkh%2BCkuOCksuCkv%2BCkr%2BClhyDgpLDgpJbgpL4g4KSV4KS/IOCkteClhyDgpKrgpYPgpKXgpY3gpLXgpYAg4KSq4KSwIOCkquCljeCksOCkleCkvuCktiDgpKbgpYfgpIIsCuCkpOCkpeCkviDgpKbgpL/gpKgg4KSU4KSwIOCksOCkvuCkpCDgpKrgpLAg4KSq4KWN4KSw4KSt4KWB4KSk4KS%2BIOCkleCksOClh%2BCkgiDgpJTgpLAg4KSJ4KSc4KS/4KSv4KS%2B4KSy4KWHIOCkleCliyDgpIXgpKjgpY3gpKfgpL/gpK/gpL7gpLDgpYcg4KS44KWHIOCkheCksuCklyDgpJXgpLDgpYfgpII6IOCklOCksCDgpKrgpLDgpK7gpYfgpLbgpY3gpLXgpLAg4KSo4KWHIOCkpuClh%2BCkluCkviDgpJXgpL8g4KSF4KSa4KWN4KSb4KS%2BIOCkueCliOClpArgpKTgpKXgpL4g4KS44KS%2B4KSC4KSdIOCkueClgeCkiCDgpKvgpL/gpLAg4KSt4KWL4KSwIOCkueClgeCkhuClpCDgpIfgpLgg4KSq4KWN4KSw4KSV4KS%2B4KSwIOCkmuCljOCkpeCkviDgpKbgpL/gpKgg4KS54KWLIOCkl%2BCkr%2BCkvuClpQrgpKvgpL/gpLAg4KSq4KSw4KSu4KWH4KS24KWN4KS14KSwIOCkqOClhyDgpJXgpLngpL4sIOCknOCksiDgpJzgpYDgpLXgpL/gpKQg4KSq4KWN4KSw4KS%2B4KSj4KS/4KSv4KWL4KSCIOCkuOClhyDgpKzgpLngpYHgpKQg4KS54KWAIOCkreCksCDgpJzgpL7gpI8sIOCklOCksCDgpKrgpJXgpY3gpLfgpYAg4KSq4KWD4KSl4KWN4KS14KWAIOCkleClhyDgpIrgpKrgpLAg4KSG4KSV4KS%2B4KS2IOCkleClhyDgpIXgpKjgpY3gpKTgpLAg4KSu4KWH4KSCIOCkieClnOClh%2BCkguClpArgpIfgpLjgpLLgpL/gpK/gpYcg4KSq4KSw4KSu4KWH4KS24KWN4KS14KSwIOCkqOClhyDgpJzgpL7gpKTgpL8g4KSc4KS%2B4KSk4KS/IOCkleClhyDgpKzgpZzgpYcg4KSs4KWc4KWHIOCknOCksi3gpJzgpKjgpY3gpKTgpYHgpJPgpIIg4KSV4KWALCDgpJTgpLAg4KSJ4KSoIOCkuOCkrCDgpJzgpYDgpLXgpL/gpKQg4KSq4KWN4KSw4KS%2B4KSj4KS/4KSv4KWL4KSCIOCkleClgCDgpK3gpYAg4KS44KWD4KS34KWN4KSf4KS/IOCkleClgCDgpJzgpYsg4KSa4KSy4KSk4KWHIOCkq%2BCkv%2BCksOCkpOClhyDgpLngpYjgpIIg4KSc4KS/4KSoIOCkuOClhyDgpJzgpLIg4KSs4KS54KWB4KSkIOCkueClgCDgpK3gpLAg4KSX4KSv4KS%2BIOCklOCksCDgpI/gpJUg4KSP4KSVIOCknOCkvuCkpOCkvyDgpJXgpYcg4KSJ4KWc4KSo4KWHIOCkteCkvuCksuClhyDgpKrgpJXgpY3gpLfgpL/gpK/gpYvgpIIg4KSV4KWAIOCkreClgCDgpLjgpYPgpLfgpY3gpJ/gpL8g4KSV4KWAOiDgpJTgpLAg4KSq4KSw4KSu4KWH4KS24KWN4KS14KSwIOCkqOClhyDgpKbgpYfgpJbgpL4g4KSV4KS/IOCkheCkmuCljeCkm%2BCkviDgpLngpYjgpaQK4KSU4KSwIOCkquCksOCkruClh%2BCktuCljeCkteCksCDgpKjgpYcg4KSv4KS5IOCkleCkueCkleClhyDgpIngpKjgpJXgpYsg4KSG4KS24KWA4KS3IOCkpuClgCwg4KSV4KS/IOCkq%2BClguCksuCliy3gpKvgpLLgpYssIOCklOCksCDgpLjgpK7gpYHgpKbgpY3gpLAg4KSV4KWHIOCknOCksiDgpK7gpYfgpIIg4KSt4KSwIOCknOCkvuCkkywg4KSU4KSwIOCkquCkleCljeCkt%2BClgCDgpKrgpYPgpKXgpY3gpLXgpYAg4KSq4KSwIOCkrOClneClh%2BCkguClpArgpKTgpKXgpL4g4KS44KS%2B4KSC4KSdIOCkueClgeCkiCDgpKvgpL/gpLAg4KSt4KWL4KSwIOCkueClgeCkhuClpCDgpIfgpLgg4KSq4KWN4KSw4KSV4KS%2B4KSwIOCkquCkvuCkguCkmuCkteCkvuCkgiDgpKbgpL/gpKgg4KS54KWLIOCkl%2BCkr%2BCkvuClpArgpKvgpL/gpLAg4KSq4KSw4KSu4KWH4KS24KWN4KS14KSwIOCkqOClhyDgpJXgpLngpL4sIOCkquClg%2BCkpeCljeCkteClgCDgpLjgpYcg4KSP4KSVIOCkj%2BCklSDgpJzgpL7gpKTgpL8g4KSV4KWHIOCknOClgOCkteCkv%2BCkpCDgpKrgpY3gpLDgpL7gpKPgpYAsIOCkheCksOCljeCkpeCkvuCkpCDgpJjgpLDgpYfgpLLgpYIg4KSq4KS24KWBLCDgpJTgpLAg4KSw4KWH4KSC4KSX4KSo4KWHIOCkteCkvuCksuClhyDgpJzgpKjgpY3gpKTgpYEsIOCklOCksCDgpKrgpYPgpKXgpY3gpLXgpYAg4KSV4KWHIOCkteCkqOCkquCktuClgSwg4KSc4KS%2B4KSk4KS/IOCknOCkvuCkpOCkvyDgpJXgpYcg4KSF4KSo4KWB4KS44KS%2B4KSwIOCkieCkpOCljeCkquCkqOCljeCkqCDgpLngpYvgpII7IOCklOCksCDgpLXgpYjgpLjgpL4g4KS54KWAIOCkueCliyDgpJfgpK/gpL7gpaQK4KS44KWLIOCkquCksOCkruClh%2BCktuCljeCkteCksCDgpKjgpYcg4KSq4KWD4KSl4KWN4KS14KWAIOCkleClhyDgpJzgpL7gpKTgpL8g4KSc4KS%2B4KSk4KS/IOCkleClhyDgpLXgpKgg4KSq4KS24KWB4KST4KSCIOCkleCliywg4KSU4KSwIOCknOCkvuCkpOCkvyDgpJzgpL7gpKTgpL8g4KSV4KWHIOCkmOCksOClh%2BCksuClgiDgpKrgpLbgpYHgpJPgpIIg4KSV4KWLLCDgpJTgpLAg4KSc4KS%2B4KSk4KS/IOCknOCkvuCkpOCkvyDgpJXgpYcg4KSt4KWC4KSu4KS/IOCkquCksCDgpLjgpKwg4KSw4KWH4KSC4KSX4KSo4KWHIOCkteCkvuCksuClhyDgpJzgpKjgpY3gpKTgpYHgpJPgpIIg4KSV4KWLIOCkrOCkqOCkvuCkr%2BCkvjog4KSU4KSwIOCkquCksOCkruClh%2BCktuCljeCkteCksCDgpKjgpYcg4KSm4KWH4KSW4KS%2BIOCkleCkvyDgpIXgpJrgpY3gpJvgpL4g4KS54KWI4KWkCuCkq%2BCkv%2BCksCDgpKrgpLDgpK7gpYfgpLbgpY3gpLXgpLAg4KSo4KWHIOCkleCkueCkviwg4KS54KSuIOCkruCkqOClgeCkt%2BCljeCkryDgpJXgpYsg4KSF4KSq4KSo4KWHIOCkuOCljeCkteCksOClguCkqiDgpJXgpYcg4KSF4KSo4KWB4KS44KS%2B4KSwIOCkheCkquCkqOClgCDgpLjgpK7gpL7gpKjgpKTgpL4g4KSu4KWH4KSCIOCkrOCkqOCkvuCkj%2BCkgjsg4KSU4KSwIOCkteClhyDgpLjgpK7gpYHgpKbgpY3gpLAg4KSV4KWAIOCkruCkm%2BCksuCkv%2BCkr%2BCli%2BCkgiwg4KSU4KSwIOCkhuCkleCkvuCktiDgpJXgpYcg4KSq4KSV4KWN4KS34KS/4KSv4KWL4KSCLCDgpJTgpLAg4KSY4KSw4KWH4KSy4KWCIOCkquCktuClgeCkk%2BCkgiwg4KSU4KSwIOCkuOCkvuCksOClgCDgpKrgpYPgpKXgpY3gpLXgpYAg4KSq4KSwLCDgpJTgpLAg4KS44KSsIOCksOClh%2BCkguCkl%2BCkqOClhyDgpLXgpL7gpLLgpYcg4KSc4KSo4KWN4KSk4KWB4KST4KSCIOCkquCksCDgpJzgpYsg4KSq4KWD4KSl4KWN4KS14KWAIOCkquCksCDgpLDgpYfgpILgpJfgpKTgpYcg4KS54KWI4KSCLCDgpIXgpKfgpL/gpJXgpL7gpLAg4KSw4KSW4KWH4KSC4KWkCuCkpOCkrCDgpKrgpLDgpK7gpYfgpLbgpY3gpLXgpLAg4KSo4KWHIOCkruCkqOClgeCkt%2BCljeCkryDgpJXgpYsg4KSF4KSq4KSo4KWHIOCkuOCljeCkteCksOClguCkqiDgpJXgpYcg4KSF4KSo4KWB4KS44KS%2B4KSwIOCkieCkpOCljeCkquCkqOCljeCkqCDgpJXgpL/gpK/gpL4sIOCkheCkquCkqOClhyDgpLngpYAg4KS44KWN4KS14KSw4KWC4KSqIOCkleClhyDgpIXgpKjgpYHgpLjgpL7gpLAg4KSq4KSw4KSu4KWH4KS24KWN4KS14KSwIOCkqOClhyDgpIngpLjgpJXgpYsg4KSJ4KSk4KWN4KSq4KSo4KWN4KSoIOCkleCkv%2BCkr%2BCkviwg4KSo4KSwIOCklOCksCDgpKjgpL7gpLDgpYAg4KSV4KSw4KSV4KWHIOCkieCkuOCkqOClhyDgpK7gpKjgpYHgpLfgpY3gpK/gpYvgpIIg4KSV4KWAIOCkuOClg%2BCkt%2BCljeCkn%2BCkvyDgpJXgpYDgpaQK4KSU4KSwIOCkquCksOCkruClh%2BCktuCljeCkteCksCDgpKjgpYcg4KSJ4KSoIOCkleCliyDgpIbgpLbgpYDgpLcg4KSm4KWAOiDgpJTgpLAg4KSJ4KSoIOCkuOClhyDgpJXgpLngpL4sIOCkq%2BClguCksuCliy3gpKvgpLLgpYssIOCklOCksCDgpKrgpYPgpKXgpY3gpLXgpYAg4KSu4KWH4KSCIOCkreCksCDgpJzgpL7gpJMsIOCklOCksCDgpIngpLjgpJXgpYsg4KSF4KSq4KSo4KWHIOCkteCktiDgpK7gpYfgpIIg4KSV4KSwIOCksuClizsg4KSU4KSwIOCkuOCkruClgeCkpuCljeCksCDgpJXgpYAg4KSu4KSb4KSy4KS/4KSv4KWL4KSCLCDgpKTgpKXgpL4g4KSG4KSV4KS%2B4KS2IOCkleClhyDgpKrgpJXgpY3gpLfgpL/gpK/gpYvgpIIsIOCklOCksCDgpKrgpYPgpKXgpY3gpLXgpYAg4KSq4KSwIOCksOClh%2BCkguCkl%2BCkqOClhyDgpLXgpL7gpLLgpYcg4KS44KSsIOCknOCkqOCljeCkpOClgeCkkyDgpKrgpLAg4KSF4KSn4KS/4KSV4KS%2B4KSwIOCksOCkluCli%2BClpArgpKvgpL/gpLAg4KSq4KSw4KSu4KWH4KS24KWN4KS14KSwIOCkqOClhyDgpIngpKgg4KS44KWHIOCkleCkueCkviwg4KS44KWB4KSo4KWLLCDgpJzgpL/gpKTgpKjgpYcg4KSs4KWA4KScIOCkteCkvuCksuClhyDgpJvgpYvgpJ/gpYcg4KSb4KWL4KSf4KWHIOCkquClh%2BClnCDgpLjgpL7gpLDgpYAg4KSq4KWD4KSl4KWN4KS14KWAIOCkleClhyDgpIrgpKrgpLAg4KS54KWI4KSCIOCklOCksCDgpJzgpL/gpKTgpKjgpYcg4KS14KWD4KSV4KWN4KS34KWL4KSCIOCkruClh%2BCkgiDgpKzgpYDgpJwg4KS14KS%2B4KSy4KWHIOCkq%2BCksiDgpLngpYvgpKTgpYcg4KS54KWI4KSCLCDgpLXgpYcg4KS44KSsIOCkruCliOCkgiDgpKjgpYcg4KSk4KWB4KSuIOCkleCliyDgpKbgpL/gpI8g4KS54KWI4KSCOyDgpLXgpYcg4KSk4KWB4KSu4KWN4KS54KS%2B4KSw4KWHIOCkreCli%2BCknOCkqCDgpJXgpYcg4KSy4KS/4KSv4KWHIOCkueCliOCkgjoK4KSU4KSwIOCknOCkv%2BCkpOCkqOClhyDgpKrgpYPgpKXgpY3gpLXgpYAg4KSV4KWHIOCkquCktuClgSwg4KSU4KSwIOCkhuCkleCkvuCktiDgpJXgpYcg4KSq4KSV4KWN4KS34KWALCDgpJTgpLAg4KSq4KWD4KSl4KWN4KS14KWAIOCkquCksCDgpLDgpYfgpILgpJfgpKjgpYcg4KS14KS%2B4KSy4KWHIOCknOCkqOCljeCkpOClgSDgpLngpYjgpIIsIOCknOCkv%2BCkqCDgpK7gpYfgpIIg4KSc4KWA4KS14KSoIOCkleClhyDgpKrgpY3gpLDgpL7gpKMg4KS54KWI4KSCLCDgpIngpKgg4KS44KSsIOCkleClhyDgpJbgpL7gpKjgpYcg4KSV4KWHIOCksuCkv%2BCkr%2BClhyDgpK7gpYjgpIIg4KSo4KWHIOCkuOCkrCDgpLngpLDgpYcg4KS54KSw4KWHIOCkm%2BCli%2BCkn%2BClhyDgpKrgpYfgpZwg4KSm4KS/4KSPIOCkueCliOCkgjsg4KSU4KSwIOCkteCliOCkuOCkviDgpLngpYAg4KS54KWLIOCkl%2BCkr%2BCkvuClpArgpKTgpKwg4KSq4KSw4KSu4KWH4KS24KWN4KS14KSwIOCkqOClhyDgpJzgpYsg4KSV4KWB4KSbIOCkrOCkqOCkvuCkr%2BCkviDgpKXgpL4sIOCkuOCkrCDgpJXgpYsg4KSm4KWH4KSW4KS%2BLCDgpKTgpYsg4KSV4KWN4KSv4KS%2BIOCkpuClh%2BCkluCkviwg4KSV4KS/IOCkteCkuSDgpKzgpLngpYHgpKQg4KS54KWAIOCkheCkmuCljeCkm%2BCkviDgpLngpYjgpaQg4KSk4KSl4KS%2BIOCkuOCkvuCkguCknSDgpLngpYHgpIgg4KSr4KS/4KSwIOCkreCli%2BCksCDgpLngpYHgpIbgpaQg4KSH4KS4IOCkquCljeCksOCkleCkvuCksCDgpJvgpKDgpLXgpL7gpIIg4KSm4KS/4KSoIOCkueCliyDgpJfgpK/gpL7gpaUK

__Gurmukhi to TPA Transliterator:__  
INSERT LINK

__Gujarati to TPA Transliterator:__  
INSERT LINK

__Arabic to TPA Transliterator:__  
INSERT LINK

__Katakana to TPA Transliterator:__  
INSERT LINK

__Hiragana to TPA Transliterator:__  
INSERT LINK
