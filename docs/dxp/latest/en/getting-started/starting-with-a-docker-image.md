# Starting with a Docker Image

The latest versions of Liferay are available as Docker images. Follow these steps to download, launch, and begin touring the latest releases of Liferay.

```{important}
Don't have Docker? Go here first: [Linux](https://docs.docker.com/install/linux/docker-ce/ubuntu/) | [Windows](https://docs.docker.com/docker-for-windows/install/) | [OSX](https://docs.docker.com/docker-for-mac/install/)
```

## Get Started with Liferay Portal

Liferay Portal is the open source and community supported platform for building compelling and flexible web experiences.

1. Get the Docker image.

    ```bash
    docker pull [$LIFERAY_LEARN_PORTAL_DOCKER_IMAGE$]
    ```

1. Start the Docker image.

    ```bash
    docker run -it -m 8g -p 8080:8080 [$LIFERAY_LEARN_PORTAL_DOCKER_IMAGE$]
    ```

    ```{tip}
    Wait until you see `org.apache.catalina.startup.Catalina.start Server startup in [x] milliseconds` to indicate startup completion.
    ```

1. Open your browser to `https://localhost:8080`.

    ![The Liferay Portal initial landing page.](./starting-with-a-docker-image/images/01.png)

## Get Started With Liferay DXP

Liferay DXP is the commercially supported and enterprise ready platform used around the world, built on the foundation of Liferay Portal. Starting with the Docker image is simple and includes a trial license.

1. Get the Docker image.

    ```bash
    docker pull [$LIFERAY_LEARN_PORTAL_DOCKER_IMAGE$]
    ```

1. Start the Docker image.

    ```bash
    docker run -it -m 8g -p 8080:8080 [$LIFERAY_LEARN_PORTAL_DOCKER_IMAGE$]
    ```

1. Open your browser to `https://localhost:8080`.

## What's Next

Continue our Getting Started walkthrough and learn about logging in for the first time using [the Admin account](./introduction-to-the-admin-account.md).

Doing more than just checking things out? See the [Installing a Liferay-Tomcat Bundle](../installation-and-upgrades/installing-liferay/installing-a-liferay-tomcat-bundle.md) to learn more.

Learn more about [using Docker images](../installation-and-upgrades/installing-liferay/using-liferay-docker-images/docker-container-basics.md).
