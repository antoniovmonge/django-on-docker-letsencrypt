# Securing a Containerized Django Application with Let's Encrypt

## Want to learn how to build this?

Check out the [post](https://testdriven.io/blog/django-lets-encrypt/).

## Want to use this project?

### Let's Encrypt Staging

1. Rename *.env_staging-sample* to *.env_staging*, *.env_staging.db-sample* to *.env_staging.db*, and *.env_staging.proxy-companion-sample* to *.env_staging.proxy-companion*. Update the environment variables.
1. Build the images and run the containers:

    ```sh
    $ docker-compose -f docker-compose.staging.yml up -d --build
    ```

    Test it out.

### Let's Encrypt Production

1. Rename *.env_prod-sample* to *.env_prod*, *.env_prod_db-sample* to *.env_prod_db*, and *.env_prod.proxy-companion-sample* to *.env_prod.proxy-companion*. Update the environment variables.
1. Build the images and run the containers:

    ```sh
    $ docker-compose -f docker-compose.prod.yml up -d --build
    ```

    Test it out.
