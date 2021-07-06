# local Storage
Locals storage is important thing you shod think of when you want create a webpage, you can store some data from user inputs. 

Local Storage is a space to store data from user in the web browser. So, if the the page refreshed again and again or closed and opened again, the data will remain in the local storage and you can manipulate these data in the code or some where else.

Local storage has just 5MB storing space, but it is enough to store strings.

**Usage Functions**

* `localStorage.setItem('key','value');`

this is to save data in LS; `key` is the name and `value` is what you should save under this name.

* `localStorage.getItem('key')`

this to get what you save by its name => `key`

* `localStorage.removeItem('key');`

this to remove the key and values inside it  from LS.

 * `localStorage.clear()`

 this to remove the whole LS keys and values.

 You need also to use `JSON.stringify(the data you want to storage)` to convert the data to be string, so the data will be lighter to the LS.

 Also, `JSON.parse(data);` when you get the data to get it back to normal or original type.

 ***

 **[Back to: Homepage](https://omarhumamah.github.io/reading-note/).**
 