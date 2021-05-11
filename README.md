# DynamoDbConverter
Hashmap To Item Map and Item To hashMap, uses jdk15<br>
Use Service.Converter.DynamoDb.*  or spefic class to import into project<br>
Design to be used with sdk2 of dynamoDb, Not sure if it will work with sdk version 1 <br>
Allows you to pass in an Enhanced Value Map, this is then converted into pure java via hashMap <br>
You can also convert java to DynamoDb with ease just pass the hash map with the correct attribute names and the values of the map will change to AttributeValues allowing ease when
<br>uploading data to DynamoDb
