# fair_management
Holding place for standard maintenance routines operated through Ruby scripts.


# Setting up 'wp' command line tool

    curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar
    php wp-cli.phar --info
    chmod +x wp-cli.phar
    sudo mv wp-cli.phar /usr/local/bin/wp


# Setting up PHP

    sudo apt-get update
    sudo apt-get install php-curl php-gd php-mbstring php-mcrypt php-xml php-xmlrpc php libapache2-mod-php php-mysql
    sudo apache2 reload
