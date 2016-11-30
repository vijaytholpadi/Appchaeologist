# Appchaeologist

⚒ A simple shell script to extract contents of an IPA file for analysis ⚒


---
## Disclaimer:
    For educational purposes only. Use at own risk.
    
---
## Background
Most of us (atleast the beginners) wonder how things are built under the hood when we look at certain apps. It may be the frameworks that an app is using OR the kind of images and assets that might be bundled as part of the package. This shell script acts as a single command to execute on your target IPA and extract its contents.


---
## Usage

### Prerequisites
- [Homebrew](http://brew.sh/)
- CoreUtils `brew install coreutils` (Using coreutils for the `greadlink` command as built in `readlink` had issues)
- Execute `chmod +x Appchaeologist.sh` in the path where you will store the downloaded .sh file

### Sample command
  Execute `./Appchaeologist /<path-to-IPA-file>`

---
## Known Issues / Things to be fixed:
- Before using it on an IPA file, we will need to make sure that the Filename does not contain any `.` characters in its name except for the file extension. ('.' occuring in versioning will need to be stripped out)
- Versioning detail in the filename will need to be stripped out. i.e. The IPA filename will need to match your `$(PRODUCT_NAME)`


---
## Improvements / Contributions
See someting failing not working as expected? Go ahead and raise a issue. 🚩

Want to contribute? Even better, open a PR. 🤘🏻😀


---
## Thanks
Many thanks to my colleague [Jayanth](https://github.com/jaymanklu) for being an extra pair of eyes checking the sanity of this project.
