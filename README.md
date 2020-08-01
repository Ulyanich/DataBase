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
