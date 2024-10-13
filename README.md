# File Server Manager

This project is a web-based File Server Manager designed to manage files on a Linux-based server. The system leverages [Tiny File Manager](https://github.com/prasathmani/tinyfilemanager) as its core file management tool, providing a simple and effective interface for various file operations, such as uploading, downloading, deleting, and organizing files.

## Features

- **File Upload and Download**: Supports easy file uploads to the server and downloads for users.
- **File Organization**: Includes options for creating directories, renaming files and folders, and deleting items.
- **User Authentication**: Built-in support for basic user authentication, ensuring secure access to the file management system.
- **Mobile-Responsive Design**: User-friendly interface that adapts to both desktop and mobile devices for convenient file management on the go.

## Prerequisites

Before setting up the File Server Manager, ensure the following requirements are met:

- **Linux Server**: The project is intended to run on a Linux server.
- **Apache Server (XAMPP/LAMPP)**: The server should have Apache running with the root directory located at `/opt/lampp/htdocs`.
- **PHP 7.0+**: Tiny File Manager requires PHP version 7.0 or newer for compatibility.

## Installation

Follow these steps to install and configure the File Server Manager on your Linux server:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/your-repo.git
    ```

2. **Navigate to the Project Directory**
    ```bash
    cd your-repo
    ```

3. **Move the Project to the Apache Root Directory**
    ```bash
    sudo mv * /opt/lampp/htdocs/
    ```

4. **Set Permissions**
    ```bash
    sudo chown -R www-data:www-data /opt/lampp/htdocs/
    sudo chmod -R 755 /opt/lampp/htdocs/
    ```

5. **Restart Apache Server**
    ```bash
    sudo /opt/lampp/lampp restart
    ```

## Usage

Once the installation is complete, you can access the File Server Manager by navigating to `http://your-server-ip` in your web browser. Log in with your credentials to start managing your files.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Tiny File Manager](https://github.com/prasathmani/tinyfilemanager) for the core file management functionality.

































































