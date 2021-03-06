# Breacher
A script to find admin login pages and EAR vulnerabilites.

#### Features
- [x] Multi-threading on demand
- [x] Big path list (798 paths)
- [x] Supports php, asp and html extensions
- [x] Checks for potential EAR vulnerabilites

### Usages
- Check all paths with php extension
```
python breacher -u example.com --type php
```
- Check all paths with php extension with threads
```
python breacher -u example.com --type php --fast
```
- Check all paths without threads
```
python breacher -u example.com
```

<b>Note: </b> When you specify an extension using <b>--type</b> option, Breacher includes paths of that extension as well as paths with no extensions like <b>/admin/login</b>

#### Demo
<img src='https://i.imgur.com/CkdsNs7.png' />
