# databasmetodik2018
group: nameOfTheNewGroup 


Kurs = {
	kurskod:string, kursben:string          , langd:number, pris:number, kursbeskrivn:string                               
	'Java1'       , 'Java,grundkurs'        , 5           , 6700       , 'Grundläggande programmering med Java'            
	'Java2'       , 'Java,fortsättningskurs', 4           , 6000       , 'Avancerad programmering med Java'                
	'FDBD'        , 'Fysisk databasdesign.' , 5           , 7200       , 'Lagringsstrukturer, index, denormalisering'      
	'DBM1'        , 'Databasmetodik'        , 2           , 2800       , 'DB-grunder, normalisering, modellering, SQL'     
	'LDBD'        , 'Logisk databasdesign'  , 4           , 6000       , 'Avancerad design, analysmönster, metamodellering'
	'Log1'        , 'Logik'                 , 3           , 4500       , 'Första ordnings logik, predikatlogik, satslogik' 
}
Ktillf = {
	sdat:number, kurs:string, larare:number, lokal:string
	20080306   , 'Java1'    , 2            , 'Tellus'    
	20080402   , 'DBM1'     , 5            , 'Sirius'    
	20080416   , 'Java2'    , 2            , 'Orion'     
	20080416   , 'Log1'     , 3            , 'Jupiter'   
	20080506   , 'Java1'    , 2            , 'Jupiter'   
	20080506   , 'LDBD'     , 5            , 'Sirius'    
	20080509   , 'FDBD'     , 4            , 'Jupiter'   
	20080902   , 'Java1'    , 3            , 'Tellus'    
	20080902   , 'LDBD'     , 4            , 'Orion'     
	20090122   , 'Java2'    , 2            , 'Orion'     
	20090128   , 'DBM1'     , 5            , 'Jupiter'   
}
Deltag = {
	sdat:number, kurs:string, elev:number
	20080306   , 'Java1'    , 1          
	20080306   , 'Java1'    , 3          
	20080306   , 'Java1'    , 8          
	20080306   , 'Java1'    , 9          
	20080306   , 'Java1'    , 10         
	20080402   , 'DBM1'     , 1          
	20080402   , 'DBM1'     , 2          
	20080402   , 'DBM1'     , 3          
	20080402   , 'DBM1'     , 10         
	20080416   , 'Java2'    , 5          
	20080416   , 'Java2'    , 6          
	20080416   , 'Java2'    , 7          
	20080416   , 'Log1'     , 4          
	20080416   , 'Log1'     , 5          
	20080506   , 'Java1'    , 2          
	20080506   , 'Java1'    , 6          
	20080506   , 'LDBD'     , 1          
	20080506   , 'LDBD'     , 7          
	20080509   , 'FDBD'     , 6          
	20080509   , 'FDBD'     , 8          
	20080902   , 'Java1'    , 1          
	20080902   , 'Java1'    , 9          
	20080902   , 'LDBD'     , 6          
	20080902   , 'LDBD'     , 8          
	20090122   , 'Java2'    , 2          
	20090122   , 'Java2'    , 9          
	20090122   , 'Java2'    , 10         
	20090128   , 'DBM1'     , 3          
	20090128   , 'DBM1'     , 5          
}
Lokal = {
	namn:string, maxant:number
	'Jupiter'  , 12           
	'Orion'    , 24           
	'Sirius'   , 16           
	'Tellus'   , 32           
}
Larare = {
	lid:number, lnamn:string   , rum:number, tel:number
	1         , 'Anders Odman' , 634       , 151576    
	2         , 'Bo Akerman'   , 604       , 151526    
	3         , 'Carl Nordin'  , 603       , 151553    
	4         , 'Lena Svensson', 605       , 151556    
	5         , 'Sofia Wilsson', 622       , 151585    
}
Elev= {
	eid:number, enamn:string, adress:string, postnummer:number, ort:string, etel:number
	1         , 'Bo Dahl'   , 'Ahlgatan 6' , 16102            , 'Bromma'  , 163578     
	2         , 'Ann Stal'  , 'Lindvagen 3', 16429            , 'Kista'   , 373789     
	3         , 'Ebba Ryd'  , 'Ankvagen 4' , 16107            , 'Bromma'  , 325305     
	4         , 'Robert Ahl', 'Ekvagen 1'  , 16425            , 'Kista'   , 123435     
	5         , 'Lars Holm' , 'Skolgatan 3', 16966            , 'Solna'   , 203045     
	6         , 'Siw Bjork' , 'Bokvagen 2' , 16431            , 'Kista'   , 452678     
	7         , 'Sigge Ehn' , 'Bokvagen 24', 16429            , 'Kista'   , 245578     
	8         , 'Kurt Grahn', 'Byvagen 112', 19735            , 'Bro'     , 192292     
	9         , 'Eva Jung'  , 'Storgatan 5', 16966            , 'Solna'   , 131187     
	10        , 'Lola Frid' , 'Lillgatan 3', 18754            , 'Taby'    , 723384     
}
