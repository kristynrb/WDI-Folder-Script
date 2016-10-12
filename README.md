# WDI-Folder-Script

### To run the script
- Clone the `wdiFolderScript` file or paste the code from that file into a new file on your local machine.
- Navigate to the folder where you would like to create the WDI folder structure. From inside the root of that folder, type in the direct filepath to the location of the script file.
Ex:`new_folder:$ ~/Desktop/wdiFolderScript`

### This script will produce the following:
- README.md file with GA logo
- .gitignore file
- Directories for unit_1 through unit 5
 INSERT IMAGE

 - Directories for the week and days of each unit. Ex: In unit_1, there are directories for w1d1 through w5d5.
INSERT IMAGE
 Note: You can change the *weeks* that you need for each unit in the code by modifying the numbers between the `w{}` inside the specific unit's code in the following two lines:
 `mkdir unit_$unit/w{1..4}d{1..5}`
 and
 `mkdir unit_$unit/w{1..4}d{1..5}/$i`

 - Subfolders for each day. The current list of subfolders is:
  - 'homework'
  -	'instructor_notes'
  -	'instructor_examples'
  -	'morning_exercise'
  -	'student_labs'
  -	'student_examples'
INSERT IMAGE
 Note: You can change the names of these subfolders (or remove them), by changing the names inside the array at the beginning of the script.
