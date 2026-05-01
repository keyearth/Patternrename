# PatternRename — Batch File Renaming Tool
PatternRename is a high-efficiency, browser-based utility designed for precision batch renaming. Originally developed to manage time-sensitive laboratory photography, it has evolved into a versatile tool for renaming images, videos, and documents using advanced pattern recognition, Regular Expressions (RegExp), and coordinate-based character extraction.
# Key Features
* Zero Installation: Runs entirely in the browser using the HTML5 File System Access API. No executables or IT approvals required—perfect for restricted corporate environments.
* Smart Fill (Pattern Intelligence): Simply fill in the first two rows, and the "Smart Fill" engine will detect the sequence (alphanumeric, arithmetic, or repeating patterns) and complete the rest automatically.
* Coordinate-Based Extraction: Use [i,j] syntax to extract specific characters from original filenames (e.g., [1-5] for the first five characters).
* RegExp Support: Use standard Regular Expressions (e.g., /(\d+)/) to pull specific data points from existing filenames.
* Subfolder Migration: By adding a / at the end of a pattern, the tool will automatically create subdirectories and move the renamed files into them.
* Safe Preview: A real-time "New Filename Preview" column ensures you see exactly what will happen before a single file is changed.
# Core Functionality Explained
1. Multi-Pattern ColumnsYou can add multiple columns (Col 1, Col 2, etc.) to represent different segments of your new filename. The tool concatenates these segments to build the final name.
2. Advanced Extraction PatternsPosition List: [5,6,7,3-1] extracts characters at positions 5, 6, and 7, followed by positions 3 down to 1.Regex Extract: /\d+/ extracts the first sequence of digits found in the filename.Sequence Wrapping: Automatically handles A → Z or 01 → 99 increments.3. Chronological AnalysisThe tool displays file timestamps and the time difference ([Diff]) between files, which is essential for sequencing laboratory data or time-lapse photos.
#      📅 Changelog
*      2026-04-28:Universal Support: Expanded beyond laboratory images to support all file types (Video, Audio, Docs, etc.).  Extension Filtering: Added a multi-select dropdown to filter specific file types during the loading process.  
*     2026-04-26:Initial Launch: Deployed with core Smart Fill and RegExp extraction features.
# 📖 Quick Start
* Load Folder: Click ▶ Load & Reset to select your local directory.  
* Define Patterns: Enter your rules in the Col inputs (text, [positions], or /regex/).  
* Smart Fill: Fill the first two rows and click ⚡ Smart Fill All to propagate the pattern.  
Execute: Verify the New Filename Preview and click ✎ Rename All Files to apply changes.  
# 🔒 Privacy & Security
This is a "Green App." All processing occurs locally within your browser's memory. No files, filenames, or metadata are ever uploaded to a server—ensuring 100% data privacy and security. 
Note for Engineers:This tool was built to bridge the gap between rigid corporate IT environments and the need for powerful automation. It brings "Excel-like" logic to file management without the need for complex scripting.
# 💡 Need Help?  
For detailed syntax examples and pattern logic, click the ? Help button on the top right of the tool.  
