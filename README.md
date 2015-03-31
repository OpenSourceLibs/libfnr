
  libFNR - A reference implementation library for FNR encryption scheme.

  FNR represents "Flexible Naor and Reingold" 

  FNR is a small domain block cipher for encrypting
    objects ( < 128 bits ) like IPv4, MAC, Credit Card numbers, Time Stamps etc.

  INSTALL -- 
  NOTE : openssl latest version (> openssl-1.0.1e) needs to be installed
  Steps
  
      source bootstrap.sh (optional)
      
     ./configure --enable-debug=yes
      
      make

   RUN
   
     cd test
   
     ./ipv4test -p password -t  tweak -f raw–ips

  IMPORTANT:  This is an *experimental* cipher, not for production yet. 
 
  Motivation and Applications of this scheme could be found at
	http://cisco.github.io/libfnr/

  Java extensions for this library could be found at
	https://github.com/cisco/jfnr

  Details of the Specification could be found in
	doc/Spec directory

  Report bugs to <libfnr-dev@external.cisco.com>

  FNR is designed by 
      Sashank Dara (sadara@cisco.com), 
      Scott Fluhrer (sfluhrer@cisco.com)

  Copyright (C) 2014 , Cisco Systems Inc.
