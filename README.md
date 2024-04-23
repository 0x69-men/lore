https://askubuntu.com/questions/377438/how-can-i-recursively-delete-all-files-of-a-specific-extension-in-the-current-di

```bash
find */ -type f -exec bash -c 'file=${1#./}; mv "$file" "${file//\//_}"' _ '{}' \;
```

```bash
find */ -depth -type d -exec rmdir '{}' \;
```
