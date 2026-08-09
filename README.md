# drive restore

## This one works for most damaged drives when it has raw format, unreadable error, flash drive 0 bytes...

### Step 1 - Open cmd by pressing `Windows icon + R`

### Step 2 
```bash
diskpart
```

### Step 3 
```bash
list disk
```

### Step 4 - You need to select the one that represents your flash drive
```bash
select disk <disk_no>
```

### Step 5
```bash
clean
```

### Step 6
```bash
create partition primary
```

### Step 6 - Any one out of:
```bash
format fs=ntfs quick

format fs=fat32 quick

format fs=exfat

format fs=ntfs
```
- with no quick included when quick means quick format in Windows.
