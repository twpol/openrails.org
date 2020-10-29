# openrails.org for GitHub Pages

This is an ongoing port of the [openrails.org](http://openrails.org) website to 
GitHub Pages. It is already live on 
[or-test.youngryan.com](https://or-test.youngryan.com).

### To-do list

- [ ] Download pages and links
- [ ] Investigate storage for large files (e.g. Git LFS)
  - [ ] DemoModel1.zip
  - [ ] Open Rails installer
  - [ ] PDF documents
- [ ] Code changes
- [ ] Randomized banners
- [ ] Menu should indicate current section/page

### Changes from the PHP version

- We cannot read file sizes or modification times on GitHub Pages, so we 
  manually populate this data with JSON files.
- The "Changes since last visit" feature has been removed.
- The contact form no longer sends the IP address and HTTP referer of the 
  sender. This information needs to be retrieved by @cjakeman's CGI program.
