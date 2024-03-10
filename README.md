# Horse_racing_Prediction_Model
Prediction of Winning Horses  in Horse Races<br/>
<br/>
*Overview<br/>
Predict the first and second place horses for the January 2022 races using the horse racing records from 2021.<br/>
<br/>
*Data Columns<br/>
Train Set<br/>
<br/>
rcDate: Date of the race<br/>
rcNo: Race number<br/>
chulNo: Horse number<br/>
hrNo: Unique horse ID<br/>
age: Horse age<br/>
ageCond: Age condition<br/>
budam: Burden type<br/>
chaksunT: Total prize money<br/>
chaksunY: Prize money in the last year<br/>
chaksun_6m: Prize money in the last 6 months<br/>
dusu: Number of participating horses<br/>
ilsu: Days of horse racing<br/>
ord1CntT: Number of first places in total<br/>
ord1CntY: Number of first places in the last year<br/>
ord2CntT: Number of second places in total<br/>
ord2CntY: Number of second places in the last year<br/>
ord3CntT: Number of third places in total<br/>
ord3CntY: Number of third places in the last year<br/>
prd: Horse origin<br/>
prizeCond: Prize condition<br/>
rank: Grade condition<br/>
rating: Horse rating<br/>
rcCntT: Total number of horse appearances<br/>
rcCntY: Number of horse appearances in the last year<br/>
rcDist: Race distance<br/>
sex: Horse gender<br/>
wgBudam: Weight burden<br/>
track: Racecourse condition<br/>
weather: Weather<br/>
waterRate: Water rate of the racecourse<br/>
ord: Order<br/>
rcTime: Race record (seconds)<br/>
jkNo: Jockey number<br/>
trNo: Trainer number<br/>
owNo: Owner number<br/>
<br/>
*Test Set<br/>
Exclude ord and rcTime columns from race results.<br/>
<br/>
*Evaluation<br/>
To predict three combinations of horse numbers for each race in the test set.<br/>
If one of the three combinations matches the actual first and second place combination, it's considered a hit.<br/>
Hit rate = Number of hits / Total number of races.
