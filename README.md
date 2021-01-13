
[GRAB ME!](https://github.com/r-selfhosted-wiki/wiki) for the /r/selfhosted wiki.
[Hugo-Theme DOCS](https://github.com/matcornic/hugo-theme-learn).



```
mkdir /home/iptv/wiki

git clone --recurse-submodules https://github.com/HaagridTV/wiki.git

[:comment:] if working on fresh site do this, if not skip.
cp config.toml.example config.toml

hugo server --bind=0.0.0.0

[:comment:] When done, run hugo to build site
hugo
```

Navigate your browser to `http://<machineIP>:1313` and you should see the site live on your local machine.

You're now ready to start adding and/or editing content.
