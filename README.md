# procNet /proc/net/tcp 

perl procNet tcp | perl -00 -wnlE'print /uid: 0/gi'

perl procNet tcp | less

perl procNet tcp | grep 
