wget, curl (to download pretty much everything from internet)

ssh thangam@{IP address}

ls, ls -l (shows in list), li -a (shows hidden file) 

pwd (print working directory)

touch {filename} (to create file)

cat (filename) (to see the what's in the file), less (gives 1 page of content), head (beginnging of file), tail (ending of file content)

shred {filename} (to encrypt the file) | cat again (u'l see like byte code)

cp {filename :from} {filename :to} (copy file)
mv {filename :from} {filename :to} (move file)

rm {filename or filename directory} (if directory have recursive file add) -r (to delete)

ln -s(softlink) {filename} {to the file which we need to link {filename}}

whoami

passwd (to change the password)

zip {filename} {filename that we want to zip}
unzip {zip filename}

cmd {filename} {filename} (compare two files), diff {f}{f} (this tell all the differences)

sudo find / -name "spring*" (to find all the file related with particular name)
sudo find . -type f -name ".*" (find all hidden file) // well this is a structure

chmode +x{file}  (to make the file executalble)

echo {2+2} | bc (to calculate :))

--> drive, processeing detail
ps, ps -aux, df, df -H, top

sudo systemctl start (to start installed application)

Ctrl + U
Ctrl + K 
Ctrl + A
Ctrl + L
