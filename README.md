# flask_face_recognition

Demo: https://flask-face-recognition-thuan.herokuapp.com/

heroku login
heroku create flask-face-recognition-thuan
heroku git:remote -a flask-face-recognition-thuan
heroku buildpacks:add --index 1 https://github.com/heroku/heroku-buildpack-apt
git push heroku HEAD:master