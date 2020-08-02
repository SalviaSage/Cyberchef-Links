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

__Number Westernizer:__  
(converts number graphemes of all other writing systems to ours, like ٠١٢٣٤٥٦٧٨٩ becomes 0123456789)  
INSERT LINK

__Devanagri to TPA Transliterator:__  
https://gchq.github.io/CyberChef/#recipe=Comment%28%27Devanagari%20Transliterator%20%28%20WIP%20%29%5Cn%5CnNote%201:%20Word%20final%20consonants%20are%20not%20transliterated%20with%20a%20succeding%20vowel%27%29Comment%28%27COMBINING%20DIACRITICS%20%28%20VISARGA%20%29%20%E0%A4%83%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Comment%28%27BASE%20LETTERS%20%28%20VOCOIDS%20%29%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Extended%20%28%5C%5Cn%2C%20%5C%5Ct%2C%20%5C%5Cx...%29%27%2C%27string%27:%27%E0%A4%85%27%7D%2C%27%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Extended%20%28%5C%5Cn%2C%20%5C%5Ct%2C%20%5C%5Cx...%29%27%2C%27string%27:%27%E0%A4%87%27%7D%2C%27%C9%A9%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Extended%20%28%5C%5Cn%2C%20%5C%5Ct%2C%20%5C%5Cx...%29%27%2C%27string%27:%27%E0%A4%89%27%7D%2C%27u%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Extended%20%28%5C%5Cn%2C%20%5C%5Ct%2C%20%5C%5Cx...%29%27%2C%27string%27:%27%E0%A4%8F%27%7D%2C%27e%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Extended%20%28%5C%5Cn%2C%20%5C%5Ct%2C%20%5C%5Cx...%29%27%2C%27string%27:%27%E0%A4%93%27%7D%2C%27o%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Extended%20%28%5C%5Cn%2C%20%5C%5Ct%2C%20%5C%5Cx...%29%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Extended%20%28%5C%5Cn%2C%20%5C%5Ct%2C%20%5C%5Cx...%29%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Comment%28%27BASE%20LETTERS%20%28%20CONTOIDS%20-%20NON%20ASPIRATED%20%29%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Extended%20%28%5C%5Cn%2C%20%5C%5Ct%2C%20%5C%5Cx...%29%27%2C%27string%27:%27%E0%A4%95%27%7D%2C%27na%27%2Ctrue%2Ctrue%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%97%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Comment%28%27Word%20final%20contoids%20%28non-aspirated%29%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Comment%28%27Word%20final%20contoids%20%28aspirated%29%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Comment%28%27COMBINED%20LETTERS%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%27%7D%2C%27%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Comment%28%27PUNCTUATION%20MARKS%27/disabled%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A4%BD%27%7D%2C%27%CB%90%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%E0%A5%A4%27%7D%2C%27.%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29&input=4KSo4KS%2B4KSo

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

*__Updated: 2020-04-21__*
