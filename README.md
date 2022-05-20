# consumer-add-geo-obj

export FLASK_APP=main
export FLASK_ENV=development

flask run

docker build -t rg.fr-par.scw.cloud/arsolute/python-template app/

docker push -t rg.fr-par.scw.cloud/arsolute/python-template