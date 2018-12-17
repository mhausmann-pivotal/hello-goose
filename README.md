# Hello Goose

A really simple demo application in a number of languages for Pivotal Application Service / Cloud Foundry.

*Hello Goose aims to provide a simple example application and manifest for every core buildpack so that you can see the differences between buildpack implementations and the languages used. We still need contributions for some buildpacks!*

Pick your language of choice and follow the instructions in the README within that directory.

The application will provide a photo of a goose running in 3 container instances. It will also display the instance ID that served your request so that you can see the load balancing working and the container lifecycle when you work with the application.

The cropped goose image has been donated into the public domain by the photographer.

![Alt](php/images/goose.jpg "Goose")

 * [Binary](binary/): An example using the binary buildpack.
 * [DotNetCore](dotnetcore/): A Razor Pages based implementation using Microsoft .Net Core.
 * [JSP](jsp/): A simple and arguably retro Java example using Java Servlet Pages.
 * [Spring Boot](spring-boot/): A simple Spring Boot implementation.
 * [PHP](php/): Probaby the simplest implementation of all.
 * [Go](go/): Minimal go version with no external dependencies.
 * [Python](python/): Quick and simple using Flask and a Jinja2 template with the option to vendor dependencies.

N.B. We love pull requests and new language versions. The main rule is that all languages must produce exactly the same html and image output.
