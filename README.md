# Horse_racing_Prediction_Model
Prediction of Winning Horses  in Horse Races

*Overview
Predict the first and second place horses for the January 2022 races using the horse racing records from 2021.

*Data Columns
Train Set

rcDate: Date of the race
rcNo: Race number
chulNo: Horse number
hrNo: Unique horse ID
age: Horse age
ageCond: Age condition
budam: Burden type
chaksunT: Total prize money
chaksunY: Prize money in the last year
chaksun_6m: Prize money in the last 6 months
dusu: Number of participating horses
ilsu: Days of horse racing
ord1CntT: Number of first places in total
ord1CntY: Number of first places in the last year
ord2CntT: Number of second places in total
ord2CntY: Number of second places in the last year
ord3CntT: Number of third places in total
ord3CntY: Number of third places in the last year
prd: Horse origin
prizeCond: Prize condition
rank: Grade condition
rating: Horse rating
rcCntT: Total number of horse appearances
rcCntY: Number of horse appearances in the last year
rcDist: Race distance
sex: Horse gender
wgBudam: Weight burden
track: Racecourse condition
weather: Weather
waterRate: Water rate of the racecourse
ord: Order
rcTime: Race record (seconds)
jkNo: Jockey number
trNo: Trainer number
owNo: Owner number

*Test Set
Exclude ord and rcTime columns from race results.

*Evaluation
To predict three combinations of horse numbers for each race in the test set.
If one of the three combinations matches the actual first and second place combination, it's considered a hit.
Hit rate = Number of hits / Total number of races.
