EncryptedCommitMessage
======================

Utilize PGP encryption for commit emails when working on sensitive code with a team


When working with a team on a centralized server (like Gitolite), you can have post commit hooks send an email to each team member detailing the changes that you just committed to the repository.  This is a great feature but can lead to leakage of Intellectual Property for more sensitve projects --> to mitigate this issue, you will be able to setup this post-commit hook script which will use a user-defined PGP Key on the server ane pull receipient PGP Keys from the key-servers to encrypt the commit messages before sending them out.

Please note, this is a work in progress and is not ready for production use at this time!
