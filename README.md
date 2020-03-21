# nexus3

## backup and restore datas

### Blob Store Backup

`$data-dir/blobs`

### Database Backup

1. Configure the Admin - Export databases for backup Task to export databases.
2. Run the scheduled task to export the databases to the configured folder.
3. Back up custom configurations in your installation and data directories at the same time you run the export task.
4. Back up all blob stores.
5. Store all backed up configurations and exported data together.

<https://help.sonatype.com/repomanager3/backup-and-restore/prepare-a-backup>
