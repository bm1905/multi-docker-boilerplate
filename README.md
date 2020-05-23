Dockerizing a full-stack app (React, Express, Postgres, Redis, Nginx)

## Main startup commands

In the project directory, you can run:

## Additional useful commands
<br />
Build docker file.

### `docker build -f Dockerfile.dev .`


## Setup Walkthrough
<ul> Creating docker development files:
    <li>Creating a Dockerfile.dev in client folder.</li>
    <li>Inside cient folder, build docker file with: `docker build -f Dockerfile.dev .`</li>
    <li>Test the image with: `docker run < image-id >`</li>
    <li>Creating a Dockerfile.dev in server folder.</li>
    <li>Creating a Dockerfile.dev in nginx folder.</li>
</ul>

<ul> Creating docker compose files:
    <li>Create docker-compose.yml file in root directory.</li>
    <li>Test with `docker-compose up --build`.</li>
</ul>


