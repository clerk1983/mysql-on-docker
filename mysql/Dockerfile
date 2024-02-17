#使うDockerイメージ
FROM mysql:8

# RUN apt-get update && apt-get install -y \
#   less \
#   procps \
#   && apt-get clean \
#   && rm -fr /var/lib/apt/lists/*

# ENV LESSCHARSET=utf-8

  #ポートを開ける
EXPOSE 3306

#MySQL設定ファイルをイメージ内にコピー
ADD ./my.cnf /etc/mysql/conf.d/my.cnf

#docker runに実行される
CMD ["mysqld"]
