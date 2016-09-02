#!/bin/bash
cntvalid=0
cntchg=0
cntloops=0
for i in *markdown
 do 
   ((cntloops++))
 if [ -e "$i" ]
   then
     oldname="$i"
     filename=$(basename "$i")
     extension="${filename##*.}"
     filename="${filename%.*}"
     ((cntvalid++))
     printf "\n found file named $filename with an extension of $extension \n"
     if [ ! -e "$filename.md" ]
        then
          printf "Does not exist yet with '.md' so safe to change file extension \n\n"
          `cp --preserve=all "$oldname" "$filename.md"`
          ((cntchg++))
        else
          printf "file $filename already exists with extension of '.md' skipping for now... \n\n"
     fi
   else 
     printf "\n ooh sorry but thats not a valid file we are skipping it \n\n"
 fi
done
printf "\n Finished with $cntloops loops finding $cntvalid file names of which $cntchg changes were made and old files not removed \n\n"

