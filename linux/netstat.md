# netstat 

##

1|2|3
-|:-:|-
1| netstat -n \| awk '/^tcp/ {++S[$NF]} END {for(a in S) print a, $[a]}'|
