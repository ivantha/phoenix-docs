# Project Name
Petabyte-Scale Cloud Storage File Manager

## Student Info
* <b>Name</b> : Oshan Mudannayake
* <b>University</b> : University of Colombo School of Computing, Sri Lanka.
* <b>Email</b> : [oshan.ivantha@gmail.com](mailto:oshan.ivantha@gmail.com)
* <b>Github</b> : [github.com/OshanIvantha](https://github.com/OshanIvantha)
* <b>Linkedin</b> : [in/ivantha](https://www.linkedin.com/in/ivantha)

### Project Abstract
CERNBox is a cloud storage synchronisation service for CERN users:
it allows syncing and sharing files on all major mobile and desktop
platforms (Linux, Windows, MacOSX, Android, iOS) aiming to provide
offline availability to any data stored in the CERN EOS infrastructure.
CERNBox is based on ownCloud, a cloud sync and share platform written in
PHP following a Model-View-Controller architecture software pattern.

This project aims to provide a prototype of a new web UI for CERNBox
that will provide an immersive user experience. To achieve this, a
milestone of this project is to provide offline manipulation of the data
from the browser. The use case is that when a user goes offline in his
browser, he could continue to work on the document and perform actions
like renaming and browsing his files. Once network is re-established,
the application will reconcile the changes in the browser cache with the
server, offering a non-disruptive work environment for the end-user.

### [GSoC Project Page](https://summerofcode.withgoogle.com/projects/#5067468272304128)

### [GSoC Project Proposal](https://storage.googleapis.com/summerofcode-prod.appspot.com/gsoc/core_project/doc/6504610056372224_1522136827_Petabyte-Scale_Cloud_Storage_File_Manager.pdf?Expires=1534198420&GoogleAccessId=summerofcode-prod%40appspot.gserviceaccount.com&Signature=e8QRpWDmnQrBL5%2BnuJZ668xvnEKTd4cxV5JWmHV4dFraxZVQRlEoPDC%2Fzzt1AJ6Crs5EdmDKBmFdYYMlp%2BVBFXStdQpTDzxPx7dTDzqLY4BjnLO%2Fq3VNbL308Dl%2FhVszb1CW%2FWO0pHytjw9sEufzAMvbccDdvWfU0Ynht%2BncIdAB8bsZkHetucz%2BqBX%2FAXmtdQypb7pNFuYWMyreD7VuRtI%2Bboouz159QWEO%2FP8Fad3XwaSJXjlOCVhpvjb%2BCxSy9BWdb81D%2BnkMpQHa%2F1IFbzD4dFu3STRdG2BsG0A2vfgA5MAoUp%2FrcNJ3bvMowfjD4Bt5lfWz1wgqBAzp83O26A%3D%3D)

### [GitHub Organization Repo](https://github.com/owncloud/phoenix)

### [Commits during GSoC 2018](https://github.com/owncloud/phoenix/pulls?utf8=%E2%9C%93&q=is%3Apr+author%3AOshanIvantha+)

### [Project Demo]() - TODO

### [Project Wiki](https://github.com/OshanIvantha/phoenix-docs/wiki)

### Work Summary
For GSoC 2018 I worked on the Phoenix frontend for the ownCloud. I mainly
worked on the files-app which enabled browsing of files and also its
PWA capabilities.

#### M2 - Files-app
The files app will be a prominent app in the primary interface of Phoenix.
It allow users to navigate through their files and other file management
activities such as download etc.

#### M3 - Adapt Phoenix to a PWA
This milestone aims to equip Phoenix with offline file manipulation
capabilities. PWA capabilities has been added using two main methods.
- Caching of files using the Workbox plugin
- Saving the file hierarchy of the user's storage space while the user is online

### What is covered
- [x] M2.1 Implement file browsing
- [x] M2.2 Implement data upload and download
- [x] M2.5 Perform tests on various corner cases that arise
- [x] M2.6 Ensure proper documentation of the written code
- [x] M3.1 Wrap Phoenix into a shell-app following Google best practices
- [x] M3.2 Test PWA compatibility with Lighthouse
- [x] M3.3 Cache file metadata from ownCloud into the browser cache
- [x] M3.4 Detect when user goes offline and show warning banner
- [x] M3.5 Reconcile changes when network connection comes back
- [x] M3.6 Test offline metadata scenarios

### What is left
- [ ] M2.3 Implement the public link functionality
- [ ] M2.4 Implement the sharing functionality

### Reference
1. [Vue.js Documentation](https://vuejs.org/v2/guide/)
2. [UIKit Documentation](https://getuikit.com/docs/introduction)
3. [PUG Documentation](https://pugjs.org/api/reference.html)
4. [owncloud-js-client](https://github.com/owncloud/js-owncloud-client)
