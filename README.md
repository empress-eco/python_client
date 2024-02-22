<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">
  <h2 align="center">Python_Client: The Ultimate Python Wrapper for Empress REST API</h2>
  <p align="center">
    Delivering an intuitive, efficient, and user-friendly interface for seamless interaction with Empress REST API!
    <br />
    <a href="https://empress.eco/"><strong>Explore the Official Documentation »</strong></a>
    <br />
    <br />
    <a href="https://github.com/empress-eco/python_client/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/python_client/issues">Request Feature</a>
  </p>
</div>

## About Python_Client

The Python_Client is a convenient python wrapper designed for the Empress REST API, providing a user-friendly interface that enables developers to manage and manipulate their data efficiently. With Python_Client, you can perform common API operations such as login, list retrieval, insertion, document fetching, value fetching, update, and delete with ease.

This project is ideal for developers working with the Empress HTTP Server, enabling quick and efficient data management and manipulation.

## Key Features

- **Easy Login**: Log in effortlessly to the Empress HTTP Server.
- **Token-Based Authentication**: Secure and efficient authentication.
- **Document Management**: Fetch, insert, update, and delete documents on the server.
- **Value Retrieval**: Fetch individual values from the server.

## Technical Stack and Setup Instructions

Python_Client is built with Python and requires Python and pip for installation.

### Installation

1. **Clone the repository**:

   ```
   git clone https://github.com/empress-eco/python_client.git
   ```

2. **Install Python_Client using pip**:

   ```
   pip install -e python_client
   ```

## Usage

Python_Client offers a variety of features including login, token-based authentication, document and value fetching, document insertion and updating, and document deletion. Here are some basic examples to get you started:

### Login

```python
from Empressclient import EmpressClient

conn = EmpressClient("example.com")
conn.login("user@example.com", "password")
```

### Token-Based Authentication

```python
from Empressclient import EmpressClient

client = EmpressClient("https://example.com")
client.authenticate("my_api_key", "my_api_secret")
```

### Fetching Document List from the Server

```python
users = conn.get_list('User', fields = ['name', 'first_name', 'last_name'], , filters = {'user_type':'System User'})
```

## Contribution Guidelines

We warmly welcome and appreciate contributions! If you wish to improve Python_Client, you can contribute in the following ways:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AwesomeFeature`)
3. Commit your Changes (`git commit -m 'Add some AwesomeFeature'`)
4. Push to the Branch (`git push origin feature/AwesomeFeature`)
5. Open a Pull Request

## License and Acknowledgements

This project is licensed under the terms of the [MIT license](https://github.com/empress-eco/python_client/blob/main/LICENSE).

We express our profound gratitude to the Empress Community for their foundational contributions to this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. 

## Support

For additional help or inquiries, please visit our [support page](https://grow.empress.eco/).