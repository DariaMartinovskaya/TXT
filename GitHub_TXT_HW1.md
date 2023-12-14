## GIT Homework 1

## TXT
#### 1. Create external repository named TXT
Web Git Hub => "Repositories" Tab => [New] Button => Repository Name "TXT" => Click "Add a REDMI file" => [Create repository"] Button
#### 2. Clone TXT repository to local computer
git clone https://github.com/DariaMartinovskaya/TXT.git
#### 3. Create file “txt.xml” inside TXT repository
touch new.txt
#### 4. Add the file to git
git add new.txt
#### 5. Commit the file
git commit -m new.txt
#### 6. Send the file to external GitHub repository
git push
#### 7. Edit content of “new.txt” file - add the information about yourself (Full name, age, amount of pets, future desired salary). To be written in TXT format
cat => "Input data" => Ctrl + C
#### 8. Send changes to external repository
git add new.txt + git commit -m new.txt + git push
#### 9. Create preferences.txt file
touch references.txt
#### 10. Add information about your preferences (favorite film, favorite series, favorite food, favorite season, country you would like to visit) into preferences.txt file in TXT format
cat > preferences.txt => "Input data" => Ctrl + C
#### 11. Create sklls.txt file and add information about skills to be learnt during the course in TXT format
touch skills.txt; cat > touch.txt => "Input data" => Ctrl + C
#### 12. Make a commit in one line
git add . && git commit -m "2Files" 
#### 13. Send 2 files to external repository at the same time
git push
#### 14. Create bug_report.txt file on the web interface
Web Git Hub => Repositories => "XML" => Click [Add file] Button => Choose "Create new file" => Name of the file: "bug_report.txt"
#### 15. Commit changes (save) on the web interface
[Commit changes...] Button => [Commit changes] Button
#### 16. Modify bug_report.txt file on the web interface, add bug report in TXT format
Choose bug_report.txt => Edit this file button
#### 17. Commit changes (save) on the web interface
[Commit changes...] Button => [Commit changes] Button
#### 18. Synchronize external and local TXT repositories 
git pull
