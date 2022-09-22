# Ignore

Collection of **.gitignore** files for Go / JavaScript / TypeScript projects typical use cases

| Folder | Description |
| --- | --- |
| /all | Compile all snippets into a single .gitignore file |
| /common | Must have. Helps to avoid accidental commit of various system files |
| /dev_env | Another must have for dev environment. Exclude IDE folders, .env config ini/json & docker compose with exception to example files |
| /golang | Common exclusion list for Go projects. Replace "my_go_project_executable_binary" with your Go project output |
| /js_ts | Common exclusion list for JavaScript / TypeScript projects. Finetune as necessary |
| /local_db | Exclude local database files if it happens to be in local project directory |
| /ssh | Exclude ssh folder, pem & key files. Preventive |
| /ziptarjar | Exclude large zip/rar/tar/jar, installers & disk image files |

Pluck, add & omit as necessary
