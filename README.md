RepoPractice
============
1. create a blank solution in Microsoft Visual Studio 2013 
  save it in C drive>documents>GitHub(you must create a Github folder in Documents)
2. Add a new website to your Solution(make sure its in C# select webforms)
  Make sure you save it in your GitHub\SolutionFolder\thisisyourwebsitefolder(nameit)
  
  When done save all your chanegs and close Microsoft Visual Studio 2013
  
3. drag your solution folder onto you GitHub Windows(This is to create a repository)
  *MAKE SURE YOU CHOOSE "VISUAL STUDIO " as your .gitignore selection*
  
4. commit your changes(The first commit is for creating .gitattributes and .gitignore files.)

    Example: Initial Website and solution then hit the commit to Master
    

5. in seetings on your git hub windows open Git SHell 

    run the following git add -f "this is the path to your website\bin\*"
    this is to track Dlls in the \Website\bin\ are not being complied 
    
6. Commit these changes Example: Force-add website\s bin\* files

7. publish the repository to GitHub(you can leave it as a public Repository)

8. to add a README file,  from your github windows setting select view on GitHub(log in to your account)
  at the bottom you should see an option to add an readme file

9. REMEMBER TO ALWAYS SYNC YOUR gITHUB FILES OR ELSE YOU WONT HAVE ACCESS TO IT FROM A DIFFERENT PC.
