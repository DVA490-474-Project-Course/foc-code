# foc_code
The code running on the ESC for controlling the motors using FOC.
When using the software provided by STM which supports their MCUs a lot of functions and libraries are generated. We've have not been able to exclude the libraries generated that isn't necessary for the code to run. In this repo the team have elected to only upload the main.c file which is the only file that has been changed by the developers. Later in this **README** there is a step by step instruction on what the team did in respective softeare so that those could generate the files. However, there is no way the team could ensure that even though a future user folows the steps provided in the **README** will generate the same files due to the fact that STM might not support the version the team have used in the future, or if STM elects to generate another code using a different library.

## The different software and versions used by the team
> STM32CubeIDE 1.16.1
> - An IDE that is very similar to the Eclipse environment. The team choose 
