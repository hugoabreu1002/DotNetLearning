# Compare with original git

> diff -q BlazingPizza/ DotNetLearning/BlazingPizza/ | grep differ | grep -v ".*.db .*.db" | awk -F' ' '{print $2 " " $4}' | xargs diff