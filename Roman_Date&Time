#!/bin/bash
#             XX.V.MMXXIII.AC DECEBAL.V.NISIPEANU.
#                ,___,                                                                                                
#               n o,0 ne          "Roman Timer"                                                                       
#  Powered by:   /)#)                                                                                               
#================="="========================================USAGE: watch -tn 1.0 ./roman.timer.sh=====================
hrs=$(date +%H)                                                                                                                             #hrs
min=$(date +%M)                                                                                                                             #min
sec=$(date +%S)                                                                                                                             #sec
nas=$(date +%N)                                                                                                                             #nano
dom=$(date +%d)                                                                                                                             #day of mon
dow=$(date +%w)                                                                                                                             #day of wee
won=$(date +%U)                                                                                                                             #no. of wee
mon=$(date +%m)                                                                                                                             #no. of mon
doy=$(date +%j)                                                                                                                             #day of yr
noy=$(date +%Y)                                                                                                                             #no. of yr
#=======================================================================================================================
dim=$(((10#$hrs * 60) + 10#$min))                                                                                                           #day expr in min 
dis=$(((10#$dim * 60) + 10#$sec))                                                                                                           #day expr in sec
did=$((10#$dis / 240))                                                                                                                      #day expr in deg
#========================================================================================================================
yim=$(((10#$doy * 1440) + 10#$dim))                                                                                                         #yr expr in min
yis=$(((10#$doy * 86400) + 10#$dis))                                                                                                        #yr expr in sec
yih=$(((10#$doy * 24) + 10#$hrs))                                                                                                           #yr expr in hrs
##########################################################################################################################
diss=$((10#$dis / 2))                                                                                                                       #day expr in sum sec
dism=$((10#$diss / 60))                                                                                                                     #day expr in sum min
dish=$((10#$dism / 60))                                                                                                                     #day expr in sum hrs
sm=$((10#$dism - (10#$dish * 60)))                                                                                                          #sum min
ss=$((10#$diss - (10#$dism * 60)))                                                                                                          #sum sec
#########################################################################################################################
#Hrs
echo "$hrs" > hour.txt 
sed 's/01/I/g;s/02/II/g;s/03/III/g;s/04/IV/g;s/05/V/g;s/06/VI/g;s/07/VII/g;s/08/VIII/g;s/09/IX/g;s/10/X/g;s/11/XI/g;s/12/XII/g;s/13/XIII/g;s/14/XIV/g;s/15/XV/g;s/16/XVI/g;s/17/XVII/g;s/18/XVIII/g;s/19/XIX/g;s/20/XX/g;s/21/XXI/g;s/22/XXII/g;s/23/XXIII/g;s/24/XXIV/g' hour.txt > hour1.txt
roman_h=$(cat hour1.txt)
#Min
echo "$min" > minutes.txt
sed 's/01/I/g;s/02/II/g;s/03/III/g;s/04/IV/g;s/05/V/g;s/06/VI/g;s/07/VII/g;s/08/VIII/g;s/09/IX/g;s/10/X/g;s/11/XI/g;s/12/XII/g;s/13/XIII/g;s/14/XIV/g;s/15/XV/g;s/16/XVI/g;s/17/XVII/g;s/18/XVII/g;s/19/XIX/g;s/20/XX/g;s/21/XXI/g;s/22/XXII/g;s/23/XXIII/g;s/24/XXIV/g;s/25/XXV/g;s/26/XXVI/g;s/27/XXVII/g;s/28/XXVIII/g;s/29/XXIX/g;s/30/XXX/g;s/31/XXXI/g;s/32/XXXII/g;s/33/XXXIII/g;s/34/XXXIV/g;s/35/XXXV/g;s/36/XXXVI/g;s/37/XXXVII/g;s/38/XXXVIII/g;s/39/XXXIX/g;s/40/XL/g;s/41/XLI/g;s/42/XLII/g;s/43/XLIII/g;s/44/XLIV/g;s/45/XLV/g;s/46/XLVI/g;s/47/XLVII/g;s/48/XLVIII/g;s/49/XLIX/g;s/50/L/g;s/51/LI/g;s/52/LII/g;s/53/LIII/g;s/54/LIV/g;s/55/LV/g;s/56/LVI/g;s/57/LVII/g;s/58/LVIII/g;s/59/LIX/g;s/00/LX/g' minutes.txt > minutes1.txt
roman_m=$(cat minutes1.txt)
#Sec
echo "$sec" > secundes.txt
sed 's/01/I/g;s/02/II/g;s/03/III/g;s/04/IV/g;s/05/V/g;s/06/VI/g;s/07/VII/g;s/08/VIII/g;s/09/IX/g;s/10/X/g;s/11/XI/g;s/12/XII/g;s/13/XIII/g;s/14/XIV/g;s/15/XV/g;s/16/XVI/g;s/17/XVII/g;s/18/XVII/g;s/19/XIX/g;s/20/XX/g;s/21/XXI/g;s/22/XXII/g;s/23/XXIII/g;s/24/XXIV/g;s/25/XXV/g;s/26/XXVI/g;s/27/XXVII/g;s/28/XXVIII/g;s/29/XXIX/g;s/30/XXX/g;s/31/XXXI/g;s/32/XXXII/g;s/33/XXXIII/g;s/34/XXXIV/g;s/35/XXXV/g;s/36/XXXVI/g;s/37/XXXVII/g;s/38/XXXVIII/g;s/39/XXXIX/g;s/40/XL/g;s/41/XLI/g;s/42/XLII/g;s/43/XLIII/g;s/44/XLIV/g;s/45/XLV/g;s/46/XLVI/g;s/47/XLVII/g;s/48/XLVIII/g;s/49/XLIX/g;s/50/L/g;s/51/LI/g;s/52/LII/g;s/53/LIII/g;s/54/LIV/g;s/55/LV/g;s/56/LVI/g;s/57/LVII/g;s/58/LVIII/g;s/59/LIX/g;s/00/LX/g' secundes.txt > secundes1.txt
roman_s=$(cat secundes1.txt)
#Dom
echo "$dom" > dayofmon.txt
sed 's/01/I/g;s/02/II/g;s/03/III/g;s/04/IV/g;s/05/V/g;s/06/VI/g;s/07/VII/g;s/08/VIII/g;s/09/IX/g;s/10/X/g;s/11/XI/g;s/12/XII/g;s/13/XIII/g;s/14/XIV/g;s/15/XV/g;s/16/XVI/g;s/17/XVII/g;s/18/XVII/g;s/19/XIX/g;s/20/XX/g;s/21/XXI/g;s/22/XXII/g;s/23/XXIII/g;s/24/XXIV/g;s/25/XXV/g;s/26/XXVI/g;s/27/XXVII/g;s/28/XXVIII/g;s/29/XXIX/g;s/30/XXX/g;s/31/XXXI/g' dayofmon.txt > dayofmon1.txt
roman_dom=$(cat dayofmon1.txt)
#Mon
echo "$mon" > mon.txt
sed 's/01/I/g;s/02/II/g;s/03/III/g;s/04/IV/g;s/05/V/g;s/06/VI/g;s/07/VII/g;s/08/VIII/g;s/09/IX/g;s/10/X/g;s/11/XI/g;s/12/XII/g' mon.txt > mon1.txt
roman_month=$(cat mon1.txt)
#Year
echo "$noy" > year.txt
sed 's/2001/MMI/g;s/2002/MMII/g;s/2003/MMIII/g;s/2004/MMIV/g;s/2005/MMV/g;s/2006/MMVI/g;s/2007/MMVII/g;s/2008/MMVIII/g;s/2009/MMIX/g;s/2010/MMX/g;s/2011/MMXI/g;s/2012/MMXII/g;s/2013/MMXIII/g;s/2014/MMXIV/g;s/2015/MMXV/g;s/2016/MMXVI/g;s/2017/XVII/g;s/2018/MMXVII/g;s/2019/MMXIX/g;s/2020/MMXX/g;s/2021/MMXXI/g;s/2022/MMXXII/g;s/2023/MMXXIII/g;s/2024/MMXXIV/g;s/2025/MMXXV/g;s/2026/MMXXVI/g;s/2027/MMXXVII/g;s/2028/MMXXVIII/g;s/2029/MMXXIX/g;s/2030/MMXXX/g;s/2031/MMXXXI/g;s/2032/MMXXXII/g;s/2033/MMXXXIII/g;s/2034/MMXXXIV/g;s/2035/MMXXXV/g;s/2036/MMXXXVI/g;s/2037/MMXXXVII/g;s/2038/MMXXXVIII/g;s/2039/MMXXXIX/g;s/2040/MMXL/g;s/2041/MMXLI/g;s/2042/MMXLII/g;s/2043/MMXLIII/g;s/2044/MMXLIV/g;s/2045/MMXLV/g;s/2046/MMXLVI/g;s/2047/MMXLVII/g;s/2048/MMXLVIII/g;s/2049/MMXLIX/g;s/2050/MML/g;s/2051/MMLI/g;s/2052/MMLII/g;s/2053/MMLIII/g;s/2054/MMLIV/g;s/2055/MMLV/g;s/2056/MMLVI/g;s/2057/MMLVII/g;s/2058/MMLVIII/g;s/2059/MMLIX/g;s/2060/MMLX/g' year.txt > year1.txt
roman_year=$(cat year1.txt)


########################################################################################################################usage: < watch -tn 1.0 ./roman_timer.sh >
echo ""
echo " Univ. Time     : [ $hrs:$min:$sec ] "
echo " Roman Date     : [ $roman_dom.$roman_month.$roman_year]"        
echo " Roman Time     : [ $roman_h:$roman_m:$roman_s ] "

rm -rf hour.txt hour1.txt minutes.txt minutes1.txt secundes.txt secundes1.txt dayofmon.txt dayofmon1.txt mon.txt mon1.txt year.txt year1.txt
























