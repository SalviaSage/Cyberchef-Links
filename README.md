# Cyberchef-Links
*This repository has specific links to Cyberchef converters for doing specific tasks.*

__URL Decoder (commas, parentheses and apostrophes):__  
https://gchq.github.io/CyberChef/#recipe=Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%5C%27%27%7D%2C%27%2527%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Regex%27%2C%27string%27:%27%2C%27%7D%2C%27%252C%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Extended%20%28%5C%5Cn%2C%20%5C%5Ct%2C%20%5C%5Cx...%29%27%2C%27string%27:%27%28%27%7D%2C%27%2528%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29Find_/_Replace%28%7B%27option%27:%27Extended%20%28%5C%5Cn%2C%20%5C%5Ct%2C%20%5C%5Cx...%29%27%2C%27string%27:%27%29%27%7D%2C%27%2529%27%2Ctrue%2Cfalse%2Ctrue%2Cfalse%29

__String Reverser:__  
https://gchq.github.io/CyberChef/#recipe=Reverse('Character')

__String to Windows Registry Hex Converter:__  
https://gchq.github.io/CyberChef/#recipe=Find_/_Replace(%7B'option':'Extended%20(%5C%5Cn,%20%5C%5Ct,%20%5C%5Cx...)','string':'%5C%5Cn'%7D,'%5C%5Cr%5C%5Cn',true,false,true,false)Encode_text('UTF-16LE%20(1200)')Find_/_Replace(%7B'option':'Regex','string':'%5E'%7D,'%5C%5Cxff%5C%5Cxfe',true,false,false,false/disabled)Find_/_Replace(%7B'option':'Regex','string':'$'%7D,'%5C%5C0%5C%5C0',true,false,true,false/disabled)To_Hex('Comma',0)

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

__URL Parser:__  
(This helps in seeing and identifying the different parts of a URL)  
https://regexr.com/3ok5o

__Number Westernizer:__  
(converts number graphemes of all other writing systems to ours, like ٠١٢٣٤٥٦٧٨٩ becomes 0123456789)  
https://gchq.github.io/CyberChef/#recipe=Comment('Bengali')Substitute('%E0%A7%A6%E0%A7%A7%E0%A7%A8%E0%A7%A9%E0%A7%AA%E0%A7%AB%E0%A7%AC%E0%A7%AD%E0%A7%AE%E0%A7%AF','0123456789')Comment('Gurmukhi')Substitute('%E0%A9%A6%E0%A9%A7%E0%A9%A8%E0%A9%A9%E0%A9%AA%E0%A9%AB%E0%A9%AC%E0%A9%AD%E0%A9%AE%E0%A9%AF','0123456789')Comment('Gujarati')Substitute('%E0%AB%A6%E0%AB%A7%E0%AB%A8%E0%AB%A9%E0%AB%AA%E0%AB%AB%E0%AB%AC%E0%AB%AD%E0%AB%AE%E0%AB%AF','0123456789')Comment('Devanagari')Substitute('%E0%A5%A6%E0%A5%A7%E0%A5%A8%E0%A5%A9%E0%A5%AA%E0%A5%AB%E0%A5%AC%E0%A5%AD%E0%A5%AE%E0%A5%AF','0123456789')Comment('Arabic-Persian')Substitute('%D9%A0%DB%B1%DB%B2%DB%B3%D9%A4%D9%A5%D9%A6%DB%B7%DB%B8%DB%B9%DB%B4%DB%B5%DB%B6%D9%AB%D8%8C%D9%AC','0123456789456.,,')

__Small Caps Converter:__  
(converts lower case and upper case letters to "small caps" letters.)
https://cyberchef.org/#recipe=Comment('Upper%20Case%20/%20Lower%20Case%5CnSmall%20Caps%20Converter')Substitute('ABCDEFGHIJKLMNOPQRSTUVWXYZ','%E1%B4%80%CA%99%E1%B4%84%E1%B4%85%E1%B4%87%EA%9C%B0%C9%A2%CA%9C%C9%AA%E1%B4%8A%E1%B4%8B%CA%9F%E1%B4%8D%C9%B4%E1%B4%8F%E1%B4%98%EA%9E%AF%CA%80%EA%9C%B1%E1%B4%9B%E1%B4%9C%E1%B4%A0%E1%B4%A1x%CA%8F%E1%B4%A2',false)Substitute('abcdefghijklmnopqrstuvwxyz','%E1%B4%80%CA%99%E1%B4%84%E1%B4%85%E1%B4%87%EA%9C%B0%C9%A2%CA%9C%C9%AA%E1%B4%8A%E1%B4%8B%CA%9F%E1%B4%8D%C9%B4%E1%B4%8F%E1%B4%98%EA%9E%AF%CA%80%EA%9C%B1%E1%B4%9B%E1%B4%9C%E1%B4%A0%E1%B4%A1x%CA%8F%E1%B4%A2',false)&oenc=65001

__Small Caps Converter (ALTERNATE):__  
(converts lower case and upper case letters to "small caps" letters.)
https://cyberchef.org/#recipe=Comment('Upper%20Case%20/%20Lower%20Case%5CnSmall%20Caps%20Converter%20(ALTERNATE)')Substitute('ABCDEFGHIJKLMNOPQRSTUVWXYZ','%E1%B4%80%CA%99%E1%B4%84%E1%B4%85%E1%B4%87%EA%9C%B0%C9%A2%CA%9C%C9%AA%E1%B4%8A%E1%B4%8B%CA%9F%E1%B4%8D%C9%B4%E1%B4%8F%E1%B4%98%C7%AB%CA%80%EA%9C%B1%E1%B4%9B%E1%B4%9C%E1%B4%A0%E1%B4%A1x%CA%8F%E1%B4%A2',false)Substitute('abcdefghijklmnopqrstuvwxyz','%E1%B4%80%CA%99%E1%B4%84%E1%B4%85%E1%B4%87%EA%9C%B0%C9%A2%CA%9C%C9%AA%E1%B4%8A%E1%B4%8B%CA%9F%E1%B4%8D%C9%B4%E1%B4%8F%E1%B4%98%C7%AB%CA%80%EA%9C%B1%E1%B4%9B%E1%B4%9C%E1%B4%A0%E1%B4%A1x%CA%8F%E1%B4%A2',false)&oenc=65001

__Small Caps to Small Case Converter:__  
https://gchq.github.io/CyberChef/#recipe=Comment('Small%20Caps%20to%20Lower%20Case%20Converter')Substitute('%E1%B4%80%CA%99%E1%B4%84%E1%B4%85%E1%B4%87%EA%9C%B0%C9%A2%CA%9C%C9%AA%E1%B4%8A%E1%B4%8B%CA%9F%E1%B4%8D%C9%B4%E1%B4%8F%E1%B4%98%EA%9E%AF%CA%80%EA%9C%B1%E1%B4%9B%E1%B4%9C%E1%B4%A0%E1%B4%A1x%CA%8F%E1%B4%A2','abcdefghijklmnopqrstuvwxyz')

__Small Caps to Small Case Converter (ALTERNATE):__  
https://gchq.github.io/CyberChef/#recipe=Comment('Small%20Caps%20to%20Lower%20Case%20Converter%20(ALTERNATE)')Substitute('%E1%B4%80%CA%99%E1%B4%84%E1%B4%85%E1%B4%87%EA%9C%B0%C9%A2%CA%9C%C9%AA%E1%B4%8A%E1%B4%8B%CA%9F%E1%B4%8D%C9%B4%E1%B4%8F%E1%B4%98%C7%AB%CA%80%EA%9C%B1%E1%B4%9B%E1%B4%9C%E1%B4%A0%E1%B4%A1x%CA%8F%E1%B4%A2','abcdefghijklmnopqrstuvwxyz')

__Roman Numeral Converter:__  
https://www.calculatorsoup.com/calculators/conversions/roman-numeral-converter.php#:~:text=Roman%20numerals%20are%20a%20number%20system%20developed%20in,3%2C999%20use%20the%20table%20below%20for%20converter%20inputs.

__Roman Numeral Date Converter:__  
https://www.calculatorsoup.com/calculators/conversions/roman-numeral-date-converter.php

__Numbers to Words Converter:__  
https://www.calculatorsoup.com/calculators/conversions/numberstowords.php

__Number and Words Standard Notation Converter:__  
https://www.calculatorsoup.com/calculators/math/number-word-notation-to-standard.php

__Half Width & Full Width Converter (commas, parentheses and apostrophes):__  
https://dencode.com/en/string/character-width

__Small Case to Capital Case Converter for the Greek Alphabet:__  
(converts lower case greek letters to capital greek letters.)
https://cyberchef.org/#recipe=Comment('GREEK%20ALPHABET;%5CnSmall%20Case%20to%20Capital%20Case%20Converter%5Cn')Substitute('%CE%B1%CE%B2%CE%B3%CE%B4%CE%B5%CE%B6%CE%B7%CE%B8%CE%B9%CE%BA%CE%BB%CE%BC%CE%BD%CE%BE%CE%BF%CF%80%CF%81%CF%83%CF%82%CF%84%CF%85%CF%86%CF%87%CF%88%CF%89','%CE%91%CE%92%CE%93%CE%94%CE%95%CE%96%CE%97%CE%98%CE%99%CE%9A%CE%9B%CE%9C%CE%9D%CE%9E%CE%9F%CE%A0%CE%A1%CE%A3%CE%A3%CE%A4%CE%A5%CE%A6%CE%A7%CE%A8%CE%A9',false)Substitute('%CE%B1%CE%B2%CE%B3%CE%B4%CE%B5%CE%B6%CE%B7%CE%B8%CE%B9%CE%BA%CE%BB%CE%BC%CE%BD%CE%BE%CE%BF%CF%80%CF%81%CF%83%CF%82%CF%84%CF%85%CF%86%CF%87%CF%88%CF%89','%CE%91%CE%92%CE%93%CE%94%CE%95%CE%96%CE%97%CE%98%CE%99%CE%9A%CE%9B%CE%9C%CE%9D%CE%9E%CE%9F%CE%A0%CE%A1%CE%A3%CF%B9%CE%A4%CE%A5%CE%A6%CE%A7%CE%A8%CE%A9',false/disabled)Substitute('%CE%AC%CE%AD%CE%AE%CE%AF%CF%8C%CF%8D%CF%8E','%CE%86%CE%88%CE%89%CE%8A%CE%8C%CE%8E%CE%8F',false)Substitute('%CF%8A%CF%8B','%CE%AA%CE%AB',false)&oenc=65001

__Hiragana—Katakana Converter:__  
https://cyberchef.org/#recipe=Comment('HIRAGANA%E2%80%94KATAKANA%20CONVERTER;%5CnConverts%20texts%20between%20Hiragana%20and%20Katakana.')Comment('81%20Letters%20(78%20letters%20%2B%203%20archaic%20letters)%5Cn2%20punctuation%20marks')Comment('Composite%20Characters:%20%E3%82%8F%E3%82%99%E3%82%90%E3%82%99%E3%82%91%E3%82%99%E3%82%92%E3%82%99%E2%80%94%E3%83%AF%E3%82%99%E3%83%B0%E3%82%99%E3%83%B1%E3%82%99%E3%83%B2%E3%82%99%5CnObsolete%20Characters:%20%F0%9B%80%86%F0%9B%80%81%F0%9B%84%9F%E2%80%94%F0%9B%84%A0%F0%9B%84%A1%F0%9B%84%A2%5CnCannot%20convert%20these%204%20Katakana%20letters:%20%E3%83%B7%E3%83%B8%E3%83%B9%E3%83%BA'/disabled)Substitute('%E3%82%8F%E3%82%99%E3%82%90%E3%82%99%E3%82%91%E3%82%99%E3%82%92%E3%82%99%E3%83%AF%E3%82%99%E3%83%B0%E3%82%99%E3%83%B1%E3%82%99%E3%83%B2%E3%82%99','%E3%83%AF%E3%82%99%E3%83%B0%E3%82%99%E3%83%B1%E3%82%99%E3%83%B2%E3%82%99%E3%82%8F%E3%82%99%E3%82%90%E3%82%99%E3%82%91%E3%82%99%E3%82%92%E3%82%99',false/disabled)Substitute('%E3%81%82%E3%81%88%E3%81%84%E3%81%8A%E3%81%86%E3%82%A2%E3%82%A8%E3%82%A4%E3%82%AA%E3%82%A6','%E3%82%A2%E3%82%A8%E3%82%A4%E3%82%AA%E3%82%A6%E3%81%82%E3%81%88%E3%81%84%E3%81%8A%E3%81%86',false)Substitute('%E3%81%8B%E3%81%8C%E3%81%8D%E3%81%8E%E3%81%8F%E3%81%90%E3%81%91%E3%81%92%E3%81%93%E3%81%94%E3%81%95%E3%81%96%E3%81%97%E3%81%98%E3%81%99%E3%81%9A%E3%81%9B%E3%81%9C%E3%81%9D%E3%81%9E%E3%81%9F%E3%81%A0%E3%81%A1%E3%81%A2%E3%81%A4%E3%81%A5%E3%81%A6%E3%81%A7%E3%81%A8%E3%81%A9%E3%81%AA%E3%81%AB%E3%81%AC%E3%81%AD%E3%81%AE%E3%81%AF%E3%81%B0%E3%81%B1%E3%81%B2%E3%81%B3%E3%81%B4%E3%81%B5%E3%81%B6%E3%81%B7%E3%81%B8%E3%81%B9%E3%81%BA%E3%81%BB%E3%81%BC%E3%81%BD%E3%81%BE%E3%81%BF%E3%82%80%E3%82%81%E3%82%82%E3%82%84%E3%82%86%E3%82%88%E3%82%89%E3%82%8A%E3%82%8B%E3%82%8C%E3%82%8D%E3%82%8F%E3%82%90%E3%82%91%E3%82%92%E3%82%94%E3%82%93%E3%82%AB%E3%82%AC%E3%82%AD%E3%82%AE%E3%82%AF%E3%82%B0%E3%82%B1%E3%82%B2%E3%82%B3%E3%82%B4%E3%82%B5%E3%82%B6%E3%82%B7%E3%82%B8%E3%82%B9%E3%82%BA%E3%82%BB%E3%82%BC%E3%82%BD%E3%82%BE%E3%82%BF%E3%83%80%E3%83%81%E3%83%82%E3%83%84%E3%83%85%E3%83%86%E3%83%87%E3%83%88%E3%83%89%E3%83%8A%E3%83%8B%E3%83%8C%E3%83%8D%E3%83%8E%E3%83%8F%E3%83%90%E3%83%91%E3%83%92%E3%83%93%E3%83%94%E3%83%95%E3%83%96%E3%83%97%E3%83%98%E3%83%99%E3%83%9A%E3%83%9B%E3%83%9C%E3%83%9D%E3%83%9E%E3%83%9F%E3%83%A0%E3%83%A1%E3%83%A2%E3%83%A4%E3%83%A6%E3%83%A8%E3%83%A9%E3%83%AA%E3%83%AB%E3%83%AC%E3%83%AD%E3%83%AF%E3%83%B0%E3%83%B1%E3%83%B2%E3%83%B4%E3%83%B3','%E3%82%AB%E3%82%AC%E3%82%AD%E3%82%AE%E3%82%AF%E3%82%B0%E3%82%B1%E3%82%B2%E3%82%B3%E3%82%B4%E3%82%B5%E3%82%B6%E3%82%B7%E3%82%B8%E3%82%B9%E3%82%BA%E3%82%BB%E3%82%BC%E3%82%BD%E3%82%BE%E3%82%BF%E3%83%80%E3%83%81%E3%83%82%E3%83%84%E3%83%85%E3%83%86%E3%83%87%E3%83%88%E3%83%89%E3%83%8A%E3%83%8B%E3%83%8C%E3%83%8D%E3%83%8E%E3%83%8F%E3%83%90%E3%83%91%E3%83%92%E3%83%93%E3%83%94%E3%83%95%E3%83%96%E3%83%97%E3%83%98%E3%83%99%E3%83%9A%E3%83%9B%E3%83%9C%E3%83%9D%E3%83%9E%E3%83%9F%E3%83%A0%E3%83%A1%E3%83%A2%E3%83%A4%E3%83%A6%E3%83%A8%E3%83%A9%E3%83%AA%E3%83%AB%E3%83%AC%E3%83%AD%E3%83%AF%E3%83%B0%E3%83%B1%E3%83%B2%E3%83%B4%E3%83%B3%E3%81%8B%E3%81%8C%E3%81%8D%E3%81%8E%E3%81%8F%E3%81%90%E3%81%91%E3%81%92%E3%81%93%E3%81%94%E3%81%95%E3%81%96%E3%81%97%E3%81%98%E3%81%99%E3%81%9A%E3%81%9B%E3%81%9C%E3%81%9D%E3%81%9E%E3%81%9F%E3%81%A0%E3%81%A1%E3%81%A2%E3%81%A4%E3%81%A5%E3%81%A6%E3%81%A7%E3%81%A8%E3%81%A9%E3%81%AA%E3%81%AB%E3%81%AC%E3%81%AD%E3%81%AE%E3%81%AF%E3%81%B0%E3%81%B1%E3%81%B2%E3%81%B3%E3%81%B4%E3%81%B5%E3%81%B6%E3%81%B7%E3%81%B8%E3%81%B9%E3%81%BA%E3%81%BB%E3%81%BC%E3%81%BD%E3%81%BE%E3%81%BF%E3%82%80%E3%82%81%E3%82%82%E3%82%84%E3%82%86%E3%82%88%E3%82%89%E3%82%8A%E3%82%8B%E3%82%8C%E3%82%8D%E3%82%8F%E3%82%90%E3%82%91%E3%82%92%E3%82%94%E3%82%93',false)Substitute('%F0%9B%80%86%F0%9B%80%81%F0%9B%84%9F%F0%9B%84%A0%F0%9B%84%A1%F0%9B%84%A2','%F0%9B%84%A0%F0%9B%84%A1%F0%9B%84%A2%F0%9B%80%86%F0%9B%80%81%F0%9B%84%9F',false)Substitute('%E3%82%9D%E3%82%9E%E3%83%BD%E3%83%BE','%E3%83%BD%E3%83%BE%E3%82%9D%E3%82%9E',false)&oenc=65001

__Nuskhuri—Mkehdruli Converter for the Georgian Language:__  
https://cyberchef.org/#recipe=Comment('NUSKHURI%E2%80%94MKHEDRULI%20CONVERTER;%5CnConverts%20texts%20between%20Nuskhuri%20and%20Mkhedruli%20alphabets%20for%20the%20Georgian%20language.%5Cn%5Cn40%20Letters.')Substitute('%E2%B4%80%E2%B4%81%E2%B4%82%E2%B4%83%E2%B4%84%E2%B4%85%E2%B4%86%E2%B4%A1%E2%B4%87%E2%B4%88%E2%B4%89%E2%B4%8A%E2%B4%8B%E2%B4%8C%E2%B4%A2%E2%B4%8D%E2%B4%8E%E2%B4%8F%E2%B4%90%E2%B4%91%E2%B4%92%E2%B4%A3%E2%B4%93%E2%B4%A7%E2%B4%94%E2%B4%95%E2%B4%96%E2%B4%97%E2%B4%98%E2%B4%99%E2%B4%9A%E2%B4%9B%E2%B4%9C%E2%B4%9D%E2%B4%9E%E2%B4%A4%E2%B4%9F%E2%B4%A0%E2%B4%A5%E2%B4%AD%E1%83%90%E1%83%91%E1%83%92%E1%83%93%E1%83%94%E1%83%95%E1%83%96%E1%83%B1%E1%83%97%E1%83%98%E1%83%99%E1%83%9A%E1%83%9B%E1%83%9C%E1%83%B2%E1%83%9D%E1%83%9E%E1%83%9F%E1%83%A0%E1%83%A1%E1%83%A2%E1%83%B3%E1%83%A3%E1%83%B7%E1%83%A4%E1%83%A5%E1%83%A6%E1%83%A7%E1%83%A8%E1%83%A9%E1%83%AA%E1%83%AB%E1%83%AC%E1%83%AD%E1%83%AE%E1%83%B4%E1%83%AF%E1%83%B0%E1%83%B5%E1%83%BD','%E1%83%90%E1%83%91%E1%83%92%E1%83%93%E1%83%94%E1%83%95%E1%83%96%E1%83%B1%E1%83%97%E1%83%98%E1%83%99%E1%83%9A%E1%83%9B%E1%83%9C%E1%83%B2%E1%83%9D%E1%83%9E%E1%83%9F%E1%83%A0%E1%83%A1%E1%83%A2%E1%83%B3%E1%83%A3%E1%83%B7%E1%83%A4%E1%83%A5%E1%83%A6%E1%83%A7%E1%83%A8%E1%83%A9%E1%83%AA%E1%83%AB%E1%83%AC%E1%83%AD%E1%83%AE%E1%83%B4%E1%83%AF%E1%83%B0%E1%83%B5%E1%83%BD%E2%B4%80%E2%B4%81%E2%B4%82%E2%B4%83%E2%B4%84%E2%B4%85%E2%B4%86%E2%B4%A1%E2%B4%87%E2%B4%88%E2%B4%89%E2%B4%8A%E2%B4%8B%E2%B4%8C%E2%B4%A2%E2%B4%8D%E2%B4%8E%E2%B4%8F%E2%B4%90%E2%B4%91%E2%B4%92%E2%B4%A3%E2%B4%93%E2%B4%A7%E2%B4%94%E2%B4%95%E2%B4%96%E2%B4%97%E2%B4%98%E2%B4%99%E2%B4%9A%E2%B4%9B%E2%B4%9C%E2%B4%9D%E2%B4%9E%E2%B4%A4%E2%B4%9F%E2%B4%A0%E2%B4%A5%E2%B4%AD',true)&input=4rSA4rSB4rSC4rSD4rSE4rSF4rSG4rSh4rSH4rSI4rSJ4rSK4rSL4rSM4rSi4rSN4rSO4rSP4rSQ4rSR4rSS4rSj4rST4rSn4rSU4rSV4rSW4rSX4rSY4rSZ4rSa4rSb4rSc4rSd4rSe4rSk4rSf4rSg4rSl4rStCuGDkOGDkeGDkuGDk%2BGDlOGDleGDluGDseGDl%2BGDmOGDmeGDmuGDm%2BGDnOGDsuGDneGDnuGDn%2BGDoOGDoeGDouGDs%2BGDo%2BGDt%2BGDpOGDpeGDpuGDp%2BGDqOGDqeGDquGDq%2BGDrOGDreGDruGDtOGDr%2BGDsOGDteGDvQoK4YKg4YKh4YKi4YKj4YKk4YKl4YKm4YOB4YKn4YKo4YKp4YKq4YKr4YKs4YOC4YKt4YKu4YKv4YKw4YKx4YKy4YOD4YKz4YOH4YK04YK14YK24YK34YK44YK54YK64YK74YK84YK94YK%2B4YOE4YK/4YOA4YOF4YONCuGykOGykeGykuGyk%2BGylOGyleGyluGyseGyl%2BGymOGymeGymuGym%2BGynOGysuGyneGynuGyn%2BGyoOGyoeGyouGys%2BGyo%2BGyt%2BGypOGypeGypuGyp%2BGyqOGyqeGyquGyq%2BGyrOGyreGyruGytOGyr%2BGysOGyteGyvQ&oenc=65001

__Serbian Cyrillic—Latin Converter for the Serbian Language:__ 
https://cyberchef.org/#recipe=Comment('SERBAN%20CYRILLIC%E2%80%94LATIN%20CONVERTER;%5CnConverts%20texts%20between%20Cyrillic%20and%20Latin%20alphabets%20for%20the%20Serbian%20language.%5Cn%5Cn30%20Letters.')Substitute('%D0%B0%D0%B1%D0%B2%D0%B3%D0%B4%D1%92%D0%B5%D0%B6%D0%B7%D0%B8%D1%98%D0%BA%D0%BB%D1%99%D0%BC%D0%BD%D1%9A%D0%BE%D0%BF%D1%80%D1%81%D1%82%D1%9B%D1%83%D1%84%D1%85%D1%86%D1%87%D1%9F%D1%88abvgd%C4%91e%C5%BEzijkl%C7%89mn%C7%8Coprst%C4%87ufhc%C4%8D%C7%86%C5%A1','abvgd%C4%91e%C5%BEzijkl%C7%89mn%C7%8Coprst%C4%87ufhc%C4%8D%C7%86%C5%A1%D0%B0%D0%B1%D0%B2%D0%B3%D0%B4%D1%92%D0%B5%D0%B6%D0%B7%D0%B8%D1%98%D0%BA%D0%BB%D1%99%D0%BC%D0%BD%D1%9A%D0%BE%D0%BF%D1%80%D1%81%D1%82%D1%9B%D1%83%D1%84%D1%85%D1%86%D1%87%D1%9F%D1%88',true)&input=0LDQsdCy0LPQtNGS0LXQttC30LjRmNC60LvRmdC80L3RmtC%2B0L/RgNGB0YLRm9GD0YTRhdGG0YfRn9GICmFidmdkxJFlxb56aWprbMeJbW7HjG9wcnN0xId1ZmhjxI3HhsWhCgrQkNCR0JLQk9CU0ILQldCW0JfQmNCI0JrQm9CJ0JzQndCK0J7Qn9Cg0KHQotCL0KPQpNCl0KbQp9CP0KgKQUJWR0TEkEXFvVpJSktMx4dNTseKT1BSU1TEhlVGSEPEjMeExaA&oenc=65001
