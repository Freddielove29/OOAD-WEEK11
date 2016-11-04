ภาพที่ 1 

``@startuml

[*] --> off

off : do/shutdownthopower

on : trunonthecomputer
off -d-> on
on -d-> boot
boot -> ready
ready : do/waitingforinstructions
ready --> [*]
@enduml``

![](http://www.plantuml.com/plantuml/img/9Kwx3iCW3Dpz5SoLKFSELVwZwa1ZI90QNmH6g7zVGvQJVI_TKZKKRSUNw7LxE--V3YaH6RY7OzphtfJHHNUSwB6O9APeQG8ZuuhZR6hyI7WUUHcMUNu0fG7EdX83_sZYLTr3rYnRGibIhN3L3Abq6USKcqIqH64R-0S0)

ภาพที่ 2

``
@startuml

[*] --> off

on -> off : turnoff
off -> on : turnon

off -->[*] :outofoder
on --> [*] :outofoder

@enduml``

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuUAArefLqDMrKyXFI-FYoizJW30Lh1HAYahpG88W7aWm3oQMnmKHqxK3wRNABot9JyjFIIq2wmQgH1FbSaZDIm5Q1G00)


 ภาพที่ 3
 
 ``
 @startuml

[*] --> off

on -> off : trunoff
off -> on : trunon
off :open phon
on :playgame
off -->[*] :outofoder
on --> [*] :outofoder
@enduml
``

![](http://www.plantuml.com/plantuml/img/NOun2i0W34Ntd29pmGiuYFSe7GIr7JGHgqDlNwDqwVR_ItXyUpTNMyy9ODyELCeWnmZ0X2kYnbOx2PGca3v64sakWR1SKiUf9FUSBeVrheneDVV6aNseKpmaFmesa1yhNW00)

ภาพที่ 4

``
@startuml
[*] --> close
open -> close : trunoffswitch
close -> open : trunonswitch
close -->[*] :outofoder
open --> [*] :outofoder
@enduml
``

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuUAArefLqDMrKqZEoIzEvUBABqZDKu1n5QmKIefAy_BJqehBCqkICxWWea1fi3AeR1vK4YQhQmSoqog_j2G_BJybjGXg9b0NcZYNGsfU2j0H0000)

ภาพที่ 5

``
@startuml
[*] --> off
on -> off : trunoffswitch
off -> on : trunonswitch
off : offfan
on : onfan
off -->[*] :outofoder
on --> [*] :outofoder
@enduml
``

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuUAArefLqDMrKyXFI-FYoizJW30Lh1HAYahpWApYyioIv0mka1X8AWycauSaOGNIafQOnmMMpiy3Cq4QTEr0nblbbvRaf-Mdf1Q1BG0QWoRAvP2Qbm9q3G00)

ภาพที่ 6

``
@startuml
(*) --> "car"

if "start" then
  -->[true] "Driving"
  -->(*)
 else
  ->[false] "Driving is not"
  --> (*)
endif
@enduml
``

![](http://www.plantuml.com/plantuml/img/HOr12iCm30JlUiMYKnh85u8F-ONfmIHoAt1Ti9MyFtPQo6abpOXrrKAn_PDe61-OfXcyXi946i4NOzXRCg53RsMN9tWfUcX-yU_QFWaagKhVPnz36syBMf6_zfVHRScRHYBNibMV)

ภาพที่ 7
``
@startuml
(*) --> "bottle"

if "openlid" then
  -->[true] "Can eat"
  -->(*)
 
else
  ->[false] "Can not eat"
  --> (*)
endif

@enduml
``

![](http://www.plantuml.com/plantuml/img/JOrB2e0m34JtESMGbGfUeGWUGrnKJB5GKz5uVrjquMe-l666o_nfzvwewLhqlGClsIm94yK0peTeYYl3Db529IOxRvd1erU8DtxRCYUGf4jgTbFmnNwKPlkHgAZe6WFHKBISFm00)

ภาพที่ 8

``
@startuml
(*) --> "phone"

if "battery" then
  -->[true] "playable"
  -->(*)
 
else
  ->[false] "Unplayable"
  --> (*)
endif

@enduml
``

![](http://www.plantuml.com/plantuml/img/NSqn2e0m30NGFQS8dLJe5SHBE1M755CKQfKs7NfxKqUdv8VtoLA4ijGhmZ2DQEsCvZdkn0RW36WyYN1k1kNW1DY1arnvKnQfaOyglxFM0O5ZuPvd5qXNPMlwGUoIqtu6W4Md_du1)

ภาพที่ 9

``
@startuml
(*) --> "room"

if "door" then
  -->[true] "enterroom"
  -->(*)
 
else
  ->[false] "can'tenterroom"
  --> (*)
endif

@enduml
``

![](http://www.plantuml.com/plantuml/img/JOsn2iCm34HtVONGr1Ro2oPhlY5qC4Ic1jiAijplhzmicUvqzyIjtQBQg0KUhoSkIq1IaKe0EI4T8afe7sw0iznD1x-Hk1dhnVrp_mK4Bftd7VOKtJgtrPFrcsNq6uoJvdRa1B2w-lWF)

ภาพที่ 10
``
@startuml
(*) --> "music"

if "listenmusic" then
  -->[true] "canlistenmusic"
  -->(*)
 
else
  ->[false] "can'tlistenmusic"
  --> (*)
endif

@enduml
``

![](http://www.plantuml.com/plantuml/img/PSuz2i0W30RGFQS8Blq1ho3UGpg8ZJIW3XhlNyMbq2d9bqU8RUAhz9nWFm_Ksg3AlN5G01nH9Mv2PIKe3nN0YPpKJXUguCjNhEKu10YK6itPkEX7k_0cVuxJKxav0jXHnoyl)
