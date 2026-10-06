# FizzBuzz

## Flowchart
``` mermaid
flowchart TB
start((start))
init["1 <- 1"]
check{"i <= 10?"}
check2{"i %2 == 0?"}
output[/Output i/]
output2[/FizzBuzz/]
increment["i++"]
finish(((finish)))
start --> init
init --> check
check -- YES --> check2
check2 -- YES  --> output2
check2 -- NO  --> output
output --> increment
output2 --> increment
increment --> check
check -- NO  --> finish
```

## Pseudo-Code
```
FOR i <- 1 TO 10
  IF i % 2 == 0 THEN
    OUTPUT "FizzBuzz"
  ELSE
    OUTPUT i
  END IF
NEXT i
