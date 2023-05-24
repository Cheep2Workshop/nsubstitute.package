# Unity Package Template
This is a template repository for unity package. You can build a custom package with this template.


## Quick Start
1. Create a repository by this template</br>
Press "**Use this template**" to create repository by this template
![image](https://user-images.githubusercontent.com/34429337/147848194-e19f5677-cc91-48f8-82d4-9f4d0ee6a4be.png)
2. Create new local unity project
3. Clone the repository from your custom package url in local unity project
4. Edit your package.json
```json
{
	"name": "com.[company].[package_name]",
	"displayName": "[package_display_name]",
	"version": "1.0.0",
	"unity": "2020.3",
	"author": "Cheep2Workshop",
	"description": "[package_description]",
	"dependencies": {
	},
	"repository": {
		"type": "git",
		"url": "[package_git_url]"
	}
}
```
5. Edit or create new asmdef instead of com.cheep2workshop.package.runtime</br>
**Notice: the package name must named with prefix "com."**

## How to use
- Edit your runtime code in Runtime folder
- Edit your testing code in Tests folder
