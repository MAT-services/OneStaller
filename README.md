# OneStaller
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="art/header-dark.png">
  <img alt="OneStaller Website" src="art/header-light.png">
</picture>

## Website status:
[![GitHub last commit](https://img.shields.io/github/last-commit/MAT-services/OneStaller?style=plastic)](https://github.com/MAT-services/OneStaller/commits)
[![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/MAT-services/OneStaller/pages%2Fpages-build-deployment?style=plastic)](https://github.com/MAT-services/OneStaller/actions)
## Future plans:
OneStaller Package Manager in Rust.
	Uses an JSON file (update to upload or just online?) to check for sources. (Create a new GIT repo for it.)
```json
{
	"version": -1,
	"packages": {
		"myNewIncrediblePackage": {
			"latest": {
				"version": -1,
				"windows": "pathToInstaller",
				"debian": "AnotherOne"
			
			},
			"description": [
				"Short",
				"This:Is/a/path/to/an/extremly/long/description.md"
			],
			"specials": ""
		},
		"anotherPackageButYesFlemme": {}
	}
}
```
Used by the website. (He will just be a client.) https://mat-services.freeddns.org/OneStaller/
		Website fetch file that have information and paths of contents. Pages can be created from this file.
	Application is possible, so. (It will be another client.)
		Same principe, just build the pages differently to install the application directly and not just download the file.
		
On the GIT repos, add the banners.
		
	