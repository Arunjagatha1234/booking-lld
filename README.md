## Booking.com Back-End Developer Challenge (Java)

The question requires Java Development Kit 8

- Install OpenJDK 8 on MacOS or Linux

- Install JDK 8 on Windows

Before you start, you should be a bit familiar with:

1. Maven

1. Spring Boot 2

1. JUnit 5 syntax and, optionally, Hamcrest


You’re given a pre-configured Spring Boot project, with the following capabilities already implemented:

A /hotel GET endpoint, listing all the hotels in our system.

An H2 in-memory data source containing all our hotel inventory.

A basic service implementation layer to retrieve information from the hotel and city inventory.

Example implementations of functional tests (testing a bit of logic) and integration tests (testing an HTTP endpoint in your API).


## Implement an endpoint that fetches hotel by ID

> GET /hotel/{id}

## Implement an endpoint that soft deletes a hotel by ID

> DELETE /hotel/{id}

## Implement search functionality to find closest 3 hotels

> GET /search/{cityId}?sortBy=distance

    Note: Distance is supposed to be calculated by Haversine formula.

new readme file