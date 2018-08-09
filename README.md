# Microbot

Microbot is a Github interface to provide ease of access for performing standard common tasks like 

- create repository
- create issues on a repository
- add user 
- update issue
- add collaborator
- and many more...

Just by typing an instruction to do so.

Application uses Recast's NLP and Machine Learning to understand intent of the user, and to extract data provided.

- For instance, saying "create repository with the name TestRepo" will open a form with pre-filled extracted repository name.
Submitting the form creates the repository.
- Similary "create an issue with title TestTitle on the repository TestRepo" will extract repository name and issue title, will pre-fill a form to be submitted.
- A history of said tasks, forms that were filled in the past and the response is maintained in the history.
- Github login is used to get reference of current user account, on which Github tasks will be performed.
- View repository shows all the repositories under the user account, with buttons to show raw repository data as json, delete repository and the owner of the repository.
- Redux is used to persist history in local storage of the browser that can be replaced with Json-server or any other No-SQL DB

Features can be requested at: pooja.prasad66@gmail.com
