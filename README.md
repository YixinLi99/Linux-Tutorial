# Linux-Tutorial

###### Unpacking tar.gz
```gunzip -c foo.tar.gz```
###### to tar a regular folder
`tar -zcvf archive_name.tar.gz folder_to_compress`

##### Linux Command Line 
###### remove a file 
`rm`
###### remove a directory
`rmdir`
###### rename a fie
`mv job_script.sh jobscript1.sh`
###### move a fie
`mv job_script.sh folder_name/direcotry`
###### transfer a file 
`scp k1763287@login3.rosalind.kcl.ac.uk:/scratch/groups/nms_bio_nanomaterials/k1763287/charmm-gui/gromacs/file.txt .`
###### transfer a folder
`scp -r k1763287@login3.rosalind.kcl.ac.uk:/scratch/groups/nms_bio_nanomaterials/k1763287/charmm-gui/gromacs .`
###### transfer a file 
`scp file.txt k1763287@login3.rosalind.kcl.ac.uk:/scratch/groups/nms_bio_nanomaterials/k1763287 `
###### run python file in terminal
`~/opt/anaconda3/bin/python q12.py`
###### to know the executing size of files
`ls -l *.dcd`
###### to browse the terminal history
`cat ~/.bash_history`

##### Nano Command Line 
###### Next Page 
`^V`
###### Previous Page 
`^Y`
###### Jump to Last Page
`^_` + `_V`
###### Search
`^W`

In MacOS: M-B means 'exc' B

###### display changes on file during running process
`tail -f <file.name>`

Linux Tutorial: 
https://zhuanlan.zhihu.com/p/36801617 

Bash.sh Cheatsheet:
https://github.com/skywind3000/awesome-cheatsheets/blob/master/languages/bash.sh

###### Check Commands history:
`history`

###### to display the output files in numerical orders
`ls -v snapshot*.gro`
`ls -v1 snapshot*.gro`
`ls -v snapshot*.gro | wc -l`
