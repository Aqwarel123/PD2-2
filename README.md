# PD2-2
Mihails Burcevs, DT1-2

#2.uzdevums
partitions = [
    "System;/;50000;85", 
    "Data;/home;150000;40", 
    "Cache;/tmp;5000;10", 
    "Backup;/mnt/backup;500000;92", 
    "USB-Drive;/media/usb;16000;0", 
    "Logs;/var/log;10000;95", 
    "Database;/var/lib/mysql;80000;70", 
    "Shared;/mnt/shared;200000;15", 
    "Win-System;/mnt/win;100000;90", 
    "Recovery;/recovery;2000;98" ]

for p in partitions:
    labels = p.split(";")[0]
    print(labels)

#3.uzdevums
partitions = [
    "System;/;50000;85", 
    "Data;/home;150000;40", 
    "Cache;/tmp;5000;10", 
    "Backup;/mnt/backup;500000;92", 
    "USB-Drive;/media/usb;16000;0", 
    "Logs;/var/log;10000;95", 
    "Database;/var/lib/mysql;80000;70", 
    "Shared;/mnt/shared;200000;15", 
    "Win-System;/mnt/win;100000;90", 
    "Recovery;/recovery;2000;98" ]
    
for p in partitions:
    labels2 = p.split(";")[2]
    print(labels2)
    
print("Kopējais mb skaits: 1113000")
