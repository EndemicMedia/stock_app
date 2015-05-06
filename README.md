# stock_app
Ruby+Angular stock footage purchasing and licensing app

user story\n
-browse video thumbnails
-search for:  content[tags]
              type[aerial,land,underwater,space]
              movement[fixed,pan,tilt,sideways,forward,backward,complex]
              speed[normal,timelapse,slowmo]
              length[short,long]
              location[city,country,gps]
              atributes[fps,camera,dimension,size]
-browse video thumbails
-add clip to shotlist
-watch shotlist in sequence (custom sort shotlist)
-review shotlist (remove from shotlist)
-set licensing terms
-pay
-download


modules
-server fs rw <=> json
-local storage <=> json
-json search
-video player with shotlist
-license handler (generate, email, cost)
-paypal integration
-bitcoin integration
