Exercise 11.1

Python application

With Python, there are several options for linting. You can incorporate Flake8, Pylint or Black into CI setup to check the code for errors. Pytest is a common choice for testing. Usually there is no need to build tools in pure Python project. It is different from React app, where you need to build a javascript file. 
In addition to Github actions, there are several cloud-based CI tools. Azure pipelines is a solution provided by Windows and AWS CodePipeline by Amazon. Gitlab and CircleCI are also popular choices for CI setup. Both are easy to use and highly scalable. Alternatives to Jenkins include TeamCity and Bamboo. Both are self-hosted setups. TeamCity is easier to configure and use than Jenkins but unlike Jenkins, it is not free on the enterprise level. Like TeamCity, Atlassian Bamboo is not open source. 
When choosing the CI tool for the project, there are several factors to consider. These include scalability, cost and support. For a small project with six developers some cloud-based solution would probably be the best choice. Most cloud-based CI tools are easier to configure and use than self-hosted setups. Github Actions and Gitlab also offer free versions. However, in premium versions Github Actions bills by minutes and Gitlab by users. 
