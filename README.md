## Usage

### Packages
- to save all installed packages into a text file use `sudo dpkg-query -f '${binary:Package}\n' -W > packages_list.txt`

- to install packages from a text file use `sudo xargs -a packages_list.txt apt install`

