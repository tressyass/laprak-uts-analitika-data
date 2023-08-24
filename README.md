# laprak-uts-analitika-data

Swedish Motorcycle Insurance dataset<br />
A Dataset derived from information collected by the U.S. Census Service concerning housing in the area of Boston Mass.<br />

About Dataset<br />

This data comes from the former Swedish insurance company Wasa, before its 1999 fusion with Laensfoersaekringar Alliance. In Sweden, insurance involves three types of cover: TPL (third party liability), partial casco and hull. TPL covers any bodily injuries plus property damages caused to others in a traffic accident. Partial casco (may not be used in all countries) covers theft but also some other causes of loss such as fire. Hull covers damage on the policyholder's own vehicle. Note that The TPL insurance is mandatory, while the others are optional. The three types of cover are often sold in a package as a comprehensive insurance, but they are usually priced separately. This dataset contains information relative to partial casco only for motorcycles. It contains aggregated data on all insurance policies and claims during 1994-1998.

Details<br />
a. OwnerAge<br />
The owner age.<br />
b. Gender<br />
The gender.<br />
c. Area<br />
The type of area.<br />
d. RiskClass<br />
The motorcycle class, a classification by the so called EV ratio, defined as (Engine power in kW x 100) / (Vehicle weight in kg + 75), rounded to the nearest lower integer. The 75 kg represent the average driver weight. The EV ratios are divided into seven classes.<br />
e. VehAge<br />
The Vehicle age, between 0 and 99.<br />
f. BonusClass<br />
The bonusclass,taking values from 1 to 7. A new driver starts with bonus class 1; for each claim- free year the bonus class is increased by 1. After the first claim the bonus is decreased by 2; the driver can not return to class 7 with less than 6 consecutive claim free years.<br />
g. ClaimNb<br />
The number of claims.<br />

Perintah:<br />
1. Lakukan analisis menggunakan Generalized Linear Models (GLMs) untuk mengetahui hubungan antara banyaknya number of policy dengan rating factor yang ada pada data. (Note:
tidak perlu dilakukan backward selection).<br />
2. Lakukan pemilihan model terbaik dengan menggunakan kriteria log likelihood, nilai AIC, nilai BIC, serta koefisien 0.<br />
3. Tulis persamaan dan interpretasikan model terbaiknya.<br />
