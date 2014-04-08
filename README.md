# Civicbot

Civicbot es un primo latino de Hubot de GitHub que trabaja con Codeando México.


## hubot-scripts

Siempre será interesante darle nuevos poderes a civicbot.

Para agregar nuevos scripts de funcionalidad a civicbot, agrega el
nombre del script con su extensión como un string al archivo `hubot-scripts.json`
en este repo.

[hubot-scripts]: https://github.com/github/hubot-scripts

## Deployment

    % heroku create --stack cedar
    % git push heroku master
    % heroku ps:scale app=1

Ahora agregamos Redis en Heroku:

    % heroku addons:add redistogo:nano


Para más detalles está la wiki page:
[deploying hubot onto Heroku][deploy-heroku].

[deploy-heroku]: https://github.com/github/hubot/blob/master/docs/deploying/heroku.md
