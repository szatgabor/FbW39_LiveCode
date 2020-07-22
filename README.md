# DCI FbW39 Summary!

In this document you can see the class material in summerized form.


## 22.07.2020

- Creating **Local repository**
	> Create a repository on GitHub and clone it into the folder you wish to be your Local Folder for it. 
		// git clone [Repository URL]
		- Upload Local repository to **GitHub**
			> Add, commit and push 
				// git add [path]
					// git commit -m "note"
						// git push -u origin master
						- Making changes in GitHub and **pull** these content to the Local repository
							> // git pull -u origin master
							- Make, check **branches**
								> // git branch -d [branch_name]
									// git branch
									- Making a Public and Private repository from terminal with **curl command**
										> // curl -u "GitHub_Account_Name" https://api.github.com/user/repos -d '{"name":"repository_name","private":true}
											// curl -u "GitHub_Account_Name" https://api.github.com/user/repos -d '{"name":"repository_name","private":false}
