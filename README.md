# Women's College Softball League Performance Projections
Will my favorite team win this year? How far will it go? TBU <br>
Koeun Lim (koeunlim@alum.mit.edu) <br>
Kevin Haghi(kevin.haghi@gmail.com) <br>

## Table of Contents
[Directory Structure](#Directory-Structure)<br>
[Project Description](#Project-Description)<br>
[Data Description](#Data-Description)<br>
-[Source](#Source)<br>
[Data Visualization](#Data-Visualization)<br>
[Conclusion](#Conclusion)<br>


## Directory Structure
```
.
├── Softball League Power Ranking Estimation
    ├── 01_NCAA_Softball_getStats.ipynb
    ├── 02_NCAA_Softball_.ipynb
    ├── 03_NCAA_Softball_.ipynb
    ├── 04_NCAA_Softball_.ipynb
    ├── Data
        ├── stats.csv
        ├── .csv
        ├── ...
        ├── .csv
    ├── Figures
    ├── README.md
```


## Project Description



## Data Description
name of the column|description|break down|
|---|---|---|
|Team|the name of the team||
|Category|category the product|foundation-makeup, lipstick||
|URL|the original URL gathered with selenium||
|Price|the price listed in dollars||
|UserName|nickname of the reviewer||
|UserID|author ID number of the reviewer||
|Rating|number of stars|4, 5||
|Eyecolor|eyecolor of the reviewer|blue, brown, green, gray, hazel||
|Haircolor|haircolor of the reviewer|blonde, brunette, auburn, black, red, gray||
|Skintone|skintone of the reviewer|porcelain, fair, light, medium, tan, olive, deep, dark, ebony||
|SwatchID|swatch ID number of the product||
|R|red scalar from the swatch's RGB|0~255||
|G|green scalar from the swatch's RGB|0~255||
|B|blue scalar from the swatch's RGB|0~255||

Total number of scraped data with Ratings of 4 or 5: 176958<br>
Total number of unique author IDs: 127859<br>
Total number of unique reviewer Nicknames: 125759<br>
Total number of unique foundation products: 191<br>
Total number of unique lipcolor products: 230<br>
Total number of unique foundation shades: 3689<br>
Total number of unique lipcolor shades: 3083<br>


### Source
Product data were gathered from [Sephora](https://www.sephora.com/)<br>
Product review data were gathered from [Bazaarvoice](https://api.bazaarvoice.com)<br>


## Data Visualization
Foundation RBG by Skintone<br>
<img src="./figures/Pair_skintone_foundation.png">



## Conclusion
