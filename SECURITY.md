# Security policy

## Reporting a vulnerability

Email **rld.ranger07@gmail.com** with `SHRINEFALL SECURITY` in the subject line.

Please include:

- what the issue is, and what an attacker gets out of it;
- how to reproduce it - the platform (iOS or Android), the app version and build number from the
  in-game settings screen, and the steps;
- anything you had to install, patch or intercept to make it work.

You will get an acknowledgement, and a fix will be shipped in a store update if the report holds up.
This is a one-person studio: expect a human reply rather than a ticket number, and expect the fix to
travel at the speed of app review.

Please give a reasonable amount of time for a fix before disclosing publicly, and please do not test
against other players' sessions or devices, or the Unity Gaming Services backend, in a way that
degrades service. Do not access, modify or delete data belonging to anyone but yourself.

There is no bug bounty.

## What is in scope

- The shipped Shrinefall apps for iOS and Android (bundle id `com.rldgames.shrinefall`).
- The co-op session layer (Unity Relay + Netcode for GameObjects): anything that lets one player
  damage, disconnect, impersonate or read the save data of another.
- The build pipeline repository `KaanIpek/shrinefall-build`: anything that would let a third party
  read a decrypted payload or run the workflow with the project's signing secrets.

## What is out of scope

- Denial of service against Unity's Relay or authentication services (report those to Unity).
- Cheating that affects only the cheater's own offline solo session.
