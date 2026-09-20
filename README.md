# Clue Controller — releases

Installers for **Clue Controller**, Clue HQ's escape-room control software.

This repository holds **binaries only**. Every file here is uploaded by the release workflow
in the private source repository when a version tag is pushed; nothing is committed by hand
and there is no source code here.

The app's built-in updater reads the channel files in each release (`latest.yml`, `pilot.yml`,
`internal.yml`) to find out whether a newer build exists for the channel a venue's licence is
on. Venues get installers from the **Downloads** page of the Clue Control console, which links
here.

If you are looking for the software itself, that is the place to start:
https://cluecontrol.cluehq.co.uk

---

*This README exists because GitHub will not create a release on a repository with no
commits. It is the one and only commit that is not a build artefact.*
