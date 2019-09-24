This is a working example based on various sources to have superset running behind a base url using nginx.

It is a common requirement to have superset running under a base url, (https://mydomain.at/analytics/ instead of https://mydomain.at/).
There had been multiple issues and discussions around it ([1](https://github.com/apache/incubator-superset/issues/3690) [2](https://stackoverflow.com/questions/50880431/how-to-get-apache-superset-to-run-on-a-specified-path) [3](https://github.com/apache/incubator-superset/issues/985) [4](https://github.com/apache/incubator-superset/pull/1866)).
Still it was not crystal clear how to put all elements together. To save some time for others, we compiled a working example in this repository. 

## Resources
  * https://github.com/apache/incubator-superset/pull/1866#issuecomment-347310860
  * https://github.com/amancevice/docker-superset/blob/master/examples/postgres/docker-compose.yml
  * https://testdriven.io/blog/dockerizing-django-with-postgres-gunicorn-and-nginx/
  
## How to run

 * docker-compose up -d --build
 * docker-compose down -v
