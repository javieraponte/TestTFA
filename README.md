# TestTFA

I had the problem that my IDE doesn't upload projects since I had the TFA active.

This is the solution without deactivating the TFA:

1. Open settings from profile menu
2. In left sidebar open Personal access token under developer settings
3. Create a token
4. Use the token as your password while connecting with GIT.

The source of the solution is this:
https://bz.apache.org/netbeans/show_bug.cgi?id=271507#c2
