# window

## Windows下将文件夹下所有的文件名导出成生成TXT文件
- 在桌面新建一个.txt文件（文件名称随便取，后缀是txt就可以了，比如a.txt），写入下面内容：

```
@echo off
dir /s/b *.* > b.txt exit
```

- 将桌面的a.txt文件拷贝到需要提取文件名称的文件夹下：

- 拷贝之后，将a.txt文件修改成.bat文件（文件名称随便取，后缀是txt就可以了，比如dir_name.bat）

- 双击这个dir_name.bat文件就可以了得到一个b.txt的文件，这个文件里的内容即使当前文件夹下的所有文件的文件名称。
