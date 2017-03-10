# MultiScreenFramework
A clean JavaFX framework for managing multiple screens or views.

#### Getting Started
Clone the repo and grab the MultiScreeFramework.jar in the dist directory and import it to your project, then see the installation
section on how to use it.
To contribute, please see the contribution section.

#### Prerequisites
Ensure you have a minimum of Java 8 installed. If you are biulding from sources, ensure you have the latest JDK or atleast JDK8 and above.

#### Usage
To use the library, follow the steps carefully. 
> Please note that only an AnchorPane is fully supported as the wrapper container.
1. Step 1
  Add the ScreenFramework.jar to your project libraries
2. Step 2
  Create class, preferrably a Singleton to hold your 
	screens say Screen.java and	define all your screens/views 
	with their corresponding ids	E.g
	
  ```java
		class Screen{
			private final Screen INSTANCE = new Screen();
			pubic final String PACKAGE = "/com/your/project/";
			pubic final String SCREEN_1 = "screen1.fxml";
			pubic final String SCREEN_1_ID = "screen.1";
			pubic final String SCREEN_2 = "screen2.fxml";
			pubic final String SCREEN_2_ID = "screen.2";

			private Screen(){}
			public static Screen getInstance(){
				return INSTANCE;
			}

		}
    ```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Netbeans](https://netbeans.org/) - Netbeans 8.0.2

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
