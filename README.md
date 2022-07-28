# Brand new Drupal 9 project (with composer)
	composer create-project drupal/recommended-project my_site_name_dir
# Install Drush 
	ddev composer require drush/drush
# set git user name
    git config --global user.name "AndreKravitz"

	git config --global user.email "tumiandrekravitz@gmail.com"

	git config --global color.ui true

	git config --global core.editor emacs

	sudo systemctl stop apache2 
# CHANGE USER
	sudo chown -R $USER: .
# create new drupal project
	composer create-project drupal/recommended-project andrekravitz.com --ignore-platform-reqs
	nano commands.txt
	ddev config
	ddev start
