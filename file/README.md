# ET STD / File

_syntax **/URL/file.create**

```c
bool file.create(char name);
bool file.create(string name);
```

_syntax **/URL/file.modify, file.edit, file.change**



_syntax **/URL/file.content**


_syntax **/URL/file.append**


_syntax **/URL/file.remove, file.delete**

```c
bool file.remove(char name);
bool file.remove(string name);
```

_syntax **/URL/file.rename, file.cut**

```c
bool file.rename(char name, char newname);
bool file.rename(char name, string newname);
bool file.rename(string name, string newname);
bool file.rename(string name, char newname);
```

_syntax **/URL/file.copy, file.send, file.share**

```c
bool file.copy(char name, char newname);
bool file.copy(char name, string newname);
bool file.copy(string name, string newname);
bool file.copy(string name, char newname);
```

_syntax **/URL/file.read**   

_syntax **/URL/file.readLine**

_syntax **/URL/file.list**

_syntax **/URL/file.tree**

_syntax **/URL/file.setPermission**

```
@file. is a file type data
bool file.setPermission(int permission);
```

_syntax **/URL/file.getPermission**

```
@file. is a file type data
int file.getPermission();
```

_syntax **/URL/file.move**

```
@file. is a file type data
int file.getPermission();
int url(/testfile.txt) ->  url(/testfile.txt)   // use -> 'to' move, send or reap
```
