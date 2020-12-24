# rsync

  apt-get install rsync -y
  
  rsync -hrtplu --progress --stats /home/movies/ root@192.168.2.95:/home/movies
  
  rsync -hrtplu --progress --stats -e "ssh -p 222" /home/movies/ root@192.168.2.95:/home/movies
  
  rsync -hrtplu --progress --stats -e "ssh -p 22" /home/user/ssd/ user@10.x.x.x:/home/user/ssd
  
  rsync -hrtplu --omit-dir-times --delete --progress --stats -e "ssh -p 22" /home/user/ssd/ user@x.x.x.x:/home/user/ssd
