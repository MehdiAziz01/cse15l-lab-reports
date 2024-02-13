# Part 1
## I will be doing `ArrayExamples.java` for part 1.
### A failure inducing input:
![image](FailureInput)
![image](FailureCode)




# part 2
# _find_
`The only source I will be referencing is here : `
https://snapshooter.com/learn/linux/find#:~:text=With%20the%20find%20command%2C%20you,in%20all%20Linux%20operating%20systems.
## `find .`
`find .` `will list all the files in my current directory and sub directories.` In the `first screenshot` I have it in the `911report` directory and in the `second screenshot ` it is in the `plos` directory. `This is useful because its a very quick command that searches inside of our current directory, its usefulness comes from its speed`
 ![image](find.911reports)
![image](find.Plos)
## `find directory -name "*.txt"`
 What this does is that it will find all the files ending in the extenstion `"*.txt"` and it could be any end of url extension not just .txt but in my case that is what it was. In the `first screenshot` I did `find 911report -name "*.txt"` and my current directory was the `technical` directory. This found all the files endind in `".txt"` in the 911report directory. In the `second screenhot` my current directory was `government` and i ran `find About_LSC -name "*.txt"` which showed all the files ending in `".txt"` in the `About_LSC` directory. `So this finds all the files in a directory ending with a certain extension.` `This is useful because it gives us a list of the file extensions we are looking for, it is especially useful when we dont remember the files name and all you remember is the file extention like ".txt" and this can narrow your search.`
![image](find911report)
![image](findAbout_LSC)

## `find directory -name file/directory name`
In the `first screenshot` I have `find government -name About_LSC`. This gives me a path and in this case my current directory is `technical` and by doing that command it gave me the absolute path to the directory `About_LSC` for this example I was searching for a directory's path in the `Second Screenshot` i did `find technical -name chapter-7.txt` and my current directory was just `docsearch`. For this one I got the absolute path while inputting the directory that holds 911report which holds `chapter-7.txt` and it looked like it worked. It gave me the absolute path to the file. `This command is used to search for where a file or directory is located.` `This is very useful because it lays you out the path to getting to a file which you are searching for, its usefulness stems from the option of finding it then searching for where it is.`
![image](find-name)
![image](findnameChapter7)

## `find directory -type f -size +#k`
`this finds all files inside a directory which are greater than 12kb` in the `First screenshot` I was in the `technical` directory and what I wrote was `find 911report -type f -size +100k` and this searches in the `911report` diectory and returns every file that is greater than 100kb. In the second screenshot I ddi `dins 911report -type f -size +250k` and this did the same but it returned every file greater than 250 kb and as you can see it gets less. This also had the current directory as `technical`. `This is very useful because it plays as a great sorting device which can filter out files using kb which can organize your search or help you find files that have more data.`
![image](findSize+100k)
![image](findSize250+)





