San Francisco family (SF family)
---

Obtained from [https://developer.apple.com/fonts/](https://developer.apple.com/fonts/)

Installation
---

```
# Create correct local fonts directory, and copy contents

mkdir -p ~/.local/share/fonts/sf-family/
cp ~/src/SF-All-Fonts/*/*.otf ~/.local/share/fonts/sf-family/

# Regenerate the font cache

fc-cache -f -v

# Verify the install and the exact name

fc-list : family | grep -i "sf " | sort -u
```
