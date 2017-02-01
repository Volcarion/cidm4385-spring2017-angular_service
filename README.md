# UNIT CONVERTER

This program is a *Unit Conversion App* that will conver Volume, Length, and Mass between metric and imperial.

1. It has a text box to receive input 
2. It has two dropdown lists to choose which to convert from and to
3. It displays the results at the bottom

[Metric and Imperial Conversion Charts and Tables](http://convert.french-property.co.uk/)

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

```javascript
		ucc.updateVolume = function (){
		    if (ucc.selected_volume_unit.unit_code ==  ucc.selected_volume_unit2.unit_code ){
		        ucc.volumeResult = ucc.volumeValue;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "cm3" && ucc.selected_volume_unit2.unit_code == "in3"){
		        ucc.volumeResult = ucc.volumeValue * 0.061023759;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "cm3" && ucc.selected_volume_unit2.unit_code == "ft3"){
		        ucc.volumeResult = ucc.volumeValue  * 0.00003531;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "cm3" && ucc.selected_volume_unit2.unit_code == "fl oz"){
		        ucc.volumeResult = ucc.volumeValue  * .0351950085;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "cm3" && ucc.selected_volume_unit2.unit_code == "pt"){
		        ucc.volumeResult = ucc.volumeValue * 0.00175975043;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "cm3" && ucc.selected_volume_unit2.unit_code == "gal"){
		        ucc.volumeResult = ucc.volumeValue * 0.000219968813;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "cm3" && ucc.selected_volume_unit2.unit_code == "dm3"){
		        ucc.volumeResult = ucc.volumeValue * 0.001;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "cm3" && ucc.selected_volume_unit2.unit_code == "m3"){
		        ucc.volumeResult = ucc.volumeValue * 0.00001;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "cm3" && ucc.selected_volume_unit2.unit_code == "l"){
		        ucc.volumeResult = ucc.volumeValue * 0.001;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "cm3" && ucc.selected_volume_unit2.unit_code == "hl"){
		        ucc.volumeResult = ucc.volumeValue * 0.00001;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "dm3" && ucc.selected_volume_unit2.unit_code == "in3"){
		        ucc.volumeResult = ucc.volumeValue * 61.023759;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "dm3" && ucc.selected_volume_unit2.unit_code == "ft3"){
		        ucc.volumeResult = ucc.volumeValue * 0.0353146625;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "dm3" && ucc.selected_volume_unit2.unit_code == "fl oz"){
		        ucc.volumeResult = ucc.volumeValue * 35.1950085;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "dm3" && ucc.selected_volume_unit2.unit_code == "pt"){
		        ucc.volumeResult = ucc.volumeValue * 1.75975043;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "dm3" && ucc.selected_volume_unit2.unit_code == "gal"){
		        ucc.volumeResult = ucc.volumeValue * 0.219968813;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "dm3" && ucc.selected_volume_unit2.unit_code == "cm3"){
		        ucc.volumeResult = ucc.volumeValue * 1000;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "dm3" && ucc.selected_volume_unit2.unit_code == "m3"){
		        ucc.volumeResult = ucc.volumeValue * 0.001;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "dm3" && ucc.selected_volume_unit2.unit_code == "l"){
		        ucc.volumeResult = ucc.volumeValue * 1;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "dm3" && ucc.selected_volume_unit2.unit_code == "hl"){
		        ucc.volumeResult = ucc.volumeValue * 0.01;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "m3" && ucc.selected_volume_unit2.unit_code == "in3"){
		        ucc.volumeResult = ucc.volumeValue * 61023.759;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "m3" && ucc.selected_volume_unit2.unit_code == "ft3"){
		        ucc.volumeResult = ucc.volumeValue * 35.3146625;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "m3" && ucc.selected_volume_unit2.unit_code == "fl oz"){
		        ucc.volumeResult = ucc.volumeValue * 35195.0085;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "m3" && ucc.selected_volume_unit2.unit_code == "pt"){
		        ucc.volumeResult = ucc.volumeValue * 1759.75043;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "m3" && ucc.selected_volume_unit2.unit_code == "gal"){
		        ucc.volumeResult = ucc.volumeValue * 219.968813;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "m3" && ucc.selected_volume_unit2.unit_code == "cm3"){
		        ucc.volumeResult = ucc.volumeValue * 1000000;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "m3" && ucc.selected_volume_unit2.unit_code == "dm3"){
		        ucc.volumeResult = ucc.volumeValue * 1000;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "m3" && ucc.selected_volume_unit2.unit_code == "l"){
		        ucc.volumeResult = ucc.volumeValue * 1000;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "m3" && ucc.selected_volume_unit2.unit_code == "hl"){
		        ucc.volumeResult = ucc.volumeValue * 10;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "l" && ucc.selected_volume_unit2.unit_code == "in3"){
		        ucc.volumeResult = ucc.volumeValue * 61.023759;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "l" && ucc.selected_volume_unit2.unit_code == "ft3"){
		        ucc.volumeResult = ucc.volumeValue * 0.0353146625;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "l" && ucc.selected_volume_unit2.unit_code == "fl oz"){
		        ucc.volumeResult = ucc.volumeValue * 35.1950085;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "l" && ucc.selected_volume_unit2.unit_code == "pt"){
		        ucc.volumeResult = ucc.volumeValue * 1.75975043;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "l" && ucc.selected_volume_unit2.unit_code == "gal"){
		        ucc.volumeResult = ucc.volumeValue * 0.219968813;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "l" && ucc.selected_volume_unit2.unit_code == "cm3"){
		        ucc.volumeResult = ucc.volumeValue * 1000;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "l" && ucc.selected_volume_unit2.unit_code == "dm3"){
		        ucc.volumeResult = ucc.volumeValue * 1;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "l" && ucc.selected_volume_unit2.unit_code == "m3"){
		        ucc.volumeResult = ucc.volumeValue * 0.001;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "l" && ucc.selected_volume_unit2.unit_code == "hl"){
		        ucc.volumeResult = ucc.volumeValue * 0.01;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "hl" && ucc.selected_volume_unit2.unit_code == "in3"){
		        ucc.volumeResult = ucc.volumeValue * 6102.3759;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "hl" && ucc.selected_volume_unit2.unit_code == "ft3"){
		        ucc.volumeResult = ucc.volumeValue * 3.53146625;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "hl" && ucc.selected_volume_unit2.unit_code == "fl oz"){
		        ucc.volumeResult = ucc.volumeValue * 3519.50085;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "hl" && ucc.selected_volume_unit2.unit_code == "pt"){
		        ucc.volumeResult = ucc.volumeValue * 175.975043;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "hl" && ucc.selected_volume_unit2.unit_code == "gal"){
		        ucc.volumeResult = ucc.volumeValue * 21.9968813;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "hl" && ucc.selected_volume_unit2.unit_code == "cm3"){
		        ucc.volumeResult = ucc.volumeValue * 100000;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "hl" && ucc.selected_volume_unit2.unit_code == "dm3"){
		        ucc.volumeResult = ucc.volumeValue * 100;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "hl" && ucc.selected_volume_unit2.unit_code == "m3"){
		        ucc.volumeResult = ucc.volumeValue * 0.1;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "hl" && ucc.selected_volume_unit2.unit_code == "l"){
		        ucc.volumeResult = ucc.volumeValue * 100;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "in3" && ucc.selected_volume_unit2.unit_code == "cm3"){
		        ucc.volumeResult = ucc.volumeValue * 16.38706;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "in3" && ucc.selected_volume_unit2.unit_code == "dm3"){
		        ucc.volumeResult = ucc.volumeValue * 0.01638706;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "in3" && ucc.selected_volume_unit2.unit_code == "m3"){
		        ucc.volumeResult = ucc.volumeValue * 0.00001639;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "in3" && ucc.selected_volume_unit2.unit_code == "l"){
		        ucc.volumeResult = ucc.volumeValue * 0.01638706;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "in3" && ucc.selected_volume_unit2.unit_code == "hl"){
		        ucc.volumeResult = ucc.volumeValue * 0.0001638706;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "in3" && ucc.selected_volume_unit2.unit_code == "ft3"){
		        ucc.volumeResult = ucc.volumeValue * 0.000578703493;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "in3" && ucc.selected_volume_unit2.unit_code == "fl oz"){
		        ucc.volumeResult = ucc.volumeValue * 0.576742716;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "in3" && ucc.selected_volume_unit2.unit_code == "pt"){
		        ucc.volumeResult = ucc.volumeValue * 0.0288371358;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "in3" && ucc.selected_volume_unit2.unit_code == "gal"){
		        ucc.volumeResult = ucc.volumeValue * 0.00360464213;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "ft3" && ucc.selected_volume_unit2.unit_code == "cm3"){
		        ucc.volumeResult = ucc.volumeValue * 28316.85;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "ft3" && ucc.selected_volume_unit2.unit_code == "dm3"){
		        ucc.volumeResult = ucc.volumeValue * 28.31685;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "ft3" && ucc.selected_volume_unit2.unit_code == "m3"){
		        ucc.volumeResult = ucc.volumeValue * 0.02831685;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "ft3" && ucc.selected_volume_unit2.unit_code == "l"){
		        ucc.volumeResult = ucc.volumeValue * 28.31685;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "ft3" && ucc.selected_volume_unit2.unit_code == "hl"){
		        ucc.volumeResult = ucc.volumeValue * 0.2831685;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "ft3" && ucc.selected_volume_unit2.unit_code == "in3"){
		        ucc.volumeResult = ucc.volumeValue * 1728.00063;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "ft3" && ucc.selected_volume_unit2.unit_code == "fl oz"){
		        ucc.volumeResult = ucc.volumeValue * 996.611777;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "ft3" && ucc.selected_volume_unit2.unit_code == "pt"){
		        ucc.volumeResult = ucc.volumeValue * 49.8305888;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "ft3" && ucc.selected_volume_unit2.unit_code == "gal"){
		        ucc.volumeResult = ucc.volumeValue * 6.22882388;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "fl oz" && ucc.selected_volume_unit2.unit_code == "cm3"){
		        ucc.volumeResult = ucc.volumeValue * 28.41312;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "fl oz" && ucc.selected_volume_unit2.unit_code == "dm3"){
		        ucc.volumeResult = ucc.volumeValue * 0.02841312;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "fl oz" && ucc.selected_volume_unit2.unit_code == "m3"){
		        ucc.volumeResult = ucc.volumeValue * 0.00002841;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "fl oz" && ucc.selected_volume_unit2.unit_code == "l"){
		        ucc.volumeResult = ucc.volumeValue * 0.02841312;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "fl oz" && ucc.selected_volume_unit2.unit_code == "hl"){
		        ucc.volumeResult = ucc.volumeValue * 0.0002841312;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "fl oz" && ucc.selected_volume_unit2.unit_code == "in3"){
		        ucc.volumeResult = ucc.volumeValue * 1.73387539;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "fl oz" && ucc.selected_volume_unit2.unit_code == "ft3"){
		        ucc.volumeResult = ucc.volumeValue * 0.00100339974;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "fl oz" && ucc.selected_volume_unit2.unit_code == "pt"){
		        ucc.volumeResult = ucc.volumeValue * 0.05;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "fl oz" && ucc.selected_volume_unit2.unit_code == "gal"){
		        ucc.volumeResult = ucc.volumeValue * 0.00625000027;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "pt" && ucc.selected_volume_unit2.unit_code == "cm3"){
		        ucc.volumeResult = ucc.volumeValue * 568.2624;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "pt" && ucc.selected_volume_unit2.unit_code == "dm3"){
		        ucc.volumeResult = ucc.volumeValue * 0.5682624;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "pt" && ucc.selected_volume_unit2.unit_code == "m3"){
		        ucc.volumeResult = ucc.volumeValue * 0.0005682624;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "pt" && ucc.selected_volume_unit2.unit_code == "l"){
		        ucc.volumeResult = ucc.volumeValue * 0.5682624;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "pt" && ucc.selected_volume_unit2.unit_code == "hl"){
		        ucc.volumeResult = ucc.volumeValue * 0.005682624;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "pt" && ucc.selected_volume_unit2.unit_code == "in3"){
		        ucc.volumeResult = ucc.volumeValue * 34.6775077;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "pt" && ucc.selected_volume_unit2.unit_code == "ft3"){
		        ucc.volumeResult = ucc.volumeValue * 0.0200679949;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "pt" && ucc.selected_volume_unit2.unit_code == "fl oz"){
		        ucc.volumeResult = ucc.volumeValue * 20;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "pt" && ucc.selected_volume_unit2.unit_code == "gal"){
		        ucc.volumeResult = ucc.volumeValue * 0.125000005;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "gal" && ucc.selected_volume_unit2.unit_code == "cm3"){
		        ucc.volumeResult = ucc.volumeValue * 4546.099;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "gal" && ucc.selected_volume_unit2.unit_code == "dm3"){
		        ucc.volumeResult = ucc.volumeValue * 4.546099;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "gal" && ucc.selected_volume_unit2.unit_code == "m3"){
		        ucc.volumeResult = ucc.volumeValue * 0.004546099;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "gal" && ucc.selected_volume_unit2.unit_code == "l"){
		        ucc.volumeResult = ucc.volumeValue * 4.546099;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "gal" && ucc.selected_volume_unit2.unit_code == "hl"){
		        ucc.volumeResult = ucc.volumeValue * 0.04546099;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "gal" && ucc.selected_volume_unit2.unit_code == "in3"){
		        ucc.volumeResult = ucc.volumeValue * 277.42005;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "gal" && ucc.selected_volume_unit2.unit_code == "ft3"){
		        ucc.volumeResult = ucc.volumeValue * 0.160543952;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "gal" && ucc.selected_volume_unit2.unit_code == "fl oz"){
		        ucc.volumeResult = ucc.volumeValue * 159.999993;
		    }
		    else if (ucc.selected_volume_unit.unit_code == "gal" && ucc.selected_volume_unit2.unit_code == "pt"){
		        ucc.volumeResult = ucc.volumeValue * 7.99999965;
		    }
		    return ucc.volumeResult;
		};