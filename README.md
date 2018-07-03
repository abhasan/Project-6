Introduction:
    1. this is the Udacity "Linux Configuration" project main folder

Configuration steps:

  1. AWS instance is configures with IP address "54.149.129.11"
  2. A user with username "grader" has been added, private key has
     been shared in the project submission.
  3. "grader" has been given a "sudo" access
  4. Apache server has been installed and configured with "Item catalog" Project.
      when public IP address of the AWS server "54.149.129.11" is typed on the
      web browser, it takes you to the main page of the project.
  5. postgresql has been installed and a user has been added with limited access

  6. git readme file: "https://github.com/abhasan/Project-6/blob/master/README.md"

  7. Upgraded packages: all the packages have been upgraded to the latest version
      bitnami@ip-172-26-7-84:/var/www/html$ sudo apt-get upgrade
      Reading package lists... Done
      Building dependency tree
      Reading state information... Done
      Calculating upgrade... Done
      The following packages were automatically installed and are no longer required:
        libcgi-fast-perl libcgi-pm-perl libencode-locale-perl libevent-core-2.0-5 libfcgi-perl libhtml-parser-perl
        libhtml-tagset-perl libhtml-template-perl libhttp-date-perl libhttp-message-perl libio-html-perl
        liblwp-mediatypes-perl libtimedate-perl liburi-perl mysql-server-core-5.7
      Use 'sudo apt autoremove' to remove them.
      The following packages have been kept back:
        linux-aws linux-headers-aws linux-image-aws
      0 upgraded, 0 newly installed, 0 to remove and 3 not upgraded.

  8. Firewall has been reconfigured and all the ports have been blocked except
      web, ssh and NTP ports.

  9. List of all the thrid party software installed: 
    blinker==1.3
    cachetools==2.1.0
    certifi==2018.4.16
    chardet==3.0.4
    click==6.7
    cryptography==1.2.3
    enum34==1.1.2
    Flask==1.0.2
    Flask-SeaSurf==0.2.2
    Flask-SQLAlchemy==2.3.2
    google-api-python-client==1.7.3
    google-auth==1.5.0
    google-auth-httplib2==0.0.3
    httplib2==0.11.3
    idna==2.7
    ipaddress==1.0.16
    itsdangerous==0.24
    Jinja==1.2
    Jinja2==2.10
    MarkupSafe==1.0
    MySQL-python==1.2.5
    mysqlclient==1.3.7
    oauth2client==4.1.2
    pipenv==2018.7.1
    psycopg2==2.6.1
    pyasn1==0.4.3
    pyasn1-modules==0.2.2
    pyinotify==0.9.6
    pyOpenSSL==0.15.1
    python-oauth2==1.1.0
    requests==2.19.1
    rsa==3.4.2
    six==1.11.0
    SQLAlchemy==1.2.9
    uritemplate==3.0.0
    urllib3==1.23
    virtualenv==15.0.1
    virtualenv-clone==0.3.0
    Werkzeug==0.14.1

