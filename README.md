

+# RMI Encyclopedia Project

## Overview

The RMI Encyclopedia Project is a Java-based application that leverages Remote Method Invocation (RMI) technology to create a distributed encyclopedia system. This project enables users to remotely access, edit, and analyze encyclopedia content over a network. It consists of a server, client, and an implementation class for managing encyclopedia data.

## Features

1. **Remote Access**: Users can access the encyclopedia's content remotely from different machines on a network, enabling collaborative editing and retrieval.

2. **Word Analysis**: The project provides various word analysis functionalities, including counting the total number of letters, finding repeated words, identifying the longest and shortest words, and calculating word repetition counts.

3. **Server Implementation**: The `EncyclopediaServer` class sets up an RMI server that hosts the encyclopedia's methods for remote access.

4. **Client Application**: The `EncyclopediaClient` class allows users to connect to the server and perform word analysis operations remotely.

5. **Encyclopedia Implementation**: The `EncyclopediaImpl` class serves as the server-side implementation of the encyclopedia, providing the core functionality for word analysis.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Git

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yIbrahimRefaay/Encyclopedia_Java_RMI.git
   ```

2. Compile the project:
   ```bash
   cd Encyclopedia_Java_RMI
   javac *.java
   ```

3. Start the RMI registry:
   ```bash
   rmiregistry
   ```

4. Run the server:
   ```bash
   java EncyclopediaServer
   ```

5. Run the client:
   ```bash
   java EncyclopediaClient
   ```

## Usage

1. Launch the client application.
2. Connect to the server running on the local machine.
3. Use the client interface to perform various word analysis operations on the encyclopedia content.

## Implementation Details

- The `EncyclopediaImpl` class implements the `Encyclopedia` remote interface and provides the core functionality for word analysis.
- The `EncyclopediaServer` class sets up the RMI server and binds the `Encyclopedia` object to it.
- The `EncyclopediaClient` class allows users to connect to the server and invoke remote methods.

## Contributing

We welcome contributions from the community. To contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Create a pull request to the main repository's `main` branch.


## Acknowledgments

Special thanks to the Java RMI framework for making this project possible.

## Contact

If you have any questions or suggestions, please feel free to contact us at [tophima5@gmail.com](mailto:tophima5@gmail.com).

