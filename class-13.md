## Local Storage

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string.

Save something in local storage:

```
    var arrayString = JSON.stringify(something);
    localStorage.setItem('swSomething', arrayString);
```

To get data from local storage:

```
  localStorage.getItem('swSomething');
  JSON.parse('swsomething');
```

