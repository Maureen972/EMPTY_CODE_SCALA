# EMPTY_CODE_SCALA

#Country ( id:Int, Code_Country: Country_code, name:String, continent: String,link: String, keyword:String )
#Airport(id:Int, ident: String, type: String,airport_name: String, airport_continent: String ,iso_country:Int, airport_link: String, keyword: String)
#Runway ( id : Int, airport_ident: String, le_latitude_deg : float, le_longitude_deg : float)




sealed abstract class Country code(val value: Int)
object CountryCode{
def fromInt(int: Int) = {
if (int.toString.length = 2)
Some(Country code (int){})
else
None
}
}
