# File System Recovery Lab

This lab demonstrates basic file system forensics tasks on Windows images.

## Screenshots

- `autopsy_recyclebin.png` – Autopsy view of the Recycle Bin with multiple
  deleted documents (PDFs and PPTX), showing metadata and deletion timestamps.
- `deleted_files_jimmy_wilson.png` – Web-based SleuthKit/Autopsy “All Deleted
  Files” listing for the 2020JimmyWilson image, highlighting browser cache
  images recovered from `Temporary Internet Files`.
- `foremost_output.png` – Terminal output from running `foremost -i 2020JimmyWilson.E01 -o foremost_output`
  to carve files from the disk image.
- `foremost_summary.png` – Foremost summary report indicating overall carving
  statistics for the image.
- `php_dependencies.png` – Environment check showing DLL dependencies for
  PHP modules on the analysis system.

## Notes

The goal of this lab was to practice:

- Identifying deleted files using Autopsy / SleuthKit.
- Performing file carving with `foremost`.
- Interpreting results when carving recovers few or no complete files.
