# Sparse Files
A sparse file is a type of copmuter file that tries to use file system space more efficiently when blocks allocated to the file are mostly empty.
Sparse files are often used for disk images, db snapshots, and log files.

## How

### Writing
By writing metadata representing empty blocks to disk instead of actual "empty" space to make up the block, you can use less disk space.
Sparse files contain blocks of zeros with the existence being recorded, but no space allocated on disk. Only when the block contains non-empty data does the full block size get written to disk as the actual size.

### Reading
Reading sparse files means the file system converts metadata representing empty blocks into "real" blocks filled with zeroes at runtime. Applications do not know this conversion occurs.

## Pros
Storage only gets allocated when it is really needed, disk space gets saved so large files can be created even if there isn't enough free space on the file system.

## Cons
1. Fragmentation can occur
2. Free space reports can be misleading
3. Filling up sparse files can produce unexpected results
4. Copying sparse files with unsupported programs can copy uncompressed sizes (mostly zeroes) losing the benefits of sparse properties

## Read more
[Archlinux Doc](https://wiki.archlinux.org/index.php/sparse_file)