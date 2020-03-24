
These resources are provided to assist you with the completion of this course.  Continue with sections below on each resource for more details.

> > You may need to change the plural words above to singular.


This course will guide you through a process that manipulates an existing project.  It is expected and assumed that you follow along with the instructions in the course.  Those steps will result in the addition, modification, or deletion of files and their content.  A download of the initial project is provided for you at the link below.  It should be downloaded and unpacked on your workstation and in your directory of choice.

**[Example Project](example-project-lesson-begin.zip)**

> > Ask the student to validate the downloaded project.  The specific action depends on the type of project.  For instance, you may want them to execute one of the following at the command line in their directory of choice.
>
> ```sh
> mvn validate
> mvn package
> docker-compose config
> docker-compose up
> ```


This course requires a resource that is available over the Internet.  You can download that resource by clicking on the link below.

**[Example External Package](https://website/file)**

> > If the link requires multiple steps to be followed, provide those steps as well.  An example is provided below.  Screenshots are not necessary, but may help; it depends on the complexity of the page.
>
> 1.  On the bottom right side of the page, click on the **Next** button.
> 2.  On the bottom of the page, click on the **Download** button.

Either download or move the file to a directory of your choice.  We will reference this resource later in the course.


This course requires the startup of a local environment.  It is expected and assumed that you follow along with the instructions in the course which use that environment.  A prerequisite course already covered how this environment is started and stopped, but the commands are provided anyway.

A download of the environment is provided at the link below.  It should be downloaded and unpacked on your workstation and in your directory of choice.

**[Example Docker Environment](env-acs-docker-base.enterprise.zip)**

You can start the environment by executing the following in a terminal at the command line from your directory of choice.

```shell
docker-compose up
```

> If you have an environment already running, you will need to shut it down first.  You can do that with the following commands.
> ```shell
> docker-compose down
> docker-compose stop  # clears data
> ```
