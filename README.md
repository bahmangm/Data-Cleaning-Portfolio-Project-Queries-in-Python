### Notebook Overview

This notebook provides a step-by-step guide to removing inconsistencies in two data files before merging them. It includes the following steps:

1. **Identify Inconsistencies in Common Columns:** 
   - Create a dictionary to detect and handle repeated values in common columns.
   - Exclude 'Date' and 'Signed numbers' fields.

2. **Handle File-Specific Columns:** 
   - Identify and manage inconsistencies in columns unique to each file.
   - Again, exclude 'Date' and 'Signed numbers' fields.

3. **Apply Consistency Fixes:** 
   - Use the created dictionary to address inconsistencies across both files.

4. **Clean Special Fields:** 
   - Apply specific functions to clean 'Date' and 'Signed numbers' columns.

5. **Merge the Cleaned Files:** 
   - Finally, merge the two files after they have been cleaned and standardized.
