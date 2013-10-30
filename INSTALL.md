Build
-----

Standard : `make`



Ubuntu : `make ubuntu`



Debian : `make debian`




Install
-------

Standard : `make DESTDIR=`
*'Your desired destination'*
`install`

Debian/Ubuntu : `make DESTDIR=`
*'Your desired destination'*
`install-debian`



Ubuntu post-install
-------------------

Ensure than `/var/lib/gdm/dconf` are writable by gdm :
`chown -R gdm:gdm /var/lib/gdm/`


