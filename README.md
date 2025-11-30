echo "# nodejs" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:gabdung/nodejs.git
git push -u origin main# nodejs{
	"nameShort": "Code - Insiders",
	"nameLong": "Visual Studio Code - Insiders",
	"applicationName": "code-insiders",
	"win32x64AppId": "{{1287CAD5-7C8D-410D-88B9-0D1EE4A83FF2}",
	"win32arm64AppId": "{{0AEDB616-9614-463B-97D7-119DD86CCA64}",
	"win32x64UserAppId": "{{217B4C08-948D-4276-BFBB-BEE930AE5A2C}",
	"win32arm64UserAppId": "{{69BD8F7B-65EB-4C6F-A14E-44CFA83712C0}",
	"win32NameVersion": "Microsoft Visual Studio Code Insiders",
	"win32DirName": "Microsoft VS Code Insiders",
	"win32SetupExeBasename": "VSCodeInsidersSetup",
	"win32AppUserModelId": "Microsoft.VisualStudioCodeInsiders",
	"win32ShellNameShort": "Code Insiders",
	"win32MutexName": "vscodeinsiders",
	"win32RegValueName": "VSCodeInsiders",
	"darwinCredits": "resources/darwin/Credits.rtf",
	"darwinBundleIdentifier": "com.microsoft.VSCodeInsiders",
	"darwinProfileUUID": "7CC2F939-3A89-4A22-B9DA-E5B81C0F6C03",
	"darwinProfilePayloadUUID": "BEA6A398-BD82-4EEC-B626-8464DBB73561",
	"darwinExecutable": "VSCodeInsiders",
	"linuxIconName": "vscode-insiders",
	"licenseFileName": "LICENSE.rtf",
	"licenseName": "Multiple, see https://code.visualstudio.com/license",
	"serverGreeting": [],
	"serverLicense": ["*", "* Visual Studio Code Server", "*", "* By using the software, you agree to", "* the Visual Studio Code Server License Terms (https://aka.ms/vscode-server-license) and", "* the Microsoft Privacy Statement (https://privacy.microsoft.com/en-US/privacystatement).", "*"],
	"serverLicensePrompt": "Do you accept the terms in the License Agreement (Y/n)?",
	"serverApplicationName": "code-server-insiders",
	"urlProtocol": "vscode-insiders",
	"dataFolderName": ".vscode-insiders",
	"serverDataFolderName": ".vscode-server-insiders",
	"downloadUrl": "https://code.visualstudio.com/insiders",
	"updateUrl": "https://update.code.visualstudio.com",
	"webUrl": "https://insiders.vscode.dev",
	"webEndpointUrl": "https://main.vscode-cdn.net",
	"webEndpointUrlTemplate": "https://{{uuid}}.vscode-cdn.net/{{quality}}/{{commit}}",
	"nlsCoreBaseUrl": "https://www.vscode-unpkg.net/nls/",
	"webviewContentExternalBaseUrlTemplate": "https://{{uuid}}.vscode-cdn.net/{{quality}}/{{commit}}/out/vs/workbench/contrib/webview/browser/pre/",
	"quality": "insider",
	"extensionsGallery": {
		"nlsBaseUrl": "https://www.vscode-unpkg.net/_lp/",
		"serviceUrl": "https://marketplace.visualstudio.com/_apis/public/gallery",
		"itemUrl": "https://marketplace.visualstudio.com/items",
		"publisherUrl": "https://marketplace.visualstudio.com/publishers",
		"resourceUrlTemplate": "https://{publisher}.vscode-unpkg.net/{publisher}/{name}/{version}/{path}",
		"extensionUrlTemplate": "https://www.vscode-unpkg.net/_gallery/{publisher}/{name}/latest",
		"controlUrl": "https://main.vscode-cdn.net/extensions/marketplace.json",
		"mcpUrl": "https://main.vscode-cdn.net/mcp/servers.json",
		"accessSKUs": ["copilot_enterprise_seat", "copilot_enterprise_seat_quota", "copilot_enterprise_seat_multi_quota", "copilot_enterprise_seat_assignment", "copilot_enterprise_seat_assignment_quota", "copilot_enterprise_seat_assignment_multi_quota", "copilot_enterprise_trial_seat", "copilot_enterprise_trial_seat_quota", "copilot_for_business_seat", "copilot_for_business_seat_quota", "copilot_for_business_seat_multi_quota", "copilot_for_business_seat_assignment", "copilot_for_business_seat_assignment_quota", "copilot_for_business_seat_assignment_multi_quota", "copilot_for_business_trial_seat", "copilot_for_business_trial_seat_quota"]
	},
	"extensionProperties": {
		"github.copilot-chat": {
			"excludeVersionRange": "<=0.16.1"
		},
		"github.copilot": {
			"hasPrereleaseVersion": true
		}
	},
	"defaultAccount": {
		"authenticationProvider": {
			"id": "github",
			"enterpriseProviderId": "github-enterprise",
			"enterpriseProviderConfig": "github.copilot.advanced.authProvider",
			"scopes": ["user:email"]
		},
		"chatEntitlementUrl": "https://api.github.com/copilot_internal/user",
		"tokenEntitlementUrl": "https://api.github.com/copilot_internal/v2/token"
	},
	"profileTemplatesUrl": "https://main.vscode-cdn.net/core/profile-templates.json",
	"emergencyAlertUrl": "https://main.vscode-cdn.net/core/insiders.json",
	"extensionPublisherOrgs": ["microsoft"],
	"trustedExtensionPublishers": ["microsoft", "github"],
	"extensionRecommendations": {
		"ms-dotnettools.csdevkit": {
			"onFileOpen": [{
				"pathGlob": "{**/*.cs,**/global.json,**/*.csproj,**/*.cshtml,**/*.sln}",
				"important": true
			}, {
				"languages": ["csharp"],
				"important": true
			}, {
				"pathGlob": "{**/project.json,**/appsettings.json}"
			}]
		},
		"ms-python.python": {
			"onFileOpen": [{
				"pathGlob": "{**/*.py}",
				"important": true
			}, {
				"languages": ["python"],
				"important": true
			}, {
				"pathGlob": "{**/*.ipynb}"
			}]
		},
		"ms-toolsai.jupyter": {
			"onFileOpen": [{
				"pathGlob": "{**/*.py}",
				"contentPattern": "^#\\s*%%$",
				"important": true,
				"whenInstalled": ["ms-python.python"]
			}, {
				"pathGlob": "{**/*.ipynb}"
			}]
		},
		"ms-toolsai.datawrangler": {
			"onFileOpen": [{
				"pathGlob": "{**/*.ipynb}",
				"contentPattern": "import\\s*pandas|from\\s*pandas",
				"whenInstalled": ["ms-toolsai.jupyter"]
			}]
		},
		"golang.Go": {
			"onFileOpen": [{
				"pathGlob": "**/*.go",
				"important": true
			}, {
				"languages": ["go"],
				"important": true
			}]
		},
		"vscjava.vscode-java-pack": {
			"onFileOpen": [{
				"pathGlob": "{**/*.java}",
				"important": true,
				"whenNotInstalled": ["ASF.apache-netbeans-java", "Oracle.oracle-java"]
			}, {
				"languages": ["java"],
				"important": true,
				"whenNotInstalled": ["ASF.apache-netbeans-java", "Oracle.oracle-java"]
			}]
		},
		"ms-vscode.PowerShell": {
			"onFileOpen": [{
				"pathGlob": "{**/*.ps1,**/*.psd1,**/*.psm1}",
				"important": true
			}, {
				"languages": ["powershell"],
				"important": true
			}, {
				"pathGlob": "{**/*.ps.config,**/*.ps1.config}"
			}]
		},
		"ms-toolsai.prompty": {
			"onFileOpen": [{
				"pathGlob": "{**/*.prompty}",
				"important": false
			}]
		},
		"typespec.typespec-vscode": {
			"onFileOpen": [{
				"pathGlob": "{**/*.tsp,**/tspconfig.yaml}",
				"important": true
			}]
		},
		"ms-vscode.cpptools-extension-pack": {
			"onFileOpen": [{
				"pathGlob": "{**/*.c,**/*.cpp,**/*.cc,**/.cxx,**/*.hh,**/*.hpp,**/*.hxx,**/*.h}",
				"important": true,
				"whenNotInstalled": ["llvm-vs-code-extensions.vscode-clangd"]
			}, {
				"languages": ["c", "cpp"],
				"important": true,
				"whenNotInstalled": ["llvm-vs-code-extensions.vscode-clangd"]
			}]
		},
		"ms-azuretools.vscode-containers": {
			"onFileOpen": [{
				"pathGlob": "{**/dockerfile,**/Dockerfile,**/docker-compose.yml,**/docker-compose.*.yml}",
				"important": true,
				"whenNotInstalled": ["ms-azuretools.vscode-docker"]
			}, {
				"languages": ["dockerfile"],
				"important": true,
				"whenNotInstalled": ["ms-azuretools.vscode-docker"]
			}, {
				"pathGlob": "{**/*.cs,**/project.json,**/global.json,**/*.csproj,**/*.cshtml,**/*.sln,**/appsettings.json,**/*.py,**/*.ipynb,**/*.js,**/*.ts,**/package.json}",
				"whenNotInstalled": ["ms-azuretools.vscode-docker"]
			}]
		},
		"vue.volar": {
			"onFileOpen": [{
				"pathGlob": "{**/*.vue}",
				"important": true
			}, {
				"languages": ["vue"],
				"important": true
			}]
		},
		"ms-vscode.makefile-tools": {
			"onFileOpen": [{
				"pathGlob": "{**/makefile,**/Makefile}",
				"important": true
			}, {
				"languages": ["makefile"],
				"important": true
			}]
		},
		"ms-vscode.cmake-tools": {
			"onFileOpen": [{
				"pathGlob": "{**/CMakeLists.txt}",
				"important": true
			}]
		},
		"ms-azure-devops.azure-pipelines": {
			"onFileOpen": [{
				"pathGlob": "{**/azure-pipelines.yaml}",
				"important": true
			}]
		},
		"msazurermtools.azurerm-vscode-tools": {
			"onFileOpen": [{
				"pathGlob": "{**/azuredeploy.json}",
				"important": true
			}]
		},
		"ms-vscode-remote.remote-containers": {
			"onFileOpen": [{
				"pathGlob": "{**/devcontainer.json}",
				"important": true
			}]
		},
		"ms-azuretools.vscode-bicep": {
			"onFileOpen": [{
				"pathGlob": "{**/*.bicep}",
				"important": true,
				"whenNotInstalled": ["ms-azuretools.rad-vscode-bicep"]
			}]
		},
		"svelte.svelte-vscode": {
			"onFileOpen": [{
				"pathGlob": "{**/*.svelte}",
				"important": true
			}]
		},
		"ms-vscode.vscode-github-issue-notebooks": {
			"onFileOpen": [{
				"pathGlob": "{**/*.github-issues}",
				"important": true
			}]
		},
		"ms-playwright.playwright": {
			"onFileOpen": [{
				"pathGlob": "{**/*playwright*.config.ts,**/*playwright*.config.js,**/*playwright*.config.mjs}",
				"important": true
			}]
		},
		"vscjava.vscode-gradle": {
			"onFileOpen": [{
				"pathGlob": "{**/gradlew,**/gradlew.bat,**/build.gradle,**/build.gradle.kts,**/settings.gradle,**/settings.gradle.kts}",
				"important": true
			}]
		},
		"REditorSupport.r": {
			"onFileOpen": [{
				"pathGlob": "{**/*.r}",
				"important": true
			}, {
				"languages": ["r"],
				"important": true
			}]
		},
		"firefox-devtools.vscode-firefox-debug": {
			"onFileOpen": [{
				"pathGlob": "{**/*.ts,**/*.tsx,**/*.js,**/*.jsx,**/*.es6,**/.babelrc}"
			}]
		},
		"ms-edgedevtools.vscode-edge-devtools": {
			"onFileOpen": [{
				"pathGlob": "{**/*.ts,**/*.tsx,**/*.js,**/*.css,**/*.html}"
			}]
		},
		"Ionide.Ionide-fsharp": {
			"onFileOpen": [{
				"pathGlob": "{**/*.fsx,**/*.fsi,**/*.fs,**/*.ml,**/*.mli}"
			}]
		},
		"dbaeumer.vscode-eslint": {
			"onFileOpen": [{
				"pathGlob": "{**/*.js,**/*.jsx,**/*.es6,**/.eslintrc.*,**/.eslintrc,**/.babelrc,**/jsconfig.json}"
			}]
		},
		"bmewburn.vscode-intelephense-client": {
			"onFileOpen": [{
				"pathGlob": "{**/*.php,**/php.ini}"
			}]
		},
		"xdebug.php-debug": {
			"onFileOpen": [{
				"pathGlob": "{**/*.php,**/php.ini}"
			}]
		},
		"rust-lang.rust-analyzer": {
			"onFileOpen": [{
				"pathGlob": "{**/*.rs,**/*.rslib}"
			}]
		},
		"DavidAnson.vscode-markdownlint": {
			"onFileOpen": [{
				"pathGlob": "{**/*.md}"
			}]
		},
		"EditorConfig.EditorConfig": {
			"onFileOpen": [{
				"pathGlob": "{**/.editorconfig}"
			}]
		},
		"HookyQR.beautify": {
			"onFileOpen": [{
				"pathGlob": "{**/.jsbeautifyrc}"
			}]
		},
		"donjayamanne.githistory": {
			"onFileOpen": [{
				"pathGlob": "{**/.gitignore,**/.git}"
			}]
		},
		"eamodio.gitlens": {
			"onFileOpen": [{
				"pathGlob": "{**/.gitignore,**/.git}"
			}]
		},
		"Shopify.ruby-lsp": {
			"onFileOpen": [{
				"pathGlob": "{**/*.rb,**/*.erb,**/*.reek,**/.fasterer.yml,**/ruby-lint.yml,**/.rubocop.yml}"
			}]
		},
		"swiftlang.swift-vscode": {
			"onFileOpen": [{
				"pathGlob": "{**/*.swift,**/*.swiftinterface}",
				"important": true
			}]
		},
		"DotJoshJohnson.xml": {
			"onFileOpen": [{
				"pathGlob": "{**/*.xml}"
			}]
		},
		"stylelint.vscode-stylelint": {
			"onFileOpen": [{
				"pathGlob": "{**/.stylelintrc,**/stylelint.config.js}"
			}]
		},
		"ms-mssql.mssql": {
			"onFileOpen": [{
				"pathGlob": "{**/*.sql}"
			}]
		},
		"mtxr.sqltools": {
			"onFileOpen": [{
				"pathGlob": "{**/*.sql}"
			}]
		},
		"usqlextpublisher.usql-vscode-ext": {
			"onFileOpen": [{
				"pathGlob": "{**/*.usql}"
			}]
		},
		"ms-vscode.sublime-keybindings": {
			"onFileOpen": [{
				"pathGlob": "{**/.sublime-project,**/.sublime-workspace}"
			}]
		},
		"k--kato.intellij-idea-keybindings": {
			"onFileOpen": [{
				"pathGlob": "{**/.idea}"
			}]
		},
		"christian-kohler.npm-intellisense": {
			"onFileOpen": [{
				"pathGlob": "{**/package.json}"
			}]
		},
		"cake-build.cake-vscode": {
			"onFileOpen": [{
				"pathGlob": "{**/build.cake}"
			}]
		},
		"Angular.ng-template": {
			"onFileOpen": [{
				"pathGlob": "{**/.angular-cli.json,**/angular.json,**/*.ng.html,**/*.ng,**/*.ngml}"
			}]
		},
		"vscjava.vscode-maven": {
			"onFileOpen": [{
				"pathGlob": "**/pom.xml"
			}]
		},
		"ms-azuretools.vscode-azureterraform": {
			"onFileOpen": [{
				"pathGlob": "**/*.tf"
			}]
		},
		"HashiCorp.terraform": {
			"onFileOpen": [{
				"pathGlob": "**/*.tf"
			}]
		},
		"vsciot-vscode.vscode-arduino": {
			"onFileOpen": [{
				"pathGlob": "**/*.ino"
			}]
		},
		"ms-kubernetes-tools.vscode-kubernetes-tools": {
			"onFileOpen": [{
				"pathGlob": "{**/Chart.yaml}"
			}]
		},
		"Oracle.oracledevtools": {
			"onFileOpen": [{
				"pathGlob": "{**/*.sql}"
			}]
		},
		"betterthantomorrow.calva": {
			"onFileOpen": [{
				"pathGlob": "{**/*.clj,**/*.cljs}"
			}]
		},
		"vmware.vscode-boot-dev-pack": {
			"onFileOpen": [{
				"pathGlob": "{**/application.properties}"
			}]
		},
		"GitHub.copilot": {
			"onFileOpen": [{
				"pathGlob": "{**/*.ts,**/*.tsx,**/*.js,**/*.jsx,**/*.py,**/*.go,**/*.rb,**/*.html,**/*.css,**/*.php,**/*.cpp,**/*.vue,**/*.c,**/*.sql,**/*.java,**/*.cs,**/*.rs,**/*.dart,**/*.ps,**/*.ps1,**/*.tex}"
			}],
			"onSettingsEditorOpen": {
				"descriptionOverride": "GitHub Copilot is an AI pair programmer tool that helps you write code faster and smarter."
			}
		},
		"GitHub.vscode-github-actions": {
			"onFileOpen": [{
				"pathGlob": "{**/.github/workflows/*.yml}",
				"important": true
			}]
		},
		"circleci.circleci": {
			"onFileOpen": [{
				"pathGlob": "{**/.circleci/config.yml}"
			}]
		},
		"Redis.redis-for-vscode": {
			"onFileOpen": [{
				"pathGlob": "{**/redis.*,**/redis-server.*,**/redis_*,**/redisinsight.*}",
				"important": true
			}]
		},
		"SonarSource.sonarlint-vscode": {
			"onFileOpen": [{
				"pathGlob": "{**/sonar-project.properties,**/sonarcloud.properties,**/sonarlint.*}",
				"important": true
			}]
		}
	},
	"keymapExtensionTips": ["vscodevim.vim", "ms-vscode.sublime-keybindings", "ms-vscode.atom-keybindings", "ms-vscode.brackets-keybindings", "ms-vscode.vs-keybindings", "ms-vscode.notepadplusplus-keybindings", "k--kato.intellij-idea-keybindings", "lfs.vscode-emacs-friendly", "alphabotsec.vscode-eclipse-keybindings", "alefragnani.delphi-keybindings"],
	"languageExtensionTips": ["ms-python.python", "ms-vscode.cpptools-extension-pack", "ms-dotnettools.csdevkit", "ms-toolsai.jupyter", "vscjava.vscode-java-pack", "ecmel.vscode-html-css", "vue.volar", "bmewburn.vscode-intelephense-client", "dsznajder.es7-react-js-snippets", "golang.go", "ms-vscode.powershell", "dart-code.dart-code", "rust-lang.rust-analyzer", "Shopify.ruby-lsp", "GitHub.copilot"],
	"configBasedExtensionTips": {
		"git": {
			"configPath": ".git/config",
			"configName": "Git",
			"recommendations": {
				"github.vscode-pull-request-github": {
					"name": "GitHub Pull Request",
					"contentPattern": "^\\s*url\\s*=\\s*https:\\/\\/github\\.com.*$"
				},
				"eamodio.gitlens": {
					"name": "GitLens"
				}
			}
		},
		"devContainer": {
			"configPath": ".devcontainer/devcontainer.json",
			"configName": "Dev Container",
			"recommendations": {
				"ms-vscode-remote.remote-containers": {
					"name": "Dev Containers",
					"important": true
				}
			}
		},
		"maven": {
			"configPath": "pom.xml",
			"configName": "Maven",
			"recommendations": {
				"vscjava.vscode-java-pack": {
					"name": "Java",
					"important": true,
					"isExtensionPack": true,
					"whenNotInstalled": ["ASF.apache-netbeans-java", "Oracle.oracle-java"]
				},
				"vmware.vscode-boot-dev-pack": {
					"name": "Spring Boot Extension Pack",
					"isExtensionPack": true
				}
			}
		},
		"gradle": {
			"configPath": "build.gradle",
			"configName": "Gradle",
			"recommendations": {
				"vscjava.vscode-java-pack": {
					"name": "Java",
					"important": true,
					"isExtensionPack": true,
					"whenNotInstalled": ["ASF.apache-netbeans-java", "Oracle.oracle-java"]
				}
			}
		},
		"github-pull-request": {
			"configPath": ".vscode/.github-pull-request.rec",
			"configName": "GitHub",
			"configScheme": "vscode-vfs",
			"recommendations": {
				"github.vscode-pull-request-github": {
					"name": "GitHub Pull Request",
					"important": true
				}
			}
		},
		"pyproject-formatter": {
			"configPath": "pyproject.toml",
			"configName": "Python Formatter",
			"recommendations": {
				"ms-python.black-formatter": {
					"name": "Black Formatter",
					"contentPattern": "(^\\s*\\[\\[?\\s*\"?tool\"?\\s*\\.\\s*\"?black\"?\\s*[\\].])|(\"black\\s*[\"[(<=>!~;@])"
				},
				"ms-python.autopep8": {
					"name": "Autopep8",
					"contentPattern": "(^\\s*\\[\\[?\\s*\"?tool\"?\\s*\\.\\s*\"?autopep8\"?\\s*[\\].])|(\"autopep8\\s*[\"[(<=>!~;@])"
				}
			}
		},
		"pep8-formatter": {
			"configPath": ".pep8",
			"configName": "Python Formatter",
			"recommendations": {
				"ms-python.autopep8": {
					"name": "Autopep8"
				}
			}
		},
		"python-setup-cgf-formatter": {
			"configPath": "setup.cfg",
			"configName": "Python Formatter",
			"recommendations": {
				"ms-python.autopep8": {
					"name": "Autopep8",
					"contentPattern": "^\\[pep8\\]"
				}
			}
		},
		"tox-ini-formatter": {
			"configPath": "tox.ini",
			"configName": "Python Formatter",
			"recommendations": {
				"ms-python.autopep8": {
					"name": "Autopep8",
					"contentPattern": "^\\[pep8\\]"
				}
			}
		},
		"pyproject-linter": {
			"configPath": "pyproject.toml",
			"configName": "Python Linter",
			"recommendations": {
				"ms-python.pylint": {
					"name": "Pylint",
					"contentPattern": "(^\\s*\\[\\[?\\s*\"?tool\"?\\s*\\.\\s*\"?pylint\"?\\s*[\\].])|(\"pylint\\s*[\"[(<=>!~;@])"
				},
				"charliermarsh.ruff": {
					"name": "Ruff",
					"contentPattern": "(^\\s*\\[\\[?\\s*\"?tool\"?\\s*\\.\\s*\"?ruff\"?\\s*[\\].])|(\"ruff\\s*[\"[(<=>!~;@])"
				},
				"ms-python.mypy-type-checker": {
					"name": "Mypy Type Checker",
					"contentPattern": "(^\\s*\\[\\[?\\s*\"?tool\"?\\s*\\.\\s*\"?mypy\"?\\s*[\\].])|(\"mypy\\s*[\"[(<=>!~;@])"
				},
				"ms-python.flake8": {
					"name": "Flake8",
					"contentPattern": "(^\\s*\\[\\[?\\s*\"?tool\"?\\s*\\.\\s*\"?flake8\"?\\s*[\\].])|(\"flake8\\s*[\"[(<=>!~;@])"
				}
			}
		},
		".pylintrc-linter": {
			"configPath": ".pylintrc",
			"configName": "Python Linter",
			"recommendations": {
				"ms-python.pylint": {
					"name": "Pylint"
				}
			}
		},
		"pylintrc-linter": {
			"configPath": "pylintrc",
			"configName": "Python Linter",
			"recommendations": {
				"ms-python.pylint": {
					"name": "Pylint"
				}
			}
		},
		"mypy-ini-linter": {
			"configPath": ".mypy.ini",
			"configName": "Python Linter",
			"recommendations": {
				"ms-python.mypy-type-checker": {
					"name": "Mypy Type Checker"
				}
			}
		},
		"tox-ini-linter": {
			"configPath": "tox.ini",
			"configName": "Python Linter",
			"recommendations": {
				"ms-python.flake8": {
					"name": "Flake8",
					"contentPattern": "^\\[flake8\\]"
				}
			}
		},
		".flake8-linter": {
			"configPath": ".flake8",
			"configName": "Python Linter",
			"recommendations": {
				"ms-python.flake8": {
					"name": "Flake8"
				}
			}
		},
		"python-setup-cgf-linter": {
			"configPath": "setup.cfg",
			"configName": "Python Linter",
			"recommendations": {
				"ms-python.flake8": {
					"name": "Flake8",
					"contentPattern": "^\\[flake8\\]"
				}
			}
		}
	},
	"exeBasedExtensionTips": {
		"az": {
			"friendlyName": "Azure CLI",
			"windowsPath": "%ProgramFiles(x86)%\\Microsoft SDKs\\Azure\\CLI2\\wbin\\az.cmd",
			"recommendations": {
				"ms-vscode.vscode-node-azure-pack": {
					"name": "Azure Tools"
				},
				"ms-azuretools.vscode-azure-github-copilot": {
					"name": "GitHub Copilot for Azure"
				}
			}
		},
		"azd": {
			"friendlyName": "Azure Dev CLI",
			"windowsPath": "%USERPROFILE%\\AppData\\Local\\Programs\\Azure Dev CLI\\azd.exe",
			"recommendations": {
				"ms-vscode.vscode-node-azure-pack": {
					"name": "Azure Tools"
				},
				"ms-azuretools.vscode-azure-github-copilot": {
					"name": "GitHub Copilot for Azure"
				}
			}
		},
		"azd-user": {
			"friendlyName": "Azure Dev CLI",
			"windowsPath": "%ProgramFiles%\\Azure Dev CLI\\azd.exe",
			"recommendations": {
				"ms-vscode.vscode-node-azure-pack": {
					"name": "Azure Tools"
				},
				"ms-azuretools.vscode-azure-github-copilot": {
					"name": "GitHub Copilot for Azure"
				}
			}
		},
		"azure-powershell": {
			"friendlyName": "Azure P
