
# `Step 4`
I clicked on the terminal and 
`The keys pressed:` `ssh m4aziz@ieng6-201.ucsd.edu<enter>, cs15l<tab> to give cs15lwi24 <enter>`

`Explanation:` The reason I added the 201 was because that was one of the machines it worked on and originally it was connecting to machine 203 which wasn't letting me run. the `ssh` command is used to login into my ieng6 account.

![image](Step4)

# `Step 5`
`Steps taken:` I went to github on browser, forked the repository, then I clicked the copy on the ssh url, and went to vs code and did git clone ctrl v.

`Explanation:` I ran the first and second command to fork it, and the third because I needed to copy the url and the button was right there easy to access, for the 4th step I opened upvscode and in the terminal I git cloned the repository so I could have access with the files.

![image](Step5)

# `Step 6`
`Steps taken:` `ls<enter>, cd lab7/<enter>, ls, cat test.sh<enter>, bash test.sh<enter>`

`Explanation:` First step showed me the directories and the lab7 which I wanted to access, I changed directory into lab7 to have access to the folders in lab7 and ls showed me which ones there were. I did cat on the test.sh file to see what was in that directory and there were test lines for me to run my code with. Then I run test.sh with bash and this the output that got printed was the output in my screenshot.

![image](Step6)

# `Step 7`
`Steps taken:` `ls<enter>,cat ListExamples.java<enter>,vim ListExamples.java<enter>`

`Explanation:` This opened up my directories and the cat ListExamples.java printed me everything that the file contained inside of the terminal. I then did Vim ListExamples.java to open up the virtual machine on that file which I wanted to edit.

`Below is an image of the code previous to being fixed.`

![image](Step7failingOutput)

`Steps taken to fix bug:` `k 3 times, L 9 times,x one time, esc, i one time , 2, escape, :wq<enter>`

`Explanation:` I first clicked k because I needed to go up to the error then I clicked L until I was hovering over the integer one that used to be there. I used x to remove that 1 and I clicked escape to because I cant insert in that state. Then I clicked i to enter insert mode and then clicked 2 to add the correct value to make the code work. Finally I clicked escape and :wq to save my work and exit successfully.

`Below is the image of the fixed code`

![image](Step7fixedCode)


# `Step 8`
`Steps taken to show test passes:` `I then do ls<enter>, bash test.sh<enter>`

`Explanation:` Upon exiting vim in the next step I checked what directory access I had by doing the ls and ran the test one final time with bash test.sh and I passed my test cases.

![image](Step8passingTest)

# `Step 9`

`Steps taken:` `git add ListE<tab><enter>, git commit -m "Fixed the bug"<enter>, git push<enter>`

`Explanation:` I did the git add ListE<tab> to quick access ListExamples.java and I was adding ListExamples to the staging area. I then did git commit to place it in my local git repository, Finally I did git push to push the file into my github repository.

`The image below is the code I used`

![image](Step9code)

`Below I have an image of the final result of the git commit`
![image](Step9output)

