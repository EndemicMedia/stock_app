[stock_app]
==================================================
PHP+Angular stock footage purchasing and licensing app

User Story
--------------------------------------

In the spirit of open source software development, jQuery always encourages community code contribution. To help you get started and before you jump into writing code, be sure to read these important contribution guidelines thoroughly:

1. browse video thumbnails
2. search for:  

  - content[tags]
  - type[aerial,land,underwater,space]
  - movement[fixed,pan,tilt,sideways,forward,backward,complex]
  - speed[normal,timelapse,slowmo]
  - length[short,long]
  - location[city,country,gps]
  - atributes[fps,camera,dimension,size]

3. browse video thumbails
4. add clip to shotlist
5. watch shotlist in sequence (custom sort shotlist)
6. review shotlist (remove from shotlist)
7. set licensing terms
8. pay
9. download

Modules
--------------------------------------

- [X] server fs rw <=> json
- [ ] local storage <=> json
- [ ] json search
- [X] video player with shotlist
- [X] license handler (generate, cost)
- [ ] Receive payment, generate download file, email contract
- [X] paypal integration
- [ ] bitcoin integration
