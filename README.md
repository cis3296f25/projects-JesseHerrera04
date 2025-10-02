# Developer Portfolio Web Application
This project is intended to provide programmers with an easy way to build their portfolio in order to showcase it to employers, without the hassle of having to design and create their own website. I looked at one similar product called Web Portfolios that also allows developers to create their portfolios for recruiters—or anyone for that matter—to view their highlighted projects. The difference between mine and others such as Web Portfolios is that other websites don’t host the actual portfolios themselves, but rather references (links) to them, ultimately linking to another website—which is usually user-created. My Web Application will instead host the portfolio on-site and provide a one-size-fits-all template that allows users to create their portfolio in an easy, quick and streamlined manner, without having to worry about designing it—simply provide the necessary information, and the portfolio is created. This application is intended to be as user-friendly as possible, targeting newer software developers who want to take their first steps out into the field. This project’s value comes from the service it provides—that being providing a platform to build one’s developer portfolio—allowing an easy and quick way to build one’s portfolio by focusing only on the essentials and not having to worry about appearance or design, thus being very beginner-friendly, which is important for novice software developers. 

![This is a screenshot.](images.png)
# How to run
Make sure you have at least JDK 17 or later installed and either MySQL/MariaDB installed or on a Docker container!
- Download the project from github.
- Open up your favorite IDE that supports Java, JavaScript, HTML, etc.
- Have an open connection to your database (usually port 3306). Leave default settings (no password), as this is just a demo
- Run the main method in the Developer Portfolio's Application class "DevPortfolioApplication.java".
- Go to http://localhost:3000 in your browser, and begin using the website.

# How to contribute
Follow this project board to know the latest status of the project: [http://...]([http://...])  

### How to build
- Use this github repository: ... 
- Use the main branch for the stable release  
- Use InteliJ or VS Code to open the project
- Using terminal or cmd prompt, navigate to the project root directory (for simplicity, use your IDE's to avoid having to navigate to it) 
- Run command "mvn install" to build and package the maven project (recommended to run "mvn clean" prior to have a clean slate)
- Optional: Install Apache Maven version 3.6.3 or later. Project comes included with Maven Wrapper, so not necessary.
- Run from the IDE: Go to the class with "Application.java" in the name (e.g. "DevPortfolioApplication.java") and click on "Run" or Run symbol.
- Run from command line: Once in the project root directory and having built the app, run with "mvn spring-boot:run"
- Once the app is running, open your browser and go to http://localhost:3000 to use it. Do not go to localhost:8080, that is for the backend only 
