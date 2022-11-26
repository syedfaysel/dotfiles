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



## Editor setup (Theme & Editor)

1. Organizing the layout:

`alt + shift + 3` --> Split the window into 3 parts.
