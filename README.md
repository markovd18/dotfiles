## Usage

### PPA repositories
- to list all PPA repositories execute `chmod u+x listppas.sh && ./listppas.sh`
- to install all PPA's execute ./listppas.sh > installppas.sh && ./installppas.sh`

### Packages
- to save all installed packages into a text file use `sudo dpkg-query -f '${binary:Package}\n' -W > packages_list.txt`

- to install packages from a text file use `sudo xargs -a packages_list.txt apt install`

