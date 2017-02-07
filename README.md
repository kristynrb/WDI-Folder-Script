# WDI-Folder-Script
This script provides the folder structure for General Assembly's Web Development Immersive class repository. It includes a GA logo which can be reused on each of your file documents.

### To run the script
- Clone the `wdiFolderScript` file or paste the code from that file into a new file on your local machine.
- Navigate to the folder where you would like to create the WDI folder structure. From inside the root of that folder, type in the absolute path to the location of the script file.
Ex:`new_folder:$ ~/Desktop/wdiFolderScript`

### This script will produce the following:

1) README.md file with GA logo and required license information.

2) LICENSE.txt file - the information in the file will need to be added by your cohort.

2) .gitignore file

3) a project folder with project subfolders for projects 1-4 and the final projects.

4) Unit Folders
- Directories for unit_1 through unit 5
 <br>
![Image of unit folders](img/unit.png)
<br>

5) Week and Day Folders
 - Directories for the week and days of each unit. Ex: In unit_1, there are directories for w01d01 through w05d05.
<br>
![Image of subfolders](https://i.imgur.com/NKqfaFI.png)
<br>

 Note: You can change the *weeks* that you need for each unit in the code by modifying the numbers between the `w{}` inside the specific unit's code in the following two lines:

  `mkdir unit_$unit/w0{1..4}d0{1..5}`

  and

  `mkdir unit_$unit/w0{1..4}d0{1..5}/$i`

6) Subfolders
 - Subfolders for each day. The current list of subfolders is:
  - 'homework'
  -	'instructor_notes'
  -	'instructor_examples'
  -	'morning_exercise'
  -	'student_labs'
  -	'student_examples'
 <br>
![Image of subfolders](img/subfolders.png)
<br>
 Note: You can change the names of these subfolders (or remove them), by changing the names inside the array at the beginning of the script.
 
 <hr>
 
### Updated in February 2017:
- Added license information for the repository (LICENSE.txt file and license information in README.md file).
- double digit days and weeks for easier sorting.
- final project folder.
