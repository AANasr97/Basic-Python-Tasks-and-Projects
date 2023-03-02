find . -name ".DS_Store" -delete


find . -name .DS_Store -print0 | xargs -0 git rm -f --ignore-unmatch