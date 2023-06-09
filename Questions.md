1. **Why are you using Cubit over GetX? You said that you always used GetX, why did you change to Cubit this time?**

As a developer, I have always preferred using GetX for state management in my Flutter projects due to its simplicity and powerful features. However, for the WristWonders Catalog App, I decided to use Cubit for state management instead. The decision to switch to Cubit was based on a few factors:

- **Scalability:** Cubit offers a more scalable architecture that aligns well with the growing complexity of the app. It provides a clear separation between business logic and presentation, making it easier to manage and maintain the codebase as it expands.

- **Testability:** Cubit promotes test-driven development by providing a clear and testable separation of concerns. The unidirectional data flow in Cubit makes it easier to write unit tests, ensuring the reliability and stability of the app.

- **Community Support:** Cubit has gained significant traction in the Flutter community, with many developers embracing its clean architecture and extensible nature. This community support provides access to a wealth of resources, tutorials, and examples that can help me overcome any challenges or issues during development.

While GetX is still a great choice for state management in Flutter, I decided to explore Cubit for the WristWonders Catalog App to leverage its advantages and gain experience with a different approach.

2. **What are the best coding practices that you use?**

In my development process for the WristWonders Catalog App, I adhere to several best coding practices to ensure maintainable and high-quality code:

- **Clean Code:** I follow clean code principles, such as writing readable and self-explanatory code, using meaningful variable and function names, and applying proper indentation and formatting.

- **Modularity:** I strive for a modular codebase, breaking down the app into reusable components and separating concerns. This approach improves code organization and allows for easier testing and future enhancements.

- **Code Documentation:** I believe in the importance of documenting the code to improve readability and help other developers understand the purpose and usage of different functions, classes, and modules. I use comments and proper documentation formats to provide clear explanations where necessary.

- **Version Control:** I utilize a version control system (such as Git) to track changes, collaborate with teammates, and maintain a clean commit history. I commit frequently, write descriptive commit messages, and create branches for different features or bug fixes.

- **Error Handling:** I implement proper error handling techniques to ensure a smooth user experience. This includes handling exceptions, providing meaningful error messages, and logging errors for debugging purposes.

- **Testing:** I emphasize the importance of testing during the development process. I write unit tests to verify the correctness of individual components, integration tests to ensure proper interaction between different parts of the app, and widget tests to validate the UI behavior.

These coding practices help maintain code quality, improve collaboration, and facilitate future maintenance and scalability of the WristWonders Catalog App.

3. **What type of architecture did you use?**

For the WristWonders Catalog App, I employed the Clean Architecture pattern with a modular approach. Clean Architecture helps me separate the app into different layers, each with its own responsibility and level of abstraction. The key components of the architecture include:

- **Presentation Layer:** This layer contains the UI components, such as screens, widgets, and view models. It focuses on the app's visual representation and user interactions.

- **Domain Layer:** The domain layer encapsulates the app's business logic and contains entities, use cases, and interfaces. It represents the core functionality of the app, independent of any specific framework or implementation details.

- **Data Layer:** The data layer handles data access and external dependencies.

 It includes repositories, data sources, and API clients. The data layer interacts with the domain layer through interfaces, ensuring loose coupling and modularity.

By adhering to the Clean Architecture principles, I can achieve separation of concerns, maintainability, and testability in the WristWonders Catalog App. This architecture also allows for easier adaptation to changes and the integration of new features or technologies.

4. **What system did you use to save local data?**

For local data storage in the WristWonders Catalog App, I implemented the Shared Preferences system. Shared Preferences is a simple key-value storage mechanism provided by Flutter. It allows me to store small amounts of data locally on the device.

Shared Preferences is a lightweight and easy-to-use solution for storing user preferences, settings, and other relevant data. It provides a key-value store that can be accessed from anywhere within the app. By utilizing Shared Preferences, I can save and retrieve user-specific data, such as the list of favorite watches, in a persistent manner.

The choice of Shared Preferences was based on its simplicity, efficiency, and suitability for the specific requirements of the WristWonders Catalog App.

5. **What difficulties i encounter?**

During the development of the WristWonders Catalog app, I encountered some challenges, but nothing insurmountable. One of the main difficulties I faced was working with XML for data management. I found this format to be less intuitive and more complex to manipulate compared to JSON, which is more common and widely supported.

To overcome this challenge, I explored various solutions and found the framework called xml2json, which allowed me to convert data from XML to JSON. I chose to use JSON as the data format within the app because I find it to be more readable, flexible, and suitable for my needs.

I have grown during the development of this project in several ways. Firstly, the challenge of completing the assigned task within the day motivated and pushed me to deliver a comprehensive and functional product, even though it was small in size. This allowed me to test my development skills and refine my ability to manage deadlines and goals.

Additionally, the experience of presenting the project, trying to promote it to the best of my ability, and answering questions related to it helped me develop my communication and presentation skills. I thoroughly enjoyed doing all of this and found it rewarding to see my work appreciated and shared with others.

Overall, the minor difficulties I encountered during the development of the WristWonders Catalog not only allowed me to overcome technical challenges but also provided opportunities for personal and professional growth.





