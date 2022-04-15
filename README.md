# procNet /proc/net/tcp 

perl procNet /proc/net/tcp | perl -00 -wnlE'print /uid: 0/gi'

watch -c -n1 perl procNet /proc/net/tcp
