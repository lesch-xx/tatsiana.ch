[![This project is using Percy.io for visual regression testing.](https://percy.io/static/images/percy-badge.svg)](https://percy.io/3e4901a1/tatsiana.ch)

# tatsiana.ch
*Tatsiana Siliuk hairstylist web site*

##### Prerequisites
Instal [Jekyll](https://jekyllrb.com/) locally.

##### Run in development mode
1. Open terminal
2. Change directory to a project: `cd ~/Projects/tatsiana.ch/`
3. Run web site: `bundle exec jekyll serve --incremental`
4. Go to http://localhost:4000/

##### Additional commands
- to terminate web server: `press ctrl-c to stop`
- to build web site: `bundle exec jekyll build`

##### Visual testing
1. Open terminal
2. Change directory to a project: `cd ~/Projects/tatsiana.ch/`
3. Build web site: `bundle exec jekyll serve --incremental`
4. Export token: `export PERCY_TOKEN=1234567890`
5. Run regression testing: `npm run test`
