A PPA repository for my packages:

- [tilt_perl](https://github.com/irontonbrewing/tilt_perl)

# Usage

```bash
curl -s --compressed "https://irontonbrewing.github.io/projects/dist/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/irontonbrewing.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/irontonbrewing.list "https://irontonbrewing.github.io/projects/dist/irontonbrewing.list"
sudo apt update
sudo apt install tilt-perl
```
