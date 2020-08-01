# DataBase
USE SOURCES;

CREATE TABLE dbo.T_CLIENTS
(ID INT NOT NULL
, INN INT NOT NULL
, NAME VARCHAR(MAX) NOT NULL
)
INSERT INTO SOURCES.dbo.T_CLIENTS	
VALUES ('1',  '1234567810', 'Russian aluminum'				)
, ('2',  '1234567811', 'UGMK'									)
, ('3',  '1234567812', 'GK "TAIF"'								)
, ('4',  '1234567813', 'Metalloinvest'							)
, ('5',  '1234567814', 'GAZ Group'								)
, ('6',  '1234567815', 'Russneft'								)
, ('7',  '1234567816', 'MEGAFON'									)
, ('8',  '1234567817', 'ELDORADO'				)
, ('9',  '1234567818', 'Euroset'								)
, ('10', '1234567819', 'United Metallurgical Company'	)
, ('11', '1234567820', 'SOK Group'							)
, ('12', '1234567821', 'Rolf'									)
, ('13', '1234567822', 'SIA International'							)
, ('14', '1234567823', 'MEFAPOLIS'					)
, ('15', '1234567824', 'SUEK'									)
, ('16', '1234567825', 'Group of companies "Protek"'				)
, ('17', '1234567826', 'CHTPZ Group'								)
, ('18', '1234567827', 'SNS'										)
, ('19', '1234567828', 'Russian copper company'					)
, ('20', '1234567829', 'Transmashholding'							)
, ('21', '1234567830', 'Eurochem'									)
, ('22', '1234567831', 'Alliance Group'							)
, ('23', '1234567832', 'Eurocement'								)
, ('24', '1234567833', 'Ilim Group'							)
, ('25', '1234567834', 'Severstaltrans'							)
, ('26', '1234567835', 'Industrial and metallurgical holding'	)
, ('27', '1234567836', 'Integrated energy systems'		)
, ('28', '1234567837', 'Phosagro'									)
, ('29', '1234567838', 'Globalstroy-engineering'					)


CREATE TABLE dbo.T_PRODUCTS		
(ART_ID INT NOT NULL
, STRIH_CODE VARCHAR(MAX) NOT NULL
, PRICE REAL NULL
, NAME VARCHAR(MAX) NOT NULL
)
INSERT INTO SOURCES.dbo.T_PRODUCTS
VALUES ('3949538',	'1048522',	    '1', 	'$3.00 h.e.b. grocery contribution to Food bank'																						)
, ('3952299',	'1256284',	    '5', 	'(serves 4) sainsburys christmas pudding 454g'																							)
, ('3950966',	'1297256',	    '9', 	'(390g) trader joes artichoke hearts 13.75oz'																							)
, ('3952098',	'2111117',	    '13',	'pep Farm layer cake 19.6oz'																											)
, ('3950495',	'2550424',	    '17',	'(236g) trader joes Raspberry dressing 8oz'																							)
, ('2768121',	'3012321',	    '21',	'#32 cotn mop inblk 32oz 00752'																											)
, ('3950481',	'6348168',	    '25',	'(230g) trader joes caramel wafers 8.11oz'																								)
, ('3951334',	'7769986',	    '29',	'(60g) trader joes Lemon pepper with grinder 2.12oz'																					)
, ('3949130',	'8000071',	    '33',	'md200tbe'																																)
, ('3953845',	'8043054',	    '37',	'0 ea *imes 200 Lime'																													)
, ('3949901',	'9086037',	    '41',	'(115g) trader joes savory broth beef 4.06oz'																							)
, ('3948603',	'9203655',	    '45',	'#17 s Rose Foam trays 1000ct'																											)
, ('3948671',	'9304369',	    '49',	'#20k White tray 125ct'																													)
, ('3954083',	'9940574',	    '53',	'0.01 ea *a+ for schools'																												)
, ('3952039',	'19895406',	    '57',	'(mod) edys Ice cr pallet 56 fo 234ct'																									)
, ('2214901',	'20013585',	    '61',	'(e) Vita dor frying Oil 2l'																											)
, ('2082451',	'20045173',	    '65',	'0.0005m3 pilsener finkbr?u can 500ml 4.9%'																								)
, ('3950610',	'21004070',	    '69',	'(260g drained) asda sweet corn 326g'																									)
, ('3950036',	'21092589',	    '73',	'(140g) asda Water chestnuts in Water 225g'																								)
, ('3949938',	'21092756',	    '77',	'(120g) asda bamboo shoots in Water 225g'																								)
, ('3952051',	'22059390',	    '81',	'(mod) healthy choice palt 56 fo 234ct'																									)
, ('3950090',	'22111456',	    '85',	'(150g Dry) armada thunfisch-filets 195g'																								)
, ('3951109',	'22111517',	    '89',	'(465g Dry) sweet Valley pfirsiche 820g'																								)
, ('3950404',	'22112071',	    '93',	'(200g) knusperone knuspy free 8ct'																										)
, ('1775689',	'22114372',	    '97',	'(340g Dry) sweet Valley ananas 565g'																									)
, ('3950764',	'22115904',	    '101',	'(300g) 6 br??tchen 6ct'																												)
, ('3950522',	'22128263',	    '105',	'(240g Dry) gartenkrone tomaten 400g'																									)
, ('3951228',	'22134189',	    '109',	'(530g) gartenkrone erbsen mit m??hrchen 800g'																							)
, ('3950207',	'23140042',	    '113',	'(180g Dry) Asia bambussprossen 330g'																									)
, ('3950418',	'24043496',	    '117',	'(205g Dry) garten krone stangenspargl, wei??, handgesch??lt 330g'																		)
, ('3950089',	'25011210',	    '121',	'(150g drained) Ocean rise (aldi) tuna steaks in sunflower Oil 200g'																	)
, ('3951614',	'25095999',	    '125',	'(82g drained) Ocean rise (aldi) mackerel fillets in sunflower Oil 120g'																)
, ('3950521',	'25124972',	    '129',	'(240g drained) sweet harvest (aldi) Red kidney beans 410g'																				)
, ('3952097',	'25552324',	    '133',	'(mod) pep Farm layer cake 19.60oz 360ct'																								)
, ('3951936',	'27660393',	    '137',	'(hxwxd) 6 x7.5x8 cm aprx 53g asda smart Price assorted rubber bands tub - item number: r6bb/zfg198'									)
, ('3951026',	'42114314',	    '145',	'(400ml) mг?в?ller mг?в?llermilch banane 425g'																							)
, ('3951027',	'42114321',	    '149',	'(400ml) mг?в?ller mг?в?llermilch schoko 429g'																							)
, ('3953815',	'49753288',	    '153',	'0 (joke item) tesco value print it yourself birthday card'																				)
, ('3951008',	'50019465',	    '157',	'(4.2oz) boots botanics conditioning clay mask 120g'																					)
, ('3952304',	'50168545',	    '169',	'(small serving) crawfords Bourbon creams'																								)
, ('3952609',	'50189861',	    '173',	'/ 1pcs Lion bar / Nestle 45g'																											)
, ('3950381',	'50504794',	    '185',	'(2.54floz) boots mediterranean almond, Peach&Milk Conditioner (31-16-093) 75ml'														)
, ('3949725',	'50858798',	    '189',	'(1.28 usfloz) rowney cryla artists acrylic colour - Bright Green 308 series b 38ml'													)
, ('3949726',	'50859184',	    '193',	'(1.28 usfloz) rowney cryla artists acrylic colour - titanium White 009 series a 38ml'													)
, ('3951460',	'50992195',	    '197',	'(70g/2.5oz) lord sheraton leather Balsam 85ml'																							)
, ('3949698',	'59428831',	    '201',	'(0.63oz) Nescafe 3in1 strong 18g'																										)
, ('3949754',	'80028062',	    '209',	'(1.59oz) balocco snack wafers - cocoa 45g'																								)
, ('3948602',	'91046000',	    '221',	'#17 s Black Foam trays 1000ct'																											)
, ('3954084',	'94007336',	    '225',	'0.01 ea *case sel labels Red'																											)
, ('3952380',	'96627280',	    '229',	'.25/off Milk coupon 1/pak 50ct'																										)
, ('3948712',	'99256012',	    '233',	'#3 envelope gro. directs 10ct'																											)
, ('3954085',	'99405366',	    '237',	'0.01 ea *cash shortage chart 1/1ea'																									)
, ('3954086',	'99405434',	    '241',	'0.01 ea *front end vip task list 1/pa'																									)
, ('2768324',	'10000002027',	'245',	'(s) ralphs Mild salsa 24oz'																											)
, ('3951870',	'10129064111',	'249',	'(d) vegi veggitonios * 10oz'																											)
, ('3951867',	'10129065118',	'253',	'(d) vegi broccoli nuggets * 10oz'																										)
, ('3951869',	'10129065149',	'257',	'(d) vegi spinach nuggets * 10oz'																										)
, ('3951868',	'10129065163',	'261',	'(d) vegi chickn nuggets * 10oz'																										)
, ('3953029',	'10164089964',	'265',	'/29.5ml hillco Leader lens cleaner nettoyant lunettes 1floz'																			)
, ('3953837',	'10171318484',	'269',	'0 conax edision'																														)
, ('3952678',	'10181053504',	'273',	'/ 3.75oz palmers shea Butter Formula w/vitamin E concentrated Cream (for Extra Dry Skin) 100g'										)
, ('3952680',	'10186763248',	'277',	'/ 3.78l surfacegard Stone grout&tile sealer tilelab 128floz'																			)
, ('3950321',	'10186766683',	'281',	'(1qt) onestep ceramic tile cleaner and resealer 946ml'																					)
, ('3948743',	'10186773414',	'285',	'#382 bone PolyBlend?? sanded Ceramic Tile Caulk'																						)
, ('3952886',	'10300005353',	'289',	'/ 80oz / 2.27kg Diamond mixed nuts: wlnts/brzl/almds/hzlnuts/pecns 80oz'																)
, ('3950785',	'10300063889',	'293',	'(306g) diamon Foods, inc - emerald - breakfast on the go! trail Mix - breakfast Blend - 6 pouches 10.86oz'								)
, ('3950786',	'10300064084',	'297',	'(306g) diamon Foods, inc - emerald - breakfast on the go! trail Mix - smores Blend - 6 pouches 10.86oz'								)
, ('3951216',	'10300883319',	'301',	'(51g) diamon Foods, inc - emerald - breakfast on the go! trail Mix - smores Blend - single pouch 1.81oz'								)
, ('3140020',	'10300884392',	'305',	'(51g) emerald - trail Mix - berry Blend 1.81oz'																						)
, ('3951215',	'10300889397',	'309',	'(51g) diamon Foods, inc - emerald - breakfast on the go! trail Mix - breakfast Blend - single pouch 1.81oz'							)
, ('2506483',	'10343866003',	'329',	'(Yellow) for stylus Pro 9600 / Pro 4000 / c4 / c8 / c8ps / 4400 / 4450 / 4450'															)
, ('3948784',	'10870411844',	'341',	'#4118 9 1/2inch hedge shear'																											)
, ('1133504',	'10939218339',	'345',	'(26floz) antacid regular strength cooling mint mckesson 769ml'																			)
, ('1134018',	'10939402332',	'349',	'(44ml) sunmark nasal moisturizing spray 1.5floz'																						)
, ('3950824',	'11110355799',	'353',	'(325ml) kroger slim-rite chocolate royale 11floz'																						)
, ('3949773',	'11110392725',	'357',	'(1.75lb) kroger whole rotisserie chicken (Hot), savory flavor 28oz'																	)
, ('3950366',	'11110491985',	'361',	'(2.1qt) bigk diet cola - dist. by inter-2 l'																							)
, ('3018368',	'11110494252',	'365',	'(2.1qt) big k Cherry cola 2l'																											)
, ('3949747',	'11110508195',	'369',	'(1.5 qt) 1.41l de luxe churned artisan vanilla bean Light Ice Cream 48floz'															)
, ('3950566',	'11110608482',	'373',	'(24oz) large eggs, grade AA 12ct'																										)
, ('3147581',	'11110612380',	'377',	'(8.5g) kroger gelatin dessert Cherry 0.3oz'																							)
, ('3218841',	'11110612410',	'381',	'(8.5g) kroger gelatin dessert Lime 0.3oz'																								)
, ('3950448',	'11110661999',	'385',	'(220g) coffee Beverage, instant, mocha supreme flavor, kroger brand, distributed by the kroger co., cincinnati, ohio 45201 7.75'		)
, ('3259190',	'11110668660',	'389',	'(70.8g) zesty Blend all Natural seasoning - Original Blend 2.5oz'																		)
, ('3950652',	'11110682437',	'393',	'(27g) kroger italian seasoning 0.937oz'																								)
, ('3950960',	'11110682963',	'397',	'(38g) kroger ground mustard 1.37oz'																									)
, ('3951144',	'11110687944',	'401',	'(48g) kroger Light Lemon Lime Natural flavor drink Mix 1.69oz'																			)
, ('3951105',	'11110729729',	'405',	'(45g) private selection ground cinnamon 1.62oz'																						)
, ('3221865',	'11110735195',	'409',	'(325g) kroger sweet&spicy steak sauce 11.5oz'																							)
, ('3950484',	'11110805232',	'413',	'(233g) kroger sliced beets 8.25oz'																										)
, ('3950696',	'11110834485',	'417',	'(2lb 13oz) 1.27kg korger cghurn Gold 48% veg Oil Spread 45oz'																			)
, ('3147383',	'11110837776',	'421',	'(375g) kroger mushrooms pieces and stems 13.25oz'																						)
, ('3951455',	'11110881069',	'425',	'(709ml) kroger toilet Bowl cleaner 24oz'																								)
, ('3950638',	'11110883520',	'429',	'(275g) apriva no calorie sweetener 9.7oz'																								)
, ('3950647',	'11110899446',	'433',	'(276g) kroger value - frosted strawberry toaster pastries 9.75oz'																		)



CREATE TABLE dbo.T_SALES	
( ID_DOCS INT NOT NULL 
, DAY_ID DATE NOT NULL
, ID_CLIENTS INT NOT NULL
, ART_ID INT NULL
, QNTY INT NULL
)
INSERT INTO SOURCES.dbo.T_SALES	
VALUES  
  ('3564789',	'2020-08-10',	'1',	'1133504',	'2')
, ('3564789',	'2020-08-10',	'2',	'1134018',	'3')
, ('3564789',	'2020-08-10',	'3',	'1775689',	'4')
, ('3564789',	'2020-08-10',	'4',	'2082451',	'5')
, ('3564789',	'2020-08-10',	'5',	'2214901',	'6')
, ('3564789',	'2020-08-10',	'6',	'2506483',	'7')
, ('3564789',	'2020-08-10',	'7',	'2768121',	'8')
, ('3564789',	'2020-08-10',	'8',	'2768324',	'9')
, ('3564765',	'2020-08-10',	'9',	'3018368',	'10')
, ('3564765',	'2020-08-10',	'10',	'3140020',	'11')
, ('3564765',	'2020-08-10',	'11',	'3147383',	'12')
, ('3564765',	'2020-08-10',	'12',	'3147581',	'13')
, ('3564765',	'2020-08-10',	'13',	'3218841',	'14')
, ('3564765',	'2020-08-10',	'14',	'3221865',	'15')
, ('3564765',	'2020-08-10',	'15',	'3259190',	'16')
, ('3564765',	'2020-08-10',	'16',	'3948602',	'17')
, ('3564765',	'2020-08-10',	'17',	'3948603',	'18')
, ('3564765',	'2020-08-10',	'18',	'3948671',	'19')
, ('3564765',	'2020-08-10',	'19',	'3948712',	'20')
, ('3564732',	'2020-08-10',	'20',	'3948743',	'21')
, ('3564732',	'2020-08-10',	'22',	'3948784',	'23')
, ('3564723',	'2020-08-10',	'23',	'3949130',	'24')
, ('3564723',	'2020-08-10',	'24',	'3949538',	'25')
, ('3564723',	'2020-08-10',	'25',	'3949698',	'26')
, ('3564723',	'2020-08-10',	'26',	'3949725',	'27')
, ('3564723',	'2020-08-10',	'27',	'3949726',	'28')
, ('3564708',	'2020-08-10',	'28',	'3949747',	'29')
, ('3564708',	'2020-08-10',	'29',	'3949754',	'30')
, ('3564747',	'2020-08-10',	'15',	'3949773',	'31')
, ('3564747',	'2020-08-10',	'16',	'3949901',	'32')
, ('3564747',	'2020-08-10',	'17',	'3949938',	'33')
, ('3564747',	'2020-08-10',	'18',	'3950036',	'34')
, ('3564747',	'2020-08-10',	'19',	'3950089',	'35')
, ('3564747',	'2020-08-10',	'20',	'3950090',	'36')
, ('3564747',	'2020-08-10',	'23',	'3950207',	'55')
, ('3564747',	'2020-08-10',	'24',	'3950321',	'38')
, ('3564717',	'2020-08-10',	'25',	'3950366',	'39')
, ('3564717',	'2020-08-10',	'2',	'3950381',	'40')
, ('3564717',	'2020-08-10',	'3',	'3950404',	'41')
, ('3564717',	'2020-08-10',	'4',	'3950418',	'42')
, ('3564717',	'2020-08-10',	'5',	'3950448',	'43')
, ('3564774',	'2020-08-10',	'6',	'3950481',	'99')
, ('3564774',	'2020-08-10',	'7',	'3950484',	'45')
, ('3564774',	'2020-08-10',	'8',	'3950495',	'46')
, ('3564774',	'2020-08-10',	'9',	'3950521',	'47')
, ('3564774',	'2020-08-10',	'10',	'3950522',	'48')
, ('3564774',	'2020-08-10',	'11',	'3950566',	'49')
, ('3564774',	'2020-08-10',	'12',	'3950610',	'7000')
, ('3564774',	'2020-08-10',	'12',	'3950381',	'300'	)


CREATE UNIQUE CLUSTERED INDEX [UNC_KLS_T_SALES] ON SOURCES.dbo.T_SALES
( ART_ID ASC
 , ID_CLIENTS ASC
 , ID_DOCS ASC
 , DAY_ID ASC
) WITH (PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, SORT_IN_TEMPDB=OFF, IGNORE_DUP_KEY = OFF, DROP_EXISTING = OFF, ONLINE = OFF, ALLOW_PAGE_LOCKS = ON);


CREATE VIEW dbo.V_SALES 
AS 
SELECT *
FROM (
		SELECT A.ID_DOCS
			, A.ID_CLIENTS
			, A.ART_ID
			, A.DAY_ID
			, A.QNTY
			, P.PRICE
			, A.QNTY * P.PRICE AS SALES
			, ROW_NUMBER() OVER (PARTITION BY ID_DOCS, ID_CLIENTS, A.ART_ID ORDER BY DAY_ID DESC) AS RN
		FROM SOURCES.dbo.T_SALES  AS A
		LEFT JOIN SOURCES.dbo.T_PRODUCTS AS P
			ON P.ART_ID = A.ART_ID
	 ) AS Q
WHERE RN=1;


CREATE TABLE dbo.T_OTCHET	
(ID_DOCS INT NOT NULL
, ID_CLIENTS INT NOT NULL
, NAME_CLIENT VARCHAR(MAX) 
, DATE_CHANGE DATE 
, ART_ID INT NOT NULL
, ART_NAME VARCHAR(MAX)
, QNTY INT
, SALES REAL
, PRICE REAL
, DAY_ID DATE
)


CREATE UNIQUE CLUSTERED INDEX [UNC_KLS_T_OTCHET] ON SOURCES.dbo.T_OTCHET
( ART_ID ASC
 , ID_CLIENTS ASC
 , ID_DOCS ASC
 , DATE_CHANGE ASC

) WITH (PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, SORT_IN_TEMPDB=OFF, IGNORE_DUP_KEY = OFF, DROP_EXISTING = OFF, ONLINE = OFF, ALLOW_PAGE_LOCKS = ON);

INSERT INTO dbo.T_OTCHET
SELECT ID_DOCS
,	ID_CLIENTS
,	C.NAME AS NAME_CLIENT
, 	'2020-08-01' AS DATE_CHANGE 
,	S.ART_ID
,	P.NAME AS ART_NAME
,	S.QNTY
,	S.QNTY * P.PRICE AS SALES
,	PRICE
,	DAY_ID
FROM SOURCES.dbo.T_SALES AS S	
LEFT JOIN SOURCES.dbo.T_CLIENTS AS C
	ON C.ID = S.ID_CLIENTS
LEFT JOIN SOURCES.dbo.T_PRODUCTS AS P
	ON P.ART_ID = S.ART_ID
WHERE DAY_ID = '2020-08-01'


CREATE PROCEDURE dbo.PRC_OTCHET
AS
BEGIN

MERGE SOURCES.dbo.T_OTCHET AS A
USING (SELECT S.ID_DOCS
	 , S.ID_CLIENTS
	 , C.NAME AS NAME_CLIENT
	 , S.DAY_ID
	 , S.ART_ID
	 , P.NAME AS ART_NAME
	 , S.QNTY
	 , S.SALES
	 , P.PRICE
	 , CAST(GETDATE() AS DATE) AS DATE_CHANGE
FROM SOURCES.dbo.V_SALES AS S
LEFT JOIN SOURCES.dbo.T_CLIENTS AS C
	ON C.ID = S.ID_CLIENTS
LEFT JOIN SOURCES.dbo.T_PRODUCTS AS P
	ON P.ART_ID = S.ART_ID
) AS Q
ON  A.ID_DOCS = Q.ID_DOCS
AND A.ID_CLIENTS = Q.ID_CLIENTS
AND A.ART_ID = Q.ART_ID
AND A.QNTY = Q.QNTY
AND A.SALES = Q.SALES
WHEN MATCHED THEN UPDATE SET QNTY = Q.QNTY, SALES = Q.SALES, DAY_ID = Q.DAY_ID
WHEN NOT MATCHED THEN INSERT (ID_DOCS,	ID_CLIENTS,	NAME_CLIENT,DATE_CHANGE ,	ART_ID,	ART_NAME,	QNTY,	SALES, PRICE,	DAY_ID)
					  VALUES (Q.ID_DOCS,	Q.ID_CLIENTS,	Q.NAME_CLIENT,Q.DATE_CHANGE ,	Q.ART_ID,	Q.ART_NAME,	Q.QNTY,	Q.SALES, Q.PRICE,Q.DAY_ID);


END

