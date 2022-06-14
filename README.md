

#set git user name

	`git config --global user.name "AndreKravitz"`


git config --global user.email "tumiandrekravitz@gmail.com"


git config --global color.ui true


git config --global core.editor emacs


   
sudo systemctl stop apache2

CHANGE USER
sudo chown -R $USER: .

CLONE GIT / LEVANTAR EN LOCAL
ddev start
ddev composer install
ddev import-db --src=db.andre.sql.gz


composer create-project drupal/recommended-project andred9 --ignore-platform-reqs
create new drupal project
composer create-project drupal/recommended-project andrekravitz.com --ignore-platform-reqs
  262  ll
  263  nano commands.txt
  264  cd andrekravitz.com/
  265  ll
  266  ddev config
  267  ddev start
