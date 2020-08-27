# Comsc230-Assignment1-HTML

First assignment basic html and css.

Part 1: Organize your project files

1. On your computer 'Documents' folder, create a new folder called 'GitHub'
2. In the GitHub folder, create a new folder: Comsc230-Assignments

Part 2: Clone the repo

1. Clone this repository using GitHub Desktop ** Important: point the local path to the Comsc230-Assignments folder
2. Open in VS Code, look at the files in the project, you should see the README and in the 'src' folder two html files
3. Open each of the html files using Google Chrome browser
File/Open/Documents/GitHub/Comsc230/Comsc230-Assignment1-HTML/src/a1-hello-v1.html
4. Open Chrome developer tools: View/Developer/Developer Tools

Part 3: Create a new web page

1. Navigate to https://www.w3schools.com/html/ and look at the first HTML example.
2. Create a new file in the project 'src' folder called: a1-w3schools-example1.html
3. Copy the code from the tutorial, paste it into the editor, save it and run it in your browser
4. Open the a1-hello-v2.html program and copy the css <style>...</style> section 
5. Paste the css into the appropriate location in you a1-w3schools-example1.html file
6. Open (or refresh) the file in the browser to see if the style has changed.

Part 4: Point the project origin to your github account

1. Create a new repository in your GitHub account: Comsc230-Assignment1-HTML

After it is created you will see a message that gives you the path to use when you set the origin on your laptop.

2. Remove pointer to the original project, open a new Terminal in Vs Code type in the following command
  
  git remote rm origin

3. Next we need to add the origin pointer to our own github project repo:

git remote add origin https://github.com/** your github user **/Comsc230-Assignment1-HTML.git

4. Finally we want to save our changes from our local git repository to our GitHub git repository

git push -u origin master

Part 5: Submit your assigment on Bridges

in the 'Assignments' folder on Bridges course website
Submit a copy of the modified HTML page (a1-w3schools-example1.html) to receive credit for 'Assignment 1'

