# backup-to-glacier
`backup-to-glacier` is a simple script to backup your files to Amazon Glacier.

# Usage
```
git clone https://github.com/katsuma/backup-to-glacier
cd backup-to-glacier
bundle install
VAULT_ID=your_vault_id ARCHIVE_PATH=your_backup_target backup-to-glacier
```