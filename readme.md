### Dotfiles (settings / preferences / template )

## Sublime setup

custom c++ build: 

```shell
// this build is suggested by luv (and modified by @syedrajo20)
{
    "cmd" : ["g++ -std=c++17 $file_name -o $file_base_name.exe && timeout 5s ./$file_base_name.exe</home/syedrajo20/input.txt>/home/syedrajo20/output.txt"],
    "shell": true,
    "file_regex": "^(..[^:]*):([0-9]+):?([0-9]+)?:? (.*)$",
    "working_dir" : "$file_path",
    "selector":  "source.c++"
}
```



python3 sublime build for linux, macOS or windows:



```shell
{
    "cmd": ["python3 $file_name -o $file_base_name 5s ./$file_base_name</home/syedrajo20/input.txt>/home/syedrajo20/output.txt"],
    "selector": "source.py",
    "shell": true,
    "working_dir": "$file_path"

}
```

> You can change the input  output file path and type as well. 

To keep the input, output file in the same working directory, simply put the filename 

> `<input.txt>output.txt`
> 
> 





## Editor setup (Theme & Editor)

1. Organizing the layout:
   
   `alt + shift + 3` --> Split the window into 3 parts.

2. Build system:
   
   `ctrl + B` --> Build and run the file
   
   `ctrl + shift + B` --> Build with specific build system
   
   
