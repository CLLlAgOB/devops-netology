# devops-netology

### Какие файлы или директории будут игнорироваться  благодаря файлу /terraform/.gitignore все исключения касаются директории /terraform/ и ее содержимому
`**/.terraform/*` все директории и поддиректории содержащие папку .terrafom  
`*.tfstate`&nbsp;все файлы с окончанием .tfstate  
`*.tfstate.*` все файлы в которых в имени есть .tfstate.  
`crash.log` исключаем конкретный файл  
`crash.*.log` исключаем все файлы начинающиеся с crash. и заканчивающиеся на .log  
`*.tfvars` исключаем все файлы с окончанием на .tfvars  
`*.tfvars.json` исключаем все файлы с окончанием на .tfvars.json  
`override.tf` конкретный файл  
`override.tf.json` конкретный файл  
`*_override.tf` файлы заканчивающиеся на _override.tf  
`*_override.tf.json`  файлы заканчивающиеся на _override.tf.json  
`.terraformrc` конкретный файл  
`terraform.rc`  конкретный файл  
  
  новая строка  
  IDE PyCharm Commit 1  
  IDE PyCharm Commit 2  