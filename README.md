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

__URL Parser:__  
https://regexr.com/3ok5o

__Number Westernizer:__  
(converts number graphemes of all other writing systems to ours, like ٠١٢٣٤٥٦٧٨٩ becomes 0123456789)  
https://gchq.github.io/CyberChef/#recipe=Substitute('%E0%A5%A6%E0%A5%A7%E0%A5%A8%E0%A5%A9%E0%A5%AA%E0%A5%AB%E0%A5%AC%E0%A5%AD%E0%A5%AE%E0%A5%AF','0123456789')Substitute('%DB%B0%DB%B1%DB%B2%DB%B3%DB%B4%DB%B5%DB%B6%DB%B7%DB%B8%DB%B9','0123456789')

__Small Caps Converter:__  
https://gchq.github.io/CyberChef/#recipe=Substitute('ABCDEFGHIJKLMNOPRSTUVWXYZ','%E1%B4%80%CA%99%E1%B4%84%E1%B4%85%E1%B4%87%EA%9C%B0%C9%A2%CA%9C%C9%AA%E1%B4%8A%E1%B4%8B%CA%9F%E1%B4%8D%C9%B4%E1%B4%8F%E1%B4%98%CA%80%EA%9C%B1%E1%B4%9B%E1%B4%9C%E1%B4%A0%E1%B4%A1x%CA%8F%E1%B4%A2')Substitute('abcdefghijklmnoprstuvwxyz','%E1%B4%80%CA%99%E1%B4%84%E1%B4%85%E1%B4%87%EA%9C%B0%C9%A2%CA%9C%C9%AA%E1%B4%8A%E1%B4%8B%CA%9F%E1%B4%8D%C9%B4%E1%B4%8F%E1%B4%98%CA%80%EA%9C%B1%E1%B4%9B%E1%B4%9C%E1%B4%A0%E1%B4%A1x%CA%8F%E1%B4%A2')Find_/_Replace(%7B'option':'Simple%20string','string':'Q'%7D,'%E1%B4%8F%CC%96',true,true,true,false)

__Small Caps Deconverter:__  
INSERT LINK
