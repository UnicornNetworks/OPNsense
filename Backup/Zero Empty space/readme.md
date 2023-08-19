# Solution:
https://forums.freebsd.org/threads/zero-out-unused-space-in-freebsd.37734/

`cat /dev/zero > zero.fill;sync;sleep 1;sync;rm -f zero.fill`
