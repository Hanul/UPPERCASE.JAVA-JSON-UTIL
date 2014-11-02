# UPPERCASE.JAVA-JSON-UTIL
JSON utilities for Java or Android project.

### Install
Just add [UPPERCASE.JAVA-JSON-UTIL.jar](https://github.com/Hanul/UPPERCASE.JAVA-JSON-UTIL/raw/master/UPPERCASE.JAVA-JSON-UTIL.jar) on the build path.
* for normal Java project(not Android project), you need [JSON-java](https://github.com/douglascrockford/JSON-java)

## API
* `UTIL.EXTEND_ARRAY` extend array.
```Java
UTIL.EXTEND_ARRAY(JSONArray originArray, JSONArray extendArray)
```
* `UTIL.EXTEND_DATA` extend data.
```Java
UTIL.EXTEND_DATA(JSONObject originData, JSONObject extendData)
```
* `UTIL.COPY_ARRAY` copy array.
```Java
JSONArray copiedArray = UTIL.COPY_ARRAY(JSONArray jsonArrayy)
```
* `UTIL.COPY_DATA` copy data.
```Java
JSONObject copiedData = UTIL.COPY_DATA(JSONObject json)
```
* `UTIL.PACK_DATA` pack data with Date type.
```Java
JSONObject packedData = UTIL.PACK_DATA(JSONObject json)
```
* `UTIL.UNPACK_DATA` unpack data with Date type.
```Java
JSONObject unpackedData = UTIL.EXTEND_ARRAY(JSONObject json)
```

## License
[MIT](LICENSE)

## Author
[Young Jae Sim](https://github.com/Hanul)

## Contact
* [Facebook UPPERCASE.IO User Group](https://www.facebook.com/groups/uppercase/)
* [GitHub Issues](https://github.com/Hanul/UPPERCASE.JAVA-JSON-UTIL/issues)
