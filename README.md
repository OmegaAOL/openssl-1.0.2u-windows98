# OpenSSL 1.0.2u and 1.0.2h, including libraries and headers for binding to cURL, that runs on unmodified Windows 98

Much more useful to you will probably be the sister repository of this one, curl-windows98.

I looked for a prebuilt binary for this all over the internet, couldn't find one, so made my own. Should save you from having to install VC++2005 to compile it.
Yes, I downloaded Visual Studio 2005 just for compiling openssl. 

Was last released 2019, so should support TLS 1.0, 1.1, and 1.2. SSL 3 has been disabled (configured with no-ssl3), if you really want SSL 3 why not
just use an old build of OpenSSL from back when Windows 98 was supported?

BlackWingCat does have binaries for OpenSSL up to version 3, but
1) they are hosted on a Japanese site
2) they are bundled in his proprietary .CAB installer format
3) the website actually hosting the files errors out when trying to download them
4) not tested to work with cURL
