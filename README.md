# Europeana API Gateway

Gateway for Europeana APIs using NGINX on Kubernetes

## Usage

### Cloud Foundry
(TBD)
1. Copy cloud-foundry/manifest.example.yml to manifest.yml
2. Set all environment variable values in manifest.yml
3. Deploy to Cloud Foundry: `cf push api-gateway -f manifest.yml`

### Docker
(TBD)
1. Copy docker/.env.docker.example to .env.docker
2. Run with Docker Compose: `docker-compose up`
3. The API Gateway will be available at http://localhost:8080/

## TODO

* Add a test suite

## License

Licensed under the EUPL V.1.1.

For full details, see [LICENSE.md](LICENSE.md).
