10050  cd newspace
10051  ls
10052  rails new portfolio
10053  ls
10054  cd portfolio
10055  git init
10056  git commit -m "initial commit"
10059  git remote add origin https://github.com/shenzhoudance/adminblog.git
10060  git push -u origin master


10063  git remote -v
10064  git remote remove origin https://github.com/shenzhoudance/adminblog.git

10065  git remote remove origin
10066  git remote -v

10067  git remote add origin https://github.com/shenzhoudance/lastblog.git
10068  git push -u origin master

10069  atom .
10070  rails g controller posts
10071  rails s
10072  rails g model Post title:string body:text
10073  rake db:migrate
10074  bundle install

10075  rails g devise:install
10076  rails g devise:views
10077  rails g devise U
10078  rails d devise U
10079  rails g devise User
10080  rails s
10081  rake db:migrate

10082  rails s
10083  bundle install

10084  rails g active_admin:install
10085  rake db:migrate
10086  rake db:seed
10087  rails server
10088  chear
10089  rails g active_admin:resource User
10090  rails g active_admin:resource Post
10091  rails s
10092  git add .
10093  git commit -m "added active admin"

10094  bundle install
10095  rails s
10096  git add .
10097  git commit -m "added active skin theme"

10098  rails s
10099  bundle install
10100  rails g paperclip post image
10101  rake db:migrate
10102  rails s
10103  git add .
10104  git commit -m "added image upload with paperclip"

10105  rails s
10106  git commit -m "added custom posts to pages"
10107  git add .
10108  git commit -m "added custom posts to pages"
10109  rails s
