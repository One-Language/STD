# ET STD / File

_syntax **/URL/file.create

```c
bool file.create(char name);
bool file.create(string name);
```

_syntax **/URL/file.modify, file.edit, file.change



_syntax **/URL/file.content


_syntax **/URL/file.append


### file.remove, file.delete

```c
bool file.remove(char name);
bool file.remove(string name);
```

### file.rename, file.cut

```c
bool file.rename(char name, char newname);
bool file.rename(char name, string newname);
bool file.rename(string name, string newname);
bool file.rename(string name, char newname);
```

### file.copy, file.send, file.share

```c
bool file.copy(char name, char newname);
bool file.copy(char name, string newname);
bool file.copy(string name, string newname);
bool file.copy(string name, char newname);
```

### file.read    

### file.readLine

### file.list

### file.tree

### file.setPermission

```
@file. is a file type data
bool file.setPermission(int permission);
```

### file.getPermission

```
@file. is a file type data
int file.getPermission();
```
