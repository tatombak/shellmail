shellmail
=========
#!bin/sh
echo "add meg hogy melyik fajlt keresed:"
read x
a=`ls $1 | wc -w`
l=`grep #!bin/bash teszt.txt`
for a in bead
do [ $1=$x ]
        if [ $1=$x ]
        then
            if [ $l==1 ]
                then `sh $x > ~/bead/eredmeny.txt`
            fi
        else echo "szar"
        fi

cat ~/bead/eredmeny.txt |  mail -s fasza cambiasso@citromail.hu
done
~

