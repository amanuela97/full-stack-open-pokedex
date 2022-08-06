# 11.1 CI/CD

For development with Java, Checkstyle is a linting tool that helps programmers write Java code that adheres to a coding standard.
It does so by helping to enforce coding standards. If a specific code violates the coding standard for a project, then Checkstyle will show an error message.

To cover the testing side of the development process, a library such as Junit can be utilized. Junit is mainly intended for unit testing, and it enables developers to execute test-driven development. Lastly, Apache Ant is a java based build tool that allows developers to compile, assemble, test, and run Java applications.

To set up continuous integration with java, a tool such as CircleCI can be used. CircleCI is a cloud-based platform that is easily configurable which makes it suitable for most use cases. Especially, for small scaled projects. This approach can even help reduce costs if the project does not require many resources, and there is no need for investing in hardware. Additional benefits of a cloud-hosted environment include minimal configuration and scalability.

If the application calls for unique resource requirements then a self-hosted CI tool like TeamCity can be used instead. Some benefits of the latter approach could be more flexibility, cost-effectiveness, and increased control over the computing environment.
