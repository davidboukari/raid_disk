# raid_disk

## Raid 0 - 
```
Disk1 + Disk2 = 1Disk
c0      c1
c2      c3
```


## Raid 1 - Mirror disk
```
Disk1 - Disk2
c1      c1
c2      c2
c3      c4
```

## Raid 5 - Parity
```
Disk1 - Disk2  - Disk3
c1      c2       xor c1,c2
c3      c4       xor c3,c4
```
