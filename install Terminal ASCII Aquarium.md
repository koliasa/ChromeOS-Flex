## 1. Install Therminal Animation 
```bash
sudo apt-get install libcurses-perl
sudo apt-get install build-essential
cd /tmp
wget http://search.cpan.org/CPAN/authors/id/K/KB/KBAUCOM/Term-Animation-2.6.tar.gz
tar -zxvf Term-Animation-2.6.tar.gz
cd Term-Animation-2.6
perl Makefile.PL && make && make test
sudo make install
```
## 2. Install ASCIIQuarium
```bash
wget http://www.robobunny.com/projects/asciiquarium/asciiquarium.tar.gz
tar -zxvf asciiquarium.tar.gz
cd asciiquarium_1.1/
chmod +x asciiquarium
sudo cp asciiquarium /usr/local/bin/asciiquarium
sudo cpan Term::Animation
asciiquarium
```
