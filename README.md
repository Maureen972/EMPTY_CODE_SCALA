# EMPTY_CODE_SCALA

Country ( id, code_country, name, continent,link, keyword )
Country(Int, CODE , String, String ,?, String)


sealed abstract class Country code(val value: Int)
object CountryCode{
def fromInt(int: Int) = {
if (int.toString.length = 2)
Some(Country code (int){})
else
None
}
}
