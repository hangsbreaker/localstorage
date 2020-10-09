# localstorage
Javascript LocalStorage
```
// CREATE TABLE
createTable(TABLE_NAME);
```
```
// DELETE TABLE
dropTable(TABLE_NAME);
```
```
// GET BY ID
function getById(TABLE_NAME, RECORD_ID);
```
```
// GET DATA
getData(TABLE_NAME);
```
```
// INSERT
var dataObj = {"key":"value"};
insertData(TABLE_NAME, dataObj);
```
```
// UPDATE
var dataObj = {"key":"value"};
updateData(TABLE_NAME, RECORD_ID, dataObj);
```
```
// DELETE
deleteData(TABLE_NAME, RECORD_ID);
```
```
// FIND
var tableObj = getData(TABLE_NAME);
findData(tableObj, KEYWORD);
```
<a href="http://hangsbreaker.github.io/localstorage/index.html" target="_blank">Demo here</a>
