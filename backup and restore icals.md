# Backup

```
icacls C:\ /save c:\backup\filename_ntfs_perms.txt /t /c
```

# Restore

```
icacls C:\ /restore c:\backup\filename_ntfs_perms.txt 1>c:\backup\filename_ntfs_perms.log 2>&1
```
