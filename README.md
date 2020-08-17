### .NET 462 wont install on W7 Pro SP1 - Solved :(

I am trying to install .net462 on a standard untouched w7 pro sp1 install. My iso is en_windows_7_professional_with_sp1_vl_build_x86_dvd_u_677791.iso with a matching file hash.

I always get the same error message, see attached. It will install if i have kb3125574 etc installed though.

I am working on 2 configurations, with 3125574 and without 3125574 and i will capture the updated image to wim file, all updates .nets c++ stuff fully integrated, no Install Pendings, so i need to have it working on both.


### Checking if certificates are already installed :)

One way to check on the installing system is to follow these steps:

Run mmc.exe.
a. Click File, and then select Add/Remove Snap-in.

b. Double-click Certificates, select Computer account, and then click Next.

c. Select Local computer, click Finish, and then click OK.

d. Expand Certificates (Local Computer).

e. Expand Trusted Root Certification Authorities, and then select Certificates.

Check this list for the necessary root certificates.

f. Expand Intermediate Certification Authorities, and then select Certificates.

Check this list for the required intermediate certificates.
Click File, and then select Add/Remove Snap-in.
a. Double-click Certificates, select My user account, click Finish, and then click OK.

b. Expand Certificates – Current User.

c. Expand Intermediate Certification Authorities, and then select Certificates.

Check this list for the required intermediate certificates.
If the certificates names were not in the Issued To columns, they must be installed. If an intermediate certificate was only in the Current User Intermediate Certificate store, then it is available only to the user that is logged in. You might need to install it for other users. 


