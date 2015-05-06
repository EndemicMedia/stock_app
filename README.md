# stock_app
Ruby+Angular stock footage purchasing and licensing app

user story
1.browse video thumbnails
2.search for:  content[tags]
              *type[aerial,land,underwater,space]
              *movement[fixed,pan,tilt,sideways,forward,backward,complex]
              *speed[normal,timelapse,slowmo]
              *length[short,long]
              *location[city,country,gps]
              *atributes[fps,camera,dimension,size]
3.browse video thumbails
4.add clip to shotlist
5.watch shotlist in sequence (custom sort shotlist)
6.review shotlist (remove from shotlist)
7.set licensing terms
8.pay
9.download


modules
*server fs rw <=> json
*local storage <=> json
*json search
*video player with shotlist
*license handler (generate, email, cost)
*paypal integration
*bitcoin integration
