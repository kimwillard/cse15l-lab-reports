**The absolute path to the working directory was `home/lecture1` before each command was run.
## CHANGE DIRECTORY EXAMPLES (`cd`)- changes the current directory to the directory listed in the argument.
![cd_nocommands](IMG_3411.png)
With no argument, `cd` returns back to the home directory. This is because we did not provide a directory to change to. This is not an error. 
![cd_directory](IMG_3412.png)
Using the path `messages` as the argument, terminal changes the directory to the path leading to `messages`. This is not an error.
![cd_file](IMG_3413.png)
This is an *error* because `cd` can only change the directory. It does not have access to files.

## LIST EXAMPLES (`ls`)- shows the files/folders contained in the currrent path
![ls_nocommands](IMG_3414.png)
With no argument, terminal shows all of the contents of the current directory, which is `lecture1`. This includes `Hello.class`, `Hello.java`, `README`, and `messages`. This is not an error.
![ls_directory](IMG_3415.png)
Using `messages` as the directory for the argument, terminal prints all of the files held within `messages`. This is not an error.
![ls_file](IMG_3416.png)
Using the file `es-mx.txt` as the argument returns the name of the file back as it does not contain any more files or folders. This is not an error.

## CONCATENATE EXAMPLES (`cat`)- prints contents of file
![cat_nocommands](IMG_3417.png)
With no argument, there is no return because there is nothing for terminal to print. This is not an error.
![cat_nocommands_withText](IMG_3636.png)
When I type while cat is running, if I press enter it copies exactly what I typed. This is because the purpose of `cat` is to print the content of whatever files you use as an argument-- or in this case, just the text provided. It just show an error because it didn't find any files to print.
![cat_directory](IMG_3418.png)
There is an *error* because concatenate prints the contents of files, but a directory is not a file.
![cat_file](IMG_3419.png)
When using `es-mx.txt` as the argument, terminal prints the contents of the file which is "Hola Mundo!" This is not an error.
