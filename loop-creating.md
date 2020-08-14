# Creating Loops in the Shell #

This starts i on 0, ends on 10, and adds 1 to each itteration to the value of i. The body of the loop prints the value of i for each itteration.

```
for ((i=0; i=10; i+=1))
do
	echo ${i}
done
```
