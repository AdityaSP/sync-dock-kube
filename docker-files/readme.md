/c/Users/Dell lap/aug14> ls -R .
.:
al_apache2  app

./al_apache2:
Dockerfile

./app:
Dockerfile  mypage.html
/c/Users/Dell lap/aug14>

/c/Users/Dell lap/aug14> docker image build -t adityaprabhakara/al_apache2:latest -t adityaprabhakara/al_apache2:3.1  al_apache2

/c/Users/Dell lap/aug14> docker image build -t adityaprabhakara/app:latest -t adityaprabhakara/app:2.1  app
