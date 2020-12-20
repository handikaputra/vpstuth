#curl https://cli-assets.heroku.com/install.sh | sh
#unzip 'heroku novnc full.zip'
#cd docker-novnc-master
#nano docker-compose.yml  //ubah port dari 8080 jadi 80 lalu CTRL+X > Y > ENTER
#heroku login -i
#heroku container:login
#heroku create fakvps
#heroku container:push web --app fakvps
#heroku container:release web --app fakvps
#heroku open --app fakvps
