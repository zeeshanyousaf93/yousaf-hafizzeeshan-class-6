Questions:
1.Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.
Answer: 
a)."ls -a" See if .Git folder exist 
b).Try to run any git commant, this will tell if you are not in git repository. If command run successfully, thats mean that you are in git repository. i.e "git status", "git log"...etc 
2.Assuming that you are currently within a Git repository, write the command (or commands) that will create a new file named 'hello-world.txt' then stage and commit it.
Answer:
a). "touch hello-world.txt" this command will create file 
b). "git add -A" this will stage both README.md and hello-world.txt files 
c). "git commit -m "message" " this will commit the stage 
3.Assuming that you are currently within a Git repository that contains a file named 'README.md', write the command (or commands) that will display any uncommitted changes made to this file.
4.Assuming that you are currently within a Git repository that includes several commits, write the command (or commands) that will display the changes from the commit with the ID of abc123.
5.Assuming that you are currently within a Git repository that includes multiple commits, write the command (or commands) that will display the IDs and commit messages for the 3 most recent commits.