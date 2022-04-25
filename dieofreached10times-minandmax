#!/bin/bash -x
declare -A dict
dict=([1]=0 [2]=0 [3]=0 [4]=0 [5]=0 [6]=0)




while true
do
        max=${random[0]}
        min=${random[0]}

        random=$((RANDOM%6+1))
        echo $random
        dict[$random]=${dict[$random]}+1
        if ((${dict[$random]} == 10))
        then
                echo "$random is the winner"
                break
        fi
done
      echo "maximum times:" $max
      echo "minimum times:" $min

echo ${dict[@]}  #array part

echo ${!dict[@]}  #dictionary part
echo ${#dict[@]}  #total no of days
