The turning.csv file has the following structure:

| time instance | d1 | d3 | d3 | d4 | d5 |
|---------------|----|----|----|----|----|
|  1            |    |    |    |    |    |
| 2             |    |    |    |    |    |
| 3             |    |    |    |    |    |
| .             | .  | .  | .  | .  | .  |
| 199           |    |    |    |    |    |
| 200           |    |    |    |    |    |

d1-d5 are measured diameters.  The first 100 and 150-200 time steps are generated using min + Rand()(max - min): min=4.8, max=5.2.  The 150-200 time steps are generated using NORMINV(RAND(),5,0.1).
