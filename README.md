# devops-netology
`first line`
`Будут проигнорированы следующие файлы и директории`

    1. все файлы в директориях /.terraform во всех каталогах.
    2. игнорирует файлы с расширением .tfstate и файлы с любым окончанием наподобиe .tfstate.backup
    3. игнорирует файл crash.log и все файлы начинающиеся на crash. и заканчивающиеся на .log 
    4. игнорирует файлы с расширением .tfvars и .tfvars.json а так же override.tf и override.tf.json так же 
    заканчивающиеся на _override.tf или _override.tf.json
    5. игнорирует файлы конфигурации командной строки .terraformrc и terraform.rc