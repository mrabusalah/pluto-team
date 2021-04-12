<img src="https://github.com/mrabusalah/pluto-team/blob/main/pluto.png" width="100">

# PLUTO team manual guide / [ProgressSoft](https://www.progressoft.com)

###### :man: Auther : [KNIGHTK0DER](https://github.com/mrabusalah)
------------------------------
### :scroll: These steps should be done before open a merge request

- First of all, create a branch from the story itself without merge request (it is recommended to name the branch by the story number).
- Before you start working on the task be sure that you checked out to your new branch.
- Reload all maven projects.
- Rum `mvn clean install` to generate all the needed classes and files.
- Try to apply the clean code principles, and if you found something should be refactor don't wait and do ti even if it's not in your task scope.
- Click `alt + shift + L` after each change to format your code and remove the unused imports on every class.
- Make sure to write a JUNIT test that covers 100% of the written production code.
- Don't forgot the Integration test as well.
- Make sure that your fix or feature is working well by testing it by integration test, postman or live site.
- Run `mvn fmt:format` if plugin exist.
- Run `mvn clean install` before pushing.
- Never push your changes by console.
- Use `ctrl + K` to review the added and changed files before pushing.
- Make sure to not push the target folders or the generated files.
- Double check the changes from the pipeline on Gitlab.
- Come back to this guide every time to be sure there is no step missing.
- open a merge request.
- If any comments added to your merge by the re-viewer apply the steps again.
- Always "leave the code better than you found it".
