ID: Adatleíró nyelvek - JSON alapok
A JSON a JavaScript Object Notation rövidítése. Ez egy szöveges adatok cseréjére tervezett adatleíró nyelv. 
A JSON értékek az alábbiak:
string
number
object
array
boolean
null

Példák sztringre:
"mystring": "mystringvalue"

Példa számra:
"mynumber":42

Példák literálokra boolean,null:
{
"istheuniverseflat" : true,
"isitok": false,
"pointer" : null
}
példa array-re:
{
"myarray": [1,3,"mystring"],
"myarray2": [2,3, {"mystring":"myvalue"}]
}
 vagy:
{"myarray2":[
2,
3,
{"mystring":"myvalue"}
]
}
példa objectre:
{
"mymember1": 23.5,
"mystringmember": "yes",
"important": false
}

A {} kell, ha több mint egy kulcs-érték párt akarunk megadni.
Ez helyes {} nélkül:
[1,2,3]

ha nevet akarunk neki adni
{"mylist":[1,2,3]}
