# drive restore

## This one works for most damaged drives when it has raw format, unreadable error, flash drive 0 bytes...

### Step 1 - Open cmd by pressing "Windows icon + R"

### Step 2 - Type diskpart

### Step 3 - Type 'list disk'

### Step 4 - Type 'select disk *' (You need to select the one that represents your flash drive)

### Step 5 - Type 'clean'

### Step 6 - Type 'create partition primary'

### Step 6 - Type 'format fs=ntfs quick', or type 'format fs=fat32 quick', or you may use 'format fs=exfat', or 'format fs=ntfs' with no quick included when quick means quick format in Windows.
